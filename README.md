# Customer Management Web Application

## Description
This project is a web application built with PHP and MySQL.  
It allows users to manage customer data  without needing direct access to the database.

Users can:
- Add new customers
- View all customers
- Edit customer information
- Delete customers

The application uses prepared statements for security and Bootstrap for styling.


## Technologies Used
- PHP (PDO)
- MySQL
- Bootstrap 5
- XAMPP (Apache & MySQL)


## Installation & Setup

1. Clone or download this repository
2. Place the project folder inside 

## C:\xampp\htdocs\

3. Start XAMPP
- Start Apache and MySql

4. Open PHPMyAdmin
   - Create a database
   - Import or Create a table called 'customers'
   Example structure:

CREATE TABLE customers (
    id INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(100),
    Addres VARCHAR(100),
    Zipcode VARCHAR(10),
    City VARCHAR(100),
    Phone VARCHAR(20),
    Email VARCHAR(100)
);

Configure database connection in:
includes/database.php

Open the project in browser:
http://localhost/eindopdracht/public/

Project Structure
/includes
    database.php

/public
    index.php
    overzicht.php
    add.php
    edit.php
    delete.php
    styles.css

## Testing

The application has been tested for:

Adding customers
Viewing customers
Editing data
Deleting data

All functionalities work as expected.

## Author

## Maciek Urban
