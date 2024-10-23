# student-grading-app
Student Grading Application
Overview
This application is a simple .NET console program that calculates and displays the average grades for a list of students based on their assignment scores. The purpose is to automate the grade calculation process for a teacher by performing basic math operations and displaying the final grade for each student.

Project Requirements
The program calculates the final grades for four students based on their five assignment scores. Each assignment is graded on a scale of 0-100, where 100 represents 100% correct.

Features:
The program calculates the average score for each student based on the five assignments.
It then displays the student's name, average score, and grade to the console in a formatted table.
Input:
Assignment scores for four students:
Sophia: 93, 87, 98, 95, 100
Nicolas: 80, 83, 82, 88, 85
Zahirah: 84, 96, 73, 85, 79
Jeong: 90, 92, 98, 100, 97
Output:
The program outputs the student’s name, average score, and grade:

css
Copy code
Student         Grade
Sophia          94.6    A
Nicolas         83.6    B
Zahirah         83.4    B
Jeong           95.4    A
Code Breakdown
Input Data: The grades for each student are stored as integers in separate variables.
Sum Calculation: The total sum of grades for each student is calculated by adding their assignment scores.
Average Calculation: The sum is divided by the number of assignments (5) to determine the average.
Output: The results are printed in a formatted table, showing each student's average score and their corresponding letter grade.
