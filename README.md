# Academic Study Performance Analyser 
Prepared by: SWEG Section A (2017/25)

■ Table of Contents

1. [Credits](#credits)
2. [Introduction](#introduction)
3. [What This Program Does](#what-this-program-does)
4. [Key Features](#key-features)
5. [Getting Started](#getting-started)
   - [What You Need](#what-you-need)
   - [Installing and Running the Program](#installing-and-running-the-program)
6. [How to Use the Program](#how-to-use-the-program)
   - [Step-by-Step Instructions](#step-by-step-instructions)
7. [Example Input and Output](#example-input-and-output)
8. [Contributing](#contributing)
   

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
