Project Name: SQL More Queries
Overview

This project aims to strengthen your understanding of SQL queries and database management using MySQL. Through a series of tasks, you'll learn various aspects of SQL, including user management, table creation, constraint implementation, data retrieval from multiple tables, and more.
Curriculum Information

    SE Foundations Average: 103.99%
    Project Type: Ongoing second chance project
    Project Start: Mar 13, 2024 6:00 AM
    Project Deadline: Mar 15, 2024 6:00 AM
    Auto QA Review: Scheduled to launch at the deadline
    Auto QA Review Results:
        Mandatory: 0.0/96
        Optional: 0.0/24
        Overall Score: 0.0%

Learning Objectives

By the end of this project, you should be able to:

    Create and manage MySQL users
    Grant and revoke privileges for users on databases and tables
    Understand primary keys and foreign keys
    Implement constraints such as NOT NULL and UNIQUE
    Retrieve data from multiple tables using JOIN and UNION
    Utilize subqueries effectively

Resources

To assist you in completing the tasks, make use of the following resources:

    Articles and tutorials on MySQL user management, constraints, joins, and subqueries
    MySQL Cheat Sheet for quick reference
    SQL Style Guide for writing clean and readable SQL queries
    MySQL 8.0 SQL Statement Syntax documentation

Setup Instructions

To set up the MySQL environment on your system:

    Update your Ubuntu system: sudo apt update
    Install MySQL Server: sudo apt install mysql-server
    Check the installed MySQL version: mysql --version
    Connect to the MySQL server: sudo mysql
    Optionally, use container-on-demand for MySQL:
        Request an Ubuntu 20.04 container
        Connect via SSH or Web terminal
        Start MySQL service in the container: service mysql start

Project Structure

    GitHub Repository: alx-higher_level_programming
    Directory: 0x0E-SQL_more_queries

Task Details

Here's a brief overview of the tasks included in this project:

    My Privileges!
        Write a script to list all privileges of MySQL users.
    Root User
        Create a MySQL server user with all privileges.
    Read User
        Create a database and a user with limited privileges.
    Always a Name
        Create a table with a non-null name column.
    ID Can't Be Null
        Create a table with a non-null ID column.
    Unique ID
        Create a table with a unique ID column.
    States Table
        Create a database and a states table.
    Cities Table
        Create a database and a cities table with a foreign key constraint.
    Cities of California
        List all cities of California without using JOIN.
    Genre ID by Show
        List shows with their genre IDs.
    Genre ID for All Shows
        List all shows with their genre IDs.
    No Genre
        List shows without a linked genre.
    Number of Shows by Genre
        Count the number of shows linked to each genre.
    My Genres
        List all genres of a specific show.
    Only Comedy
        List all comedy shows.
    List Shows and Genres
        List all shows with their linked genres.
    Not My Genre (Advanced)
        List genres not linked to a specific show.

Additional Notes

Feel free to explore additional SQL features and functionalities beyond the provided tasks. Experimenting with different queries and scenarios will deepen your understanding of SQL concepts and techniques. Good luck, and have fun!

