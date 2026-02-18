🏨 Hotel Management System (Java)
📌 Project Overview

The Hotel Management System is a Java-based desktop application designed to manage hotel operations efficiently. It provides functionality for managing rooms, customers, employees, drivers, check-ins, check-outs, and more.

This project uses Java and database connectivity for storing and retrieving hotel data.

🚀 Features

🔐 User Login System

🏠 Room Management (Add, Update, Search)

👤 Customer Management (New Customer, Customer Info)

🧾 Check-In / Check-Out System

👨‍💼 Employee Management

🚗 Driver Management

🏢 Department Management

📊 Dashboard Overview

🧑‍💼 Manager Information

🚖 Pickup Service Management

📂 Project Structure

Below are the main Java source files included in the project:

AddDrivers.java        - Add new drivers to the system
AddEmployee.java       - Add new employees
AddRoom.java           - Add new rooms
CheckOut.java          - Handle customer checkout
conn.java              - Database connection setup
CustomerInfo.java      - View customer information
Dashboard.java         - Main dashboard screen
Department.java        - Manage departments
Employee.java          - View employee details
HotelManagementSystem.java - Main entry point of application
Login.java             - User authentication
ManagerInfo.java       - Manager details
NewCustomer.java       - Register new customers
PickUp.java            - Manage pickup services
Reception.java         - Reception panel
Room.java              - Room details view
SearchRoom.java        - Search available rooms
UpdateCheck.java       - Update check-in details
UpdateRoom.java        - Update room details

🛠️ Technologies Used

Java

JDBC (Database Connectivity)

MySQL (or compatible database)

🗄️ Database Configuration

Make sure to configure your database connection inside:

conn.java


Update:

Database URL

Username

Password

Example:

Connection c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/hotelmanagement",
    "root",
    "admin@123"
);

▶️ How to Run the Project

Open the project in an IDE (IntelliJ IDEA / Eclipse / NetBeans).

Configure your database.

Run the file:

HotelManagementSystem.java


Login using your credentials.

🔑 Default Functional Flow

Login

Access Dashboard

Manage Rooms / Customers / Employees

Perform Check-In / Check-Out

Update Records as needed

📌 Requirements

JDK 8 or above

MySQL Server

Java IDE

👨‍💻 Author

Eshan Bahuguna
Hotel Management System Project
