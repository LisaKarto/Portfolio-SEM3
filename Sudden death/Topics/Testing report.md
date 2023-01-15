# Testing report

The tests that have been made for USSD.


# The user story

## As a busy student I want to be able to mark a list as done or not done, so I can see/track which lists I have completed and which I haven't.

**Acceptance criteria:**
- [x] The student can see their lists
- [x] The list has a default status; "not done"
- [x] The student can click on a button to mark their list as "done"
	- [x] The list status updates to done
- [x] The student can click on a button to mark their list as "not done"
	- [x] The list status updates to "not done"

# Backend
- mockMvc
- Mockito

test http request
```java
  @Test
    void GetUserLists() throws Exception{
        this.mockMvc.perform(get("/lists/mylists/testuid"))
                .andDo(print())
                .andExpect(status().isOk());
    }
```
test service
```java
  @Test
    public void TestShowListsFromUser(){

        com.todoapplication.todolist.model.List list1 = new com.todoapplication.todolist.model.List();
        list1.setIdList(1);
        list1.setListName("My first list from user 1");
        list1.setListType("Todo-list");
        list1.setUID("user1");
        list1.setIsDone(0);

        com.todoapplication.todolist.model.List list2 = new com.todoapplication.todolist.model.List();
        list2.setIdList(2);
        list2.setListName("My first list from user 1");
        list2.setListType("Todo-list");
        list2.setUID("user1");
        list2.setIsDone(0);

        com.todoapplication.todolist.model.List list3 = new com.todoapplication.todolist.model.List();
        list3.setIdList(3);
        list3.setListName("My first list from user 2");
        list3.setListType("Todo-list");
        list3.setUID("user2");
        list3.setIsDone(0);

        List<com.todoapplication.todolist.model.List> lists = Arrays.asList(list1,list2,list3);

        Mockito.when(listRepository.findAll()).thenReturn(lists);

        List<ListResponse> userlists = listService.ShowAllListsFromUser("user2");
        // check the array size, there's only one list from user 2 the others have been removed from the list
        assertThat(userlists.size()).isEqualTo(1);
        // check if their uids are equal
        assertThat(userlists.get(0).getUID()).isEqualTo(list3.getUID());

    }
```

# Frontend
- Vue test utils  
  
viewlists
```js
```
put status change
```js
```



