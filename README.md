Library Management System - MySQL Project

📌 Project Overview

This project implements a Library Management System using MySQL, designed to manage books, employees, customers, and transactions efficiently. The system supports book issuance, returns, and branch-wise employee management.

🏛 Database Schema

The project consists of the following key tables:

Branch: Stores details about each library branch.

Employee: Stores employee details including salary and position.

Books: Contains book information such as category, rental price, and availability.

Customer: Stores customer information and registration dates.

IssueStatus: Manages issued books and associated customers.

ReturnStatus: Tracks returned books and customer details.

📂 Project Files

library_management.sql → Contains database schema, sample data, and queries.

README.md → Project documentation.

⚙️ Setup Instructions

Install MySQL Server (if not already installed).

Open MySQL Workbench or Command Line.

Execute the SQL File:

Run library_management.sql to create tables and insert sample data.

Execute the provided queries to retrieve data.

Verify Outputs by running SELECT queries.

🔍 Key SQL Queries & Explanations

This project includes 12 SQL queries, solving various real-world problems:

Retrieve Available Books

Displays book title, category, and rental price where status is "yes".

List Employees by Salary

Retrieves employee names and salaries in descending order.

Retrieve Books Issued by Customers

Joins Books and IssueStatus to find issued books and respective customers.

Count Books by Category

Groups books based on category and counts the total.

List Employees Earning More than Rs. 50,000

Retrieves employees with high salaries.

Find Customers Registered Before 2022 Without Issued Books

Identifies customers who haven't issued any books.

Count Employees Per Branch

Counts employees grouped by branch.

Retrieve Customers Who Issued Books in June 2023

Filters issued books based on issue date.

Retrieve Book Titles Containing 'History'

Searches for books in the "History" category or with "history" in the title.

Find Branches with More than 5 Employees

Groups and filters branches based on employee count.

Retrieve Branch Managers and Addresses

Joins Employee and Branch to find managers and their branches.

List Customers Who Issued Books with Rental Price Above Rs. 25

Retrieves customers based on book rental price.
