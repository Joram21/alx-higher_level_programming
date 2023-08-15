SQL - Introduction
1. What's a database
A database is a structured collection of data that is organized and stored in a way that allows for efficient retrieval, management, and manipulation of the data. It is used to store and manage various types of information, such as text, numbers, images, and more.

2. What’s a relational database
A relational database is a type of database that stores and organizes data in tables, which are related to each other through predefined relationships. Each table consists of rows (records) and columns (fields), and the relationships between tables are established based on keys.

3. What does SQL stand for?
SQL stands for Structured Query Language. It is a domain-specific language used for managing and manipulating relational databases. SQL allows you to perform tasks like querying data, defining and modifying database structures, and controlling access to the data.

4. What’s MySQL
MySQL is an open-source relational database management system (RDBMS) that uses SQL as its query language. It is widely used for various applications, ranging from small-scale websites to large-scale enterprise systems.

5. How to create a database in MySQL
To create a database in MySQL, you can use the following SQL command:
CREATE DATABASE database_name;

6. What does DDL and DML stand for
DDL stands for Data Definition Language. It includes SQL commands that are used to define, modify, and manage the structure of a database and its objects (tables, indexes, etc.). Examples of DDL statements are CREATE, ALTER, and DROP.
DML stands for Data Manipulation Language. It includes SQL commands that are used to manipulate the data within a database. Examples of DML statements are SELECT, INSERT, UPDATE, and DELETE.DML stands for Data Manipulation Language. It includes SQL commands that are used to manipulate the data within a database. Examples of DML statements are SELECT, INSERT, UPDATE, and DELETE.

7. How to CREATE or ALTER a table
To create or alter a table, you can use the CREATE TABLE and ALTER TABLE statements.

8. How to SELECT data from a table
To select data from a table, you can use the SELECT statement.

9. How to INSERT, UPDATE or DELETE data
To insert, update, or delete data, you can use the following statements:
-- Insert data
INSERT INTO customers (id, name, email) VALUES (1, 'John Doe', 'john@example.com');

-- Update data
UPDATE customers SET email = 'new_email@example.com' WHERE id = 1;

-- Delete data
DELETE FROM customers WHERE id = 1;

10. What are subqueries
Subqueries are queries that are embedded within other queries. They allow you to retrieve data from one table and use that data in another query. Subqueries can be used in various parts of a SQL statement, such as the WHERE clause, to perform more complex operations.

11. How to use MySQL functions
MySQL provides a wide range of built-in functions that you can use to perform various operations on data. These functions include mathematical functions, string functions, date and time functions, and more.
