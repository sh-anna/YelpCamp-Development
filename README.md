# YelpCamp-Development-Process
A full-stack Node.js project from my web dev course with RESTful routing
YelpCamp is a project that was completed as a part of Colt Steele's Web Development Bootcamp course (Udemy).

Description
------------
YelpCamp is based on the popular Yelp.com , the difference being it focuses on the campgrounds that any host/owner can post for the users across the globe to check and review.

The application is hosted on heroku and can be accessed at the below web address
https://*********

Functionalities
----------------
Everyone can view the camps and reviews without signing up or logging in.
The user will have to login to edit the campground details or any comments.
The user can only edit/delete the campgrounds and comments that they have added.
All the data will pe persistent and is stored in the awazon cloud.

Technologies Used:
------------------
HTML5 - markup language for creating web pages and web applications
CSS3 - used for describing the presentation of a document written in a markup language
Bootstrap - free and open-source front-end web framework for designing websites and web applications quickly
jQuery - cross-platform JavaScript library designed to simplify the client-side scripting of HTML
DOM Manipulation - is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document
Node.js - pen-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side
Express.js - for building web applications and APIs and connecting middleware
REST - REST (REpresentational State Transfer) is an architectural style for developing web services
MongoDB - open-source cross-platform document-oriented NoSQL database program to store details like users info, campgrounds info and comments
PassportJS - authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application
Data Associations - associating user data with the respective campgrounds and comments using reference method
Heroku - cloud platform as a service used as a web application deployment model
AWS - mongodb is hosted on amazon ec2 instance

Initial Setup
=============
Add Landing Page
Add Campgrounds Page that lists all campgrounds
Each Campground has:

Name
Image
Layout and Basic Styling
========================
Create header and footer partials
Add in Bootstrap
Creating New Campgrounds
========================
Setup new campground POST route
Add in body-parser
Setup route to show form
Add basic unstyled form
Style the campgrounds page
==========================
Add a better header/title
Make campgrounds display in a grid
Style the Navbar and Form
=========================
Add a navbar to all templates
Style the new campground form
Add Mongoose
============
Install and configure Mongoose
Setup campground model
Use campground model inside of routes
Show Page
=========
Review the RESTful routes we've seen so far
Add description to the campground model
Show db.collection.drop()
Add a show route/template
Refactor Mongoose Code
======================
Create a models directory
Use module.exports
Require everything correctly!
Add Seeds File
==============
Add a seeds.js file
Run the seeds file every time the server starts
Add the Comment model!
======================
Make comment errors go away!
Display comments on campground show page
Comment New/Create
==================
Discuss nested routes
Add the comment new and create routes
Add the new comment form
Style Show Page
===============
Add sidebar to show page
Display comments nicely
Finish Styling Show Page
========================
Add public directory
Add custom stylesheet
Authentication Pt. 1 - Add User Model
=====================================
Install all packages needed for auth
Define User model
Authentication Pt. 2 - Register
===============================
Configure Passport
Add register routes
Add register template
Authentication Pt. 3 - Login
============================
Add login routes
Add login template
Authentication Pt. 4 - Logout/Navbar
====================================
Add logout route
Prevent user from adding a comment if not signed in
Add links to navbar
Authentication Pt. 5 - Show/Hide Links
======================================
Show/hide auth links in navbar
Refactor The Routes
===================
Use Express router to reoragnize all routes
Users + Comments
================
Associate users and comments
Save author's name to a comment automatically
Users + Campgrounds
===================
Prevent an unauthenticated user from creating a campground
Save username+id to newly created campground
Editing Campgrounds
===================
Add Method-Override
Add Edit Route for Campgrounds
Add Link to Edit Page
Add Update Route
Deleting Campgrounds
====================
Add Destroy Route
Add Delete button
Authorization Part 1: Campgrounds
=================================
User can only edit his/her campgrounds
User can only delete his/her campgrounds
Hide/Show edit and delete buttons
Editing Comments
================
Add Edit route for comments
Add Edit button
Add Update route
Campground Edit Route: /campgrounds/:id/edit Comment Edit Route: /campgrounds/:id/comments/:comment_id/edit

Deleting Comments
=================
Add Destroy route
Add Delete button
Campground Destroy Route: /campgrounds/:id Comment Destroy Route: /campgrounds/:id/comments/:comment_id

Authorization Part 2: Comments
==============================
User can only edit his/her comments
User can only delete his/her comments
Hide/Show edit and delete buttons
Refactor Middleware to a single file
Adding in Flash!
================
Demo working version
Install and configure connect-flash
Add bootstrap alerts to header
Adding dynamic price tag
========================
Show user-defined price
Edit new or old price
Change model for campground
