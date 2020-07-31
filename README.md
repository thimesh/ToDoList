This is a ToDoList in which you can add and remove item, when it is running on localhost:3000 it represents default today list.
we can also customize this on the basis of our own list.for eg. we can make a list localhost:3000/work ,localhost:3000/study.
this will make a new list with first letter as capital, whatever we will pass the list name it will convert first letter to capital.
I have used lodash for this functionality,which will name customized lists as Work,Study etc.

From Database Side , I have used MongoDB and Mongoose library as ODM.This will help in performing CRUD operation for this application.

Technology Stack: Javascript , Node.js, Express.js, HTML, CSS, bootstrap ,MongoDB.

Steps to run:

1.npm init
2.npm install body-parser express lodash mongoose
3.node app.js
4.In the browser goto localhost:3000
5.Try to customize it by creating list by any name for eg. localhost:3000/workout and insert, delete items in every list.

Prerequisitea: You should have MongoDB and node installed.
