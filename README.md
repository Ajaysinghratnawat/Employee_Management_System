# Employee Management System

A Java-based web application for managing employee records using **Servlets, JSP, JDBC, and MySQL**, built with a clean **layered architecture**.

---

## 🚀 Features
- Add, View, Update, Delete Employees (CRUD)
- User Authentication (Login & Registration)
- Layered Architecture (Controller, DAO, dto, Util)
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
create database ems;

use ems;

-- Create table admin
create table admin_details(name varchar(100)
,email varchar(100),
password varchar(100));

-- create employee
create table employee(
id int ,
name varchar(100),
email varchar(100),
salary double,
department varchar(50)
);
```
