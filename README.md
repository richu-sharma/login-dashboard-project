📌 Login Dashboard System
🔷 Project Overview

The Login Dashboard System is a desktop-based authentication application built using Python, CustomTkinter, and MySQL.

This system allows users to:

Register new accounts

Login securely

Store user data in MySQL database

Access a simple dashboard after authentication

The project follows Object-Oriented Programming (OOP) principles and demonstrates database connectivity in Python.

🛠️ Technologies Used

Python

CustomTkinter (Modern UI for Tkinter)

Tkinter

MySQL

mysql-connector-python

OOP Concepts

✨ Features

✅ User Registration
✅ User Login Authentication
✅ MySQL Database Integration
✅ Dashboard Screen
✅ Error Handling
✅ Clean GUI Layout
✅ Dark Mode UI

🗂️ Project Structure
LoginDashboardProject/
│
├── main.py
├── README.md
└── (Database: MySQL - students table)
🗄️ Database Setup

Create a database in MySQL:

CREATE DATABASE richa;

USE richa;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    student_name VARCHAR(100),
    contact_no VARCHAR(15),
    email VARCHAR(100),
    password VARCHAR(100)
);
▶️ How to Run the Project

Install required libraries:

pip install customtkinter mysql-connector-python

Make sure MySQL server is running.

Update database credentials inside:

def connect_db():
    return mysql.connector.connect(
        host="localhost",
        user="root",
        password="",
        database="richa"
    )

Run the project:

python main.py
📚 Learning Outcomes

GUI development using CustomTkinter

Database integration with Python

Authentication system logic

Git & GitHub project deployment

Object-Oriented Programming

Screenshots
https://github.com/richu-sharma/login-dashboard-project/blob/main/1.png
https://github.com/richu-sharma/login-dashboard-project/blob/main/2.png

👩‍💻 Author

Richa Sharma
GitHub: https://github.com/richu-sharma
