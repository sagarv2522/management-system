# 📚 Library Management System

A desktop-based **Library Management System** developed using **Python**, **PyQt5**, and **MySQL** to simplify library operations through an intuitive graphical user interface. The application enables librarians to efficiently manage books, users, borrowing activities, and generate reports while maintaining a clean and organized workflow.

---

## 📖 Project Overview

This project was developed to demonstrate practical software engineering principles through a real-world desktop application. Rather than focusing on advanced algorithms, the application emphasizes:

- Modular application design
- Database-driven development
- CRUD operations
- User-friendly GUI
- Data validation
- Report generation
- Maintainable source code

---

## ✨ Features

### 📚 Book Management
- Add new books
- Update book details
- Delete books
- Search books
- Manage book categories
- Manage authors
- Manage publishers

### 👥 User Management
- Register users
- Edit user information
- User login support

### 🔄 Library Operations
- Issue books
- Return books
- Track borrowing history
- Manage rental duration

### 📊 Reports
- Export book records
- Export user records
- Export borrowing history
- Generate Excel reports

### 🎨 User Interface
- Desktop application built with PyQt5
- Multiple application themes
- Easy navigation
- Responsive interface

---

## 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| GUI Framework | PyQt5 |
| Database | MySQL |
| UI Designer | Qt Designer |
| Database Connector | MySQLdb |
| Report Generation | XlsxWriter |
| Spreadsheet Reading | xlrd |

---

## 📂 Project Structure

```
LibraryManagementSystem/
│
├── index.py                # Main application
├── library.ui              # Qt Designer UI
├── db.sql                  # Database schema
├── icons.qrc
├── icons_rc.py
├── README.md
│
├── assets/
│   ├── icons/
│   └── themes/
│
├── styles/
│   ├── darkblue.css
│   ├── darkgray.css
│   ├── darkorange.css
│   └── qdark.css
│
└── database/
```

---

## 🗄️ Database Modules

The application manages the following entities:

- Books
- Categories
- Authors
- Publishers
- Users
- Borrowing Operations

The database is implemented using MySQL with relational tables to maintain data integrity and efficient querying.

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/library-management-system.git

cd library-management-system
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install PyQt5
pip install mysqlclient
pip install xlrd
pip install XlsxWriter
```

### Configure Database

1. Install MySQL Server.
2. Create a database named:

```
library
```

3. Import the provided SQL schema.

```
db.sql
```

4. Update the database credentials inside the application if required.

---

## ▶️ Run Application

```bash
python index.py
```

---

## 📸 Screenshots

Add screenshots of:

- Dashboard
- Book Management
- User Management
- Borrow/Return Module
- Reports
- Themes

---

## 🎯 Learning Outcomes

This project demonstrates knowledge of:

- Python programming
- Object-Oriented Programming
- Desktop application development
- Database connectivity
- CRUD operations
- SQL
- GUI design
- Event-driven programming
- Report generation
- Software project organization

---

## 🔮 Future Improvements

- Password hashing
- Role-based authentication
- Barcode integration
- QR code support
- Email notifications
- PDF reports
- Dashboard analytics
- Search optimization
- Backup and restore
- Unit testing
- Logging
- Docker deployment

---

## 📄 License

This project is intended for educational and portfolio purposes.

---

## 👨‍💻 Author

**Kiruba Sagar**

- Python Developer
- Data Science Enthusiast
- Machine Learning Enthusiast

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile
