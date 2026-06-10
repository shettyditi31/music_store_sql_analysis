# Music_Analysis_SQL
Data Analytics Project showcasing Music Analysis using SQL 
📌 Project Overview

This project analyzes a Music Store database using SQL to answer real-world business questions related to customer behavior, sales performance, music preferences, and revenue generation.

The analysis covers beginner, intermediate, and advanced SQL concepts including:

Joins
Aggregate Functions
Common Table Expressions (CTEs)
Window Functions
Subqueries
Data Filtering
Ranking Functions
Business-Oriented Analysis

The project demonstrates how SQL can be used to extract meaningful insights from a relational database and support data-driven decision-making.

🛠 Tools Used
SQL
PostgreSQL
Relational Database Management
Git & GitHub

📂 Project Structure
Music-Store-SQL-Analysis/
│
├── Music Project.sql              # SQL queries and solutions
├── MusicDatabaseSchema.png        # Database schema
├── album.csv
├── artist.csv
├── customer.csv
├── employee.csv
├── genre.csv
├── invoice.csv
├── invoice_line.csv
├── media_type.csv
└── README.md

🗄 Database Schema
The project uses a music store database containing information about:

Customers
Employees
Invoices
Invoice Lines
Artists
Albums
Tracks
Genres
Media Types
Playlists

📊 Business Questions Solved
Easy Level
Find the senior-most employee based on job title.
Identify countries with the highest number of invoices.
Find the top 3 invoice totals.
Determine the city generating the highest revenue.
Identify the best customer based on total spending.
Moderate Level
Find all Rock music listeners.
Identify the top 10 Rock artists by track count.
Find tracks longer than the average song length.
Advanced Level
Calculate the amount spent by each customer on artists.
Determine the most popular music genre in each country.
Identify the highest-spending customer for every country.

📈 SQL Concepts Demonstrated
Joins
INNER JOIN
(Used to combine data from multiple related tables.)

Aggregate Functions
COUNT()
SUM()
AVG()
(Used for business metrics and revenue analysis.)

Subqueries
Used to compare values against calculated results such as averages.
Common Table Expressions (CTEs)
WITH
(Used to simplify complex analytical queries.)

Window Functions
ROW_NUMBER()
OVER()
(Used for ranking and partition-based analysis.)

🔍 Key Insights Generated
Identified the highest revenue-generating city.
Discovered the most valuable customers.
Determined customer music preferences.
Analyzed genre popularity by country.
Found top-performing artists based on sales and track count.
Evaluated customer spending patterns across different artists.

🚀 How to Run
Create a PostgreSQL database.
Import the Music Store dataset tables.
Open the Music Project.sql file.
Execute the queries individually.
Review the results and insights generated.

📚 Learning Outcomes
Through this project, I gained hands-on experience with:
Writing complex SQL queries
Database analysis
Data exploration
Business intelligence reporting
Query optimization techniques
Advanced SQL concepts such as CTEs and Window Functions

