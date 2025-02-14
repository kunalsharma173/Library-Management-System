# Library Management System

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)  
![SQLite](https://img.shields.io/badge/Database-SQLite-orange)  

## Overview
A **Library Management System** built using Python's **Tkinter** for the GUI and **SQLite** for database management. This project is designed to streamline library operations, including book management, user authentication, and fine calculation.

## Features
### 🔑 User Authentication
- Secure login for librarians.

### 📚 Book Management
- Add, edit, delete, and search books.
- Issue and return books with automatic fine calculation.

### 📊 Dashboard
- Intuitive interface for managing library operations.
- View book availability and issue history.

### 🔎 Data Analytics
- Track book availability, issue history, and overdue fines.

### 💰 Fine Calculation
- Automatically calculates fines for overdue books.

## Installation
### Clone the Repository
```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```

### Install Dependencies
Ensure you have **Python 3.x** installed. Then, install the required libraries:
```bash
pip install tk
```
> Note: `tkinter` is included by default in standard Python installations.

### Run the Application
Execute the Python script to start the application:
```bash
python main.py
```

## Usage
### 🔐 Login
- Use the default credentials or register a new librarian account.
- **Default credentials:** 
  - **User ID:** `1`
  - **Password:** `1`

### 🏠 Dashboard
- Add, edit, delete, or search books.
- Issue books to students and manage returns.

### ⏳ Fine Calculation
- The system automatically calculates fines for overdue books.

### 📈 Data Analytics
- View book availability and issue history in the dashboard.

## Database Schema
This project uses **SQLite** for database management. The database schema includes the following tables:
- `adm`: Stores librarian login credentials.
- `stbook`: Stores book details (ID, title, author, edition, price, etc.).
- `student`: Stores student details (Roll No, USN, name, course, etc.).

## Contributing
Contributions are welcome! Follow these steps to contribute:

1. **Fork** the repository.
2. **Create a new branch:**
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes:**
   ```bash
   git commit -m 'Add some feature'
   ```
4. **Push to the branch:**
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a pull request.**

## Contact
For any questions or feedback, feel free to reach out:

---
🚀 Happy Coding! 🎯
