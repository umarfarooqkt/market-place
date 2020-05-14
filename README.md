# README

This is a basic market place application

At this moment this application is using a sqllite database temporarily

# Setup and run

- git clone
- rails db:migrate
- rails server

# Usage/routes

- /items
- item/new
- item/edit

- /login
- /signup

- /home/index

A user needs to be logged in to add a new item.
The User has to be authorized(have created the item) to make changes to an item.
