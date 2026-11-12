# 🛒 E-Commerce Website Using PHP

A full-stack **E-Commerce Website** developed using **Object-Oriented PHP, MySQL, HTML5, CSS3, JavaScript, and Bootstrap**.

This project provides an online shopping platform where users can browse products, create accounts, place orders, and manage their previous orders. An admin panel allows administrators to manage products and customer orders.

## 🚀 Features

### 👤 Public User
- Browse available products
- Search for products
- View product details
- Create a user account

### 🔐 Registered User
- Sign in to their account
- Search and view products
- Place orders
- Change email and password
- View previous orders
- Update previous orders
- Delete previous orders

### 👨‍💼 Admin
- Add new products
- Update existing products
- Delete products
- View and confirm customer orders

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- PHP
- MySQL
- Object-Oriented PHP

## 📂 Project Structure

```text
E-Commerce-Website-Using-PHP/
│
├── admin/              # Admin panel and management functionality
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── images/             # Product and website images
├── includes/           # Reusable PHP files
├── index.php           # Main website page
└── ...
```

> The exact folder structure may vary depending on the project version.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/e-commerce-website-php.git
```

### 2. Move the Project

If you are using **XAMPP**, move the project folder into:

```text
C:\xampp\htdocs\
```

For example:

```text
C:\xampp\htdocs\e-commerce-website-php
```

### 3. Start XAMPP

Open the XAMPP Control Panel and start:

- Apache
- MySQL

### 4. Create the Database

Open **phpMyAdmin**:

```text
http://localhost/phpmyadmin
```

Create a MySQL database for the project and import the project's SQL database file if one is provided.

### 5. Configure the Database

Update the PHP database configuration with your local MySQL credentials.

Typical configuration:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "your_database_name";
```

Make sure the database name matches the database you created in phpMyAdmin.

### 6. Run the Project

Open your browser and visit:

```text
http://localhost/e-commerce-website-php/
```

## 🖥️ User Roles

| User Type | Available Features |
|---|---|
| Public User | Search products, view products, create account |
| Registered User | Browse products, place orders, manage account and previous orders |
| Admin | Add, update, delete products and confirm orders |

## 📸 Screenshots

Screenshots of the application can be added here to demonstrate the user interface.

## 🔒 Security Note

This project is intended for **learning and demonstration purposes**.

Before using it in a production environment, consider implementing additional security measures such as:

- Password hashing
- Input validation and sanitization
- Prepared SQL statements
- CSRF protection
- Secure session management
- Environment variables for database credentials

## 🎯 Purpose

This project demonstrates how to build a basic e-commerce application using **PHP and MySQL**, including user authentication, product management, shopping/order functionality, and an administrator panel.

## 📄 License

This project is available for educational and personal learning purposes.
