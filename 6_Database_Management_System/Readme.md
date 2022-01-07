## Types of DBMS: 
* Hierarchical
* Network, Rational
* Object-Oriented

### What is DBMS?

As the name suggests DBMS or Database Management System is a set of applications or programs that enable users to create and maintain a database. DBMS provides a tool or an interface for performing various operations such as inserting, deleting, updating, etc. into a database.

### What is RDBMS?

RDBMS stands for Relational Database Management System. It helps to access and store data more efficiently than DBMS. RDBMS stores data in the form of tables as compared to DBMS which stores data as files. Storing data as rows and columns makes it easier to locate specific values in the database and makes it more efficient as compared to DBMs.


### What is Database?

A Database is an organized, consistent, and logical collection of data that can easily be updated, accessed, and managed. Databases mostly contain sets of tables or objects (anything created using create command is a database object) which consist of records and fields. 
A tuple or a row represents a single entry in a table. An attribute or a column represents the basic units of data storage, which contain information about a particular aspect of the table. DBMS extracts data from a database in the form of queries given by the user.

### What are the advantages of a DBMS?

* **Data Sharing** - Data from a single database can be simultaneously shared by multiple users. Such sharing also enables end-users to react to changes quickly in the database environment.
* **Integrity constraints** - The existence of such constraints allows storing data in an organized and refined manner.
* **Controlling redundancy in a database** - Eliminates redundancy in a database by providing a mechanism that integrates all the data in a single database.
* **Data Independence** - This allows changing the data structure without altering the composition of any of the executing application programs.

Data independence refers to the characteristic of being able to modify the schema at one level of the database system without altering the schema at the next higher level.
Logical Data Independence: Logical data independence refers to the characteristic of being able to change the conceptual schema without having to change the external schema.
Physical Data Independence: Physical data independence can be defined as the capacity to change the internal schema without having to change the conceptual schema.

            External Level
                   |
            Logical level
                   |
            Physical Level

* **Provides backup and recovery facility** - It can be configured to automatically create the backup of the data and restore the data in the database whenever required.
* **Data Security** - DBMS provides the necessary tools to make the storage and transfer of data more reliable and secure. Authentication (the process of giving restricted access to a user) and encryption (encrypting sensitive data such as OTP, credit card information, etc.) are some popular tools used to secure data in a DBMS.

### What is Deadlock in DBMS ?

In a database, a deadlock is an unwanted situation in which two or more transactions are waiting indefinitely for one another to give up locks. Deadlock is said to be one of the most feared complications in DBMS as it brings the whole system to a Halt.

Deadlock can arise if the following four conditions hold simultaneously (Necessary Conditions) 

* **Mutual Exclusion** - One or more than one resource are non-shareable (Only one process can use at a time) 
* **Hold and Wait** - A process is holding at least one resource and waiting for resources. 
* **No Preemption** - A resource cannot be taken from a process unless the process releases the resource. 
* **Circular Wait** - A set of processes are waiting for each other in circular form. 


### Why is Functional Dependency? 
Functional Dependency (FD) is a constraint that determines the relation of one attribute to another attribute in a Database Management System (DBMS)
 Notes :- In a relational database, a tuple is one record (one row). Typically separated by commas, the values may be parameters for a function call or a set of data values for a database.

### Why is normalization used?

Normalization is a technique for organizing data in a database. It is important that a database is normalized to minimize redundancy (duplicate data) and to ensure only related data is stored in each table. It also prevents any issues stemming from database modifications such as insertions, deletions, and updates.

### What is SQL?

SQL is used to communicate with a database. A language which enables a user to create, modify and essentially interact with a database.

### SQL v/s Nosql

* SQL databases are relational, NoSQL databases are non-relational.
* SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.
* SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.


### What are SQL Joins?

SQL joins are used to combine records from two tables in a database system.

* (INNER) JOIN: Returns records that have matching values in both tables
* LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table
* RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table
* FULL (OUTER) JOIN: Returns all records when there is a match in either left or right table.

### What are ACID Properties ?

* **A (Atomicity)** - Transactions either take place or they dont. ('all or nothing' property)
* **C (Consistency)** -	 Db must be consistent before and after a transaction.
* **I (Isolation)** - Multiple transaction don't interfere with each other.
* **D (Durability)** -  Changes survive eventual failures of the system.



### Difference between Delete, Drop, Truncate?

* **Delete** - It is used to delete one or more rows of a table based on a condition. <BR/>
Example -  DELETE FROM Customers WHERE CustomerName = “Robinhood”;

* **Drop** - It is used to delete the complete table or database, schema is also removed.<BR/>
Example:  DROP TABLE LOGS;
                   DROPS DATABASE LOGS_DB;

* **Truncate** - It is used to clear the data inside the table. The table schema remains intact.
Example:  TRUNCATE TABLE LOGS;


### SQL Constraints

SQL constraints are used to specify rules for the data in a table.
Constraints are used to limit the type of data that can go into a table. This ensures the accuracy and reliability of the data in the table. If there is any violation between the constraint and the data action, the action is aborted.
Constraints can be column level or table level. Column level constraints apply to a column, and table level constraints apply to the whole table.<BR/>

The following constraints are commonly used in SQL:

* **NOT NULL** - Ensures that a column cannot have a NULL value.
* **UNIQUE** - Ensures that all values in a column are different.
* **PRIMARY KEY** - The PRIMARY KEY constraint that uniquely identifies each record in a table.
* **FOREIGN KEY** - A FOREIGN KEY is a field (or collection of fields) in one table, that refers to the PRIMARY KEY in another table.
* **CHECK** - Ensures that the values in a column satisfies a specific condition.
* **DEFAULT** - Sets a default value for a column if no value is specified.
* **CREATE INDEX** - Used to create and retrieve data from the database very quickly.

[SQL Keywords](https://www.w3schools.com/sql/sql_ref_keywords.asp) 