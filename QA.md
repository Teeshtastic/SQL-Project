What are your risk areas? Identify and describe them.



QA Process:
Describe your QA process and include the SQL queries used to execute it.

** I am using this query to check if I have any problems with my primary keys.**

```SQL
SELECT 		column1, AVG(column2)
FROM 		table1
GROUP BY 	column1
LIMIT 		2;
```

