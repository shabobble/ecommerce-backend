# ecommerce-backend

[![badge](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit)

Thirteenth week's homework for UNH Full-Stack Web Development Boot Camp

## Description

The goal of this project was to build the back-end for an e-commerce site by modifying starter code and configuring a working Express.js API to use Sequelize to interact with a MySQL database. Our main tasks were to ensure that the application allowed the user to:

* Connect to a database using Sequelize

* Enter schema and seed commands to create a development database seeded with test data

* Start the server by entering a command to invoke the application, syncing the Sequelize models to the MySQL database

* Open API GET routes in Insomnia Core for categories, products, and tags to view the data for each of these displayed in a formatted JSON

* Open API POST, PUT, and DELETE routes in Insomnia Core for categories, products, and tags to view the data for each of these displayed in a formatted JSON

## Built with

* Node.js
* Express.js
* MySQL
* Sequelize
* Javascript

## Links

* [GitHub Repository](https://github.com/shabobble/ecommerce-backend)

## Screenshots

![Demo GIF](/Assets/demo.gif)

## Video Demo

![Demo Video Recording of App](https://www.youtube.com/watch?v=PTBpS1TOtME)

## Installation

1. Clone the repository from Github to your computer.

2. Open a terminal and navigate to the directory where you cloned the repository.

3. 
```bash
npm install
```

4. Open MySQL Workbench and execute schema.sql

5. 
 ```bash
 node seeds/index.js
 ```

6. 
```bash
node server.js
```

## Usage

1. Open Insomnia Core

2. Navigate to localhost:3001/api/

    * products to view products
    * tags to view tags
    * categories to view categories

3. Send a GET request on the path to view all.

4. Send a POST request on the path to create a new item, ensuring your request body contains:

    * product_name, stock, price, and tagIds for the products API (tagIds is an array of numbers)
    * category_name for the categories API
    * tag_name for the tags API

5. Send a PUT request on the path to update an existing item, ensuring your path includes the id of the item you're updating after a '/' after the existing path.

6. Send a DELETE request on the path to delete an existing item, ensuring your path includes the id of the item you're deleting after a '/' after the existing path.

## Credits

My full-stack web development course is being offered as a collaboration between Trilogy Education Services and UNH Professional Development and Training.

* Instructor - Benjamin Hutchins [GitHub](https://github.com/benhutchins)
* TA - Andrew Hatfield
* Tutor - Joseph Young
* Study Group - Alan Balcom [GitHub](https://github.com/abalcs), Erica Fagioli [GitHub](https://github.com/efagioli01) and Swetha Reddivari [GitHub](https://github.com/swethareddyl)

## __License__ 

 This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit). 