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

**Testing**
- [x] backend
- [ ] Frontend 

obj: Push dockerhub CI

- [ ] Backend

dockerfile
```dockerfile
FROM openjdk:8-jdk-alpine
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]

```

docker.yml
```
```

- [ ] Frontend

dockerfile
```
```

docker.yml
```
```