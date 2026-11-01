# SQL Projects

## Relational Databases, SQL Querying, Data Analysis & Business Intelligence

### Business Analytics Portfolio | SQL Learning & Development

## Project Overview

**SQL Projects** is a dedicated section of my Business Analytics portfolio focused on developing practical SQL skills through relational database exploration, structured queries, data validation, and business-focused analytical exercises.

This section will document my progression from understanding how databases organize information to writing SQL queries that retrieve, filter, combine, summarize, and analyze business data.

My professional background includes more than 20 years of experience in accounting and financial operations, including bookkeeping, accounts receivable, accounts payable, reconciliations, financial reporting, and enterprise business systems.

This experience provides a practical foundation for understanding transactional information, financial accuracy, business processes, and the importance of reliable reporting.

As I continue studying Business Analytics, I intend to expand that foundation through SQL, relational database concepts, data modeling, and analytical problem-solving.

Projects will be developed progressively and documented only after the relevant SQL queries, database explorations, and validation procedures have been completed.

**Portfolio Category:** SQL / Business Analytics / Database Analysis / Business Reporting

**Current Status:** Planned — No Completed Portfolio Projects

**Primary Language:** SQL

**Learning Level:** Beginner to Intermediate

**Potential Database Systems:** SQLite, PostgreSQL, or another appropriate educational database

**Supporting Tools:** Microsoft Excel; potentially Python and Power BI

**Data Approach:** Public, synthetic, or appropriately authorized and protected datasets

**Primary Goal:** Learn to understand relational databases, write accurate SQL queries, validate results, and explain how database information can support business decisions.

**Expected Deliverables:** SQL scripts, database documentation, entity relationship diagrams, validated query outputs, business interpretations, and project READMEs.

---

# 1. Purpose

Businesses depend on databases to store and organize information related to sales, customers, products, payments, invoices, expenses, and operations.

SQL, or Structured Query Language, is used to interact with relational databases and retrieve information needed for reporting and analysis.

Developing SQL skills requires two complementary abilities:

1. Understanding how information is structured and related within a database.
2. Writing queries that accurately answer specific business questions.

This section supports both areas through organized, practical learning projects.

### Central Learning Question

**How can SQL and relational database knowledge be used to retrieve accurate information, evaluate business performance, and support evidence-based decision-making?**

### Supporting Questions

- How is business information organized in relational databases?
- What does each database table represent?
- How are records connected?
- What are primary and foreign keys?
- How can SQL retrieve relevant records?
- How can transactions be filtered and summarized?
- How can multiple tables be joined accurately?
- How can business KPIs be calculated?
- How can incorrect results be identified?
- What conclusions can be supported by the available data?

---

# 2. SQL Project Directory

This section is organized into two primary learning areas.

| Project Area | Focus | Directory |
|---|---|---|
| Database Analysis | Database structures, schemas, keys, relationships, entity relationship diagrams, and data integrity | [Database Analysis](Database-Analysis/README.md) |
| Business Queries | SQL statements that answer specific business questions through filtering, aggregation, joins, and analytical calculations | [Business Queries](Business-Queries/README.md) |

### How the Folders Work Together

**Database Analysis** establishes an understanding of the information.

**Business Queries** uses that understanding to retrieve and analyze the information.

Both areas support the development of accurate, explainable SQL skills.

Neither folder currently contains completed portfolio projects.

---

# 3. Learning Philosophy

My SQL learning approach emphasizes understanding database logic and business meaning rather than simply memorizing SQL commands.

### Recommended Learning Process

1. Understand the business scenario.
2. Identify the analytical question.
3. Explore the database structure.
4. Identify relevant tables and fields.
5. Understand table relationships.
6. Write a plain-language query plan.
7. Develop the SQL statement.
8. Execute the query.
9. Review the returned records.
10. Validate the results.
11. Explain the SQL logic.
12. Interpret the business meaning.
13. Document lessons learned.

### Important Principle

**A SQL query is not considered complete simply because it executes successfully. Its results must also be accurate, relevant, and understandable.**

---

# 4. Learning Progression

SQL learning in this section follows a structured progression.

| Stage | Focus | Intended Outcome |
|---|---|---|
| 1 | Database Fundamentals | Understand tables, columns, records, and data types |
| 2 | Database Relationships | Understand keys, cardinality, and relational structures |
| 3 | Basic SQL Queries | Retrieve, filter, and sort records |
| 4 | SQL Aggregation | Calculate totals, counts, averages, and grouped summaries |
| 5 | Joins & Subqueries | Combine information and perform more complex analysis |
| 6 | Data Validation | Verify accuracy and investigate unexpected results |
| 7 | Business Interpretation | Translate query outputs into meaningful findings |
| 8 | Portfolio Documentation | Present reproducible SQL projects |

The progression will be based on understanding and practical application rather than speed.

---

# 5. Database Fundamentals

## Purpose

Understand how relational databases organize information.

### Core Concepts

- Databases
- Tables
- Rows
- Columns
- Data types
- Schemas
- Primary keys
- Foreign keys
- Relationships
- Constraints

### Business Application

A hypothetical retail database may contain separate tables for customers, orders, products, and payments.

Understanding those tables is necessary before calculating sales or analyzing customer behavior.

### Learning Objective

Develop the ability to explain what a database contains and how its information is organized.

---

# 6. Relational Database Structure

### Illustrative Database

| Table | Business Purpose |
|---|---|
| Customers | Stores customer information |
| Orders | Stores order-level transactions |
| OrderItems | Stores products included in orders |
| Products | Stores product details |
| Payments | Stores payment transactions |

### Important Principle

**Relational databases connect information through defined relationships rather than storing every business detail in a single table.**

---

# 7. Primary Keys & Foreign Keys

## Primary Key

A field or combination of fields that uniquely identifies a record.

## Foreign Key

A field that references a related record in another table.

### Illustrative Relationship

```text
Customers
customer_id (PK)
     |
     | One-to-Many
     |
Orders
order_id (PK)
customer_id (FK)
```

### Important Consideration

Understanding keys is essential for writing accurate joins and identifying data integrity problems.

---

# 8. Understanding Data Grain

**Data grain** describes what one row represents.

### Examples

| Table | Grain |
|---|---|
| Customers | One row per customer |
| Orders | One row per order |
| OrderItems | One row per order line |
| Products | One row per product |
| Payments | One row per payment transaction |

### Why Grain Matters

An order may contain multiple order items.

Joining order-level and item-level data can multiply records.

If calculations do not account for that difference, revenue or transaction counts may be overstated.

### Important Principle

**Correct SQL aggregation begins with understanding the level of detail represented by each table.**

---

# 9. Entity Relationship Diagrams

An **Entity Relationship Diagram (ERD)** visually represents database tables and their relationships.

### Potential ERD Components

- Tables
- Primary keys
- Foreign keys
- Relationship lines
- Cardinality
- Optionality

### Learning Objective

Develop the ability to interpret and create diagrams that explain how business information is connected.

### Related Folder

[Database Analysis](Database-Analysis/README.md)

---

# 10. SQL Fundamentals

SQL provides commands for retrieving and manipulating relational information.

This portfolio will initially focus on analytical querying rather than database administration or production data modification.

### Foundational SQL Elements

| SQL Element | Purpose | Business Application |
|---|---|---|
| `SELECT` | Retrieve columns | View transaction details |
| `FROM` | Identify source table | Select sales records |
| `WHERE` | Filter rows | Orders within a reporting period |
| `ORDER BY` | Sort results | Rank transactions |
| `GROUP BY` | Group records | Revenue by category |
| `HAVING` | Filter aggregated groups | Categories above a threshold |
| `JOIN` | Combine tables | Orders and customers |
| `COUNT` | Count records | Number of orders |
| `SUM` | Calculate totals | Revenue |
| `AVG` | Calculate averages | Average transaction value |
| `MIN` / `MAX` | Identify extremes | Earliest or latest dates |
| Subqueries | Use nested results | Above-average price comparisons |

---

# 11. SELECT Statements

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

What order identifiers, dates, and revenue amounts are recorded?

### Learning Concepts

- Column selection
- Table identification
- Basic query structure

---

# 12. Filtering with WHERE

## Purpose

Retrieve records that meet defined conditions.

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

### Potential Applications

- Revenue thresholds
- Date ranges
- Customer groups
- Product categories
- Transaction classifications

---

# 13. Sorting with ORDER BY

## Purpose

Organize results according to selected values.

### Illustrative SQL

```sql
SELECT
    order_id,
    revenue
FROM sales
ORDER BY revenue DESC;
```

### Business Question

Which individual sales records have the highest revenue?

### Important Consideration

Ranking products by total revenue requires grouping when multiple records belong to the same product.

---

# 14. Aggregate Functions

Aggregate functions summarize data.

| Function | Purpose | Business Example |
|---|---|---|
| `COUNT()` | Count rows or non-null values | Number of transactions |
| `SUM()` | Calculate totals | Total revenue |
| `AVG()` | Calculate averages | Average recorded amount |
| `MIN()` | Find minimum value | Earliest transaction |
| `MAX()` | Find maximum value | Largest transaction |

### Important Principle

**Aggregate functions must be applied at the correct level of detail to produce meaningful business metrics.**

---

# 15. GROUP BY

## Purpose

Summarize records by category or another grouping field.

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

Which product categories generate the highest total recorded revenue?

### Learning Concepts

- Grouping
- Aggregation
- Sorting
- Business comparisons

---

# 16. HAVING

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

| Clause | Function |
|---|---|
| `WHERE` | Filters rows before aggregation |
| `HAVING` | Filters groups after aggregation |

---

# 17. SQL Joins

## Purpose

Combine information from related tables.

### Common Join Types

- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL OUTER JOIN`

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

Join behavior and supported syntax may vary by database system.

---

# 18. Avoiding Incorrect Join Results

Joins are a common source of analytical errors.

### Potential Problems

- Incorrect join keys
- Unexpected duplicate rows
- Missing matching records
- Many-to-many relationships
- Repeated order-level amounts
- Incorrect aggregation

### Recommended Validation

1. Identify table grain.
2. Review join keys.
3. Count records before joining.
4. Count records after joining.
5. Investigate unexpected duplicates.
6. Reconcile totals.

### Important Principle

**A query can execute successfully while returning incorrect business results.**

---

# 19. Subqueries

## Purpose

Use one query's result within another query.

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

### Learning Concepts

- Nested queries
- Aggregate comparisons
- Filtering based on calculated values

---

# 20. Working with NULL Values

`NULL` represents missing or unknown information.

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

Missing values should not automatically be treated as zero.

Different SQL functions handle null values differently.

---

# 21. SQL Data Quality

## Purpose

Evaluate whether database information is suitable for analysis.

### Potential Checks

- Missing values
- Duplicate identifiers
- Incorrect data types
- Invalid dates
- Orphaned records
- Unexpected negative values
- Inconsistent categories
- Incomplete reporting periods

### Important Principle

**Data quality should be evaluated before relying on query outputs for business decisions.**

---

# 22. SQL Query Validation

## Purpose

Verify that query results are accurate.

### Potential Validation Methods

- Compare row counts.
- Check unique identifiers.
- Reconcile financial totals.
- Validate grouping logic.
- Review join cardinality.
- Test date filters.
- Compare with manual calculations.
- Use Excel for independent verification.
- Inspect small record samples.

### Important Principle

**Correct SQL syntax does not guarantee correct analytical results.**

---

# 23. Translating Business Questions into SQL

Every project should begin with a clearly defined business question.

### Question-to-Query Process

1. State the business question.
2. Identify relevant tables.
3. Identify required fields.
4. Define the reporting grain.
5. Determine filters.
6. Determine calculations.
7. Write the SQL query.
8. Execute the query.
9. Validate the result.
10. Explain the business meaning.

### Example Question

**Which product categories generate the most revenue?**

### Required Logic

- Identify the sales data.
- Select the category field.
- Calculate total revenue.
- Group by category.
- Sort results.
- Validate totals.

---

# 24. SQL for Business KPI Reporting

SQL can be used to calculate business performance indicators.

### Potential KPIs

- Total Revenue
- Number of Orders
- Unique Customers
- Average Order Value
- Units Sold
- Sales Growth
- Repeat Purchase Count
- Outstanding Invoice Amounts

### Important Consideration

KPI definitions should be documented before queries are developed.

For example, average order value requires order-level revenue and an appropriate count of orders.

---

# 25. SQL for Accounting & Financial Analysis

My accounting and financial operations experience provides practical scenarios for SQL learning.

### Potential Applications

- Invoice summaries
- Payment transaction counts
- Outstanding balance reporting
- Revenue aggregation
- Expense categorization
- Financial transaction analysis
- Reconciliation support
- Reporting period comparisons

### Important Principle

Financial queries require accurate definitions, appropriate data grain, and careful validation.

---

# 26. SQL for Sales & Customer Analytics

### Potential Applications

- Top products by revenue
- Monthly sales trends
- Customer purchase frequency
- Repeat customer analysis
- Product category comparisons
- Regional sales summaries

### Important Consideration

The ability to answer these questions depends on the available database fields and data quality.

---

# 27. SQL for Operational Analysis

### Potential Applications

- Transaction volumes
- Processing activity
- Order fulfillment counts
- Inventory-related summaries
- Operational performance reporting

### Important Consideration

Operational metrics should be defined according to the business process represented by the database.

---

# 28. Connecting SQL to Excel, Python & Power BI

SQL can support broader analytical workflows.

| Tool | Potential Role |
|---|---|
| SQL | Retrieve, filter, join, and summarize data |
| Excel | Validate calculations and perform additional analysis |
| Python | Clean, explore, and visualize data |
| Power BI | Create interactive business reports |

### Potential Future Workflow

1. Explore the database.
2. Write SQL queries.
3. Validate results.
4. Export or connect approved data.
5. Analyze information in Excel or Python.
6. Create Power BI reports.
7. Document business findings.

### Important Consideration

This represents a potential future workflow rather than a completed integrated analytics project.

---

# 29. Potential Project Ideas

These are future learning opportunities, not completed projects.

## Database Analysis Projects

| Project | Difficulty | Primary Focus |
|---|---|---|
| Public Sample Database Exploration | Beginner | Tables, columns, keys |
| Entity Relationship Diagram Analysis | Beginner to Intermediate | Relationships and cardinality |
| Synthetic Retail Database Analysis | Intermediate | Schema exploration and integrity |

## Business Query Projects

| Project | Difficulty | Primary Focus |
|---|---|---|
| Top Products by Revenue | Beginner | `SUM`, `GROUP BY`, `ORDER BY` |
| Monthly Sales Summary | Beginner to Intermediate | Date aggregation |
| Repeat Customer Analysis | Intermediate | `COUNT`, `GROUP BY`, `HAVING` |
| Products Above Average Price | Intermediate | Subqueries and `AVG` |

### Important Principle

Projects should be selected according to current skill development and completed progressively.

---

# 30. Proposed Project File Structure

Each completed project should have its own subfolder.

### Illustrative Structure

```text
SQL-Projects/
│
├── README.md
│
├── Database-Analysis/
│   ├── README.md
│   └── Example-Database-Exploration/
│       ├── README.md
│       ├── queries/
│       ├── diagrams/
│       └── documentation/
│
└── Business-Queries/
    ├── README.md
    └── Example-Sales-Queries/
        ├── README.md
        └── queries/
```

### Potential Files

- SQL scripts (`.sql`)
- Entity relationship diagrams
- Database schemas
- Data dictionaries
- Query result samples
- Validation notes
- Project READMEs

### Important Consideration

This structure is illustrative. Project folders should be created as projects are completed.

---

# 31. Project Documentation Requirements

Each completed project should include:

### Project Overview

- Project title
- Business problem
- Analytical objective
- Intended audience

### Data Documentation

- Data source
- Database system
- Tables used
- Key fields
- Relationships
- Data grain
- Reporting period

### SQL Methodology

- SQL statements
- Explanation of query logic
- Filters
- Joins
- Aggregations
- Assumptions

### Validation

- Expected results
- Actual results
- Reconciliation checks
- Data quality findings
- Errors and corrections

### Business Interpretation

- Findings
- Supporting evidence
- Limitations
- Potential recommendations

### Learning Reflection

- Concepts practiced
- Challenges encountered
- Skills demonstrated
- Lessons learned
- Potential improvements

### Documentation Reference

[Project Documentation Standards](../Documentation/Project-Documentation-Standards.md)

---

# 32. Data Privacy & Ethical Practices

All projects should use public, synthetic, or appropriately authorized and protected information.

### Data Guidelines

- Do not publish confidential company records.
- Do not expose customer information.
- Do not include account numbers.
- Do not publish passwords or credentials.
- Use fictional business scenarios where appropriate.
- Label synthetic information.
- Document data permissions.
- Avoid unsupported business claims.

### Documentation References

- [Dataset Sources](../Documentation/Dataset-Sources.md)
- [Project Documentation Standards](../Documentation/Project-Documentation-Standards.md)

---

# 33. Professional Development & Career Alignment

This section supports my ongoing development toward roles such as:

- Data Analyst
- Business Analyst
- Business Intelligence Analyst
- Financial Data Analyst
- Reporting Analyst
- Operations Analyst
- Marketing Analyst
- Database Analyst

### Intended Skills

- SQL fundamentals
- Relational databases
- Data retrieval
- Database exploration
- Primary and foreign keys
- Entity relationships
- SQL joins
- Aggregation
- Subqueries
- Data quality assessment
- Query validation
- Business KPI calculations
- Analytical interpretation
- Technical documentation

These represent intended learning outcomes rather than completed competencies.

---

# 34. SQL Learning Checklist

### Database Fundamentals

- [ ] Understand relational databases
- [ ] Identify tables and columns
- [ ] Understand data types
- [ ] Identify primary keys
- [ ] Identify foreign keys
- [ ] Understand relationships
- [ ] Define table grain
- [ ] Interpret an ERD

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

### Analytical Skills

- [ ] Translate a business question into SQL
- [ ] Validate query results
- [ ] Reconcile calculations
- [ ] Identify data quality issues
- [ ] Explain findings
- [ ] Document limitations

### Portfolio Development

- [ ] Complete first database exploration
- [ ] Complete first independent business query
- [ ] Save SQL scripts
- [ ] Document results
- [ ] Create project READMEs
- [ ] Update Portfolio Progress

---

# 35. Long-Term Learning Vision

The long-term objective of this section is to develop practical SQL and relational database skills that can be applied to business reporting, financial analysis, operations, customer analytics, and business intelligence.

The initial focus is on understanding database structures and writing accurate queries that answer clearly defined questions.

As my technical skills develop, I intend to progress toward more advanced SQL techniques, data modeling, query optimization fundamentals, and integration with Excel, Python, and Power BI.

For my professional development, SQL will complement my accounting and financial operations background while supporting my broader Business Analytics education and career goals.

**The goal is not simply to write SQL queries. It is to understand the underlying data, retrieve accurate information, validate calculations, and communicate findings that support meaningful business decisions.**

---

## Current Status

**Planned — SQL Learning Framework Established**

No completed SQL portfolio projects have been added to this section yet.

The Database Analysis and Business Queries folders establish the structure for future learning and portfolio development.

Projects will be added only after the database explorations or SQL queries have been independently completed, tested, validated, explained, and documented.

Progress is tracked in [Portfolio Progress](../Documentation/Portfolio-Progress.md).

---

## Related Documentation

- [Dataset Sources](../Documentation/Dataset-Sources.md)
- [Analytical Methodology](../Documentation/Analytical-Methodology.md)
- [Project Documentation Standards](../Documentation/Project-Documentation-Standards.md)
- [Portfolio Progress](../Documentation/Portfolio-Progress.md)

---

## Navigation

[Return to Portfolio Home](../README.md)

---

*This section documents an ongoing educational and professional development journey. Planned SQL exercises and database analyses do not represent completed projects, validated business findings, or demonstrated technical competencies until the supporting work has been completed and documented.*
