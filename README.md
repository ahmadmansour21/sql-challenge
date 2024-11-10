# sql-challenge

All code is written by me with the help of Xpert AI tool when experiencing challenges and roadblocks

The code for table schema and the relevant queries can be found in the "EmployeeSQL" folder in the sql-challenge repository.
The ERD as well as the code to generate the diagram can be found in the "ERD image" folder in the sql-challenge repository.

1. ERD diagram 
The recommended tool of quickDBD was used to generate the diagram. Using what was taught in class, the tables were individually made and then linked to each other via one table's primary key and its corresponding foreign key in another table.

2. Table Schemata
Basic postgreSQL commands were used to generate the tables such as CREAT TABLE (). The columns as per the provided csv files are specified in the brackets and the data type is specified for each column (varchar, int or date).
Once created, import relevant csv files into each table using the import/export tool and check that this worked using SELECT * FROM.

3. Queries
Now that the tables are created and the values are inserted, we use postgreSQL to query the tables to return all the desired information.
This section mainly was concerned with doing the correct joins to get the relevant information - a simple join between two tables or a more complex one where a third table is introduced to create a link between two tables that otherwise do not have columns in common.
Additionally, the use of WHERE, LIKE and EXTRACT were used for different filters.