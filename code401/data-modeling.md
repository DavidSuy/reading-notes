# Readings: Data Modeling

## Reading

### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1. What type of database is the best fit for the complex query intensive environment?

   For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries. On a high-level, NoSQL don’t have standard interfaces to perform complex queries, and the queries themselves in NoSQL are not as powerful as SQL query language.

2. What type of database is the best fit for hierarchical data storage?

   NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data). Hbase is an example for this purpose.

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

   For scalability: In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

### [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

   One-to-may relationship are some cases an entry in one table can be related to more than one entry in another. A many-to-one relationship is similar to a one-to-many relationship, this difference is in the point-of-view you take when naming the relationship.

2. Prior to designing your relational database, it might be useful to **_ a _** of the database tables and their relationships.

   When working with SQL databases it is often useful to create diagrams of the database tables and their relationships.

3. Explain the difference between a primary and foreign key.

   Primary keys uniquely identify each row in a table. A table typically has one primary key, but can have more. Foreign Key is a column or set of columns which match a primary key in another table.

## Videos

### [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. How do we treat keywords and parameters differently in SQL syntax?

   The SQL keyword MODIFY is used to change the structure, properties or constraints of a table. Data values to be added to a table are specified by using the SQL VALUES clause.

2. Define normalization within the context of schemas and data.

   The goal of normalized schemas is to avoid storage of duplicate data so that stored data can't become inconsistent. Because tables with a normalized schema don't contain duplicate data, they are highly suitable for supporting transactions in which data is inserted, updated, and deleted.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

   One-to-one: A record in one table is related to one record in another table. One-to-many: A record in one table is related to many records in another table. Many-to-many: Multiple records in one table are related to multiple records in another table.

## Bookmark and Review

[sequelize api](https://sequelize.org/master/)
