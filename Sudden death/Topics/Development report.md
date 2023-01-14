# Development report

Development USSD


# The user story

## As a busy student I want to be able to mark a list as done or not done, so I can see/track which lists I have completed and which I haven't.

**Acceptance criteria:**
- [x] The student can see their lists
- [x] The list has a default status; "not done"
- [x] The student can click on a button to mark their list as "done"
	- [x] The list status updates to done
- [x] The student can click on a button to mark their list as "not done"
	- [x] The list status updates to "not done"


# Database  
Needed alterations for database; added required datbase fields to table. 

**UID**: added a user id so students can see their own lists.   
**Done boolean**: added is_done field to mark list done or undone.

![database](https://cdn.discordapp.com/attachments/621767149463142402/1063810724218019860/image.png)

# Backend

## Update models to new alterations: 

### list model update:  
**old**

```java
public class List {
   @Id
    private int idList;
    private String listName;
    private String listType;
}
``` 
**new**
```java
public class List {
    @Id
    private int idList;
    private String listName;
    private String listType;
    // new fields
    private String UID;
    private int isDone;
}
```

response and request model fields updated to be on par with above model not written here to avoid redundancy.
* * * 
## Update showallists method:
Change get all lists method to get specific user list and update methods to compatibility with updated models
## get all list update:

### listservice:  
**old**    
```java
public class ListService {
    @Autowired
    private ListRepository listRepository;
// create
    public void saveList(ListRequest listRequest) {
        List list = List.builder()
                .idList(listRequest.getIdList())
                .listName(listRequest.getListName())
                .listType(listRequest.getListType())
                .build();
        listRepository.save(list);
    }
// update
    public void saveList(ListRequest listRequest, int idlist)
    {
        listRequest.setIdList(idlist);
        List list = List.builder()
                .idList(listRequest.getIdList())
                .listName(listRequest.getListName())
                .listType(listRequest.getListType())
                .build();
        listRepository.save(list);
    }

// map
private ListResponse mapToListResponse(List listModel){
        return ListResponse.builder()
                .idList(listModel.getIdList())
                .listName(listModel.getListName())
                .listType(listModel.getListType())
                .build();
    }
}

```

**new**   
Updated to be compatible with altered models
```java 
public class ListService {
    @Autowired
    private ListRepository listRepository;
// create
    public void saveList(ListRequest listRequest) {
        // add new fields to builder
        List list = List.builder()
                .idList(listRequest.getIdList())
                .listName(listRequest.getListName())
                .listType(listRequest.getListType())
                // new fields
                .UID(listRequest.getUID())
                .isDone(listRequest.getIsDone())
                .build();
        listRepository.save(list);
    }
// update
     public void saveList(ListRequest listRequest, int idlist)
    {
        listRequest.setIdList(idlist);
        List list = List.builder()
                .idList(listRequest.getIdList())
                .listName(listRequest.getListName())
                .listType(listRequest.getListType())
                // new fields
                .UID(listRequest.getUID())
                .isDone(listRequest.getIsDone())
                .build();
        listRepository.save(list);
    }

// map
private ListResponse mapToListResponse(List listModel){
        return ListResponse.builder()
                .idList(listModel.getIdList())
                .listName(listModel.getListName())
                .listType(listModel.getListType())
                // new fields
                .UID(listModel.getUID())
                .isDone(listModel.getIsDone())
                .build();
        }
}
```
Method to retrieve lists from specified user
```java 
// get lists from user
    public java.util.List<ListResponse> ShowAllListsFromUser(String UID){
        java.util.List<List> lists = listRepository.findAll();
        java.util.List<ListResponse> userlists = lists.stream().map(this::mapToListResponse).collect(Collectors.toList());

        Iterator<ListResponse> i = userlists.iterator();
        while (((Iterator<?>) i).hasNext()) {
            ListResponse s = i.next();
           // do not show list if uid is null or is not equal to the given UID
            if(s.getUID() == null  || !s.getUID().equals(UID)) {
                i.remove();
            }
        }
        return userlists;
    }    

```


### listcontroller

**new**  
added getmapping to see a users lists
```java
  @GetMapping("/mylists/{UID}")
    public java.util.List<ListResponse> listAllFromUser(@PathVariable String UID) {
        return listService.ShowAllListsFromUser(UID);
    }
```

# Frontend

## Alterations made to show new info

### **service.vue** 

create a new function to get specific lists
```javascript
export async function getlistsFromUser(uid) {
  try {
    const response = await axios.get(Vue.prototype.$Api + "lists/mylists" + uid);
    return response.data;
  } catch (error) {
    return [];
  }
}
```

### **listviewallcomponent.vue** 

the home page should show user specific lists
```js
import { getlistsFromUser } from '@/services/lists/listService';

export default {
    name: "listenPage",
    data() {
        return {
            res: []
        };
    },
    methods: {
        getlistsFromUser: function () {
            getlistsFromUser(this.$auth.user.sub).then((result) => {
                console.log(result);
                this.res = result;
            })
        },
    },
    created() {
        this.getlistsFromUser();
    },
    components: { NewListFormModal }
}
```

The done or not done status shoud be shown depending on the list status
```js
    <b-col>
        <div v-if="list.isDone">✔ Done</div>
        <div v-if="!list.isDone">❌Not done</div>
    </b-col>
```

create new list should be altered to attach the uid
```js
    form: {
            listName: '',
            listType: null,
            uid: this.$auth.user.sub
        }
```
### New controls

button to toggle list status  
![example button](https://cdn.discordapp.com/attachments/621767149463142402/1063915399734890496/image.png)

```js
   <b-button v-b-tooltip.hover.top title="Toggle done status" style="line-height:2;"@click="ToggleStatus()">
        <b-button-text v-if="this.res.isDone">✔</b-button-text>
        <b-button-text v-if="!this.res.isDone">❌</b-button-text>
    </b-button>
```





