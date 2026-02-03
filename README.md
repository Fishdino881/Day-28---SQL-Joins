# Day-28 SQL-Joins

Overview

On Day 28, I studied SQL JOINs, which are used to combine data from multiple tables based on a related column. Joins are essential for working with normalized databases and real-world datasets.

Topics Covered

1. INNER JOIN
Returns only the rows that have matching values in both tables.

SELECT employees.name, departments.department_name
FROM employees
INNER JOIN departments
ON employees.dept_id = departments.id;


2. LEFT JOIN
Returns all records from the left table and matching records from the right table.

SELECT employees.name, departments.department_name
FROM employees
LEFT JOIN departments
ON employees.dept_id = departments.id;


3. RIGHT JOIN
Returns all records from the right table and matching records from the left table.

SELECT employees.name, departments.department_name
FROM employees
RIGHT JOIN departments
ON employees.dept_id = departments.id;


4. FULL JOIN
Returns all records when there is a match in either table.

SELECT employees.name, departments.department_name
FROM employees
FULL JOIN departments
ON employees.dept_id = departments.id;



Learning Outcome

Understood how tables are related using keys
Learned when to use different types of joins
Improved ability to query data across multiple tables
