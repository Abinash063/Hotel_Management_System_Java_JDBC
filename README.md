🏨 Hotel Reservation System (Java + JDBC + MySQL)
📌 Overview

The Hotel Reservation System is a console-based Java application developed using JDBC and MySQL.
It provides a simple and efficient way to manage hotel room reservations through a menu-driven interface with complete CRUD operations.



✨ Features

➕ Add New Reservation

📋 View All Reservations

🔍 Get Room Number by Reservation ID

✏️ Update Reservation Details

❌ Delete Reservation

🚪 Exit Application Safely

🧠 Application Flow

Program starts using an infinite while(true) loop

Main menu is displayed repeatedly

User selects an option

Selected operation is executed using JDBC queries

Application exits safely when the exit option is chosen

🛠️ Technologies Used

Programming Language: Java

Database: MySQL (Localhost)

Connectivity: JDBC

IDE: Eclipse / IntelliJ IDEA / NetBeans

Driver: MySQL Connector/J

🗄️ Database Information

Database Name: hotel_db

Table Name: reservations

Table Structure
Column Name	Data Type
reservation_id	INT (Primary Key, Auto Increment)
guest_name	VARCHAR(100)
room_number	INT
contact_number	VARCHAR(15)
reservation_date	DATE

🧾 SQL Setup
CREATE DATABASE hotel_db;
USE hotel_db;

CREATE TABLE reservations (
    reservation_id INT AUTO_INCREMENT PRIMARY KEY,
    guest_name VARCHAR(100),
    room_number INT,
    contact_number VARCHAR(15),
    reservation_date DATE
);
🔗 JDBC Configuration
Download MySQL Connector/J

Add the JAR file to your project build path

Use the following connection format:

java
Copy code
String url = "jdbc:mysql://localhost:3306/hotel_db";
String user = "root";
String password = "your_password";


▶️ How to Run the Project
Create the database using the provided SQL script

Configure JDBC driver in your IDE

Update database credentials in the Java file

Run the Main class

Use the menu to manage reservations

📌 Sample Menu
pgsql
Copy code
1. Add Reservation
2. View Reservations
3. Get Room Number by Reservation ID
4. Update Reservation
5. Delete Reservation
6. Exit


👨‍💻 Author
Abinash Kumar Pandab
B.Tech CSE | Java & Database Projects

