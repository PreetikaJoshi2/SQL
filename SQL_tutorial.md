### SQL SELECT Statement:
1)  The SELECT statement is used to select data from a database.
2)  The data returned is stored in a result table, called the result-set
#### Syntax:
     SELECT * FROM table_name; (Use this syntax,If you want to select all the fields available in the table.)
     SELECT column1, column2, ...FROM table_name;(Here, column1, column2, ... are the field names of the table that you want to select.)
### SQL SELECT DISTINCT Statement:
1)   The SELECT DISTINCT statement is used to return only distinct (different) values.
2)   Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values
#### Syntax:
    SELECT DISTINCT column1, column2, ...FROM table_name;
### SQL Where Clause:
1)   The WHERE clause is used to filter records.
2)   It is used to extract only those records that fulfill a specified condition.
#### Syntax:
     SELECT column1, column2, ...FROM table_name WHERE condition;
### Operators in Where Clause:
      Operator  |   Discription  
     _____________________________
          =           Equal      
     _____________________________
          >         Greater than
     _____________________________
          <         Less than   
     _____________________________
          >=        Greater than 
                     or Equal      
      ____________________________              
         <=         Less than   
                     or equal   
     ____________________________              
         <> / !=    Not equal    
     _____________________________   
         BETWEEN    Between a    
                    certain range
     _____________________________              
         LIKE       Search for   
                    a pattern 
     ______________________________            
          IN        To specify   
                    multiple possible 
                    values for 
                    a column
          
 ### SQL AND, OR and NOT Operators: 
 The WHERE clause can be combined with AND, OR, and NOT operators.
 The AND and OR operators are used to filter records based on more than one condition:
 1) The AND operator displays a record if all the conditions separated by AND are TRUE.
 2) The OR operator displays a record if any of the conditions separated by OR is TRUE.
The NOT operator displays a record if the condition(s) is NOT TRUE.
#### AND Syntax:
     SELECT column1, column2, ...
     FROM table_name
     WHERE condition1 AND condition2 AND condition3 ...;
(Display that record which fullfill all the AND statement TRUE).
 #### OR Syntax:
     SELECT column1, column2, ...
     FROM table_name
     WHERE condition1 OR condition2 OR condition3 ...;
(Display that record which fullfill any OR statement TRUE).
