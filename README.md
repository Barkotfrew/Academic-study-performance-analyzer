# Academic Study Performance Analyser 
Prepared by: SWEG Section A (2017/25)

■ Table of Contents

1. [Credits](#credits)
2. [Introduction](#introduction)
3. [What This Program Does](#what-this-program-does)
4. [Key Features](#key-features)
5. [Getting Started](#getting-started)
   - [What You Need](#what-you-need)
6. [How to Use the Program](#how-to-use-the-program)
   - [Step-by-Step Instructions](#step-by-step-instructions)
7. [Contributing](#contributing)
   
## Credits

Here are the contributors to the "Academic-Analyzer-project" repository along with their contributions:

Arsema Seife (@Arsema137)

Contributions: Assisted with the development of the code and readme file,also contributed to the documentation.

Abenezer Shiferaw (@Abinishifex)

Contributions: Assisted with the development of the code and flow chart,also contributed to the documentation.

Beamlak Atilabachaw (@labba1)

Contributions: Project lead,contributed to the documentation and Assisted with the development of the code and read me file.

Barkot Zerihun (@BarkiZed)

Contributions: Assisted with the development of the code,read me file also the documentation and created detailed samples of the output for the users.

Abigiya Fikru (@AbigiyaFikru)

Contributions: Assisted with the development of the code,read me file and documentation, also provided quality assurance of the program.

Barkot Frew (@Barkotfrew)

Contributions:  Assisted with the development of the code,readme file and documentation,also contributed to create a sample of the user interface and experience design.

## Introduction

Are you a student wanting to easily track your study hours and see your study pattern during the week? The Academic Study Performance Analyzer is a C++ program designed to assist second-year Software Engineering students in tracking their daily study hours leading up to final exams. By recording study hours each day, students can better organize their study schedules.

Students often record their daily study time in notebooks but struggle to summarize and analyze this data. This program allows students to input their study hours for each day of the week and generates a report showing the study hours for each day, the total weekly study hours, and the average study hours per day.

## What This Program Does

Have you ever written down your study hours in a notebook and then struggled to understand your overall study habits? This program helps you:                       

Add student: Collects student data and stores it in the database.

See results: Displays all students and their study statistics.

Search student: Allows searching by student name or code.

Delete student: Removes a student record from the database.

Generate conclusion: Identifies the student who studied the most hours.

Edit student hours: Modifies a student's study hours and recalculates totals.

## Key Features
Here's what this program can do:

Data Storage: Stores student names, IDs, and study hours for each of the 7 days of the week.

Calculations:Computes total study hours for each student.

Calculates the average daily study hours for each student.

Search Functionality: Allows users to search for a student by their name or ID.

Formatted Output: Displays the results in a clean tabular format for easy analysis.

Student Data Management: Add, edit, delete, and view data for multiple students.

Result Summary: Shows the student who studied the most.

No Limit on Students: The program can handle data for many students without any issues.

## Getting Started
### What You Need

A Computer: You need a computer to run this program.

C++ Compiler: You will need a C++ compiler to build and run the program. If you don’t have one, there are many available like GCC or Visual Studio.

SQLite: This program uses SQLite to store the study data. You will need to ensure the SQLite library is set up correctly.
## How to Use the Program

Once the program is running, it will ask you for some information:

1. Number of Students: The program will first ask for the number of students you are tracking the information for.
2. Student Data: For each student, the program will ask for the student name or ID, and the number of hours they studied for each day of the week (from Day 1 to Day 7).
3. Results Table: After you've entered all the student information, the program will show you a table with your data organized in a way that makes it easy to understand and see the overall weekly study patterns.
4. Search Data: After all the data has been entered, you can search for a particular student using their name or student ID.

### Step-by-Step Instructions

1. Enter the Number of Students: When the program starts, it will first ask you how many students you want to track the data for.
2. Enter Each Student's Data:
   - The program will then ask for the name or student ID of each student.
   - After that, it will ask for the study hours for each day of the week (Day 1 to Day 7) for each student.
3. See the Results Table: Once you’ve entered all the information, the program will display a table with all the data you entered, the total weekly study time for each student, and the overall daily average.
4. Search for a Student: The program will ask if you would like to search for the data of a particular student. If you answer yes, you will be prompted to enter the name or ID of the student that you are looking for.
