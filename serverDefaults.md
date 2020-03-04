# // Dependencies

var express = require("express");
var path = require("path");

# // Sets up the Express App

var app = express();
var PORT = process.env.PORT || 3000;

# Sets up the Express app to handle data parsing

app.use(express.urlencoded({ extended: true }));
app.use(express.json());

{
"name": "starwars-express",
"version": "1.0.0",
"description": "",
"main": "server.js", <--------important
"dependencies": {
"express": "^4.16.3"
},
"devDependencies": {},
"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"start": "node server.js", <-------important
"watch": "nodemon server.js"
},
"author": "",
"license": "ISC"
}
