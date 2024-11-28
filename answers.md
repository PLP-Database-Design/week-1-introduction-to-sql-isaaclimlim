## Question 1

The main components of a DBMS are as follows:
   Software
   Hardware
   Data
   Procedure
   Data Access Language
   Users


## Question 2

A relational database is a type of database that organizes data into tables (also called relations) consisting of rows and columns. Each table represents a specific type of data, and relationships can be established between tables through keys (primary keys and foreign keys). This structure makes it easier to retrieve, manage, and update data efficiently using a query language like SQL (Structured Query Language).

Key Features of Relational Databases:
Tables: Data is stored in rows and columns.
Keys: Use primary keys to uniquely identify records and foreign keys to connect related tables.
Relationships: Tables are linked through relationships to maintain data integrity.
SQL: Allows users to perform operations such as querying, inserting, updating, and deleting data.

Examples of Relational Databases:
MySQL: Open-source and widely used for web applications and online databases.
PostgreSQL: Known for its advanced features like support for complex queries and scalability.
Oracle Database: Popular in large enterprises due to its robustness and extensive capabilities.
Microsoft SQL Server: Used in many businesses for managing large-scale databases.

Relational databases are crucial for applications where data consistency and integrity are important, such as e-commerce websites, banking systems, and content management systems.

## Question 3

SQL (Structured Query Language) can be classified into three main categories based on the types of tasks they perform. Here are the classifications:

1. Data Definition Language (DDL)
   DDL is used to define or modify the structure of the database objects like tables, indexes, and schemas.
   Think of DDL as the tool you use to create the "skeleton" of your database. For example, when you want to create a table or alter its structure, you use DDL commands.

   Common Commands:
   CREATE: To create new database objects, like tables or schemas.
   Example: CREATE TABLE Students (ID INT, Name VARCHAR(50));
   ALTER: To modify existing database structures.
   Example: ALTER TABLE Students ADD Age INT;
   DROP: To delete database objects.
   Example: DROP TABLE Students;

2. Data Manipulation Language (DML)
   DML is used to manipulate data within database objects like tables.
   Once your database is set up, DML allows you to interact with the data. It’s like feeding data into the database or making changes to it.

   Common Commands:
   INSERT: To add new data into the table.
   Example: INSERT INTO Students (ID, Name, Age) VALUES (1, 'John', 20);
   UPDATE: To modify existing data.
   Example: UPDATE Students SET Age = 21 WHERE ID = 1;
   DELETE: To remove data from a table.
   Example: DELETE FROM Students WHERE ID = 1;

3. Data Query Language (DQL)
   DQL is focused on retrieving data from the database.
   When you want to see or analyze the data stored in the database, you use DQL. It’s like asking the database a question and getting the answer.

   Common Command:
   SELECT: To retrieve data from one or more tables.
   Example: SELECT \* FROM Students;
   This command fetches all records from the "Students" table.

Each classification has a specific role in database management. DDL helps set up the database, DML lets us work with the data, and DQL allows us to retrieve insights.

## Question 4

1. Primary Key
   A Primary Key is a unique identifier for a record in a table. It ensures that no two rows have the same value in the primary key column(s).
   `Purpose:` Its main job is to uniquely identify each row in a table, helping maintain data integrity.

Characteristics:
Unique: No duplicate values are allowed.
Non-Nullable: Every record must have a value for the primary key.
Single or Composite: It can consist of one or multiple columns.

2. Foreign Key
   A Foreign Key is a column (or a set of columns) in a table that establishes a link between the data in two tables. It references a Primary Key in another table.
   `Purpose:` Its main job is to maintain relationships between tables and enforce referential integrity.

Characteristics:
The values in a foreign key column must match the values in the referenced primary key column (or be NULL if allowed).
It links rows in one table to rows in another table.

## Question 5

An Entity-Relationship Diagram (ERD) is a visual representation used to design and understand databases. It shows how data is structured and how different pieces of data (called entities) are related to each other.

In an ERD:
Entities are the main objects or things we store information about, like "Students," "Courses," or "Orders." They’re usually represented as rectangles.
Attributes are the details about the entities, like a student’s name, ID, or email. They are shown as ovals connected to their entity.
Relationships show how entities are connected. For example, a student "enrolls in" a course, or an order "contains" products. Relationships are drawn as diamonds between the entities.

ERDs help developers plan how a database will work, making it easier to organize data and ensure all relationships between data are clear. This is especially useful for creating efficient databases in projects like school systems, e-commerce websites, or inventory management apps.

## Question 6

Relational databases are widely used in software development because of their structured and efficient approach to storing and managing data. Here are some key advantages:

1. Data Organization and Integrity
   Data is stored in structured tables with defined relationships, making it easy to organize and retrieve.
   Enforcing constraints like primary keys, foreign keys, and unique constraints ensures data integrity and reduces redundancy.

2. Scalability and Performance
   Relational databases handle large volumes of data efficiently.
   Optimized queries and indexing improve performance when dealing with complex datasets.

3. Flexibility with Querying
   The use of SQL (Structured Query Language) allows developers to perform complex queries, making it easier to extract, update, and manipulate data.
   Joins and nested queries enable combining and filtering data from multiple tables.

4. Data Security
   Role-based access control ensures that only authorized users can access or modify data.
   Built-in features like encryption and transaction management further enhance security.

5. Support for Transactions
   Relational databases follow the ACID properties (Atomicity, Consistency, Isolation, Durability), ensuring reliable transactions even in case of system failures.
   This is critical for applications like banking and e-commerce where accuracy is essential.

6. Cross-Platform Support
   Most relational databases are compatible across various platforms, programming languages, and frameworks, making them versatile for integration.

7. Data Consistency
   Changes in one part of the database automatically reflect in related areas due to the established relationships, ensuring consistent data.

8. Community and Tools
   Relational databases have been around for decades, so they come with extensive documentation, tools, and community support.
   Examples include MySQL, PostgreSQL, and Microsoft SQL Server.

## Question 7

1. Integer: Used to store whole numbers. For example, it can store values like 1, 50, or -200, often used for IDs or counts.

2. String (or Text): Used to store sequences of characters, such as names, addresses, or descriptions. For instance, "John Doe" or "Product Description".

3. Float (or Decimal): Used to store numbers with decimal points, like 12.34 or -0.56. It's often used for prices, measurements, or financial data.

4. Date/Time: Used to store dates and times, such as "2024-11-22" or "15:30:00". It's essential for tracking events or logging information over time.

## Question 8

A Database Management System (DBMS) is software that helps in managing and interacting with databases efficiently. Its purpose is to store, retrieve, and manipulate data systematically while ensuring data integrity, security, and scalability.

Key purposes of a DBMS include:

1. Data Organization and Storage: A DBMS organizes data in a structured way, making it easy to store and retrieve large amounts of information.

2. Efficient Data Access: It allows users to query and retrieve data quickly using query languages like SQL.

3. Data Integrity and Consistency: Ensures that the data remains accurate and consistent even when multiple users or applications access it simultaneously.

4. Data Security: Provides access control, ensuring only authorized users can view or modify specific data.

5. Backup and Recovery: Automates data backup and recovery processes to prevent loss during system failures.

6. Concurrency Control: Allows multiple users to access and update the database at the same time without conflicts.

7. Scalability: Handles increasing amounts of data and user load as applications grow.
