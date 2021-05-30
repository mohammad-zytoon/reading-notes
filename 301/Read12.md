# Mongo and Mongoose

### NosQl vs SQl


|                        SQl                               |                  NosQl                         |
|--------------------------------------------------------- |------------------------------------------------|
| RELATIONAL DATABASE MANAGEMENT SYSTEM (RDBMS)            |Non-relational or distributed database system   |  
| These databases have fixed or static or predefined schema|They have have dynamic schema                   |             | These databases are not suited for hierarchical data     |These databases are best suited for hierarchical|
|  storage.                                                | data storage.                                  |
| These databases are best suited for complex queries      |These databases are not so good for complex quer|
| Vertically Scalable                                      |Horizontally scalable                           |
| Follows ACID property                                    |Follows CAP(consistency, availability, partition tolerance)|




1. What kind of data is a good fit for an SQL database?

  - If the data is numeric, favor SMALLINT, INTEGER, BIGINT, or DECIMAL data types. ...
  - If the data is character, use CHAR or VARCHAR data types.
  - If the data is date and time, use DATE, TIME, and TIMESTAMP data types.
  - If the data is multimedia, use GRAPHIC, VARGRAPHIC, BLOB, CLOB, or DBCLOB data types.


2. Give a real world example: numaric(5) stored as 236.

3. 

  - Semi-structured or Unstructured data / flexible schema.
  - Limited pre-defined access paths and query patterns.
  - No complex queries, stored procedures, or views.
  - High velocity transactions.
  - Large volume of data (in Terabyte range) requiring quick and cheap scalability.


4. Which type of database is best for hierarchical data storage?

  - Document based database like MongoDB, and Redis are great for small scale, 
    hierarchical data with a relatively small amount of children for each entry.

5. Which type of database is best for scalability?

  - NoSQL databases



## sql vs nosql (Video)


1. What does SQL stand for?

  - SQL (pronounced "ess-que-el") stands for Structured Query Language. SQL is 
    used to communicate with a database. According to ANSI (American National 
    Standards Institute), it is the standard language for relational database management systems.


2. What is a realational database?

  - A relational database is a type of database that stores and provides access 
    to data points that are related to one another.


3. What type of structure does a relational database work with?

  - The relational model means that the logical data structures—the data tables, 
    views, and indexes—are separate from the physical storage structures. 


4. What is a ‘schema’?

  - A schema is a cognitive framework or concept that helps organize and interpret information. 


5. What is a NoSQL database?

  - A NoSQL database provides a mechanism for storage and retrieval of data that
    is modeled in means other than the tabular relations used in relational databases.


6. Howo does it work?

  - It represents a shift away from traditional relational database management systems 
    (RDBMS). ... Relational databases rely on tables, columns, rows, or schemas to organize 
    and retrieve data. In contrast, NoSQL databases do not rely on these structures and use 
    more flexible data models.


7. What is inside of a Mongo database?

  - MongoDB stores data records as documents (specifically BSON documents) which are 
    gathered together in collections. 


8. Which is more flexible - SQL or MongoDB? and why.

  - Some research has shown that the speed of MongoDB could be 100x faster than a relational
    database. Ad-hoc querying - MongoDB is very flexible and has advanced ad hoc query features. 
    Easy setup - MongoDB is said to be easier to set-up than a relational database management 
    system (RDBMS).


9. What is the disadvantage of a NoSQL database?

  - Disadvantages. NoSQL databases don't have the reliability functions which Relational 
    Databases have (basically don't support ACID).
  
