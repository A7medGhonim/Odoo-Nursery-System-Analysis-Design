# Nursery Management System – Analysis & Design (Odoo)

A graduation project (Management Information Systems, Obour Institute, 2024/2025) that covers the **analysis, design, and setup** of an electronic management system for an educational nursery, built on **Odoo 16** using the open-source **OpenEduCat** modules.

> **Note:** This was a team project (10 students). The system is based on OpenEduCat, configured and customized for nursery needs.
> **My role:** *[Write your exact role here, e.g. system analysis, drawing the diagrams, database design, configuring modules, testing]*

---

## Problem

Many small nurseries manage students, attendance, fees, and timetables on paper or in separate Excel files. This causes lost data, late invoices, and no clear view of attendance.

## Solution

One system that manages everything in one place: students, teachers, subjects, attendance, invoices, exams, and timetables, with different permissions for **Admin**, **Management**, and **Teacher**.

## Tools

| Area | Tool |
|---|---|
| ERP platform | Odoo 16 |
| Education modules | OpenEduCat |
| Database | PostgreSQL |
| Analysis & diagrams | draw.io |

## Main Features

- Student data management and admission
- Teaching staff management
- Attendance records and reports
- Student invoices and fees
- Subjects and exams management
- Timetable management
- Login with user roles (Admin / Management / Teacher)

---

## System Analysis

### 1. Use Case Diagram
Shows what each user (Teacher, Management, Admin) can do in the system.

![Use Case](diagrams/01-use-case.png)

### 2. Flow Chart
Shows the login steps and the available processes for each user type.

![Flow Chart](diagrams/02-flow-chart.png)

### 3. Context Diagram
Shows the system as one process and how it exchanges data with outside entities.

![Context Diagram](diagrams/03-context-diagram.png)

### 4. Data Flow Diagram (DFD)
Breaks the system into processes and data stores.

![DFD](diagrams/04-dfd.png)

### 5. Entity Relationship Diagram (ERD)
Shows the main entities (Student, Teacher, Subject, Exam, Attendance, Invoices, TimeTable, User) and their relationships.

![ERD](diagrams/05-erd.png)

### 6. Database Schema
The conceptual relational design, with primary and foreign keys.

![Schema](diagrams/06-schema.png)

> The schema is a conceptual design. Odoo creates its own tables in PostgreSQL when the modules are installed.

---

## System Screenshots

> Test data only. All names, phones, and emails are fake.

### Students
![Students](screenshots/01-students.png)

### Attendance
![Attendance](screenshots/02-attendance.png)

### Invoices
![Invoices](screenshots/03-invoices.png)

### Exams
![Exams](screenshots/04-exams.png)

---

## What I Learned

- Analyzing business requirements and turning them into diagrams
- Designing a relational database (ERD to schema)
- Configuring an ERP system (Odoo) for a real use case
- Working in a team on one project

## Credits

- [OpenEduCat](https://www.openeducat.org/) for the open-source education modules
- Supervisors: Dr. Ziad Khalil and Eng. Ahmed Mosleh, Obour Higher Institute

## Author

**Ahmed Ghonim** – Data Analyst
GitHub: [A7medGhonim](https://github.com/A7medGhonim)
