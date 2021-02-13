
## Nosql-Homework-Workout-Tracker
PASSWORD AUTHENTICATION
This application allows the user to create to track their daily workouts, and easily authenticate the profile. 

# USER STORY
I want to be able to view create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I want to be able to track different exercises and the duration of them.

# TECH USED 
Bootstrap, HTML, CSS, JS, NodeJS, express, mongoose, mongoDB, body-parser and morgan.

# GETTING STARTED
Clone the repository
Run npm i to install all the packages. 
Run in the terminal node server.js
The app will be running in http://localhost:3000
 
# ROUTES
- Api-routes.js: here we have all the routes to singing in, logging in and show the user specific data from the backend .
- html-routes.js here are the routes that check whether user is signed in, whether user already has account and send them to the correct html file.
- package.json: contains all package info, node modules used, version info.
- server.js: requires packages, sets up PORT, creates express and middleware, creates routes and syncs database / logs message in terminal on successful connection to server.

# AUTHORS
- TOMAS UTRERAS