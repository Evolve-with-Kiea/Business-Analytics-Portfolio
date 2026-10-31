# Business Queries

## Purpose

This folder is for SQL queries that answer practical business questions. Each project should state the question first, then show the query and explain the result.

## SQL Elements and Business Use

| Element | Business use |
|---|---|
| SELECT | Choose the fields to retrieve |
| WHERE | Filter to a period, region, or customer group |
| ORDER BY | Rank products or customers |
| GROUP BY | Summarize by category, month, or region |
| HAVING | Filter groups, such as products with total sales above a threshold |
| JOIN | Combine orders with customers or products |
| COUNT | Count orders or customers |
| SUM | Total revenue or units |
| AVG | Average order value |
| MIN and MAX | Find earliest dates or highest and lowest values |
| Subqueries | Compare values with an overall average or a derived result |


## Question-to-Query Pattern

1. State the business question.
2. Identify the tables and fields required.
3. Decide on filters, groupings, and calculations.
4. Write the query in small steps.
5. Check the result against a manual calculation or a smaller sample.
6. Explain what the result means for the business.

## Illustrative Syntax

This example shows structure only and uses hypothetical table and column names.

```sql
SELECT category, SUM(revenue) AS total_revenue
FROM sales
GROUP BY category
ORDER BY total_revenue DESC;
```

## Common Mistakes to Check

- Joins that duplicate rows
- Filtering with WHERE when HAVING is needed
- Ignoring NULL values in calculations
- Aggregating at the wrong level of detail

## Potential Project Ideas

These are ideas for future work. They are not completed projects.

- Top products by revenue
- Monthly sales summary
- Customers with repeat purchases
- Products above average price using a subquery

## Documentation Requirements

Each project added to this folder should live in its own subfolder with a `README.md` that follows the template in [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md). Describe the business problem, data source, method, findings, limitations, and skills demonstrated.

## Data Guidelines

Use only public, synthetic, or appropriately anonymized data. See [Dataset Sources](../../Documentation/Dataset-Sources.md) and the data security standards in [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md).

## Current Status

No projects have been completed in this folder yet. This README defines scope and structure so that future work is documented consistently. Progress is tracked in [Portfolio Progress](../../Documentation/Portfolio-Progress.md).

Return to [SQL Projects](../README.md) or the [portfolio home](../../README.md).
