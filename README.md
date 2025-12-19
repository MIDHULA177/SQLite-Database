# SQLite-Database

Objective

The objective of this task is to use SQL inside Python to extract basic sales information from a SQLite database and display the results using print statements and a simple bar chart.

Tools Used

Python

SQLite (sqlite3 – built into Python)

pandas

matplotlib

Dataset

A small SQLite database named sales_data.db is created with a single table called sales.

Table Structure

product (TEXT)

quantity (INTEGER)

price (REAL)

Sample sales records are inserted directly using Python.

What the Script Does

Connects to a SQLite database (sales_data.db)

Creates a sales table if it does not exist

Inserts sample sales data

Executes an SQL query to calculate:

Total quantity sold per product

Total revenue per product

Loads the SQL query result into a pandas DataFrame

Prints the sales summary

Displays a bar chart showing revenue by product

Saves the chart as sales_chart.png
