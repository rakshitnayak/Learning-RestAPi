# Learning-RestAPi

Hey everyone , I made this app.js while learning RestAPI ..i learnt how to GET,PUT,POST,PATCH,DELETE the specific component in database!

   Server Staring code in app.js is
//////////////////////////////////////
const express = require("express");
const bodyParser = require("body-parser");
const ejs = require("ejs");
const mongoose = require('mongoose');

const app = express();

app.set('view engine', 'ejs');

app.use(bodyParser.urlencoded({
  extended: true
}));
app.use(express.static("public"));

//TODO

app.listen(3000, function() {
  console.log("Server started on port 3000");
});


To run this app.js you need to create mongodb database namely "wikidb",you must be familiar with crud operations.
-> in terminal run nodemon app.js
-> in localhost:3000/articles you can see your articles updated in mongoose database which is json format!

i made this app while learning RestAPI ..i learnt how to GET,PUT,POST,PATCH,DELETE the specific component in database!
