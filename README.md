# HR Database Management System Analysis
![HR Management](https://github.com/user-attachments/assets/7eefb5bd-eef6-49f2-8f11-383b5da40af5)

Database Solution for Human Resources Company

**Business Problem:**
Our task was to build a relational database system to replace Excel spreadsheets for an HR company managing recruiting, payroll, and compliance services.

**Company Background:**
A growing HR services company (established 2019) was hitting limits with their Excel-based data management. They needed a real database to handle company leads, employee records, job applications, and payroll data as they scaled up their operations.

**What we built:**
Created a normalized 6-table database with a complete Access application interface.

**Database Structure:**
  • Company, Employee, Job, Application, Department, Contact tables
  • Proper foreign key relationship between all entities
  • Normalized to 3NF to eliminate data redundancy
  
**Application Features:**
  •Navigation form connecting all database functions
  •Data entry forms for each table
  •SQL based reporting for applications and job postings
  •Full CRUD operations throughout the system

  **Technical Details:**
  *Schema Example:*
  '
  CREATE TABLE Company (
    company_id INT PRIMARY KEY,
    company_name VARCHAR(100),
    address VARCHAR(200),
    city VARCHAR(50),
    state VARCHAR(2),
    zip VARCHAR(10)
);

CREATE TABLE Employee (
    employee_id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    department_id INT,
    phone VARCHAR(20),
    FOREIGN KEY (department_id) REFERENCES Department(department_id)
);'

**Complex Query Implementation:**
Built multi-table joins connecting employee, application, job, company, and department data for comprehensive reporting.

**Skills Used:**
  •Database design and ER modeling
  •Normalization (1NF, 2NF, 3NF)
  •SQL (DDL/DML, joins, constraints)
  •Microsoft Access forms and reports
  •Data integrity and foreign key management

**Results:**
The system handles the HR company's core operations: tracking leads, managing job applications, processing payroll data, and generating reports. Replaced their scattered Excel files with a single, consistent database that can actually scale with their business growth.

**Tech Stack:** Microsoft Access, SQL
**Project Type:** Database design and application development group project.



