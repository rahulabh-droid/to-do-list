# to-do-list

Built With
JavaScript
Node
Express
Bootstrap
HTML
CSS
jQuery
Ajax
PostgreSQL
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisites
Link to software that is required before you attempt to start the app (e.g. node, postgresql).

Node.js
PostrgeSQL
Create Database and Table
Create a new database called weekend-to-do-app and run the SQL query from the database.sql file.

Installing
Steps to get the development environment running.

Download this project.
Start postgres if not running already by using brew services start postgresql
npm install
npm start
Navigate to localhost:5000 on your preferred web browser.
Completed Features
 Add a task to the database.
 Delete a task.
 Mark a task as complete.
 Set up app to scale with different screen sizes.
Next Steps
 Convert to a React application.
Deployment
In terminal, navigate to your project folder and type heroku create.
Login in if prompted.
Type git remote -v to ensure it was added successfully.
In terminal, type git push heroku master.
Make sure you have already set up the designated local database and have postgres running.
In terminal, type heroku addons:create heroku-postgresql:hobby-dev to set up Postgresql on your Heroku project.
Next, type heroku pg:push your_database DATABASE_URL to copy your database contents up to Heroku. your_database is the actual name of your database (e.g. weekend-to-do-app). DATABASE_URL is a heroku config variable created by the Add On. Do not replace it with something else, just type: DATABASE_URL. For example, if you were deploying the weekend-to-do-app database, you should type heroku pg:push weekend-to-do-app DATABASE_URL.
Authors
Jarvis Yang
