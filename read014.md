# What is Normalization?
Normalization is a database design technique that reduces data redundancy and eliminates undesirable characteristics like Insertion, Update and Deletion Anomalies. Normalization rules divides larger tables into smaller tables and links them using relationships. The purpose of Normalization in SQL is to eliminate redundant (repetitive) data and ensure data is stored logically.

* What is a KEY?
A KEY is a value used to identify a record in a table uniquely. A KEY could be a single column or combination of multiple columns

## What is a Primary Key?

A primary is a single column value used to identify a database record uniquely.

* It has the following attributes

* A primary key cannot be NULL

* A primary key value must be unique

* The primary key values should rarely be changed

* The primary key must be given a value when a new record is inserted.



### Database - Foreign Key

Foreign Key references the primary key of another Table! It helps connect your Tables

* A foreign key can have a different name from its primary key

* It ensures rows in one table have corresponding rows in another

* Unlike the Primary key, they do not have to be unique. Most often they aren't

* Foreign keys can be null even though primary keys can not 