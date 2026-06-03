# Student-Result-Portal
# 🎓 PHP Student Result Portal

A web-based Student Result Management System developed using PHP and MySQL. This application allows administrators to manage student records, subjects, marks, and results, while students can securely view their academic performance online.

## 📌 Features

### Admin Module

* Secure Admin Login
* Add, Update, and Delete Students
* Manage Subjects and Courses
* Enter and Update Student Marks
* Generate Student Results
* Search Student Records
* View Result Statistics

### Student Module

* View Results Using Roll Number
* Display Subject-wise Marks
* View Total Marks and Percentage
* Check Pass/Fail Status
* Simple and User-Friendly Interface

## 🛠️ Technologies Used

* PHP
* MySQL
* HTML5
* CSS3
* Bootstrap
* JavaScript

## 📂 Project Structure

student-result-portal/
│
├── assets/
├── config/
├── controllers/
├── models/
├── views/
├── uploads/
├── index.php
├── login.php
├── logout.php
└── README.md

## 🗄️ Database Tables

### Students

* student_id
* name
* roll_number
* class
* email

### Subjects

* subject_id
* subject_name

### Results

* result_id
* student_id
* subject_id
* marks

### Admin

* admin_id
* username
* password

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/Dj7517/student-result-portal.git
```

2. Move the project to the XAMPP htdocs folder

3. Create a MySQL database

```sql
CREATE DATABASE student_result_portal;
```

4. Import the provided SQL file

5. Update database credentials in:

```php
config/database.php
```

6. Start Apache and MySQL from XAMPP

7. Open:

```text
http://localhost/student-result-portal
```

## 📸 Screenshots

* Admin Dashboard
* Student Management
* Marks Entry Page
* Result Generation Page
* Student Result View

## 🎯 Learning Outcomes

* PHP CRUD Operations
* MySQL Database Design
* Authentication and Authorization
* MVC Architecture
* Form Validation
* Session Management
* Web Application Development

## 🔮 Future Enhancements

* PDF Result Download
* Email Notifications
* Grade Calculation System
* Student Dashboard
* Result Analytics
* Responsive Mobile Design

## 👨‍💻 Author

Dilip

GitHub: https://github.com/Dj7517

## 📄 License

This project still it is in deveopment phase
