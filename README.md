# node-task-app
This is the back-end for a to-do application with user authentication. Users and their associated tasks are stored in a MongoDB database.
Mongoose is used to create User and Task schemas along with their associated middleware.
Express.js is used to handle incoming requests in the style of REST API. Passwords are hashed before saving and environment variables are
taken advantage of to protect sensitive information.

This project is the result of following along the tutorials of Andrew J. Mead on Udemy.
