# SQL Commands

``` sql
    -- Create a database
    CREATE DATABASE database_name;

    -- Create a table
    CREATE TABLE table_name;

    -- Add data into table
    INSERT INTO table_name 
    (col1, col2, col3, ...)
    VALUES(val1, val2, val3, ...);

    -- Update a data
    UPDATE table_name SET column_name = value where condition;

    --example
    UPDATE Students SET date_of_birth = '15-09-1999' where id = '2';
    -- after set always provide values in key value pairs to affect more than one column

    --Delete data
    DELETE FROM table_name WHERE conditions;

    --Read data

    SELECT col1, col2, col3,... FROM table_name WHERE conditions;

    --example
    SELECT * FROM table_name; -- to select all columns from the table

    SElECT first_name, last_name FROM Students WHERE _id = 2; 

```
