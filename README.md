# E-commerce Back End Starter Code

video link: https://drive.google.com/file/d/1ph7IwBU7zRGLCH4aN0Vwck1mCoAqg16M/view

AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

THEN I am able to successfully create, update, and delete data in my database

## Installation
* Install npm "npm install" in the root diretory of the project
* Clone the project in the a folder
* create a .env file with your host, user, password, and database name

## Running the program
* use MYSQL "mysql -u "name" -p, then enter your SQL password
* add the database by running "source db/schema.sql"
* quit sql
* "npm run seed" to run the seeds js file
* start the server using "npm start"

## Features
* Allows you to view all catagories, ADD categories, update categories, view specific categories and delete categories.

* Allows you to view all tags, create new tags, update tags, view specific tags, and delete tags.

* Allows you to view all products, add new products, update products, view specific products, delete products.