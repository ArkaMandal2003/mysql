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
-Purpose is to order the retrieved records in ascending or descending order

* example:
-SELECT * FROM Products Order By Price ASC;
-SELECT * FROM Products Order By Price DESC;
