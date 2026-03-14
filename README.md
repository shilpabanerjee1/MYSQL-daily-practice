# MySQL Daily Practice Journey

This repository documents my **day-wise MySQL learning journey**, starting from **basic SQL concepts** and gradually moving towards **advanced database features** through hands-on practice in MySQL Workbench.

The goal of this repository is to **build a strong foundation in SQL and relational databases** by practicing real queries every day.



# Day 01 – Basic MySQL Practice

### Focus
Understanding basic database operations and writing the first SQL queries confidently.

### Topics Covered
- What is a database
- Difference between database and table
- How MySQL stores data in tabular format

### Database Operations
- CREATE DATABASE
- USE database
- SHOW DATABASES

### Table Operations
- CREATE TABLE
- Understanding columns and data types
- DESC table_name
- SHOW TABLES

### Queries Practiced
- INSERT INTO
- SELECT *
- SELECT column_name
- WHERE
- LIMIT



# Day 02 – Filtering & Sorting Data

### Topics Covered
- WHERE clause
- AND / OR conditions
- ORDER BY (ASC, DESC)
- DISTINCT
- LIMIT

### Learnings
- Filtering records using conditions
- Sorting query results
- Fetching unique values
- Limiting output rows



# Day 03 – Aggregate Functions & GROUP BY

### Topics Covered
- COUNT
- SUM
- AVG
- MIN
- MAX
- GROUP BY

### Practice Summary
- Calculated total students
- Found average, minimum, and maximum marks
- Performed department-wise analysis



# Day 04 – WHERE, ORDER BY, LIMIT, DISTINCT

### Practice Summary
- Advanced filtering using WHERE
- Sorting results using ORDER BY
- Limiting records using LIMIT
- Removing duplicate values using DISTINCT
- Writing combined conditional queries

### Table Used
- students



# Day 05 – LIKE, IN, NOT IN, BETWEEN

### Topics Covered
- LIKE (pattern matching)
- IN
- NOT IN
- BETWEEN

### Practice Summary
- Pattern based queries
- Filtering multiple values
- Excluding specific records
- Range based filtering
- Real-world student queries



# Day 06 – INNER JOIN

### Topics Covered
- INNER JOIN
- Table aliases
- Joining multiple tables

### Practice Summary
- Created departments table
- Joined students and departments tables
- Retrieved combined information from multiple tables
- Applied filtering on joined data



# Day 07 – LEFT JOIN

### Topics Covered
- LEFT JOIN
- NULL values in joins

### Practice Summary
- Retrieved all records from the left table
- Identified missing relationships
- Practiced real interview-style join queries



# Day 08 – GROUP BY & HAVING

### Topics Covered
- GROUP BY with aggregate functions
- HAVING clause

### Practice Summary
- Department-wise student count
- Average and maximum marks by department
- Filtering grouped results using HAVING



# Day 09 – Subqueries (Nested Queries)

### Topics Covered
- Subqueries
- Single row subqueries
- Subqueries with AVG and MAX
- Correlated subqueries

### Practice Summary
- Found students scoring above overall average
- Identified student(s) with highest marks
- Found department with highest average marks
- Students scoring above their department average
- Department(s) having maximum number of students



# Day 10 – Constraints & Keys

### Topics Covered
- PRIMARY KEY
- FOREIGN KEY
- UNIQUE
- NOT NULL
- CHECK

### Practice Summary
- Created departments table with PRIMARY and UNIQUE constraints
- Created students table with NOT NULL and CHECK constraints
- Linked tables using FOREIGN KEY
- Inserted valid data respecting constraints
- Understood parent–child table relationship



# Day 11 – JOIN Operations (INNER JOIN)

### What I Learned
- What is a JOIN in SQL
- Why JOIN is required in relational databases
- How tables are linked using PRIMARY KEY and FOREIGN KEY
- How INNER JOIN returns only matching records

### Practice Summary
- Joined students and departments tables
- Retrieved student details with department names
- Applied WHERE conditions on joined data
- Calculated department-wise student count and average marks



# Day 12 – RIGHT JOIN & FULL JOIN (MySQL)

### What I Learned
- RIGHT JOIN returns all records from the right table
- NULL values appear when no matching record exists
- MySQL does not support FULL JOIN directly
- FULL JOIN can be simulated using LEFT JOIN + UNION + RIGHT JOIN

### Tables Used
- students
- departments

### Queries Practiced
- RIGHT JOIN between students and departments
- Finding departments with no students
- Simulating FULL OUTER JOIN using UNION

### Summary
- Learned how to handle missing relationships
- Improved JOIN logic for interview questions
- Strengthened relational database understanding



# Day 13 – Views & Indexes

### What I Learned
- What is a VIEW and why it is used
- Creating and using views
- Updating data through views
- What is an INDEX
- How indexes improve query performance

### Practice Summary
- Created views for student and department data
- Retrieved data using views instead of complex queries
- Created indexes on frequently searched columns
- Understood basic performance optimization



# Day 14 – Foreign Key & Data Integrity

### What I Did
- Verified parent table (departments) data
- Inserted records into child table (students)
- Fixed foreign key issues by ensuring correct table mapping
- Retrieved student records successfully

### Key Learning
Parent table must contain referenced values before inserting into child table.



# Day 15 – ON DELETE & ON UPDATE

### What I Learned
- ON DELETE CASCADE removes dependent records automatically
- ON UPDATE CASCADE updates foreign key values automatically
- Maintains consistency between related tables

### Practice Summary
- Created parent and child tables
- Inserted sample data
- Tested DELETE and UPDATE operations
- Observed automatic changes in related records



# Day 16 – SQL Constraints Practice

### What I Learned
- NOT NULL ensures mandatory fields
- UNIQUE prevents duplicate values
- CHECK validates data range
- DEFAULT assigns automatic values

### Practice Summary
- Created tables using multiple constraints
- Inserted valid records
- Tested constraint failures for invalid data
- Understood how databases enforce rules internally



# Day 17 – SQL Views

### What I Learned
- What is a View in SQL
- Why Views are used
- How Views store SELECT queries
- How Views behave like tables

### Practice Summary
- Created a View using JOIN
- Retrieved data from the View
- Applied filtering on the View
- Listed all Views in the database

### Key Concept
Views help write clean, reusable, and secure SQL queries.



# Day 18 – SQL Index

### What I Learned
- What is an Index
- Why Index is used
- How Index improves SELECT query performance
- How to create and inspect Indexes

### Practice Summary
- Created an Index on student_name
- Executed queries before and after Index
- Viewed existing Indexes on the table

### Key Concept
Indexes make searching faster but require extra memory.



# Day 19 – SQL Transactions

### What I Learned
- START TRANSACTION begins a transaction
- COMMIT saves changes permanently
- ROLLBACK cancels changes
- SAVEPOINT allows partial rollback

### Practice Summary
- Updated records inside transactions
- Used ROLLBACK to undo changes
- Used COMMIT to save changes
- Practiced transaction safety concepts



# Day 20 – Stored Procedures

### What I Learned
- What is a Stored Procedure
- How procedures store reusable SQL logic
- Using input parameters in procedures

### Practice Summary
- Created procedure to retrieve all students
- Created procedure to retrieve students above certain marks
- Called procedures using CALL statement
- Viewed procedures using SHOW PROCEDURE STATUS



# Day 21 – MySQL Triggers

### What I Learned
- What is a Trigger
- How triggers automatically execute on table events
- Difference between BEFORE and AFTER triggers

### Practice Summary
- Created a log table
- Created an AFTER INSERT trigger
- Automatically stored inserted student names in the log table
- Verified trigger execution using SELECT query

### Key Concept
Triggers help automate actions in databases and are commonly used for logging, auditing, and enforcing business rules.



# Conclusion

This **21-day MySQL practice journey** helped me build a strong foundation in:

- SQL Queries
- Relational Database Design
- Data Integrity
- Performance Optimization
- Database Automation

Through consistent daily practice, I improved my understanding of **real-world database concepts and interview-relevant SQL topics**.

# Day 22 – SQL CASE Statement

Today I practiced **CASE statements in MySQL**, which allow conditional logic inside SQL queries.

## What I Learned
- How CASE works in SQL
- Using CASE for conditional categorization
- Applying conditions based on marks
- Combining CASE with ORDER BY

## What I Practiced
- Categorized students based on marks
- Created performance labels such as Excellent, Good, Average
- Used CASE inside SELECT queries
- Sorted categorized data

## Table Used
- students

## Key Concept
CASE statements allow SQL queries to apply conditional logic similar to if-else statements in programming.

# Day 23 – SQL Window Functions (ROW_NUMBER)

Today I practiced **Window Functions in MySQL**, specifically the ROW_NUMBER() function.

## What I Learned
- What are Window Functions
- How ROW_NUMBER() assigns ranking
- Difference between normal ranking and partition ranking
- Using ORDER BY inside window functions

## What I Practiced
- Ranked students based on marks
- Created department-wise ranking using PARTITION BY
- Observed how ranking resets for each department

## Table Used
- students

## Key Concept
Window functions allow calculations across rows related to the current row without grouping the results.

# Day 24 – SQL Ranking Functions

Today I practiced **SQL Ranking Functions** in MySQL.

## What I Learned
- What is RANK() function
- What is DENSE_RANK() function
- Difference between RANK and DENSE_RANK
- Department-wise ranking using PARTITION BY

## What I Practiced
- Ranked students based on marks
- Compared RANK and DENSE_RANK results
- Applied ranking inside departments

## Table Used
- students

## Key Concept
Ranking functions help analyze ordered data and are widely used in analytics and interview SQL questions.

# Day 25 – SQL LEAD() and LAG()

Today I practiced **LEAD() and LAG() window functions** in MySQL.

## What I Learned
- What is LAG() function
- What is LEAD() function
- How to access previous and next row values
- Using PARTITION BY with window functions

## What I Practiced
- Compared student marks with previous records
- Retrieved next row values using LEAD
- Performed department-wise comparison

## Table Used
- students

## Key Concept
LEAD and LAG functions help analyze sequential data by accessing values from previous or next rows.

# Day 26 – SQL Common Table Expression (CTE)

Today I practiced **Common Table Expressions (CTE)** in MySQL.

## What I Learned
- What is a CTE
- How CTE creates temporary result sets
- How CTE improves query readability
- Using CTE with filtering and aggregation

## What I Practiced
- Created simple CTE queries
- Filtered student records using CTE
- Calculated department-wise average marks using CTE

## Table Used
- students

## Key Concept
CTE allows complex SQL queries to be written in a cleaner and more readable way.

# Day 27 – Subquery vs CTE

Today I practiced **Subqueries and Common Table Expressions (CTE)** in MySQL and compared how the same problem can be solved using both approaches.

## What I Learned
- What is a Subquery
- What is a CTE
- Difference between Subquery and CTE
- How CTE improves readability

## What I Practiced
- Retrieved students scoring above average marks using subquery
- Solved the same problem using CTE
- Compared student marks with department average

## Table Used
- students

## Key Concept
Subqueries are useful for nested logic, while CTEs make complex queries easier to read and maintain.

# Day 28 – SQL Interview Query Practice

Today I practiced some common **SQL interview queries** using the students table.

## What I Learned
- How to find the second highest value in SQL
- How to retrieve top records using ORDER BY and LIMIT
- How to perform department-wise analysis using GROUP BY

## What I Practiced
- Found second highest marks using subquery
- Retrieved top 3 students based on marks
- Calculated highest marks for each department

## Table Used
- students

## Key Concept
Interview SQL questions often test understanding of subqueries, sorting, and aggregation functions.

# Day 29 – Detecting Duplicate Records in SQL

Today I practiced how to detect duplicate records in SQL tables.

## What I Learned
- What are duplicate records in databases
- How to detect duplicates using GROUP BY and HAVING
- How to retrieve duplicate rows using subqueries
- Basic concept of removing duplicate records

## What I Practiced
- Identified duplicate student names
- Retrieved duplicate rows from the students table
- Learned the SQL logic used to remove duplicates

## Table Used
- students

## Key Concept
Duplicate detection is important for maintaining clean and reliable database records.

# Day 30 – Mini SQL Project (Student Management System)

Today I built a small SQL project to apply the concepts learned during the MySQL practice journey.

## Project Overview
The project simulates a simple student management system with multiple tables.

## Tables Created
- students
- courses
- enrollments

## What I Practiced
- Table creation with primary and foreign keys
- Inserting relational data
- Joining multiple tables
- Performing analytical queries using GROUP BY

## Key Concept
Relational databases store data across multiple tables connected through foreign key relationships.
