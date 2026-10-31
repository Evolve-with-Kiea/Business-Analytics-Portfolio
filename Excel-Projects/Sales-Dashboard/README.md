# Sales Dashboard

## Purpose

This folder is for an Excel dashboard that summarizes sales performance using a public or synthetic dataset. The README is a project template that defines what the dashboard should cover.

## Metrics to Include

| Metric | Question it answers |
|---|---|
| Sales revenue | How much did the business earn from sales? |
| Units sold | How many items were sold? |
| Average order value | How much does a typical order bring in? |
| Sales by product | Which products contribute most? |
| Sales by category | Which product groups perform best? |
| Sales by region | Where are sales strongest or weakest? |
| Monthly sales trends | How do sales change over time? |
| Sales growth | How does this period compare with a prior period? |
| Performance against targets | Were sales goals met? |


## Suggested Excel Techniques

| Technique | Purpose in this project |
|---|---|
| SUMIFS | Total revenue or units by product, region, or month |
| COUNTIFS | Count orders that meet conditions |
| AVERAGEIFS | Average order value for a segment |
| XLOOKUP | Retrieve product or target information from reference tables |
| IF | Flag results as above or below target |
| PivotTables | Summarize large datasets quickly |
| Charts | Show trends, comparisons, and composition |
| Conditional formatting | Highlight performance against targets |
| Dashboard design | Arrange KPIs and charts for easy reading |


## Suggested Data Fields

A suitable dataset might include: order ID, order date, product, category, region, quantity, unit price, and a target table by month or region. Use a public or synthetic dataset and record its source.

## Illustrative Formula Syntax

These examples show syntax only. Adapt the ranges and column names to the actual workbook.

```text
=SUMIFS(Revenue, Region, "West")
=COUNTIFS(Region, "West", Category, "Accessories")
=AVERAGEIFS(Revenue, Category, "Accessories")
=XLOOKUP(ProductID, ProductTable[ID], ProductTable[Category])
=IF(Actual >= Target, "Met", "Below")
```

## Dashboard Planning Checklist

- [ ] Define the audience and the decisions the dashboard supports
- [ ] List the KPIs and define each one
- [ ] Document the data source and cleaning steps
- [ ] Build calculations in a separate, labeled sheet
- [ ] Choose chart types that match each question
- [ ] Add filters or slicers where useful
- [ ] Test totals against the source data
- [ ] Write an interpretation section for the reader

## Potential Project Ideas

These are ideas for future work. They are not completed projects.

- Dashboard of a retail dataset showing revenue, units, and average order value
- Regional comparison with target tracking
- Monthly trend and growth analysis for an e-commerce style dataset

## Documentation Requirements

Each project added to this folder should live in its own subfolder with a `README.md` that follows the template in [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md). Describe the business problem, data source, method, findings, limitations, and skills demonstrated.

## Data Guidelines

Use only public, synthetic, or appropriately anonymized data. See [Dataset Sources](../../Documentation/Dataset-Sources.md) and the data security standards in [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md).

## Current Status

No projects have been completed in this folder yet. This README defines scope and structure so that future work is documented consistently. Progress is tracked in [Portfolio Progress](../../Documentation/Portfolio-Progress.md).

Return to [Excel Projects](../README.md) or the [portfolio home](../../README.md).
