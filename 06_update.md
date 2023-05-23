### SQL UPDATE Statement:
The UPDATE statement is used to modify the existing records in a table.
#### UPDATE Syntax:
    UPDATE table_name
    SET column1 = value1, column2 = value2, ...
    WHERE condition;
The WHERE clause specifies which record(s) that should be updated.
   
    UPDATE Students
    SET StudentName = 'Smith', City= 'Frankfurt'
    WHERE StudentID = 101;
    
The above update statment update the students table where StudentID is 101;
#### UPDATE Multiple Records:
     UPDATE Studentss
     SET StudentName='Juan'
     WHERE Country='Mexico';
The above SQL statement will update the StudentName to "Juan" for all records where country is "Mexico".
