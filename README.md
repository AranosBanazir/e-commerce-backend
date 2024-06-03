# E-Commerce Backend 
    
## Description 
  
  A backend application for managing products, categories and tags in a database to track items for an e-commerce site. This application allows for managing the price, stock, associated tags and categories of different products to assist managing items for a business.

## Table of Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contact](#contact)

## Installation 
  
  To install the dependencies run `npm i` in your terminal at the root of the application. To build the database you will need to move into the database folder with `cd db/`. From here you will need to run the command `psql -U <username>` this will open the postgres terminal. You will need to login using your postgres user and password. While in the postgres terminal run the command `\i schema.sql` this will drop any existing databases with the same name, and then set up the ecommerce_db. To exit the postgres terminal simply do `\q`. To get back to the root of the application you will need to `cd ..` and then send the command `npm run seed` this will seed the database with some basic starter information. Congratulations, you have now set up the database, as well as given it some basic information to start with. You can now proceed to the usage instructions.

## Usage 
  
  To use the application, clone down the repository and follow the installation instructions. After following the installation instructions and seeding the database you can start up the server by runing `npx nodemon server` while the server is active you can make requests using a third-party REST platform such as [postman](https://www.postman.com), or [insomnia](https://insomnia.rest) to view and alter the database.

  A link to the video walkthrough will be provided [here](https://drive.google.com/file/d/1IB9EbO6aM23N3kyBM16wyjLQLMYYIoRB/view?usp=drive_link).

## Contact
You can contact me through any of the below methods:

Github: [AranosBanazir](https://www.github.com/AranosBanazir)

Email: [CalebSaiia@gmail.com](mailto:CalebSaiia@gmail.com)