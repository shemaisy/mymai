# MyMai – Crochet Flower E-commerce Website 🌸

This is a PHP-based e-commerce website built for my final year IT project. MyMai allows users to browse and purchase handmade crochet flowers, with features like custom orders, a product showcase, and a contact form.

## ✨ Features
- User registration and login system
- Flower collection display
- Custom flower order form
- Checkout page
- Admin panel for content management
- Simple, friendly UI for easy navigation

## 🛠️ Technologies Used
- PHP
- MySQL
- HTML, CSS, JavaScript
- XAMPP (for local testing)

## 🗂️ Project Structure
- `/images` – flower and website images  
- `index.php` – homepage  
- `signup.php`, `login.php`, `purchase.php`, `contact.php` – main sections  
- `mymai.sql` – database structure (exported from phpMyAdmin)

## 💻 How to Run Locally (Using XAMPP)
1. Copy the whole project folder to:  
   `C:/xampp/htdocs/MyMai`

2. Start **Apache** and **MySQL** in XAMPP control panel.

3. Open `phpMyAdmin` → Create a new database (e.g. `mymai_db`)  
   → Import `mymai.sql` from the project folder.

4. Edit your `config.php` or database connection file:
```php
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "mymai_db";
