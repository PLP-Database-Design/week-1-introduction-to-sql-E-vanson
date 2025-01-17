Assignment Questions

1. State and Explain the components of a DBMS(Database Management System)
->  Query Processor:
It interprets the requests (queries) received from end user via an application program into instructions. It also executes the user request which is received from the DML compiler. 
->  Storage Manager:
Storage Manager is a program that provides an interface between the data stored in the database and the queries received. It is also known as Database Control System. It maintains the consistency and integrity of the database. It is responsible for updating, storing, deleting, and retrieving data in the database.
-> Data Dictionary:
 Acts as the central repository for metadata, providing information about the database’s structure and organization.




2. What is a relational database? Give 4 examples.
   ->  Stores data in tables that can be linked by relationships. eg MySQL, Postgre SQL, Oracle, IBM Db2



   

3. State and Explain three classifications of SQL?
   ->  Data Definition Language (DDL)
         Used to define and manage the structure of a database, including tables, schemas, and indexes.
         eg: CREATE TABLE Students (ID INT, Name VARCHAR(50), Age INT);
   ->  Data Manipulation Language (DML)
         Used to interact with and manipulate the data stored within database tables.
          eg: INSERT INTO Students (ID, Name, Age) VALUES (1, 'John', 20);
   ->  Data Control Language (DCL)
         Purpose: Used to control access to the database by granting or revoking permissions.
         eg: GRANT SELECT, INSERT ON Students TO User1;




4.  What is the difference between a Primary Key and a Foreign Key?
    -> Primary Key is a Unique identifiers for each row while a foreign key is a Link between tables that connect related data



    

5.  What is an Entity-Relationship Diagram?
    ->  diagram or model that is used to represent or show the relationship between the entities or data objects that are stored in a database


    

6.   What are the advantages of relational databases?
    -> Data Organization and Structure: Data is stored in tables (rows and columns), making it easy to organize and retrieve information and Tables can be linked using primary and foreign keys, enabling complex queries
    -> Data Integrity and Accuracy:  Features like primary keys, foreign keys, and unique constraints ensure data accuracy and eliminate duplication.
    ->  Ease of Querying: SQL a standardized query language enables easy interaction with the database for CRUD operations (Create, Read, Update, Delete)
     -> Data Security Access Control: Permissions can be set using Data Control Language (DCL) to restrict access to sensitive data.
     ->  Scalability Horizontal and Vertical Scaling: RDBMS systems can scale vertically by adding resources to a single server or horizontally by distributing the load across multiple servers.




     

8.   State four types of data type used to store data in tables?
    -> Numeric Data Types: Used to store numbers, both integers and floating-point values. eg: INT, FLOAT, DECIMAL
     -> Character/String Data Types: Used to store text or character strings. eg: CHAR(n), VARCHAR(n), TEXT
     -> Date and Time Data Types: Used to store date, time, and timestamp information. eg: TIME, DATE, DATETIME
     -> Boolean Data Types: Used to store logical values such as TRUE or FALSE.




     

9.  What is the purpose of a database management system (DBMS)?
      -> It serves as an interface between users, applications, and a database, allowing for the efficient and secure organization, storage, retrieval, and management of data.
      ->  Data Organization and Storage: A DBMS provides a systematic way to store data in a structured format (e.g., tables, indexes, and schemas) for easy access and management.
      -> Data Retrieval and Querying: Users and applications can retrieve specific data using query languages like SQL.
      -> Data Integrity and Accuracy: Ensures the consistency, accuracy, and validity of data through constraints (e.g., primary keys, foreign keys, and unique constraints).
      ->  Data Security: Controls access to data by managing user permissions and roles.
