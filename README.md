# Employee Management System

A Java-based web application for managing employee records using **Servlets, JSP, JDBC, and MySQL**, built with a clean **layered architecture**.

---

## 🚀 Features
- Add, View, Update, Delete Employees (CRUD)
- User Authentication (Login & Registration)
- Layered Architecture (Controller, DAO, Model, Util, View)
- JDBC-based database connectivity
- Simple UI using HTML & CSS

---

## 🛠 Tech Stack
- **Backend:** Java, JDBC, Servlet, JSP  
- **Frontend:** HTML, CSS  
- **Database:** MySQL  
- **Server:** Apache Tomcat  
- **IDE:** Eclipse  

---

## 📥 Clone the Repository

To get a local copy of this project, run the following command:

```bash
git clone https://github.com/your-username/Employee-Management-System.git
```


# Create Databse
```sql
-- Create Database
CREATE DATABASE Employee;
USE Employee;

-- Table for User Login & Registration
CREATE TABLE information (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL,
    password VARCHAR(100) NOT NULL,
    city VARCHAR(50)
);

-- Table for Employee Data
CREATE TABLE empdata (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    dept VARCHAR(100) NOT NULL
);

-- View tables
SHOW TABLES;

-- Sample select queries
SELECT * FROM information;
SELECT * FROM empdata;
```
