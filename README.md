# Car Rental System 🚗

A desktop-based car rental management application developed using **Python (PyQt5)** and **Oracle Database (SQL)**.
This project provides a seamless interface for both users and administrators to manage car rentals efficiently and securely.

---

## 💡 Features

### 👤 User Module

* User registration and login system
* Browse available cars
* Rent cars (with or without drivers)
* View and manage bookings

### 🛠️ Admin Module

* Admin login with dashboard access
* Add, update, and remove cars
* Manage driver information
* View rental history and customer details

---

## 🧩 Tech Stack

* **Frontend / GUI:** PyQt5
* **Backend:** Python 3.13
* **Database:** Oracle 11g Express Edition
* **Language:** SQL

---

## 🗃️ Database Structure (Simplified)

* **Users Table** – stores user credentials and details
* **Cars Table** – manages car information and availability
* **Drivers Table** – keeps driver records (optional)
* **Bookings Table** – links users, cars, and booking details

*(Full SQL structure available in the included `.sql` file.)*

---

## 🚀 How to Run

1. Install the required dependencies:

   ```
   pip install pyqt5 cx_Oracle
   ```
2. Import the provided SQL file into your Oracle Database.
3. Configure database credentials in the main Python file.
4. Run the application:

   ```
   python main.py
   ```

---

## 📂 Project Structure

```
Car-Rental-System/
│
├── main.py
├── register_window.py
├── login_window.py
├── dashboard.py
├── manage_cars.py
├── manage_drivers.py
├── database.sql
├── /ui_files
│   ├── login.ui
│   ├── register.ui
│   └── dashboard.ui
└── README.md
```

---

## 🧠 Key Learning Outcomes

* Integration of **GUI and Database** in a real-world Python project
* Understanding **CRUD operations** and relational database design
* Implementation of **role-based access control (user/admin)**
* Use of **object-oriented programming (OOP)** principles

---

## 👨‍💻 Developed By

**Faraz Jehangiri**
Bachelors in Computer Science, Sir Syed University of Engineering & Technology
📍 Karachi, Pakistan
🔗 [LinkedIn Profile](https://www.linkedin.com/in/faraz-jehangiri-4a8411295)

---

> *“Code is like art — when it’s clean and meaningful, it speaks for itself.”*
