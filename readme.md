# Hi, This is a full MySQL learning repo.

# "Select":
- This command is used to retrieve data from given tables
  
# Syntax to retrieve all columns in the table:
- Select * from TableName;

# Syntax to retrieve specific columns in the table:
- Select col1,col2,col4 from TableName;

# distinct keyword:
- This command retrieves unique values for the specific columns and eliminates duplicate values

- Select distinct column from TablenName;
# Where clause:
-Purpose of this clause is to filter records based on some condition

* example:
-  Select * from TableName where condition;
-  Select col1,col2 from TableName where condition;

# Logical Operator:
- Purpose: To filter the records based on Multiple Conditions
- Different Logical Operators we can use in Where Clause Condition:
# AND
# OR
# NOT

# order by clause:
-  Purpose is to order the retrieved records in ascending or descending order

* example:
-  SELECT * FROM Products Order By Price ASC;
-  SELECT * FROM Products Order By Price DESC;

# in operator:
-  Simplifies providing multiple values in Where Clause, when all the values are from the same column

* example:
-  Select * from Customers where Country in ('USA','Canada','UK');

# MySQL Built-in Functions can be categorized into:
- String Functions
- Numeric Functions
- Date and Time Functions
- Aggregate Functions

# Documentation link of mysql functions:
- https://dev.mysql.com/doc/refman/8.4/en/built-in-function-reference.html
  
# Few Built-In Functions:
# 1. String functions

- 1. upper():
- One of the built-in functions of MySQL 
Converts the text under the specified Column data to Upper Case

- 2. lower():
- One of the built-in functions of MySQL 
Converts the text under the specified Column data to Lower Case

- 3. length():
- One of the built-in functions of MySQL 
Finds the size of the data under the specified Column

- 4. instr():
- One of the built-in functions of MySQL 
Finds the position of the given text in the data of the specified Colum

- 5. concat():
- One of the built-in functions of MySQL 
Adds Two or More Table Column data together

-  6. trim():
-  One of the built-in functions of MySQL 
Removes the leading and trailing spaces of the Column data

- 7. substr():
- One of the built-in functions of MySQL 
Retrieves a portion of text from the data of the specified column

# 2. Numeric functions:
- 1. abs():
- One of the built-in functions of MySQL
Returns the positive values irrespective of the given positive or negative number data in the specified column

- 2.mod():
- One of the built-in functions of MySQL
Returns the remainder value of the numeric data of the specified column

- 3. greatest() and least()
- Returns the greatest and least values of the given numeric values

- 4. truncate():
- Returns the numerical values with the allowed number of digits after decimal point

- 5. power() and sqrt():
- Select power(3,4);
Select sqrt(2);

# 3. Date and time functions:
- Select current_date()/Select curdate();
- both returns current date in a string format
- Select current_time()/Select curtime();
- both returns current time in hr:min:sec format
- select now()/select sysdate();
- both returns current time and date simultaneously
- Select year;
- Select month;
- Select day;
- Select monthname;
- Select dayname;

# 4. Aggregate Functions:
- Select avg(price) from Products;
- Select min(price) from Products;
- Select max(price) from Products;
- Select count(*) from Products;
- Select sum(price) from Products;

# Arithmetic operator:
- The below are the different Arithmetic Operators we can use in the SQL Statements:
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Modulus (%)
