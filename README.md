# Library-Management-System
A Python-based project using tkinter and SQLite for efficient book tracking, user management, and data analytics. Features include book management, fine calculation, and a secure dashboard for librarians. Ideal for libraries and educational institutions.

Python
Tkinter
SQLite

A Library Management System built using Python's tkinter for the GUI and SQLite for database management. This project is designed to streamline library operations, including book management, user authentication, and fine calculation.

Features
User Authentication: Secure login for librarians.

Book Management:

Add, edit, delete, and search books.

Issue and return books with automatic fine calculation.

Dashboard: Intuitive interface for managing library operations.

Data Analytics: Track book availability, issue history, and overdue fines.

Fine Calculation: Automatically calculates fines for overdue books.

Installation
Clone the Repository:

bash
Copy
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
Install Dependencies:
Ensure you have Python 3.x installed. Install the required libraries:

bash
Copy
pip install tkinter sqlite3
Run the Application:
Execute the Python script to start the application:

bash
Copy
python main.py
Usage
Login:

Use the default credentials or register a new librarian account.

Default credentials: User ID: 1, Password: 1.

Dashboard:

Add, edit, delete, or search books.

Issue books to students and manage returns.

Fine Calculation:

The system automatically calculates fines for overdue books.

Data Analytics:

View book availability and issue history in the dashboard.

Screenshots
Login Page
Dashboard
Book Management

Database Schema
The project uses SQLite for database management. The database schema includes the following tables:

adm: Stores librarian login credentials.

stbook: Stores book details (ID, title, author, edition, price, etc.).

student: Stores student details (Roll No, USN, name, course, etc.).

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or feedback, feel free to reach out:

Email: your-email@example.com

GitHub: your-username
