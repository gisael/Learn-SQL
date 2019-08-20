
# Learn SQL using MySQL in one day

## Introduction

### SQL and Databases
Ok, let's start from the very beginning. What is SQL and what it is used for.

SQL stands for Structured Query Language and is a language used
to manage data stored in data bases. Specifically in *Relational Databases*

A relational database is just a table \(with columns and rows \) or a group of tables used to store data in a ordered manner.
In a relational database, columns are categories and rows are records
with values within categories.

For example, let's see the following student's database representation:

Student ID | Student Name | Student LastName
---------- | ------------ | ----------------
001 | Caesar | Smith
002 | Charlotte | Gonzalez
003 | Adriana | Mundarain

There are different implementations of the SQL been MySQL one of the most used around the world.


### Installing MySQL

Before start coding SQL we need to install the DBMS or software required to manage SQL (MySQL in our case). Despite we can work on MySQL through the command line, we are going to make use of a GUI called MySQL Workbench.

Once we have installed MySQL server and MySQL Workbench let's create our first database in order to start adding and showing data.

To create a database we use the keyword CREATE DATABASE. Note that I typed the keyword **all caps**, this is not required since MySQL is not case sensitive by default but it is a good practice to type keywords in all caps.

The syntax to create a database is shown below:

CREATE DATABASE name_of_database;

Example:

```
CREATE DATABASE contacts;
```

The above line of code is known as an SQL statement. Every SQL statement ends with a semi-colon \(;\)




-- Using SELECT to display messages
SELECT 'Hello World';
SELECT 'MySQL is fun!';

-- this is a comment
# this is another way to comment
/* We use this
in case we want
to comment more than
one line */

CREATE DATABASE companyHR;

-- SQL statements always end with a semicolon.

To let the DBMS know what DB we want to work on, we use the USE keyword.
USE name_of_database;
USE companyHR;

To delete a DB we used
DROP DATABASE IF EXISTS wrongDB;
The IF EXISTS keyword is optional and will avoid an error incase DB does not exists
