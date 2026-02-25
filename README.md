# University Course Management System – SQL Final Project
## Project Overview

The University Course Management System is a structured relational database project built using MySQL 8.x.

It simulates the backend operations of a university academic system, managing students, courses, departments, instructors, and enrollments.

The project demonstrates strong SQL fundamentals along with advanced querying techniques and database design principles.

---

## Project Objectives

* Design a normalized relational database
* Implement proper primary and foreign key constraints
* Perform complete CRUD operations
* Execute analytical queries using joins and aggregations
* Apply subqueries and window functions
* Demonstrate real-world academic data management

---

## Database Entities

The system consists of five core entities:

### 1. Students

* student_id (PK)
* first_name
* last_name
* email
* enrollment_date
* department_id (FK)

### 2. Courses

* course_id (PK)
* course_name
* credits
* department_id (FK)

### 3. Departments

* department_id (PK)
* department_name

### 4. Instructors

* instructor_id (PK)
* instructor_name
* department_id (FK)

### 5. Enrollments

* enrollment_id (PK)
* student_id (FK)
* course_id (FK)
* enrollment_date
* grade

This structure ensures data integrity and proper relationship mapping between academic entities.

---

## Database Design Features

* Normalized schema to reduce redundancy
* Primary & Foreign key enforcement
* Referential integrity maintenance
* Realistic academic sample data
* Clean relational mapping between entities

---

## SQL Concepts Demonstrated

### CRUD Operations

* Insert new students, courses, enrollments
* Update grades and student information
* Delete records with referential integrity checks
* Retrieve structured academic data

---

### Joins

* INNER JOIN – Student enrollment details
* LEFT JOIN – Students without enrollments
* RIGHT JOIN – Courses without students

---

### Aggregations & Filtering

* COUNT students per department
* Average grade per course
* GROUP BY and HAVING for performance analysis

---

### Subqueries

* Students enrolled in multiple courses
* Courses with above-average enrollment
* Departments with highest student count

---

### Window Functions

* Rank students by grade
* Running average of grades
* Department-wise performance ranking

---

### String, Date & Numeric Functions

* Concatenate student names
* Extract enrollment year
* Grade rounding and formatting

---

### CASE Expressions

* Grade classification (A / B / C / Fail)
* Performance category tagging

---

## Business & Analytical Insights

* Identify high-performing students
* Track department-level performance
* Analyze course demand
* Monitor enrollment trends

---

## File Included

`university_course_management.sql`

Contains:

* Schema creation
* Constraints
* Sample data
* All CRUD queries
* Reporting and analytical queries

---

## How to Run

1. Open MySQL 8.x environment
2. Create a database
3. Run:

```sql
SOURCE university_course_management.sql;
```

4. Verify tables:

```sql
SHOW TABLES;
```

---

## Skills Demonstrated

* Relational Database Design
* Data Normalization
* Complex SQL Query Writing
* Window Functions & Subqueries
* Academic Data Modeling
* Analytical SQL Reporting

---

## Author

Rajvi Trivedi
Data Analyst | Business Analyst

---
