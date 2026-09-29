1. What problem does SQL solve that CSV files cannot?
SQL helps to efficiently store, search, filter, combine, and analyze large amounts of structured data.

A CSV file is basically a plain text table. It doesn't provide powerful tools for:

Searching millions of rows efficiently

Connecting related datasets

Controlling who can access or change data

Handling many users at the same time

Maintaining data consistency

A CSV file would require a separate program such as Python or Excel to perform operation.

2. What is the difference between a database table and a spreadsheet?

A database table is designed to store structured data efficiently and can handle large amounts of information. Multiple tables can also be connected using keys, such as Primary Keys and Foreign Keys. SQL is used to search, filter, and analyse the data.

A spreadsheet is more flexible and is mainly used for entering data, performing calculations, creating charts, and doing quick analysis. It is generally more suitable for smaller datasets and manual work.

3. What is a Primary Key?
A Primary Key is a column (or combination of columns) that uniquely identifies each row in a table.A primary key cannot contain duplicate values.
e.g ids

4. What is a Foreign Key?
A Foreign Key is a column that connects one table to another table's Primary Key.This allows databases to represent relationships between data.

5. What is the difference between WHERE and HAVING?
Both filter data, but they operate at different stages.

WHERE filters individual rows before grouping.

HAVING filters groups after GROUP BY.

6. What is the difference between ORDER BY and GROUP BY?
ORDER BY sorts results.

GROUP BY combines rows into groups, usually so you can perform calculations on each group.

7. What does DISTINCT do?
DISTINCT removes duplicate results.It is useful to know the unique values in a column.

8. When should you use LIMIT?
We use LIMIT when we only want certain number of rows returned.


9. What are aggregate functions?
Aggregate functions perform calculations on multiple rows and return a single result for each group.

Common aggregate functions include:

Function	Purpose
COUNT()	    Counts rows
SUM()	    Adds values
AVG()	    Calculates an average
MIN()	    Finds the smallest value
MAX()	    Finds the largest value


10. Why do Data Scientists prefer databases over Excel for large datasets?
Databases are generally better suited to large, structured, multi-user datasets.

Key reasons include:

Performance: Databases are designed to query large amounts of data efficiently.

Scalability: They can handle datasets much larger than typical spreadsheet workflows.

Relationships: Multiple tables can be connected using Primary and Foreign Keys.

SQL: Complex filtering, joining, grouping, and aggregation can be expressed precisely.

Data integrity: Databases can enforce rules that help prevent invalid or inconsistent data.

Concurrency: Multiple users and applications can work with the same database.

Security: Databases provide sophisticated permissions and access controls.

Reproducibility: SQL queries can be saved, reviewed, and rerun consistently.