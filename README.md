# PHP MySQL CRUD Application 🐘💾

A simple web-based **CRUD** (Create, Read, Update, Delete) application built with **PHP** and **MySQL**, using **XAMPP** as the local server environment.

## Features
- Create new records
- Read/list existing records
- Update existing entries
- Delete records

## Technologies Used
- PHP
- MySQL
- HTML/CSS
- XAMPP (Apache + MySQL)

## Project Files
- `index.php` – Displays all records (Read)
- `add.php` – Form to add a new record (Create)
- `update.php` – Form to edit and update a record (Update)
- `delete.php` – Handles deletion of a record (Delete)

## Setup Instructions

1. ✅ **Install XAMPP**
   - [Download XAMPP](https://www.apachefriends.org/index.html) and install it.

2. 📁 **Move Project Folder**
   - Place your project folder in:  
     ```
     C:\xampp\htdocs\
     ```

3. ⚙️ **Start Apache and MySQL**
   - Open **XAMPP Control Panel** and start:
     - Apache
     - MySQL

4. 🗃️ **Create MySQL Database**
   - Visit `http://localhost/phpmyadmin`
   - Create a new database, e.g., `crud_db`
   - Inside it, create a table with columns matching your code (e.g., `id`, `name`, `email`, etc.)

5. 🛠️ **Edit Database Connection (if needed)**
   - Ensure your DB connection in each file is correct:
     ```php
     $conn = new mysqli("localhost", "root", "", "crud_db");
     ```

6. 🌐 **Run the Application**
   - Open your browser and navigate to:
     ```
     http://localhost/your-folder-name/index.php
     ```

## ✅ Screens (Optional)
- `index.php` – Displays records with Edit/Delete buttons
- `add.php` – Form to add new data
- `update.php` – Form to update selected entry
- `delete.php` – Deletes record using GET method

