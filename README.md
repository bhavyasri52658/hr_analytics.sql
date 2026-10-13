# HR Analytics Using SQL

## Project Overview
This project analyzes employee data using PostgreSQL to understand workforce distribution, salary patterns, employee performance, and attrition across departments.

The goal is to demonstrate how SQL can transform raw HR data into meaningful business insights that support data-driven human resource decisions.

## Tools Used
- PostgreSQL
- SQL
- GitHub

## Dataset
The project uses a sample HR dataset containing 15 fictional employees across five departments:

- Human Resources
- Information Technology
- Finance
- Sales
- Marketing

The dataset includes employee details, department, salary, joining date, experience, performance rating, and employment status.

## Key SQL Concepts
- CREATE TABLE and INSERT
- SELECT, WHERE, and ORDER BY
- GROUP BY and aggregate functions
- INNER JOIN
- CASE statements
- Subqueries
- Common filtering and conditional aggregation techniques
- Window functions, including RANK()
- Date-based analysis
- KPI calculations

## Business Questions Answered
1. How many employees work in the company?
2. How many employees are active, and how many have left?
3. What is the overall employee attrition rate?
4. Which department has the highest average salary?
5. Which department has the highest attrition rate?
6. Who are the highest-paid employees?
7. Which employees earn above the company average salary?
8. How does salary vary by experience level?
9. What is the distribution of employee performance ratings?
10. How do employee salaries rank within each department?
11. What is the total monthly salary cost by department?
12. How many employees joined in each year?

## Key Findings
- Total employees: 15
- Active employees: 11
- Employees who left: 4
- Overall attrition rate: 26.67%
- Average salary: ₹54,800
- Highest salary: ₹80,000
- Lowest salary: ₹40,000
- Highest average department salary: IT, at ₹63,000
- Highest department attrition rate: Marketing, at 66.67%

These findings are based on the sample dataset and are intended to demonstrate SQL analysis rather than represent a real company.

## Project Outcome
This project demonstrates the use of SQL to analyze employee data, calculate HR metrics, identify salary patterns, compare departments, and evaluate employee attrition.

It strengthened my practical understanding of SQL querying, data aggregation, joins, conditional logic, and window functions.

## How to Run
1. Open PostgreSQL using pgAdmin or another compatible SQL client.
2. Create or select a database.
3. Open `hr_analytics.sql`.
4. Execute the script in order.
5. Review the result tables produced by each analysis query.

## Author
Bhavya
