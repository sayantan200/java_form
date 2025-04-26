This is a from created using java awt and stored in mysql 

For configuration 
  In IntelliJ:
    Right-click your project (form) → Open Module Settings (F4).
    Go to Libraries → Click + → Java.
    Select your .jar file → Apply → OK.

Create a databse in mysql
CREATE DATABASE user_registration;
USE user_registration;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255),
    password VARCHAR(255),
    email VARCHAR(255),
    full_name VARCHAR(255)
);

And run the mysql service from wamp server 
