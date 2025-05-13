# Library-Management-System

📘 Project Title: Library Management System
📋 Project Overview:
The Library Management System is a Java-based desktop application developed using Apache NetBeans IDE and connected to an SQL database (MySQL/SQLite/etc.). It allows users (admin/librarian) to manage students, books, and transactions like issuing and returning books.

🔧 Modules / Features:
Login Page


Secure login for the admin/librarian.


Username and password validation using the database.


Student Registration Page


Add a new student with details like name, roll number, course, contact, etc.


Store data in the students table.


Book Registration Page


Add a new book with title, author, publisher, ISBN, quantity.


Store data in the books table.


Issue Book


Select student and book.


Check availability of the book.


Save the transaction in issued_books table with issue date.


Return Book


Select issued book by student.


Update return date.


Increase book quantity in inventory.
🖥️ Technologies Used:
Java (Swing for GUI)


Apache NetBeans IDE


MySQL for database
▶️ How to Run the Project
✅ Prerequisites:
Install Apache NetBeans IDE (with Java support).


Install MySQL or SQLite.


Download MySQL JDBC Driver and add it to NetBeans via Libraries > Add JAR/Folder.



🚀 Steps to Run:
Create the Database:


Open MySQL Workbench or any SQL GUI.


Run the provided SQL script to create the necessary tables.


Open Project in NetBeans:


Open NetBeans > File > Open Project > Select your folder.



Build and Run:


Right-click on the project > Build.


Right-click > Run File (starting with Login.java).



🔐 Default Admin Credentials (for demo)
Username: admin
Password: admin123

Make sure to insert these into the admin table before login.

📌 Optional Enhancements
Add search functionality for books and students.


Add penalty system for late returns.


Export book/issue records as PDF or Excel.


Add user role system (admin, staff).




GitHub Link:

https://github.com/ABDULLAH482-dot/Library-Management-System.git

____________________________________________________________________________


