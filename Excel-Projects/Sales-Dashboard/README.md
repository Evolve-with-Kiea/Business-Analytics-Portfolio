# Sales Dashboard

## Excel Sales Analytics, Revenue Trends, KPI Tracking & Interactive Business Reporting

### Microsoft Excel | Business Analytics Portfolio

## Project Overview

**Sales Dashboard** is a planned Microsoft Excel analytics project focused on transforming raw sales transaction data into a structured, interactive business performance dashboard.

The project will explore how organizations measure sales activity, evaluate revenue trends, compare product and regional performance, monitor sales targets, and communicate findings to decision-makers.

The objective is to develop practical experience using Excel formulas, PivotTables, PivotCharts, slicers, conditional formatting, and dashboard design principles.

This project will also emphasize an important aspect of business analytics: understanding the business question before selecting calculations or visualizations.

My background in accounting and financial operations provides experience with transaction processing, reconciliations, financial reporting, and data accuracy. This project is intended to extend those skills into sales analytics, KPI development, interactive reporting, and business intelligence.

**Project Category:** Excel / Sales Analytics / Business Intelligence / Dashboard Development

**Current Status:** Planned — Project Framework Established

**Primary Tool:** Microsoft Excel

**Potential Future Tools:** Power Query, SQL, Power BI, Python

**Data Approach:** Public or synthetic sales data

**Difficulty:** Beginner to Intermediate

**Primary Deliverable:** Interactive Excel Sales Dashboard

**Business Application:** Retail, e-commerce, and small-business sales reporting

---

# 1. Purpose

The purpose of this project is to develop an Excel dashboard that summarizes sales performance using a structured dataset.

Sales data may contain hundreds or thousands of transaction records.

Without appropriate organization and analysis, it can be difficult to identify meaningful patterns or understand business performance.

A well-designed sales dashboard can help decision-makers answer questions such as:

- How much revenue was generated?
- How many units were sold?
- How many orders were placed?
- Which products generate the most sales?
- Which product categories perform best?
- Which regions contribute the most revenue?
- Are sales increasing or decreasing?
- Are sales targets being met?

The goal is to learn how to turn raw transaction data into clear, reliable, and actionable business information.

---

# 2. Business Scenario

## Hypothetical Retail & E-commerce Business

A fictional retail and e-commerce company sells products across several categories and geographic regions.

The business records individual sales transactions but does not have a centralized reporting dashboard.

Management currently reviews sales totals manually and wants a more efficient way to monitor performance.

The company needs an Excel dashboard that provides:

- Overall sales revenue.
- Total orders and units sold.
- Average order value.
- Monthly revenue trends.
- Product and category comparisons.
- Regional sales performance.
- Actual versus target sales.

The dashboard should allow management to filter results and identify areas that may require further investigation.

### Central Business Question

**How can a business use Microsoft Excel to evaluate sales performance, identify revenue trends, compare products and regions, and monitor progress toward sales targets?**

---

# 3. Project Objectives

The project is intended to:

1. Organize raw sales transaction data.
2. Identify relevant sales KPIs.
3. Define calculation rules.
4. Clean and validate the dataset.
5. Calculate revenue and units sold.
6. Calculate total order volume.
7. Calculate average order value.
8. Analyze sales by product.
9. Analyze sales by category.
10. Compare sales across regions.
11. Evaluate monthly sales trends.
12. Calculate period-over-period growth.
13. Compare actual sales with targets.
14. Build PivotTables and PivotCharts.
15. Add interactive filters and slicers.
16. Develop a professional Excel dashboard.
17. Validate dashboard calculations.
18. Interpret results and document findings.

---

# 4. Target Audience

The proposed dashboard is intended for a fictional small-business owner, sales manager, or operations manager.

### Potential Management Decisions

The dashboard may help users evaluate:

- Sales performance against targets.
- Product assortment.
- Regional performance differences.
- Revenue trends.
- Promotional planning.
- Sales reporting priorities.

### Dashboard Design Goal

Provide a concise overview of sales performance without requiring the user to manually review individual transaction records.

---

# 5. Core Sales KPIs

| KPI | Business Question | Measurement |
|---|---|---|
| Sales Revenue | How much sales value was generated? | Currency |
| Total Orders | How many qualifying orders were placed? | Count |
| Units Sold | How many units were sold? | Count |
| Average Order Value | What is the average sales value per order? | Currency |
| Sales by Product | Which products generate the most revenue? | Currency |
| Sales by Category | Which categories contribute most? | Currency |
| Sales by Region | Where is revenue strongest? | Currency |
| Monthly Sales | How does revenue change over time? | Currency |
| Sales Growth | How does revenue compare with the previous period? | Percentage |
| Target Attainment | How much of the sales target was achieved? | Percentage |

### KPI Reporting Standard

Every KPI should document:

- Definition
- Formula
- Data source
- Reporting period
- Inclusion rules
- Unit of measurement
- Interpretation
- Limitations

---

# 6. Sales Revenue

## Purpose

Calculate total qualifying sales value during the selected reporting period.

### Basic Formula

**Sales Revenue = Sum of Qualifying Sales Amounts**

For a simplified synthetic dataset without discounts, taxes, refunds, or shipping charges:

**Line Sales = Quantity × Unit Price**

**Total Sales Revenue = Sum of Line Sales**

### Illustrative Example

A fictional business sells:

- 10 planners at $25 each.
- 8 journals at $20 each.
- 5 workbooks at $30 each.

Total sales:

**(10 × $25) + (8 × $20) + (5 × $30) = $560**

### Important Consideration

The project must specify whether reported sales are gross sales, net sales, or another defined measure.

Sales totals should not automatically be treated as accounting revenue or cash collected.

---

# 7. Total Orders

## Purpose

Count qualifying customer orders during a reporting period.

### Definition

Total Orders represents the number of distinct qualifying order identifiers.

### Important Consideration

A dataset may contain multiple rows for one order because each row represents a different product.

Counting transaction rows may overstate order volume.

### Recommended Approach

Use distinct order identifiers when calculating order counts.

Potential methods include:

- PivotTables using the Data Model and Distinct Count.
- A unique order summary table.
- Excel dynamic array functions where supported.
- Power Query grouping.

### Business Question

How many distinct qualifying orders were recorded?

---

# 8. Units Sold

## Purpose

Calculate the total quantity of qualifying product units sold.

### Formula

**Units Sold = Sum of Quantity**

### Illustrative Example

A fictional dataset contains:

- 12 planners
- 18 journals
- 10 workbooks

**Total Units Sold = 40**

### Potential Analysis

- Units by product
- Units by category
- Units by region
- Units by month

### Important Consideration

Returned or canceled units should be treated according to documented reporting rules.

---

# 9. Average Order Value

## Purpose

Evaluate the average sales value generated per qualifying order.

### Formula

**Average Order Value = Defined Sales Amount ÷ Number of Qualifying Orders**

### Illustrative Example

- Net sales: $10,000
- Qualifying orders: 200

**Average Order Value = $50**

### Important Consideration

Average Order Value should not be calculated by simply averaging individual order-item rows.

Orders containing multiple products must be aggregated appropriately.

### Business Questions

- Is average order value increasing?
- Does AOV vary across regions?
- Are certain product categories associated with larger orders?

---

# 10. Sales by Product

## Purpose

Identify which products contribute to sales activity.

### Potential Measures

- Revenue by product
- Units sold by product
- Number of orders containing each product
- Revenue share by product

### Potential Business Questions

- Which products generate the most revenue?
- Which products sell the most units?
- Are high-volume products also high-revenue products?
- Does product performance change over time?

### Recommended Visualization

Horizontal bar chart showing revenue by product.

---

# 11. Sales by Category

## Purpose

Compare performance across product categories.

### Illustrative Categories

- Planners
- Journals
- Workbooks
- Educational Resources
- Digital Products
- Gifts

These are illustrative categories and do not represent verified product sales.

### Potential Measures

- Revenue by category
- Units sold by category
- Category revenue share
- Category growth

### Recommended Visualization

Bar chart comparing category revenue.

### Business Question

Which product categories contribute the most to total sales?

---

# 12. Sales by Region

## Purpose

Compare sales performance across geographic regions.

### Illustrative Regions

- North
- South
- East
- West

### Potential Measures

- Revenue by region
- Orders by region
- Units sold by region
- Average order value by region
- Regional target attainment

### Potential Business Questions

- Which region generates the most revenue?
- Which region has the highest average order value?
- Are regional sales targets being met?
- Do sales patterns vary across regions?

### Important Consideration

Regional comparisons should account for differences in market size, customer coverage, and reporting periods.

---

# 13. Monthly Sales Trends

## Purpose

Evaluate how sales change over time.

### Potential Measures

- Monthly revenue
- Monthly orders
- Monthly units sold
- Average order value by month

### Recommended Visualization

Line chart showing monthly sales revenue.

### Potential Business Questions

- Are sales increasing?
- Are there seasonal patterns?
- Which months have stronger performance?
- Are there unusual increases or decreases?

### Important Consideration

Short reporting periods may not provide enough information to establish seasonality.

---

# 14. Sales Growth Analysis

## Purpose

Measure changes in sales between comparable reporting periods.

### Formula

**Sales Growth % = (Current Period Sales − Previous Period Sales) ÷ Previous Period Sales × 100**

### Illustrative Example

- Previous month: $12,000
- Current month: $15,000

**Sales Growth = ($15,000 − $12,000) ÷ $12,000 × 100 = 25%**

### Interpretation

Sales increased by 25% between the two periods.

### Important Consideration

Percentage growth is undefined when the prior-period value is zero.

Negative or unusually small comparison values may require additional explanation.

---

# 15. Sales Target Tracking

## Purpose

Compare actual sales with established performance goals.

### Potential Measures

- Actual sales
- Target sales
- Dollar variance
- Percentage variance
- Target attainment

### Dollar Variance

**Variance = Actual Sales − Target Sales**

### Percentage Variance

**Variance % = (Actual Sales − Target Sales) ÷ Target Sales × 100**

### Target Attainment

**Target Attainment % = Actual Sales ÷ Target Sales × 100**

### Illustrative Example

| Metric | Hypothetical Value |
|---|---:|
| Actual Sales | $18,000 |
| Sales Target | $20,000 |
| Dollar Variance | −$2,000 |
| Percentage Variance | −10% |
| Target Attainment | 90% |

### Potential Status Indicators

- Target Met
- Below Target
- Not Available

### Important Consideration

Targets must correspond to the same reporting period and measurement scope as actual results.

---

# 16. Proposed Dataset Structure

A suitable dataset may include the following fields.

| Field | Description | Example |
|---|---|---|
| Order ID | Unique order identifier | ORD-1001 |
| Order Date | Date of purchase | 2026-01-15 |
| Product ID | Unique product identifier | PRD-001 |
| Product Name | Product description | Planner |
| Category | Product category | Stationery |
| Region | Sales region | South |
| Quantity | Units purchased | 2 |
| Unit Price | Price per unit | $25 |
| Line Sales | Quantity × Unit Price | $50 |
| Order Status | Transaction classification | Completed |
| Sales Channel | Sales source | Online |

### Optional Fields

- Discount amount
- Refund amount
- Shipping amount
- Sales tax
- Customer identifier
- Product cost
- Campaign source

Optional fields should only be included when appropriate for the project objectives and data permissions.

---

# 17. Proposed Sales Target Table

Targets should be maintained separately from raw transactions.

| Month | Region | Target Revenue |
|---|---|---:|
| January | North | $10,000 |
| January | South | $12,000 |
| February | North | $11,000 |
| February | South | $13,000 |

All values are hypothetical.

### Important Consideration

The target table must have a clearly defined level of detail.

For example, a monthly regional target should not be repeated for every transaction and then summed, because this would overstate the target.

---

# 18. Excel Techniques

| Technique | Application |
|---|---|
| Excel Tables | Structure datasets |
| SUMIFS | Calculate totals by criteria |
| COUNTIFS | Count records meeting conditions |
| AVERAGEIFS | Calculate conditional averages |
| XLOOKUP | Retrieve reference information |
| IF | Classify results |
| IFERROR | Handle calculation errors |
| PivotTables | Summarize data |
| PivotCharts | Visualize summaries |
| Slicers | Filter dashboard views |
| Conditional Formatting | Highlight performance |
| Data Validation | Improve input consistency |
| Power Query | Prepare and transform data |

---

# 19. Illustrative Excel Formulas

The following examples demonstrate syntax and should be adapted to the workbook's actual structure.

## Sales by Region

```excel
=SUMIFS(SalesData[Line Sales],SalesData[Region],"West")
```

## Units Sold by Category

```excel
=SUMIFS(SalesData[Quantity],SalesData[Category],"Journals")
```

## Count of Matching Rows

```excel
=COUNTIFS(SalesData[Region],"West",SalesData[Category],"Journals")
```

This counts matching rows, not necessarily distinct orders.

## Average Line Sales by Category

```excel
=AVERAGEIFS(SalesData[Line Sales],SalesData[Category],"Journals")
```

This calculates average line sales, not average order value.

## Product Category Lookup

```excel
=XLOOKUP([@[Product ID]],ProductTable[Product ID],ProductTable[Category],"Not Found")
```

## Target Status

```excel
=IF(ActualSales>=TargetSales,"Target Met","Below Target")
```

## Revenue Growth

```excel
=IFERROR((CurrentSales-PreviousSales)/PreviousSales,"N/A")
```

## Target Attainment

```excel
=IFERROR(ActualSales/TargetSales,"N/A")
```

### Important Formula Consideration

Formula accuracy depends on the dataset's level of detail, reporting definitions, and workbook structure.

---

# 20. Data Cleaning & Preparation

Before calculating KPIs, the dataset should be reviewed for potential errors.

### Potential Cleaning Tasks

- Remove duplicate transaction records.
- Validate order identifiers.
- Standardize dates.
- Review product categories.
- Confirm quantity values.
- Validate unit prices.
- Identify missing fields.
- Review canceled orders.
- Document refund treatment.
- Confirm region classifications.

### Potential Excel Tools

- Filters
- Sort
- Remove Duplicates
- Excel Tables
- Data Validation
- Power Query

### Important Principle

**A dashboard built on inaccurate transaction data may produce misleading business conclusions.**

---

# 21. Data Validation

The project should include checks to confirm calculation accuracy.

### Recommended Checks

- Reconcile total sales with source data.
- Confirm total units sold.
- Validate distinct order counts.
- Review average order value.
- Verify product and category totals.
- Check monthly reporting periods.
- Confirm target calculations.
- Test slicer behavior.
- Verify dashboard totals after filtering.

### Illustrative Validation Rule

**Sum of Product Revenue = Total Revenue**

This relationship should hold when product categories are mutually exclusive and all qualifying sales are included.

---

# 22. Proposed Excel Workbook Structure

| Worksheet | Purpose |
|---|---|
| Instructions | Business scenario and objectives |
| Raw Data | Original dataset |
| Clean Data | Prepared transaction records |
| Product Reference | Product IDs and categories |
| Sales Targets | Monthly or regional goals |
| KPI Definitions | Metric documentation |
| Calculations | Supporting formulas |
| PivotTables | Sales summaries |
| Monthly Trends | Period comparisons |
| Product Analysis | Product and category results |
| Regional Analysis | Geographic comparisons |
| Dashboard | Executive sales overview |
| Validation | Calculation checks |
| Findings | Analytical interpretation |
| Recommendations | Proposed business actions |
| Data Dictionary | Field descriptions |

Not every worksheet is required for the first version.

---

# 23. Proposed Dashboard Layout

## Executive Sales Overview

The dashboard should prioritize the metrics most relevant to the intended audience.

### KPI Summary

- Total Sales
- Total Orders
- Units Sold
- Average Order Value
- Sales Growth
- Target Attainment

### Sales Trends

Line chart showing monthly revenue.

### Product Performance

Bar chart showing sales by product.

### Category Performance

Bar chart comparing revenue by category.

### Regional Performance

Bar chart comparing regional sales.

### Target Tracking

Actual-versus-target comparison.

### Interactive Filters

Potential slicers:

- Month
- Region
- Product Category
- Sales Channel

### Dashboard Design Principles

- Use clear titles.
- Label reporting periods.
- Display appropriate currency formatting.
- Avoid unnecessary visual clutter.
- Keep KPI definitions consistent.
- Use accessible chart labels.
- Validate interactive filters.
- Prioritize business interpretation.

---

# 24. Suggested Beginner-Friendly Development Sequence

## Phase 1: Understand the Dataset

**Goal:** Learn how sales records are organized.

### Tasks

- Review column names.
- Identify transaction-level and order-level fields.
- Convert data into an Excel Table.
- Check data types.
- Review missing values.

## Phase 2: Calculate Basic KPIs

**Goal:** Practice foundational Excel formulas.

### Tasks

- Calculate line sales.
- Calculate total sales.
- Calculate units sold.
- Calculate distinct orders.
- Calculate average order value.

## Phase 3: Create PivotTables

**Goal:** Summarize sales information.

### Tasks

- Revenue by month.
- Revenue by product.
- Revenue by category.
- Revenue by region.

## Phase 4: Build Charts

**Goal:** Communicate trends and comparisons.

### Tasks

- Monthly sales line chart.
- Product revenue bar chart.
- Regional sales comparison.

## Phase 5: Add Targets

**Goal:** Compare results with business objectives.

### Tasks

- Create target table.
- Calculate variances.
- Calculate target attainment.
- Add status indicators.

## Phase 6: Build the Dashboard

**Goal:** Combine KPIs and visualizations.

### Tasks

- Create dashboard worksheet.
- Arrange KPI summaries.
- Position charts.
- Add slicers.
- Apply consistent formatting.

## Phase 7: Validate & Interpret

**Goal:** Confirm accuracy and explain findings.

### Tasks

- Reconcile totals.
- Test filters.
- Review KPI calculations.
- Document findings.
- Explain limitations.
- Develop recommendations.

---

# 25. Potential Project Variations

These represent future learning opportunities, not completed projects.

## Retail Sales Dashboard

**Difficulty:** Beginner

Focus:

- Revenue
- Units sold
- Average order value
- Product categories
- Monthly trends

## Regional Sales Performance Dashboard

**Difficulty:** Beginner to Intermediate

Focus:

- Regional revenue
- Order volume
- Sales targets
- Target attainment
- Regional comparisons

## E-commerce Sales Trend Dashboard

**Difficulty:** Intermediate

Focus:

- Monthly sales
- Revenue growth
- Product performance
- Sales channels
- Seasonal patterns, where supported

---

# 26. Analytical Methodology

Each dashboard project should follow a documented analytical process.

1. Define the business problem.
2. Identify the intended audience.
3. Establish project objectives.
4. Select appropriate KPIs.
5. Identify the data source.
6. Document metric definitions.
7. Clean and prepare the dataset.
8. Validate transaction records.
9. Perform calculations.
10. Create PivotTables.
11. Analyze trends.
12. Build charts.
13. Design the dashboard.
14. Test filters and calculations.
15. Interpret results.
16. Develop recommendations.
17. Document limitations.
18. Update portfolio progress.

---

# 27. Findings & Recommendations

Completed projects should include a written interpretation of dashboard results.

### Recommended Format

| Finding | Supporting Evidence | Business Interpretation | Potential Recommendation |
|---|---|---|---|
| [Finding] | [KPI or chart] | [Why it matters] | [Proposed action] |

### Potential Areas of Investigation

- Revenue trends
- Product sales
- Regional differences
- Sales target attainment
- Average order value
- Changes in order volume

### Important Principle

**The purpose of a sales dashboard is not only to display sales figures but also to support meaningful business questions.**

---

# 28. Data Quality & Limitations

### Potential Data Issues

- Duplicate order items
- Missing product categories
- Incomplete reporting periods
- Incorrect unit prices
- Inconsistent region labels
- Missing target values
- Unrecorded refunds
- Canceled transactions

### Analytical Limitations

- Synthetic data assumptions
- Limited historical periods
- Incomplete cost information
- Differences in regional market size
- Missing customer context
- Unverified sales targets

### Reporting Standard

Findings should reflect what the dataset supports and should not be generalized beyond the available evidence.

---

# 29. Data Privacy & Ethical Reporting

Use only public, synthetic, or appropriately authorized and protected datasets.

### Data Guidelines

- Do not publish customer names.
- Do not expose customer email addresses.
- Do not disclose billing or shipping addresses.
- Do not publish payment information.
- Avoid sharing confidential sales records.
- Clearly label synthetic data.
- Document dataset sources and permissions.
- Use aggregated reporting where appropriate.

### Documentation References

- [Dataset Sources](../../Documentation/Dataset-Sources.md)
- [Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md)

---

# 30. Project Documentation Requirements

Each completed project should have a dedicated subfolder and `README.md`.

### Recommended Documentation

- Project title
- Business problem
- Objectives
- Data source
- Dataset description
- Data dictionary
- KPI definitions
- Analytical methodology
- Tools used
- Excel formulas
- PivotTables and charts
- Dashboard screenshots
- Findings
- Recommendations
- Limitations
- Skills demonstrated
- Lessons learned
- Project status

### Documentation Reference

[Project Documentation Standards](../../Documentation/Project-Documentation-Standards.md)

---

# 31. Professional Development & Career Alignment

This project is intended to support development toward roles such as:

- Business Analyst
- Data Analyst
- Sales Analyst
- Reporting Analyst
- Financial Analyst
- E-commerce Analyst
- Business Intelligence Analyst
- Business Performance Analyst

### Intended Skills

- Sales data analysis
- Excel formulas
- KPI development
- PivotTables
- PivotCharts
- Slicers
- Data cleaning
- Data validation
- Sales trend analysis
- Dashboard development
- Analytical interpretation
- Business recommendations

These represent intended learning outcomes rather than completed competencies.

---

# 32. Project Completion Checklist

### Planning

- [x] Define project purpose
- [x] Identify core sales KPIs
- [x] Establish project framework
- [x] Identify proposed Excel techniques

### Dataset Preparation

- [ ] Select dataset
- [ ] Document data source
- [ ] Review data quality
- [ ] Create data dictionary
- [ ] Prepare analytical data

### KPI Development

- [ ] Calculate total sales
- [ ] Calculate total orders
- [ ] Calculate units sold
- [ ] Calculate average order value
- [ ] Calculate sales growth
- [ ] Calculate target attainment

### Data Analysis

- [ ] Analyze monthly sales
- [ ] Analyze product sales
- [ ] Compare categories
- [ ] Compare regions
- [ ] Evaluate targets

### Dashboard Development

- [ ] Create PivotTables
- [ ] Create charts
- [ ] Add slicers
- [ ] Design dashboard layout
- [ ] Validate interactive filters

### Documentation

- [ ] Document findings
- [ ] Explain limitations
- [ ] Develop recommendations
- [ ] Add workbook and supporting files
- [ ] Update Portfolio Progress

---

# 33. Long-Term Learning Vision

The long-term objective of this folder is to develop practical Excel dashboards that demonstrate the ability to analyze sales transactions, evaluate revenue trends, compare product performance, and communicate results through interactive business reports.

The project provides an opportunity to connect existing accounting and financial operations experience with the analytical techniques used in sales reporting, financial analysis, and business intelligence.

As technical skills develop, selected dashboards may be expanded using Power Query, SQL, Power BI, or Python.

The goal is to build professional portfolio evidence demonstrating how business questions can be translated into structured data analysis and clear reporting.

**The ultimate objective is to develop the ability to turn raw sales records into accurate, meaningful, and decision-ready business information.**

---

## Current Status

**Planned — Project Framework Established**

No Sales Dashboard project has been completed in this folder yet.

This README defines the intended scope, business scenario, KPI framework, analytical methods, Excel techniques, and documentation requirements.

Completed work, validated findings, dashboard files, and demonstrated skills will be added as the project progresses.

Progress is tracked in [Portfolio Progress](../../Documentation/Portfolio-Progress.md).

---

## Navigation

- [Return to Excel Projects](../README.md)
- [Portfolio Home](../../README.md)

---

*This folder is intended for educational and professional portfolio development. All illustrative figures and scenarios are hypothetical. No completed dashboards, verified business results, or demonstrated technical competencies are claimed until supporting work has been completed and documented.*
