# README

1. Define CRUD.
- CRUD stands for Create, Read, Update, Delete. This is what allows you to create, retrieve, update, and delete things on a website. 

1. Define MVC.
- MVC stands for Model View Controller. Basic structure in which most web apps are built on including mobile and desktop programs. Model is what the data looks like in the backend, View is what the viewer sees, the HTML portion, and Controller handles the incoming requests, such as the specific URL.  

1. What three files would you need to create/modify for a Rails application to respond to a `GET` request to `/tasks`, assuming you have a `Task` model.
* routes.rb
* task_controller.rb
* index.html.erb

1. What are params? Where do they come from?
- They are parameters turned into a params object. This object can now be used and be manipulated inside the application.

1. Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
- We need two routes for each creating a new Task and editing a Task, because the ‘get’ route will show you the page to edit or create a new task and the ‘patch’ or ‘post’ is the action step that works behind the scenes to actually create or edit that Task.
New Task = Get and Post
Edit Task = Get and Patch  
