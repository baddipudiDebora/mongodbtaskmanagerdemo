
Welcome, to TaskManagement Application. its features are 

The home page of the task manager application displays a summary of tasks. That summary information is comprised of the task name, due date, whether or not it's an urgent task, and once you click to expand more, you will see the task category, description, and creator. Using one of dependencies that come with Flask (Werkzeug), user authentication and authorization. Users will be able to register, see their profile, log out, and log back in again. Registered users will also be able to add a new task, which includes selecting a due date using Materialize's datepicker component, and toggling a switch to mark the task as urgent.
Users will also be able to edit tasks, but will only be permitted to edit their own tasks, not any of the tasks submitted by others. In addition to editing their tasks, users will be able to delete their own tasks as well. Whether a user is logged in or not, we'll also learn how to build a basic search function, which will filter tasks based on the user's query. You will also see how to manage the task categories list, but make it secure to only be available to an Admin user. We're consistent in our use of the Materialize framework, which means that our app will also be fully responsive by using their grid-based classes.

I have used Code Institute student template for Gitpod. The templae includes preinstalled all of the tools you need to get started. 
the template used can be found on -  https://github.com/Code-Institute-Org/gitpod-full-template

## This application uses Materialize is a responsive front-end framework in the same exact way as Bootstrap.

## This application backend is built using
click==7.1.2
dnspython==2.1.0
Flask==1.1.2
Flask-PyMongo==2.3.0
itsdangerous==1.1.0
pymongo==3.11.2
Werkzeug==1.0.1

## 
## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons.


--------

Happy coding!
