# CRUD_Classwork
Rest API'S -> HTTP -> Get, Post, Patch , Delete. 
Browser doesn;t support the Patch and Delete request.

(There is only a small difference between patch and put. If we want to update a small chunk of data we will use 
patch and if we will update a large chunks of data then we will use put.)

We will use  a client for know as postman to test our API's.

We will use a wireframe know as express. 

For storing data MongoDB database is used. 

Setup:
1. in ur vs Code cmd terminal, run command npm init. 
2. Install express using command npm i express.
3. After that, install MongoDB and mongoose.
4. Install nodemon using command (npm i nodemon --save-dev).
(Actually whenever we make a small change, we need to restart the server so that change will 
reflect.To avoid that we are installing this package.)
5. After this i made a change in script in package.json i.e. "start" : "nodemon app.js"
nodemon will always execute app.js in this case.

// app.js
1. Import the packages in the app.js you want to use.
2. Connect the database.
3. App.js will have a .listen always in the end of the file.

// Created a new folder known as routes and in that a new file was created i.e. aliens.js
1. In this, firstly we imported express.
2. Imported Router
3. then API will be created. 
4. export the module. 

// Concept of MVC 
M stands for Model - Schema
V stands for view - UI 
C stands for Controller - Router.
