📋 Objective

This task is part of the SQL Developer Internship and focuses on practicing core DML operations such as INSERT, UPDATE, and DELETE, along with handling NULL values and default constraints in SQL.


🛠 Tools Used

SQLiteStudio (you can also use DB Fiddle or any SQL IDE)



📁 What I Did

Created a table named employees with the following fields:

id (Primary Key)

name (NOT NULL)

department (NULL allowed)

salary (Default: 30000)

joining_date (Nullable)


Performed the following operations:

Inserted complete and partial data (some with NULL/default values)

Updated specific and multiple rows

Deleted a row based on condition

Used a TRANSACTION and demonstrated a ROLLBACK

Selected all data for final output


🔑 Key SQL Concepts Covered


INSERT INTO ... VALUES

INSERT INTO ... (columns) VALUES (...) for partial insertion

UPDATE ... SET ... WHERE ...

DELETE FROM ... WHERE ...

NULL value handling

DEFAULT constraint

IS NULL, ROLLBACK, and TRANSACTION