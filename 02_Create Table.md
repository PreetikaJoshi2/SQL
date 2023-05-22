### SQL CREATE TABLE Statement:
The create table statement is usedto create new table in a database.
 
    CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,   ...);
column parameters specifies the name of the column of the table.
The datatype parameter specifies the type of data the column can hold (e.g. varchar, integer, date, etc.).
   
    CREATE TABLE Students (
    StudentID int,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
    );
Here in this example we are creating a Students table where Lastname, FirstName, Address and city are the columns whoose data type is
varchar and length can be max 255 character.
The StudentID column is of type int and will hold an integer.
### Create Table Using Another Table:
A copy of an existing table can also be created using CREATE TABLE. The new table gets the same column definitions. All columns or specific columns can be selected.

    CREATE TABLE new_table_name AS
    SELECT column1, column2,...
    FROM existing_table_name
    WHERE ....;
The following SQL creates a new table called "TestTables" (which is a copy of the "Customers" table)

    CREATE TABLE TestTable AS
    SELECT customername, contactname
    FROM customers;
