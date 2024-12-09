# MEAN stack example: CRUD with Angular 16

Build a full-stack (MEAN stack) Angular 16 + Node.js example with a CRUD Application. The back-end server uses Node.js + Express for REST APIs and connects with MongoDB database, front-end side is an Angular App with HTTPClient.

i will build a full-stack Tutorial Application in that:
- it has id, title, description, published status.
- User can create, retrieve, update, delete Tutorials.
- There is a search box for finding Tutorials by title.

![mean-stack-crud-example-angular-16](mean-stack-crud-example-angular-16.png)


## Project setup

### Node.js Server
```
cd node-js-server
npm install
```
Run `node server.js`

### Angular Client
```
cd angular-16-client
npm install
```
Run `ng serve --port 8081`. Navigate to `http://localhost:8081/`.