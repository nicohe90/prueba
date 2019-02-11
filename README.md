# UI Bootcamps - Node.Js

![Globant](assets/globant.jpg)

## __IMPORTANT DISCLAIMER__
This is not your typical _crash course_, this is a **Bootcamp**.

What does that mean?

- _You will give your best_

- _We will give our best_

- _We will all have a good time_


But most important, there will be **A LOT** of humor, because a happy developer _(student, pupil, padawan, you get the point...)_ is a great and hard working developer.


_That said..._


## Welcome to the bootcamp, learning time has begun

![Workout](assets/workout.gif)

Please, use this repository as a base for all your work. The idea is to
fork this project so everyone uses the same folder structure for the
exercises.

### Index

1. [Objective](#objective)

2. [Who Should Attend](#who-should-attend)

3. [Duration](#duration)

4. [Technical Assistance](#technical-assistance)

5. [Performance Measurement](#performance-measurement)

6. [Handling advanced Developers](#handling-advanced-developers)

7. [Materials](#materials)

8. [Bootcamp Schedule](#bootcamp-schedule)

9. [General Guidelines](#general-guidelines)

10. [Learning Days](#learning-days)

  - 10.1 [Week 1: Knowing your Node](#week-1-knowing-your-node)
  - 10.2 [Week 2: Js and Node: Brothers in arms](#week-2-js-and-node-brothers-in-arms)
  - 10.3 [Week 3: From REST to TEST](#week-3-from-rest-to-test)
  - 10.4 [Week 4: Store and Deploy](#week-4-store-and-deploy)

11. [Final Project](#final-project)

### Objective

We will teach you the basics of REST API development and Node.Js development.


### Chapter 6: Testing


→ [index](#index)

## Week 4: Store and Deploy
### Chapter 7: Storing
 - [SQL Databases](#SQL-Databases)
 - Postgres
 - Sequelize

### SQL Databases

What is a database?

A database is a collection of data used in a website or application. There are various ways of representing data, but in this workshop we focus on data represented in tables with rows and columns (like Excel). Databases are useful because they are persistent and scalable. 

Within a database, a schema represents how the data is organized, specifying the format and type. For example, we might have two columns called ‘name’ and ‘age’, with name being a type of string, and age being a type of integer.

What is SQL?

SQL stands for Structured Query Language, and a query is a request for information from the database. To begin, we introduced the basic structure of SQL queries.

![SQL Cheat Sheet 1](./assets/SQL-Cheet-Sheet-1.png)

![SQL Cheat Sheet 2](./assets/SQL-Cheat-Sheet-2.png)

![SQL Cheat Sheet 3](./assets/SQL-Cheat-Sheet-3.png)

![SQL Join Types](./assets/sql-join-types.jpg)

What is ORM?

Object-Relational Mapping is a technique that lets you query and manipulates data from a database using an object-oriented paradigm. ORM loves objects as much as developers, and is available for any programming languagee of your choosing.

OK, but what does an ORM do?

ORMs can be thought of as a translator converting our code from one form to another.

The ORM software generates objects (as in OOP) that virtually map (like the map of a city) the tables in your database. Then the programmer would use these objects to interact and play with the database! So the core idea is to try and shield the programmer from having to write optimized and complex SQL code — the ORM generated objects take care of that for you.

![ORM](./assets/orm.png)


What is PostgreSQL?

PostgreSQL comes with many features aimed to help developers build applications, administrators to protect data integrity and build fault-tolerant environments, and help you manage your data no matter how big or small the dataset. In addition to being free and open source, PostgreSQL is highly extensible. For example, you can define your own data types, build out custom functions, even write code from different programming languages without recompiling your database!

Sequelize

Sequelize is a promise-based ORM for Node.js and io.js. It supports the dialects PostgreSQL, MySQL, MariaDB, SQLite and MSSQL and features solid transaction support, relations, read replication and more.

#### Reading:
 - [SQL - tutorialspoint](https://www.tutorialspoint.com/sql/sql-overview.htm)
 - [SQL - w3schools](https://www.w3schools.com/sql/default.asp)
 - [SQL Cheatsheet](http://www.sqltutorial.org/sql-cheat-sheet/)
 - [Postgres Tutorial](https://www.postgresql.org/docs/11/tutorial.html)
 - [How to get started with postgresql](https://medium.freecodecamp.org/how-to-get-started-with-postgresql-9d3bc1dd1b11)

### Chapter 8: Preparing for Production
