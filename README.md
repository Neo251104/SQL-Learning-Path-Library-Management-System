LibraryDB SQL Project
1. Project Overview

This project builds a simple Library Management Database using SQL.
It models members, books, and borrowing transactions.
It includes reporting and analytical queries.

2. Purpose

Practice database design

Practice SQL CRUD operations

Practice filtering, aggregation, joins, and CASE logic

Simulate real library reporting

3. Database Details
3.1 Database Name

LibraryDB

3.2 Tables
3.2.1 Members

Stores library member information.

Fields:

member_id Primary key

first_name

last_name

join_date

email

membership_type

3.2.2 Books

Stores book inventory details.

Fields:

book_id Primary key

title

author

genre

published_year

total_copies

available_copies

3.2.3 Borrowing

Tracks borrowing transactions.

Fields:

transaction_id Primary key

member_id Foreign key

book_id Foreign key

borrow_date

due_date

return_date

status

4. Sample Data

5 members

7 books

8 borrowing transactions

This data supports realistic querying and analysis.

5. Queries Included
5.1 Member Queries

Show all members

Show member names and emails

Find students

Find members who joined after a specific date

Count total members

Sort members alphabetically

5.2 Book Queries

Find books with zero available copies

Show book titles and authors

Find classic books published before 1950

Calculate average publication year

Identify the newest book

Count books per genre

5.3 Borrowing Queries

Show borrowing transactions from January 2024

Count how many books each member borrowed

Identify overdue books

Calculate average loan duration for returned books

6. Join-Based Reports

Members with their borrowed books

Books borrowed by a specific member

All books with borrower details, including unborrowed books

Popular books borrowed more than once

Members who never borrowed a book

7. Business Analytics
7.1 Revenue Simulation

Assigns monthly fees per membership type

Calculates total monthly revenue

7.2 Book Availability Report

IN STOCK

LOW STOCK

OUT OF STOCK

7.3 Member Loyalty Analysis

New Member

Active Member

Gold Member

8. SQL Dialect

Written using SQL Server syntax

Uses TOP, DATEDIFF, and CASE

Minor changes needed for MySQL or PostgreSQL

9. How to Run

Open SQL Server Management Studio or a compatible SQL tool

Run the script from top to bottom

Ensure database and tables are created before running queries

10. Learning Outcomes

Database relationships

INNER JOIN and LEFT JOIN usage

Aggregations with GROUP BY and HAVING

Business logic using CASE statements

11. Use Cases

Academic SQL projects

Exam preparation

Interview practice

Small library system prototype
