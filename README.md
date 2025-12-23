# Human Resources Management (HRM) System

## 📌 Project Overview
This project involves the end-to-end development of a Human Resources Management database system. The solution was built from scratch, covering the database design (ERD), implementation in MySQL, and the creation of interactive dashboards using Power BI. Additionally, a web application interface was developed to demonstrate front-end integration.


## 📂 Repository Structure
* `database/`: Contains all SQL scripts (Schema, Stored Procedures, Triggers, Views, and Functions).
* `Database_PowerBI_Dashboard`: The `.pbix` file for the HR Analytics Interactive Dashboard.
* `ERD.draw.io: The Entity Relationship Diagram of the database schema.
* `HRM-Database Analytics System`: PDF file contains screenshots of the web app portal and description of the project.

## 🚀 Features

### 1. Database Backend (MySQL)
* **Comprehensive Schema:** Handles Employees, Departments, Jobs, Contracts, Attendance, and Performance Appraisals.
* **Advanced Logic:**
    * **Stored Procedures:** For onboarding new employees, assigning jobs, and calculating performance scores.
    * **Triggers:** Automatically validates data (e.g., preventing deletion of active employees, calculating weighted KPI scores).
    * **Scalar Functions:** Custom calculations for employee age, service years, and KPI completion rates.
    * **Views:** Pre-built virtual tables for "Active Job Assignments" and "Department Statistics."

### 2. Business Intelligence (Power BI)
* **Training Dashboard:** Visualizes program completion rates and employee skill distribution.
* **Performance Dashboard:** Tracks average KPI scores, top-performing departments, and appraisal trends.
* **Job Overview:** Analyzes salary distributions and employee headcount by job level.

### 3. Web Interface
* A user-friendly web portal created to interact with the database, allowing HR managers to view dashboards and manage employee profiles.

## 🛠️ Tools Used
* **Database:** MySQL Workbench
* **Visualization:** Microsoft Power BI
* **Web Development:** Lovable.dev / React

## 👥 Team Members
* **Omar Khaled**
* **Zeina Fahim**
* **Mariam Ashraf**
* **Nada Khaled**
* **Nadeen Khalifa**
* **Malak El Koumy**
* **Nour Samir**
* **Ganna Hamza**
* **Sama Samer**
