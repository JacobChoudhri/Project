# Notebooks

The attached Jupyter notebooks to this Readme.md will serve the purpose of teaching the user how to use SQL , a data query language, on relational database management systems. Specifically using the language in order to fetch specific data from a database or update the database it self. SQL which stands for "Structured Query Language" is one of the most heavily used languages in the finance and BI sphere. This learning series will take you through three seperate notebooks leveling at Beginner, Intermediate, and finally Advanced. All of which will focus on a specific set of skills with sandboxs and tasks to practice your skills.



## 1st Notebook (Beginner)

The first notebook contains the basic functions and operators of SQL. You will take a look at things like SELECT FROM statements which are practially the stepping stones for every query you will write. You will also take a look at comparison operators like greater than and less than which can be used to fetch far more specific things from the table you are working with. Everything in the first notebook will give you a good foundation to start working with SQL.

1. Basic SELECT-FROM Statements
    *	Retrieving data from a single table
    *	Specifying column aliases
    *	Filtering rows with the WHERE clause
    *	Sorting data with the ORDER BY clause
2. Comparison Operators
    *	Using =, <>, <, >, <=, >= for comparisons
3. Logical Operators
    *	Using AND, OR, and NOT operators to combine conditions
    *	Understanding operator precedence
    *	LIKE, IN, BETWEEN
4. Aggregate Functions
    *	Calculating summary statistics with COUNT, SUM, AVG, MIN, MAX
    *	Applying aggregate functions with GROUP BY
    *	Filtering aggregated results with the HAVING clause



## 2nd Notebook (Intermediate)

The second notebook takes a bit of a deeper dive into SQL capabilities mostly focusing on unions, joins, and functions. Unions arent used as much as joins are but are still important when wanting to to access data from two or more SELECT command queries into one result set. Joins can be a very helpful tool when querying a database. There are also several types of joins as you see in the table of contents for this notebook. Similar to unions, joins gets you data from multiple tables on where they are similar or different. Its really helpful when trying to find relationships between tables.

1. Unions
    *	Combining rows from multiple SELECT statements
2. Joins
    *	Understanding different types of Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN
    *	Specifying join conditions using ON and WHERE clauses
3. Functions
    *	Using built-in functions, such as mathematical, string, and date functions
    *	Applying aggregate functions with GROUP BY and HAVING clauses
    *	Creating and using user-defined functions


## 3rd Notebook (Advanced)

This third notebook is where you will start to delve into the advanced world of SQL where the skills you will work with are often what corporate employees are using daily. Like mentioned previously there are multiple types of joins such as cross and conditional joins. CTEs (Common Table Expressions) make queries more readable whereas subqueries allow to you to do a query inside of another query to gather specific data. Like CTEs, window functions help increase the efficiency and reduce the complexity of queries that analyze partitions (windows) of a data set by providing an alternative to more complex SQL concept. Performance tuning is the general idea of optimizing your queries so that they run quicker and more efficiently.

1. Cross Joins and Conditional Joins
    *	Understanding Cross Joins and their applications
    *	Using Conditional Joins to combine data based on specific criteria
    *	Applying various join conditions using different operators
2. CTEs and Subqueries
    *	Exploring Common Table Expressions (CTEs) and their advantages
    *	Creating and using CTEs for complex queries 
    *	Leveraging Subqueries for advanced filtering and data accessing
3. Window Functions
    *	Understanding the concept of Window Functions
    *	Applying aggregate functions with Windows
4. Performance Tuning
    *	Optimizing queries using appropriate indexing strategies
    *	Identifying performance bottlenecks
    *	Understanding query optimization techniques and best practices
    *	Leveraging advanced SQL features for performance improvements


