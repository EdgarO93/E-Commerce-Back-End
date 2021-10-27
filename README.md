# E-Commerce Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
## Description
The E-Commerce Back-End app is the backend portion of an E-Commerce website built with Express.js,MySQL, Sequelize, and NodeJS. The SQL database includes tables for products, categories, tags, and product tags. API Routes are derived to perform RESTful CRUD operations using sequelized models and are tested in Insomnia. This project was helpful in further understand object relational mapping and interacting with databases. In future developments, I would like to integrate prompts to perform the CRUD operations to the database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Screenshots](#screenshots)
- [Video](#video)
- [License](#license)
- [Questions](#questions)
- [Acknowledgments](#acknowledgments)

### Installation
After downloading this repository, go into the folder of this project. Then run npm install or i. 

### Usage
First run mySQL -u root -p and enter password. Source the schema.sql. Then edit the env.Example file with your MYSQL username and password. Then save your file as .env . Then you can use run npm seed to load the database, then run npm watch to run nodemon or run npm start to just run the server.js if there are no updates expected to be made. You can open Insomnia Core to enter any route create in the /routes/api directory. Using GET,POST,PUT and DELETE functions of Insomnia you can view and update the database.

### Contributing
Feel free to fork or clone this repo and make your own versions.

### Tests
API Get, POST, PUT, and DELETE routes in Insomnia Core can be opened and tested to create,update and delete data in the database.



###  Screenshots 
View of Routes in Insomnia
![plot](assets/image-1.png)

View of Terminal running server
![plot](assets/image-2.png)

## Video


[VIDEO HERE]


<a href ="https://watch.screencastify.com/v/MDKERduVavWcMvHkka7n" target= "_blank" > Link to video. </a> 


###  License

Copyright &copy; 2021 Edgar Ortega

This project is licensed under the terms of the <a href="https://opensource.org/licenses/MIT" target= "_blank" > MIT </a> license.

### Questions

Send questions to edort93@gmail.com or visit <a href="https://github.com/edgarO93" target= "_blank" >my profile </a><br>

### Acknowledgments

```
I would like to thank online resources such as W3 schools, MDN Web Docs, and Stack Overflow.
```