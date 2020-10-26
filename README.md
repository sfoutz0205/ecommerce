# E-commerce Back End #

This is an e-commerce back end created using an existing Express.js API that I then configured, using Sequelize, to interact with a MySQL database. The database stores products, with associated categories and tags, to be easily viewed and managed. 

## Creation ## 

### Created  Using ###
* Express.js
* MySQL
* Sequelize

## App Demo ##

<img width="1128" alt="Screen Shot 2020-10-25 at 10 23 59 PM" src="https://user-images.githubusercontent.com/68661461/97133979-4f76ca00-1711-11eb-9edd-5c782d30bab2.png">

<img width="1129" alt="Screen Shot 2020-10-25 at 10 23 49 PM" src="https://user-images.githubusercontent.com/68661461/97133951-3a9a3680-1711-11eb-95f9-63dda1cca00e.png">

<img width="1125" alt="Screen Shot 2020-10-25 at 10 26 28 PM" src="https://user-images.githubusercontent.com/68661461/97133992-5bfb2280-1711-11eb-8db2-f3072241749b.png">


### Link to Full Video ###

https://drive.google.com/file/d/1f9zDhuCOJMFFQksDi3dqXu6lnPcwEu0h/view?usp=sharing

## Instructions ##

* At the command line, type the following command, replacing USERNAME with your username to enter MySQL:
    mysql -u USERNAME -p
* At the Enter Password prompt, type your password. 
* To create the database, type the following command at the mysql> prompt:
    source db/schema.sql
* Quit MySQL
* To seed the database, type the following command into the command line:
    node seeds/index.js
* To run the application and connect to the database, type the following command into the command line:
    npm start
* To test the application's api routes, navigate to Insomnia Core and run the following requests:
  PRODUCTS: http://localhost:3001/api/products/
  CATEGORIES: http://localhost:3001/api/categories/
  TAGS: http://localhost:3001/api/tags/
  
  ** Be mindful that you are using the correct PORT

  



