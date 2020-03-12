## ACG Debugging Assessment

### Simple note-taking application

### Instructions

Our developer Jon Snow has created a new note taking application for our client. QA has uncovered and reported a couple of bugs that need resolved. Our PM Thomas has asked that you resolve this bugs and submit a PR to fix them. Please see issues recorded in GH issues.

## Setup

```
// Install node_modules in client
cd client && npm i

// Install node_modules in server
cd api && npm i

// Install node_modules in root
npm i

// Single command startup in root of project
npm start
```

If you have trouble with the start command you can try to run each command seperately. If you have issues with docker/mongo you can run mongo locally off your machine as well.

https://treehouse.github.io/installation-guides/mac/mongo-mac.html

https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/

```
docker-compose up
npm --prefix api run start
npm --prefix client run start
```
