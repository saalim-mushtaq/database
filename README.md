# Database

# Creating a database

CREATE DATABASE new_database;


# Creating a table

CREATE TABLE table_name (
  column_name1 data_type,
  column_name2 data_type,
  ...
);

# Inserting data into a table

INSERT INTO table_name (column_name1, column_name2, ...)
VALUES (value1, value2, ...);


# Deleting a database

DROP DATABASE database_name;


# Deleting a table

DROP TABLE table_name;

# Insert
INSERT INTO tablename (fname,lname,age,aaddress) VALUES ('abc','bvc','12','asdew');

# Query

SELECT * FROM tablename;

SELECT name,id FROM tablename;

SELECT * FROM tablename WHERE age = 12;

