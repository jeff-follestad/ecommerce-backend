# E-commerce Back End 

## Overview

This goal of this back end project is to help online retailers modernize their e-commerce websites to create a better customer experience and increase profits.

## Acceptance Criteria

This projects leverage MySQL2 and Sequelize packages to connect Express.js API to a MySQL database and the dotenv package. The back-end includes environment variables to store sensitive data, like the MySQL username, password, and database name.

The user accesses the new database with their MySQL username, and MySQL password to an environment variable file. The user is then connected to the database using Sequelize.

When the user enters schema and seed commands, a development database is created and is seeded with test data.

The user enters the command to invoke the application and the server is started, and the Sequelize models are synced to the MySQL database.

API GET routes in Insomnia Core for categories, products, or tags, the the data for each of these routes is displayed in a formatted JSON.

API POST, PUT, and DELETE routes in Insomnia Core successfully create, update, and delete data in my database

https://www.awesomescreenshot.com/video/4200770?key=762d926bfbe03a7403deeb39d28acfa9
