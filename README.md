# Student-Management-System-Java-Swing-MySQL-
# 🎓 Student Management System

## 📌 Overview

This is a Java desktop application developed using **NetBeans (Swing GUI)** and **MySQL (XAMPP)**.
The system allows administrators and staff to register, log in, and manage student data efficiently.

---

## 🚀 Features

* 🔐 User Registration (Admin / Staff only)
* 🔑 Login Authentication System
* 🧑‍🎓 Student Management
* 📊 JTable Data Display
* 🎨 Custom UI Design
* ✅ Input Validation

---

## 🛠️ Technologies Used

* Java (Swing)
* MySQL (XAMPP)
* JDBC
* NetBeans IDE

---

## 📁 Project Includes

* Source Code
* Database File: `school_db.sql`

---

## ⚙️ Requirements

Before running the project, make sure you have:

* XAMPP (or any MySQL server)
* Java JDK 8+
* NetBeans IDE

---

## 🗄️ Database Setup

### 1. Start MySQL

Open XAMPP Control Panel and start:

* MySQL ✅

---

### 2. Import the Database

1. Open **phpMyAdmin**
2. Click **Import**
3. Select:

```sql id="dbfile1"
student_system.sql
```

4. Click **Go**

---

## 🔌 Database Connection ⚠️

This project uses **MySQL port 3307**.

If your MySQL runs on default port (3306), you must update the connection in:

```text id="fileloc"
DBConnection.java
```

Change this line if needed:

```java id="dbport"
"jdbc:mysql://localhost:3307/student_system"
```

👉 Example for default port:

```java id="dbport2"
"jdbc:mysql://localhost:3306/student_system"
```

---

## ▶️ How to Run

1. Open project in NetBeans
2. Start MySQL in XAMPP
3. Import `school_db.sql`
4. Run the project
5. Register as **admin** or **staff**
6. Login and access the dashboard

---

## 🔒 Access Control

Only users with roles:

* `admin`
* `staff`

can log into the system.

---

## ⚠️ Important Notes

* The application requires MySQL to be running
* If MySQL is not running → login will fail
* Make sure the correct port (3306 or 3307) is used

---

## 📸 Screenshots
<img width="1235" height="776" alt="Screenshot 2026-04-08 001423" src="https://github.com/user-attachments/assets/8f0418ca-e2db-4cff-b460-1b75a74ad16c" />


<img width="1263" height="787" alt="Screenshot 2026-04-08 001503" src="https://github.com/user-attachments/assets/6113ffec-31c9-4d2d-af6d-7f82025fc9b4" />



---

## ✍️ Author
Bekazi Mavunda 





Educational project

