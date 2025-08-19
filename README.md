

---

# Student Management System (Python + MySQL)

## 📌 Overview

A simple **console-based Student Management System** built using **Python** and **MySQL**.
It demonstrates complete **CRUD operations**: Add, View, Search, Update, and Delete students.

---

## ✨ Features

* Add new student
* Display all students
* Search student by ID
* Update student details
* Delete student records
* MySQL database integration

---

## 🛠 Tech Stack

* Python 3
* MySQL
* mysql-connector-python

---

## 📂 Project Structure

```
student-management-system-python-mysql/
│
├── main.py              # Console interface
├── student_manager.py   # CRUD operations
├── database.py          # DB connection
├── requirements.txt     # Dependencies
└── README.md            # Documentation
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Setup MySQL

```sql
CREATE DATABASE student_db;
USE student_db;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    marks FLOAT
);
```

### 4️⃣ Configure Database

Update `database.py` with your MySQL username & password:

```python
HOST = "localhost"
USER = "root"
PASSWORD = "your_mysql_password"
DATABASE = "student_db"
```

### 5️⃣ Run Application

```bash
python main.py
```

---


