# 🦷 SmileCare Dental Clinic Website with Appointment Booking System

A responsive dental clinic website developed using **HTML, CSS, Bootstrap, PHP, and MySQL**. The project provides an online platform where patients can explore dental services, meet doctors, and book appointments easily.

---

## 📌 Features

- 🏠 Responsive Home Page
- ℹ️ About Us Page
- 👨‍⚕️ Doctors Information Page
- 📞 Contact Page with Google Map
- 📅 Online Appointment Booking
- 💾 Appointment Data Stored in MySQL Database
- 📱 Mobile-Friendly Design using Bootstrap
- 🔒 Secure Database Operations using PHP Prepared Statements

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- PHP
- MySQL
- JavaScript

---

## 📂 Project Structure

```
SmileCare-Dental-Clinic/
│
├── index.html
├── about.html
├── doctors.html
├── appointment.html
├── contact.html
├── treatments.html
│
├── process_appointment.php
├── db_connect.php
│
├── css/
│   └── style.css
│
├── images/
│   ├── doctor1.jpg
│   ├── doctor2.jpg
│   ├── implant.jpg
│   ├── braces.jpg
│   └── ...
│
└── database/
    └── smilecare_db.sql
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/SmileCare-Dental-Clinic.git
```

### 2. Move Project

Copy the project folder to your web server directory.

For XAMPP:

```
C:\xampp\htdocs\
```

### 3. Create Database

Open **phpMyAdmin**

Create a database named

```
smilecare_db
```

Import the SQL file.

### 4. Configure Database

Edit `db_connect.php`

```php
$servername = "localhost";
$username = "root";
$password = "";
$database = "smilecare_db";
```

### 5. Run Project

Start

- Apache
- MySQL

Open

```
http://localhost/SmileCare-Dental-Clinic/
```

---

## 📸 Website Pages

- Home
- About
- Treatments
- Doctors
- Appointment Booking
- Contact

---

## 🗄️ Database

### Table: appointments

| Field | Type |
|---------|------|
| id | INT (Primary Key) |
| name | VARCHAR(100) |
| phone | VARCHAR(20) |
| email | VARCHAR(100) |
| treatment | VARCHAR(100) |
| appointment_date | DATE |
| appointment_time | TIME |

---

## 🚀 Future Enhancements

- Admin Dashboard
- Login Authentication
- Appointment Status
- Email Notifications
- SMS/WhatsApp Alerts
- Online Payment Integration
- Doctor Availability Management

---

## 📷 Screenshots

Add screenshots of:

- Home Page
- About Page
- Doctors Page
- Appointment Form
- Contact Page

---

## 👨‍💻 Author

**Sanika Kadam**

---

## 📄 License

This project is developed for educational purposes.
