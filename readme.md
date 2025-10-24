# SQL Developer Internship - Task 4: Aggregate Functions and Grouping

## Objective
[cite_start]The primary objective of Task 4 was to utilize **aggregate functions** and the **GROUP BY** clause to **summarize and analyze tabular data** from the `e_commerce` database.

## Key Concepts and Deliverables
Concept SQL Clause/Function Role in Task 4 
**Aggregation**  `SUM()`, `COUNT()`, `AVG()`, `MAX()`, `MIN()`  Used to calculate totals, averages, counts, and extremes. 
**Grouping**  `GROUP BY` Used to categorize data (e.g., summarizing orders per customer). 
**Group Filtering**  `HAVING` Used to filter the summarized results after grouping (e.g., showing only customers with > 1 order). 

### Files Included:
1.  `SQL_Script.sql`: Contains the working SQL code with examples for all required aggregates, grouping by single and multiple columns, and using both `WHERE` and `HAVING`.
2.  `Interview_Questions_Answers.md`: Detailed answers to the ten conceptual interview questions on aggregation and filtering.
3.  `README.md`: This summary document.

## Execution Details
The queries were written against the provided `e_commerce` database schema, primarily focusing on the `Orders` and `Order_Items` tables to calculate metrics such as total revenue, average order value, and the number of orders per customer. The complexity was kept at a basic level, strictly focusing on the core principles of aggregation and grouping.
