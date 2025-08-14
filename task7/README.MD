Here’s a README.md for your Task 7 (Creating Views) program, written in simple sentences and structured for GitHub submission:


Task 7 – Creating Views

This SQL program demonstrates how to create and use **views** in MySQL.
A view is a virtual table that stores a query definition and allows users to access complex queries easily.

Steps in the Program

1. Drop old tables (`Employee` and `Department`) if they exist.
2. Create the(`Department`) table with department IDs and names.
3. Create the (`Employee`) table with employee details and a foreign key to `Department`.
4. Insert sample data into both tables.

 Views Created

1. HighSalaryEmployees

    Shows employees with salary above 50,000.
    Demonstrates a simple filter view.

2. EmployeeDepartment

    Joins `Employee` and `Department` to show employee details with their department name.
    Demonstrates a join-based view.

3. DeptAvgSalary

    Shows the average salary for each department.
    Demonstrates aggregation with `GROUP BY` in a view.

4. IT\_Employees

    Shows employees working only in the IT department.
    Demonstrates a restricted view for data security/abstraction.

5. Drop View Example

    Uses `DROP VIEW IF EXISTS` to remove the `IT_Employees` view.

Key Concepts Shown

 	Creating views with `CREATE OR REPLACE VIEW`.
 	Using views to simplify queries.
 	Hiding complexity by abstracting joins and aggregations.
 	Restricting data access through views.
	Dropping views when no longer required.



