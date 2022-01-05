# SQL

**SQL** por sus siglas en inglés significa Lenguaje de Consulta Estructurada (Structured Query Language), es un lenguaje de programación diseñado para actualizar, obtener, y calcular información en bases de datos relacionales.

**SQL is a standard language for accessing and manipulating databases.**

#### What is SQL?
**SQL** stands for _Structured Query Language_ 

**SQL** lets you _access_ and _manipulate databases_

**SQL** became a standard of the _American National Standards Institute (ANSI)_ in 1986, and of the _International Organization for Standardization (ISO)_ in 1987

#### 10 Things what can do SQL

1.  **SQL** can _execute queries against a database_
2.  **SQL** can _retrieve data from a database_
3.  **SQL** can _insert records in a database_
4.  **SQL** can _update records in a database_
5.  **SQL** can _delete records from a database_
6.  **SQL** can _create new databases_
7.  **SQL** can _create new tables in a database_
8.  **SQL** can _create stored procedures in a database_
9.  **SQL** can _create views in a database_
10. **SQL** can _set permissions on tables, procedures, and views..._


#### Keep in Mind That...
SQL keywords are NOT case sensitive: `select` is the same as `SELECT`
I will write all SQL keywords in upper-case.

#### Semicolon after SQL Statements?
Some database systems require a semicolon at the end of each SQL statement.
Semicolon is the standard way to separate each SQL statement in database systems that allow more than one SQL statement to be executed in the same call to the server.
I will use semicolon at the end of each SQL statement.

#### Some of The Most Important SQL Commands

+ `SELECT` - extracts data from a database
+ `UPDATE` - updates data in a database
+ `DELETE` - deletes data from a database
+ `INSERT INTO` - inserts new data into a database
+ `CREATE DATABASE` - creates a new database
+ `ALTER DATABASE` - modifies a database
+ `CREATE TABLE` - creates a new table
+ `ALTER TABLE` - modifies a table
+ `DROP TABLE` - deletes a table
+ `CREATE INDEX` - creates an index (search key)
+ `DROP INDEX` - deletes an index

#### SQL Statements
Most of the actions you need to perform on a database are done with SQL statements.

I will use the well-known **Northwind** sample database.

The following SQL statement selects all the records in the ***"Customers"*** table:

`SELECT` * FROM Customers;

Below is a selection from the "Customers" table:

A database most often contains one or more tables. Each table is identified by a name (e.g. "Customers" or "Orders"). Tables contain records (rows) with data.



Every `table` is broken up into smaller entities called `fields`. 
The fields in the Customers table consist of CustomerID, CustomerName, ContactName, Address, City, PostalCode and Country. 
A `field` is a `column` in a `table` that is designed to maintain specific information about every `record` in the `table`.

A `record`, also called a `row`, is each individual entry that exists in a `table`. For example, there are 91 records in the above Customers table. A record is a horizontal entity in a table.

A `column` is a vertical entity in a table that contains all information associated with a specific field in a table.

The SELECT DISTINCT statement is used to return only distinct (different) values.

Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.


[SQL Tutorial](https://www.w3schools.com/sql/default.asp, 'SQL Tutorial')
