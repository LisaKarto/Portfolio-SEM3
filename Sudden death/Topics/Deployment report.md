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
- [x] Frontend 

obj: Push images to dockerhub CI

- [ ] Backend
- [x] Frontend

**Backend**

dockerfile
```dockerfile
FROM openjdk:11
EXPOSE 8080
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar", "app.jar"]
```

docker.yml
```yml
name: Build & Deploy

on:
  push:
    branches: [ main ]
  workflow_dispatch:

jobs:
  build_and_push:
    name: Build & Push to DockerHub
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Login to DockerHub
        uses: docker/login-action@v2
        with:
          username: ${{ secrets.DOCKERHUB_USERNAME }}
          password: ${{ secrets.DOCKERHUB_PASSWORD }}
      - name: Set up Docker Buildx
        uses: docker/setup-buildx-action@v1
        with:
          version: v0.7.0
          context: .
          push: true
          tags: lisakarto/planpalbackend_hub:latest
      - name: build docker image
        run:  docker build . --tag lisakarto/planpalbackend_hub:latest
      - name: push to docker
        run: docker push lisakarto/planpalbackend_hub:latest
```

**Frontend**  
dockerfile
```dockerfile
FROM node:lts-alpine as build-stage
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build

FROM nginx:stable-alpine as production-stage
COPY --from=build-stage /app/dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

docker.yml
```yml
name: Create image

on:
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]
  workflow_dispatch:

jobs:
  Docker:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: 16

      - name: setup git config
        run: |
          git config user.name "GitHub Actions Bot"
          git config user.email "<>"

      - name: Dependecies
        run: npm ci

      - name: Build
        run: npm run build

      - name: Push new version
        run: git push

      - name: Login to DockerHub Registry
        run: echo ${{ secrets.DOCKERHUB_PASSWORD }} | docker login -u ${{ secrets.DOCKERHUB_USERNAME }} --password-stdin

      - name: Build Docker image
        run: docker build . --file Dockerfile --tag lisakarto/planpalfrontend_hub:latest



      - name: Push to Docker Hub
        run: docker push lisakarto/planpalfrontend_hub:latest

```