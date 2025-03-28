# User Registration Form

This project is a Java application designed for user registration. It features a graphical user interface (GUI) built with Swing and connects to a MySQL database to save and fetch user data.

## Features
- Add new user registration details.
- Display user data in a table.
- Save user data to a MySQL database.
- Retrieve and display data stored in the database.

## Technologies Used
- **Programming Language:** Java
- **Database:** MySQL
- **JDBC:** For database connectivity
- **GUI Framework:** Swing

## Prerequisites
Before running the application, ensure you have:
1. Java Development Kit (JDK) installed.
2. MySQL Server installed and running.
3. A MySQL database named `registration_db` with the following table structure:
   ```sql
   CREATE TABLE users (
       id INT PRIMARY KEY, 
       name VARCHAR(100) NOT NULL, 
       gender VARCHAR(10) NOT NULL, 
       address VARCHAR(255) NOT NULL, 
       contact VARCHAR(15) NOT NULL
   );
