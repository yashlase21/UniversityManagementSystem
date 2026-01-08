University Management System

A Java Swing & MySQL based desktop application for managing university operations digitally.

📌 Project Overview

The University Management System is a desktop-based application developed using Java Swing and MySQL to automate and simplify day-to-day administrative tasks of a university. It provides a centralized platform for managing student records, faculty details, examinations, fees, and leave applications.

This system replaces manual paperwork with a digital solution that improves efficiency, reduces errors, and ensures secure data management.

🚀 Features

Secure Login and Authentication

Student Management (Add, Update, View, Track Fees & Leave)

Faculty Management (Add, Update, View, Track Leave)

Examination Management (Enter and View Marks)

Fee Management (Define Fee Structure, Track Payments & Dues)

Leave Management (Student and Faculty Leave Applications & Tracking)

User-friendly and interactive GUI

Secure and structured database with MySQL

🛠️ Technologies Used
Technology	Purpose
Java	Core application logic
Java Swing	Graphical User Interface
JDBC	Database connectivity
MySQL	Data storage
IntelliJ IDEA / Eclipse	Development environment
🧩 System Architecture

The system follows a 3-layer architecture:

Presentation Layer — Java Swing user interface

Business Logic Layer — Java classes and event handling

Data Layer — MySQL database accessed via JDBC

This separation ensures clean code structure, easy maintenance, and scalability.

📂 Modules

Login & Authentication

Student Management

Faculty Management

Examination Management

Fee Management

Leave Management

About & System Information

🗄️ Database Design

The system uses the following tables:

student

teacher

marks

fee

leave

Primary keys and foreign keys are used to maintain data integrity and relationships.

🔐 Security

Secure login authentication

Controlled access to data

Prevention of unauthorized modifications

⚙️ Installation & Setup
Prerequisites

Java JDK 8 or above

MySQL Server

IntelliJ IDEA or Eclipse

Steps

Clone the repository:

git clone https://github.com/your-username/university-management-system.git


Import the project into your IDE.

Create the MySQL database and tables.

Update database credentials in the connection file (Conn.java or similar).

Run the main class to start the application.

📸 Screenshots

(Add screenshots of Login, Student Form, Marks Entry, Fee Module here)

⚠️ Limitations

Desktop-only application

Requires local database setup

Limited role-based permissions

🔮 Future Enhancements

Web-based version

Mobile application support

Cloud database integration

Online payment gateway

Biometric or RFID-based attendance

👨‍💻 Author

Yash Pandurang Lase
Final Year Front-End Engineering Student
Java | Swing | JDBC | MySQL

📄 License

This project is for academic and learning purposes.
