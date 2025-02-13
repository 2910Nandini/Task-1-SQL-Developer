# Task-1-SQL-Developer
# Student Management System Project for SQL Developer domain

# Objective
The project focuses on providing students with practical experience in SQL database creation,data manipulation, and analysis using student performance data.

# Project Steps
1. Database Setup
    ● Create a database named StudentManagement.
    ● Create a table named Students with the following fields:
        ○ StudentID: Primary Key, INT, an auto-incrementing integer.
        ○ Name: Stores the student's name (up to 50 characters).
        ○ Gender: A single character (VARCHAR, 1 - 'M' for Male, 'F' for Female).
        ○ Age: INT
        ○ Grade: Academic grade (VARCHAR, 10 - e.g., 'A', 'B', 'C', etc.).
        ○ MathScore, ScienceScore, EnglishScore: Integers representing scores in respective subjects.
2. Insert Data
    Populate the Students table with at least 10 sample records, including a variety of names, genders, grades, and scores in Math, Science, and English.
3. Tasks to Perform
    1. Display all students and their details to get an overview of the data.
    2. Calculate the average scores for each subject to understand subject-wise performance.
    3. Find the student(s) with the highest total score across all subjects to identify the top performer.
    4. Count the number of students in each grade to observe grade distributions.
    5. Find the average score for male and female students to compare performance by gender.
    6. Identify students whose Math score is above 80 to highlight high achievers in Math.
    7. Update the grade of a student with a specific Student ID to reflect changes or corrections.
