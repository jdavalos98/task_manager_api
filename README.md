# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions


1. Define CRUD.
CRUD stands for Create, Read, Update, and Delete. The are the 4 basic operations that you can preform on the data in a database. 

Create: Adding new data to the database
Read: Retrieving data from the database
Update: Modifying existing data in the database
Delete: Remove data from the database

2. Define MVC.
MVC stands for Model-View-Controller. It is a design pattern used in software development to separate concerns in an app. 

Model: Represents the data and logic of the application. 
View: Represents the user interface and how the data is presented.
Controller: Acts as an intermediary between the model and the view.

3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
 
 You will need to create a controller.rb file in your nested in your api/v1 directory inside your app/controllers directory. Second you will need to create a routes.rb file in your config directory. 

4. What are params? Where do they come from?

It is short for parameters and are the data passed to a controller via an HTTP request. They are accessible in the controller using the params hash, allowing you to extract and use the data sent in the request. 

6. What is the purpose of a serializer?
A serializer is used to control how dta is presented when converting Ruby objects into JSON or XML formats, and typically in API responses.

