### SQL SELECT Statement
1)  The SELECT statement is used to select data from a database.
2)  The data returned is stored in a result table, called the result-set
### SELECT Syntax  
     SELECT * FROM table_name; (Use this syntax,If you want to select all the fields available in the table.)
     SELECT column1, column2, ...FROM table_name;(Here, column1, column2, ... are the field names of the table that you want to select.)
### SQL SELECT DISTINCT Statement 
The SELECT DISTINCT statement is used to return only distinct (different) values.
Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values
### SELECT DISTINCT Syntax
    SELECT DISTINCT column1, column2, ...FROM table_name;
