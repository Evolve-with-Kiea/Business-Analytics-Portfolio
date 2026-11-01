# Business Queries

## SQL Fundamentals, Business Reporting, Data Retrieval & Analytical Problem-Solving

### SQL Projects | Business Analytics Portfolio

## Project Overview

**Business Queries** is a dedicated section of my Business Analytics portfolio focused on developing SQL skills through practical business questions, structured database queries, and analytical reporting exercises.

This folder will document my progression from foundational SQL statements to more advanced queries involving filtering, aggregation, joins, subqueries, and business performance analysis.

The purpose is to learn how to retrieve accurate information from relational databases, understand how tables connect, validate query results, and translate technical outputs into meaningful business insights.

My professional background in accounting, bookkeeping, accounts receivable, accounts payable, reconciliations, and financial operations provides a practical foundation for understanding transactional data, financial reporting, business processes, and data accuracy.

Through my ongoing Business Analytics studies, I intend to expand that experience into SQL querying, relational database concepts, business reporting, and analytical problem-solving.

Each completed project will begin with a clearly defined business question and include the SQL query, explanation of its logic, validation steps, actual results, and interpretation.

**Portfolio Category:** SQL / Business Analytics / Data Retrieval / Business Reporting

**Current Status:** Planned — Learning Framework Established

**Primary Language:** SQL

**Learning Level:** Beginner to Intermediate

**Potential Database Systems:** SQLite, PostgreSQL, or another suitable educational SQL environment

**Supporting Tools:** Microsoft Excel; potentially Python and Power BI

**Data Approach:** Public, synthetic, or appropriately authorized and protected data

**Primary Learning Goal:** Develop the ability to independently write, understand, validate, and explain SQL queries that answer practical business questions.

**Expected Deliverables:** SQL query files, project READMEs, documented database structures, verified query results, analytical explanations, and learning reflections.

---

# 1. Purpose

Organizations store information in databases containing customer records, sales transactions, products, invoices, expenses, inventory, and operational activity.

SQL, or Structured Query Language, provides a way to retrieve, filter, combine, summarize, and analyze this information.

However, writing SQL queries involves more than remembering commands.

It requires understanding the business question, identifying relevant tables, recognizing relationships, selecting appropriate calculations, and verifying that the results accurately represent the underlying data.

This folder focuses on developing those skills through practical business scenarios.

### Central Business Question

**How can SQL be used to retrieve, organize, summarize, and analyze business data to answer meaningful questions and support informed decision-making?**

### Supporting Questions

- What information does the business need?
- Which database tables contain the relevant data?
- How are the tables related?
- Which fields should be selected?
- What filters are appropriate?
- What level of detail is required?
- Which calculations should be performed?
- How can multiple tables be combined?
- How can query results be validated?
- What conclusions are supported by the results?

---

# 2. Learning Objectives

Projects in this folder are intended to strengthen my ability to:

1. Understand relational database fundamentals.
2. Identify tables and columns.
3. Understand primary and foreign keys.
4. Retrieve information using `SELECT`.
5. Filter records using `WHERE`.
6. Sort results using `ORDER BY`.
7. Calculate totals using `SUM`.
8. Count records using `COUNT`.
9. Calculate averages using `AVG`.
10. Identify minimum and maximum values.
11. Group records using `GROUP BY`.
12. Filter aggregated results using `HAVING`.
13. Combine tables using `JOIN`.
14. Understand join types.
15. Use aliases.
16. Work with `NULL` values.
17. Write subqueries.
18. Understand data grain.
19. Validate query results.
20. Explain business findings.
21. Document SQL projects.
22. Develop independent SQL problem-solving skills.

---

# 3. Learning Philosophy

The goal is to understand SQL logic rather than memorize completed queries.

### Recommended Learning Process

1. Read the business question.
2. Explain the expected result in plain language.
3. Identify the required tables.
4. Review the relevant columns.
5. Understand the relationships.
6. Write a basic query.
7. Add filters or calculations.
8. Run the query.
9. Inspect the results.
10. Check for unexpected records.
11. Validate calculations.
12. Explain what the query does.
13. Interpret the business meaning.
14. Document lessons learned.

### Important Principle

**A query is not considered understood simply because it runs. I should be able to explain how it retrieves information, why each SQL clause is used, and whether the result answers the intended business question.**

---

# 4. Question-to-Query Framework

Every project should follow a consistent analytical process.

| Stage | Question to Answer | Expected Documentation |
|---|---|---|
| Business Question | What does the business need to know? | Problem statement |
| Data Identification | Which tables contain the information? | Tables and fields |
| Data Grain | What does each row represent? | Level of detail |
| Query Planning | Which SQL clauses are required? | Plain-language logic |
| Query Development | How should the SQL be written? | SQL statement |
| Execution | What does the query return? | Actual results |
| Validation | Are the results accurate? | Verification checks |
| Interpretation | What do the results mean? | Business findings |
| Limitations | What cannot be concluded? | Assumptions and caveats |
| Documentation | How can the work be reviewed? | README and SQL file |

---

# 5. SQL Concepts & Business Applications

| SQL Element | Technical Purpose | Potential Business Application |
|---|---|---|
| `SELECT` | Retrieve specified columns | Display order details |
| `FROM` | Identify source table | Select sales transactions |
| `WHERE` | Filter rows | Orders within a date range |
| `ORDER BY` | Sort results | Rank products by revenue |
| `GROUP BY` | Aggregate records by category | Monthly sales summary |
| `HAVING` | Filter aggregated groups | Categories above a revenue threshold |
| `JOIN` | Combine related tables | Orders with customer information |
| `COUNT` | Count records or values | Number of orders |
| `SUM` | Calculate totals | Revenue or units sold |
| `AVG` | Calculate averages | Average transaction amount |
| `MIN` | Find minimum values | Earliest transaction date |
| `MAX` | Find maximum values | Highest transaction amount |
| `DISTINCT` | Identify unique values | Unique customer identifiers |
| `CASE` | Apply conditional logic | Classify transaction amounts |
| Subqueries | Use nested query results | Products above average price |

---

# 6. Understanding Relational Databases

A relational database organizes information into tables that may be connected through defined relationships.

### Hypothetical Business Database

| Table | Information Stored |
|---|---|
| Customers | Customer identifiers and attributes |
| Orders | Order-level transactions |
| OrderItems | Individual products within orders |
| Products | Product details and prices |
| Categories | Product classifications |

### Important Principle

**Understanding how data is organized is necessary before combining tables or calculating business metrics.**

---

# 7. Primary Keys & Foreign Keys

## Primary Key

A field, or combination of fields, used to uniquely identify a record.

### Example

`CustomerID` in a Customers table.

## Foreign Key

A field used to reference a related record in another table.

### Example

`CustomerID` in an Orders table.

### Potential Relationship

```text
Customers
CustomerID
    |
    | One-to-Many
    |
Orders
CustomerID
OrderID
```

### Important Consideration

Database relationships should be verified before joining tables.

---

# 8. Understanding Data Grain

**Data grain** describes what one row represents.

### Examples

| Table | Potential Grain |
|---|---|
| Customers | One row per customer |
| Orders | One row per order |
| OrderItems | One row per order line |
| Products | One row per product |
| Payments | One row per payment transaction |

### Why Grain Matters

An order may contain multiple products.

Joining Orders to OrderItems may create multiple rows for the same order.

If an order-level amount is summed after this join, revenue may be overstated.

### Important Principle

**Correct aggregation depends on understanding the level of detail represented by each table.**

---

# 9. SELECT Statements

## Purpose

Retrieve specified information from a table.

### Illustrative SQL

```sql
SELECT
    order_id,
    order_date,
    revenue
FROM sales;
```

### Business Question

What are the order identifiers, dates, and revenue amounts in the sales table?

### Concepts Demonstrated

- Selecting columns
- Identifying the source table
- Retrieving records

### Learning Questions

- Why select specific columns?
- What does `FROM` do?
- How does the result change when additional columns are selected?

---

# 10. Filtering with WHERE

## Purpose

Retrieve only records that meet defined conditions.

### Illustrative SQL

```sql
SELECT
    order_id,
    revenue
FROM sales
WHERE revenue > 100;
```

### Business Question

Which sales records have revenue greater than $100?

### Potential Business Applications

- Orders above a threshold
- Transactions within a reporting period
- Customers from a selected region
- Products in a specific category

### Important Consideration

Filters determine which records are included in the analysis.

---

# 11. Comparison Operators

| Operator | Meaning |
|---|---|
| `=` | Equal to |
| `<>` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

### Potential Business Applications

- Revenue thresholds
- Inventory levels
- Price comparisons
- Transaction classifications

---

# 12. Logical Operators

## Purpose

Combine multiple filtering conditions.

### Common Operators

- `AND`
- `OR`
- `NOT`

### Illustrative SQL

```sql
SELECT
    order_id,
    revenue,
    region
FROM sales
WHERE revenue > 100
  AND region = 'East';
```

### Business Question

Which orders in the East region have revenue greater than $100?

### Important Consideration

Logical conditions should be reviewed carefully to avoid unintentionally including or excluding records.

---

# 13. Sorting with ORDER BY

## Purpose

Arrange query results in a meaningful order.

### Illustrative SQL

```sql
SELECT
    product_name,
    revenue
FROM sales
ORDER BY revenue DESC;
```

### Business Question

Which sales records have the highest revenue?

### Important Consideration

This example sorts individual records. Ranking products by total revenue requires aggregation when products appear in multiple records.

---

# 14. Aggregate Functions

Aggregate functions summarize multiple values.

| Function | Purpose | Business Example |
|---|---|---|
| `COUNT()` | Count non-null values or rows, depending on usage | Number of orders |
| `SUM()` | Calculate a total | Total revenue |
| `AVG()` | Calculate an average | Average transaction amount |
| `MIN()` | Find minimum value | Earliest order date |
| `MAX()` | Find maximum value | Highest transaction amount |

### Important Principle

**Aggregation methods must match the meaning and grain of the underlying business data.**

---

# 15. COUNT

## Purpose

Count records or non-null values.

### Illustrative SQL

```sql
SELECT
    COUNT(*) AS total_records
FROM orders;
```

### Business Question

How many rows are stored in the Orders table?

### Important Consideration

`COUNT(*)` counts rows, while `COUNT(column_name)` counts non-null values in the specified column.

If an order can appear more than once, counting rows may not equal counting unique orders.

---

# 16. SUM

## Purpose

Calculate totals.

### Illustrative SQL

```sql
SELECT
    SUM(revenue) AS total_revenue
FROM sales;
```

### Business Question

What is the total recorded revenue?

### Important Consideration

The revenue column must be defined consistently, and duplicate or improperly joined records can distort the result.

---

# 17. AVG

## Purpose

Calculate an arithmetic average.

### Illustrative SQL

```sql
SELECT
    AVG(revenue) AS average_record_revenue
FROM sales;
```

### Business Question

What is the average revenue per non-null sales record?

### Important Consideration

Average revenue per record is not necessarily the same as average order value.

If each order contains multiple rows, order-level aggregation may be required.

---

# 18. MIN & MAX

## Purpose

Identify minimum and maximum values.

### Illustrative SQL

```sql
SELECT
    MIN(order_date) AS earliest_order,
    MAX(order_date) AS latest_order
FROM orders;
```

### Business Question

What is the earliest and latest recorded order date?

### Potential Applications

- Transaction date ranges
- Minimum prices
- Maximum order amounts
- Inventory comparisons

---

# 19. GROUP BY

## Purpose

Summarize records by one or more categories.

### Illustrative SQL

```sql
SELECT
    category,
    SUM(revenue) AS total_revenue
FROM sales
GROUP BY category
ORDER BY total_revenue DESC;
```

### Business Question

Which product categories generate the most recorded revenue?

### Concepts Demonstrated

- Grouping
- Aggregation
- Sorting

### Important Consideration

The query assumes the sales table contains valid category and revenue fields.

---

# 20. HAVING

## Purpose

Filter groups after aggregation.

### Illustrative SQL

```sql
SELECT
    category,
    SUM(revenue) AS total_revenue
FROM sales
GROUP BY category
HAVING SUM(revenue) > 1000;
```

### Business Question

Which product categories have total revenue above $1,000?

### WHERE Versus HAVING

| Clause | Purpose |
|---|---|
| `WHERE` | Filters rows before grouping |
| `HAVING` | Filters groups after aggregation |

### Important Principle

**Use WHERE to filter individual records and HAVING to filter aggregated results.**

---

# 21. JOIN Fundamentals

## Purpose

Combine information from related tables.

### Common Join Types

- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL OUTER JOIN`

### Important Consideration

SQL join support and syntax can vary by database system.

### Example Business Scenario

Combine order information with customer details to analyze purchasing activity.

---

# 22. INNER JOIN

## Purpose

Return records with matching values in both tables.

### Illustrative SQL

```sql
SELECT
    o.order_id,
    c.customer_name
FROM orders AS o
INNER JOIN customers AS c
    ON o.customer_id = c.customer_id;
```

### Business Question

Which orders have matching customer records?

### Important Consideration

Orders without matching customer records will not appear in this result.

---

# 23. LEFT JOIN

## Purpose

Return all records from the left table and matching records from the right table.

### Illustrative SQL

```sql
SELECT
    c.customer_id,
    o.order_id
FROM customers AS c
LEFT JOIN orders AS o
    ON c.customer_id = o.customer_id;
```

### Business Question

Which customers have orders, and which customers have no matching orders?

### Important Consideration

Customers with multiple orders will appear on multiple rows.

---

# 24. Avoiding Duplicate Totals After Joins

## Purpose

Prevent incorrect calculations caused by mismatched table grain.

### Potential Problem

An Orders table contains one row per order.

An OrderItems table contains multiple rows per order.

Joining these tables may repeat order-level values.

### Recommended Checks

- Identify table grain.
- Review join keys.
- Count records before joining.
- Count records after joining.
- Validate unique identifiers.
- Compare totals with source tables.

### Important Principle

**A query can run successfully and still return incorrect business totals.**

---

# 25. DISTINCT

## Purpose

Identify unique values.

### Illustrative SQL

```sql
SELECT DISTINCT
    customer_id
FROM orders;
```

### Business Question

Which unique customer identifiers appear in the Orders table?

### Important Consideration

Using `DISTINCT` should not replace investigating unexpected duplicate records.

---

# 26. COUNT DISTINCT

## Purpose

Count unique non-null values.

### Illustrative SQL

```sql
SELECT
    COUNT(DISTINCT customer_id) AS unique_customers
FROM orders;
```

### Business Question

How many distinct customers have recorded orders?

### Important Consideration

This assumes customer identifiers are consistently recorded.

---

# 27. Working with NULL Values

`NULL` represents a missing or unknown value in SQL.

### Illustrative SQL

```sql
SELECT
    order_id
FROM orders
WHERE customer_id IS NULL;
```

### Business Question

Which orders have no recorded customer identifier?

### Important Consideration

`NULL` is not equivalent to zero or an empty string.

Aggregate functions may handle null values differently depending on the function.

---

# 28. CASE Expressions

## Purpose

Create conditional classifications.

### Illustrative SQL

```sql
SELECT
    order_id,
    revenue,
    CASE
        WHEN revenue >= 500 THEN 'High Value'
        WHEN revenue >= 100 THEN 'Medium Value'
        ELSE 'Low Value'
    END AS order_category
FROM sales;
```

### Business Question

How can transactions be grouped into hypothetical value categories?

### Important Consideration

Classification thresholds should be documented as business-defined or hypothetical.

---

# 29. Subqueries

## Purpose

Use the result of one query within another.

### Illustrative SQL

```sql
SELECT
    product_name,
    price
FROM products
WHERE price > (
    SELECT AVG(price)
    FROM products
);
```

### Business Question

Which products are priced above the overall average product price?

### Concepts Demonstrated

- Nested queries
- Aggregate comparisons
- Filtering based on calculated values

---

# 30. SQL Aliases

## Purpose

Make query results and table references easier to understand.

### Illustrative SQL

```sql
SELECT
    category,
    SUM(revenue) AS total_revenue
FROM sales
GROUP BY category;
```

### Important Principle

Descriptive aliases improve query readability and make analytical results easier to interpret.

---

# 31. SQL Query Formatting Standards

Readable queries should follow consistent formatting.

### Recommended Practices

- Use descriptive aliases.
- Separate major SQL clauses.
- Indent join conditions.
- Use meaningful column names.
- Document complex calculations.
- Avoid unnecessary columns.
- Use comments when helpful.
- Keep business logic understandable.

### Example

```sql
-- Calculate revenue by product category
SELECT
    category,
    SUM(revenue) AS total_revenue
FROM sales
GROUP BY category
ORDER BY total_revenue DESC;
```

### Important Principle

**Clear SQL formatting supports debugging, validation, and professional documentation.**

---

# 32. Common SQL Mistakes

### Potential Errors

- Incorrect join keys
- Duplicate rows after joins
- Aggregating at the wrong grain
- Confusing `WHERE` and `HAVING`
- Ignoring `NULL` values
- Counting records instead of unique entities
- Incorrect date filters
- Missing grouping fields
- Using the wrong denominator
- Misinterpreting query results

### Recommended Approach

Identify the expected result before writing the query and validate the output afterward.

---

# 33. SQL Validation Framework

## Purpose

Verify that query results accurately represent the underlying data.

### Potential Checks

- Compare source row counts.
- Validate unique identifiers.
- Review join cardinality.
- Reconcile totals.
- Check for unexpected null values.
- Test filters.
- Verify aggregation levels.
- Compare with manual calculations.
- Review small samples.
- Confirm reporting periods.

### Important Principle

**SQL accuracy requires both correct syntax and correct business logic.**

---

# 34. Query Explanation Standard

Each completed project should explain its SQL logic in plain language.

### Recommended Questions

- What business question does the query answer?
- Which tables are used?
- Why were those tables selected?
- Which fields are retrieved?
- What filters are applied?
- Are records grouped?
- Which calculations are performed?
- Are joins required?
- How were the results validated?
- What does the output mean?

### Important Principle

**The ability to explain a query is an important part of demonstrating SQL understanding.**

---

# 35. Business Findings & Interpretation

A completed SQL project should explain what the query reveals.

### Recommended Framework

| Component | Documentation Expectation |
|---|---|
| Business Question | What information was requested? |
| Query | Which SQL statement was used? |
| Result | What values were returned? |
| Validation | How were results checked? |
| Finding | What does the output show? |
| Interpretation | Why might it matter? |
| Limitation | What remains uncertain? |
| Recommendation | What should be investigated next? |

### Important Consideration

SQL results describe information contained in the dataset. They do not automatically establish causation or support predictions.

---

# 36. Potential Project Ideas

These are future learning opportunities, not completed projects.

## Project 1: Top Products by Revenue

**Difficulty:** Beginner

**Primary SQL Concepts:** `SELECT`, `SUM`, `GROUP BY`, `ORDER BY`

### Business Scenario

A hypothetical retailer wants to identify products generating the highest revenue.

### Potential Tasks

- Select product information.
- Calculate revenue totals.
- Group by product.
- Sort results.
- Validate totals.
- Document findings.

### Intended Skills

- Aggregation
- Sorting
- Business interpretation

---

## Project 2: Monthly Sales Summary

**Difficulty:** Beginner to Intermediate

**Primary SQL Concepts:** Date handling, `SUM`, `COUNT`, `GROUP BY`

### Business Scenario

A fictional business wants to understand sales performance over time.

### Potential Tasks

- Identify transaction dates.
- Group records by month.
- Calculate monthly revenue.
- Count orders.
- Compare reporting periods.
- Document limitations.

### Intended Skills

- Time-based aggregation
- Business reporting
- Validation

### Important Consideration

Date grouping syntax varies by database system.

---

## Project 3: Customers with Repeat Purchases

**Difficulty:** Intermediate

**Primary SQL Concepts:** `COUNT`, `GROUP BY`, `HAVING`, potentially `JOIN`

### Business Scenario

A hypothetical business wants to identify customers with multiple recorded orders.

### Potential Tasks

- Identify customer records.
- Count distinct orders.
- Group by customer.
- Filter customers with repeat orders.
- Validate counts.
- Interpret results.

### Intended Skills

- Customer analytics
- Aggregation
- Filtering grouped results

---

## Project 4: Products Above Average Price

**Difficulty:** Intermediate

**Primary SQL Concepts:** `AVG`, subqueries, `WHERE`

### Business Scenario

A fictional retailer wants to identify products priced above the overall average.

### Potential Tasks

- Calculate average price.
- Write a subquery.
- Compare product prices.
- Sort results.
- Validate calculations.
- Document findings.

### Intended Skills

- Subqueries
- Aggregate calculations
- Business comparisons

---

# 37. Proposed Project File Structure

Each completed project should have its own subfolder.

### Illustrative Structure

```text
Business-Queries/
│
├── README.md
│
├── Top-Products-by-Revenue/
│   ├── README.md
│   └── query.sql
│
├── Monthly-Sales-Summary/
│   ├── README.md
│   └── query.sql
│
└── Repeat-Customer-Analysis/
    ├── README.md
    └── query.sql
```

### Potential Supporting Files

- SQL scripts (`.sql`)
- Database schema documentation
- Public or synthetic datasets
- Verified result samples
- Validation notes
- Project README

### Important Consideration

This structure is illustrative. Project folders should be created as projects are completed.

---

# 38. Project Documentation Requirements

Each completed project should include:

### Project Overview

- Project title
- Business question
- Analytical objective
- Intended audience

### Data Documentation

- Dataset source
- Database system
- Tables used
- Relevant fields
- Table relationships
- Data grain

### SQL Methodology

- SQL query
- Explanation of query logic
- Filters
- Joins
- Aggregations
- Assumptions

### Validation

- Expected results
- Actual results
- Reconciliation checks
- Errors encountered
- Corrections made

### Business Interpretation

- Findings
- Supporting evidence
- Limitations
- Potential recommendations

### Learning Reflection

- SQL concepts practiced
- Challenges encountered
- Skills demonstrated
- Lessons learned
- Potential improvements

### Documentation Reference

[Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md)

---

# 39. Data Privacy & Ethical Practices

All projects should use public, synthetic, or appropriately authorized and protected data.

### Data Guidelines

- Do not publish confidential company records.
- Do not expose customer personal information.
- Do not include account numbers.
- Do not publish credentials.
- Use fictional business scenarios.
- Label synthetic information.
- Document dataset permissions.
- Avoid unsupported business claims.

### Documentation References

- [Dataset Sources](../../Documentation/Dataset-Sources.md)
- [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md)

---

# 40. Connecting SQL to Other Analytical Tools

SQL can complement Excel, Python, and Power BI.

| Tool | Potential Role |
|---|---|
| SQL | Retrieve and summarize relational data |
| Excel | Validate calculations and explore results |
| Python | Clean, analyze, and visualize datasets |
| Power BI | Build interactive business reports |

### Potential Future Workflow

1. Retrieve data using SQL.
2. Validate query results.
3. Analyze data using Python or Excel.
4. Create Power BI visualizations.
5. Document business findings.

### Important Consideration

This is a potential future workflow rather than a completed integrated reporting system.

---

# 41. Potential Applications Across My Business Ecosystem

The SQL skills developed in this folder may eventually support business reporting across the Evolve with Kiea ecosystem.

### Shop the Evolution™

Potential applications:

- Product sales queries
- Order analysis
- Revenue summaries
- Customer purchasing patterns
- Product category performance

### Evolution Press®

Potential applications:

- Book sales reporting
- Publishing revenue summaries
- Product comparisons

### Evolve with Kiea

Potential applications:

- Digital product reporting
- Content performance summaries
- Audience engagement analysis

### Brand Evolution Marketing Agency

Potential future applications:

- Marketing campaign queries
- Customer analytics
- Business reporting
- Performance measurement
- Client reporting support

These are potential applications rather than completed SQL projects, deployed databases, or professional client work.

---

# 42. Professional Development & Career Alignment

This folder supports my ongoing development toward roles such as:

- Data Analyst
- Business Analyst
- Financial Data Analyst
- Business Intelligence Analyst
- Reporting Analyst
- Operations Analyst
- Marketing Analyst
- SQL Analyst

### Intended Skills

- SQL fundamentals
- Relational databases
- Data retrieval
- Filtering
- Sorting
- Aggregation
- Joins
- Subqueries
- Business calculations
- Data validation
- Analytical interpretation
- Technical documentation

These represent intended learning outcomes rather than completed competencies.

---

# 43. Project Completion Checklist

### Portfolio Foundation

- [x] Define folder purpose
- [x] Identify SQL concepts
- [x] Establish question-to-query workflow
- [x] Identify potential projects
- [x] Establish documentation standards

### SQL Fundamentals

- [ ] Practice `SELECT`
- [ ] Practice `WHERE`
- [ ] Practice `ORDER BY`
- [ ] Practice `COUNT`
- [ ] Practice `SUM`
- [ ] Practice `AVG`
- [ ] Practice `MIN` and `MAX`
- [ ] Practice `GROUP BY`
- [ ] Practice `HAVING`
- [ ] Practice joins
- [ ] Practice subqueries

### Project Development

- [ ] Select initial business question
- [ ] Select public or synthetic data
- [ ] Identify required tables
- [ ] Document table relationships
- [ ] Write SQL query
- [ ] Execute query
- [ ] Review results
- [ ] Validate calculations
- [ ] Explain findings

### Portfolio Documentation

- [ ] Save SQL script
- [ ] Create project README
- [ ] Document data source
- [ ] Explain query logic
- [ ] Record verified results
- [ ] Document limitations
- [ ] Update Portfolio Progress

---

# 44. Long-Term Learning Vision

The long-term objective of this folder is to develop practical SQL querying skills that can be applied to real business questions.

These projects will provide opportunities to strengthen relational database understanding, query logic, aggregation, joins, validation, and analytical communication.

As my technical skills develop, I intend to progress toward more advanced SQL techniques and integrate SQL with Excel, Python, and Power BI.

For my professional development, this folder supports the development of analytical skills applicable to accounting, financial analysis, marketing, operations, customer analytics, and business intelligence.

**The goal is not simply to write SQL statements that execute successfully. It is to understand the underlying business data, retrieve accurate information, validate results, and explain how the findings can support meaningful business decisions.**

---

## Current Status

**Planned — SQL Business Queries Framework Established**

No completed SQL Business Queries projects have been added to this folder yet.

This README defines the learning scope, foundational SQL concepts, potential project structure, and documentation requirements.

Projects will be added only after the queries have been independently written, executed, validated, explained, and documented.

Progress is tracked in [Portfolio Progress](../../Documentation/Portfolio-Progress.md).

---

## Related Documentation

- [Dataset Sources](../../Documentation/Dataset-Sources.md)
- [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md)
- [Portfolio Progress](../../Documentation/Portfolio-Progress.md)

---

## Navigation

- [Return to SQL Projects](../README.md)
- [Portfolio Home](../../README.md)

---

*This folder is intended for educational and professional portfolio development. Proposed SQL exercises do not represent completed queries, validated business findings, or demonstrated technical competencies until supporting work has been completed and documented.*
