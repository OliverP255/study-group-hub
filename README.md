# Study Group Hub
App for making and joining study groups


## 1. Front End and UI

Home page

study group creation page

study group joining page

login/signup pages

etc.

### Files to use:

index.html

The main landing page with welcome text and links/buttons to other pages.


create-group.html

Contains a form users fill out to create a new study group.


join-group.html

Lets users search or browse existing groups and join them.


group-details.html

Displays info about a specific group like members and schedule (optional to start).


login.html

Lets users log in or sign up if you want user accounts (optional).


profile.html

Shows user info and their joined groups (optional).


styles.css

The CSS file with all the styling for the site (colors, fonts, layout).


app.js

JavaScript code for things like handling form submissions, updating the UI, or fetching data from the backend.


assets/

Folder to keep all images, icons, or other static files.




## 2. Backend (Java)

### Features:

Server set up to handle api requests

authentication and login

Connection to database

### What goes where?

Application.java

This is the main file that starts our app. Usually, you don’t change this much.

model/

Put classes here that define the shape of our data. For example, a Group class that says what a study group looks like (name, members, etc.).

repository/

This folder handles all database stuff — like saving, updating, or finding groups. You usually write interfaces or classes that talk to the database here.

service/

This is where the app’s logic lives. If you need to add new features or rules (like “only 5 people per group”), write that here.

controller/

The controller listens for requests (like “create a new study group”) and calls the service to handle it, then sends a response back.

test/

This is where you put code that checks if your app works correctly. Not mandatory at first, but helpful later.




## 3. Database (SQL)

database set up 
