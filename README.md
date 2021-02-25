# Auth-Passport
 For authentication and authorization of users on the application.
 
 # Pre-Requisites for the Project:
  Node
  NPM (Node Package Manager)

# Dependencies for the project:
  Express
  Ejs
  Body-Parser
  Mongoose
  Nodemon
  Express-flash
  Bcrypt
  Passport
  Passport-local
  Cookie-parser
  Passport-google-oauth
  
 # To run:
   1. Run command "mongod" on terminal to start connection with MongoDB.
   2. On separate terminal run "nodemon index.js" or "node index.js" to start the server.
   3. The application works on port 8000, so open "http://localhost:8000/index" to get to home page.
   4. To close server press ctrl+c.

## Directory Structure
```
Authentication
├── config                   # DataBase config file
│   ├── mongoose.js
│   ├── passport-gauth-strategy.js
│   └── passport-local-strategy.js
├── controller                # Controllers
│   ├── changeController.js
│   ├── googleController.js
│   ├── indexController.js
│   ├── logoutController.js
│   ├── signinController.js
│   └── signupController.js
├── models                   # DataBase Schemas
│   └── userDb.js
├── node_modules.js
├── routes                     # Express Router 
│   ├── changeRouter.js
│   ├── google.js
│   ├── indexRouter.js
│   ├── logoutRouter.js
│   ├── signinRouter.js
│   └── signupRouter.js
├── views                     
│    └── profile.ejs
│    └── index.js
├── index.js                  # Entry point
├── package-lock.json    
└── package.json

