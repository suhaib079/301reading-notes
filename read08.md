# SQL Structured Query Language

* SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

* There are many popular SQL databases including SQLite, MySQL, Postgres, Oracle and Microsoft SQL Server. 

* A relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

* By learning SQL, the goal is to learn how to answer specific questions about this data, like "What types of vehicles are on the road have less than four wheels?", or "How many models of cars does Tesla produce?", to help us make better decisions down the road.


* To retrieve data from a SQL database, we need to write **SELECT** statements, which are often colloquially refered to as queries.

* A query in itself is just a statement which declares what data we are looking for, where to find it in the database,

* If we want to retrieve absolutely all the columns of data from a table, we can then use the asterisk (*) shorthand in place of listing all the column names individually.

        SELECT * 
        FROM mytable;

*  if you had a table with a hundred million rows of data, reading through all the rows would be inefficient and perhaps even impossible.
In order to filter certain results from being returned, we need to use a WHERE clause in the query. 

        SELECT * 
        FROM movies
        WHERE id = 6;


* DISTINCT keyword will blindly remove duplicate rows

* to sort your results by a given column in ascending or descending order, using the ORDER BY clause.

        SELECT DISTINCT director FROM movies
        ORDER BY director ASC;

### Inserting new data

When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert. 