Task 6 – Subqueries and Nested Queries

This SQL program demonstrates how to use subqueries in different parts of a query.

It works in any MySQL database without requiring CREATE DATABASE permission and will run without “table already exists” errors.

Steps in the Program

Drop old tables (Employee and Department) if they exist, so the script can run multiple times without conflicts.

Create the Department table to store department IDs and names.

Create the Employee table to store employee details such as ID, name, salary, and department ID.

Insert sample data into both tables for demonstration.

Queries in the Program
Scalar Subquery – Finds employees whose salary is above the overall average salary.

IN with Subquery – Finds employees who work in the IT department.

EXISTS Subquery – Lists departments that have at least one employee earning more than ₹60,000.

Correlated Subquery – Finds employees whose salary is higher than their department’s average salary.

Subquery in FROM Clause – Creates a derived table of average salaries per department and displays it with department names.

Key Concepts Shown
Scalar subqueries

Correlated subqueries

IN with subqueries

EXISTS for conditional checks

Derived tables using subqueries in the FROM clause

This program demonstrates advanced filtering and reporting techniques using subqueries in SELECT, WHERE, and FROM clauses.

