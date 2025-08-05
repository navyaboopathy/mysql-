🎓 College Portal Database – README  

📘 Overview

This project sets up a relational database called college_portal to manage student academic records in a college environment. It includes details about departments, students, courses, faculty, and marks.

🏗️ Database Schema
🔹 Tables and Relationships:
 1. Department

department_id (PK)

department_name

2. Student

student_id (PK)

name, email

department_id (FK → Department)

3. Course

course_id (PK)

course_name

department_id (FK → Department)

4. Faculty

faculty_id (PK)

name

course_id (FK → Course)

5. Marks

mark_id (PK)

student_id (FK → Student)

course_id (FK → Course)

marks, grade