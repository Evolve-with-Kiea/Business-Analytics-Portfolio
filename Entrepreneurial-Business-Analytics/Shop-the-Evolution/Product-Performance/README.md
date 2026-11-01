# Product Performance Analytics

## Product Sales, Revenue, Gross Margins, Returns & Demand Analysis

### Shop the Evolution™ | Business Analytics Portfolio

## Project Overview

**Product Performance Analytics** is a planned Business Analytics portfolio project focused on evaluating how individual products and product categories contribute to sales, revenue, gross profit, and overall business performance.

The project explores units sold, product revenue, gross margin, return rates, product mix, and demand patterns to identify opportunities for better pricing, merchandising, inventory planning, and product portfolio decisions.

The primary business scenario is based on **Shop the Evolution™**, the commerce initiative within the Evolve with Kiea business ecosystem.

The project is particularly relevant to businesses offering a combination of physical products, digital resources, published materials, and educational products.

The initial analysis will use a realistic synthetic dataset in Microsoft Excel. Future versions may incorporate authorized Shopify reports, verified product costs, SQL, Power Query, Python, and Power BI.

**Project Status:** Planned — Analytical Framework Defined

**Portfolio Category:** E-commerce Analytics / Financial Analytics / Product Analytics / Business Intelligence

**Primary Business Application:** Shop the Evolution™

**Related Initiatives:** Evolution Press®, Little Bosses™, Evolve with Kiea

**Potential Tools:** Microsoft Excel, Power Query, SQL, Python, Power BI, Shopify Analytics

**Initial Deliverable:** Excel product performance analysis workbook

**Future Deliverable:** Interactive product performance and profitability dashboard

---

# 1. Business Background

Product-based businesses need to understand how individual products and categories perform financially and operationally.

High sales volume does not necessarily indicate strong profitability.

A product may generate significant revenue while contributing relatively little gross profit because of production costs, discounts, returns, or other expenses.

Conversely, a lower-volume product may generate stronger margins.

Shop the Evolution™ may offer products across categories such as:

- Planners
- Journals
- Workbooks
- Books and guides
- Digital products
- Affirmation cards
- Educational activities
- Gifts and lifestyle products
- Little Bosses™ educational resources

These categories may differ in pricing, cost structure, fulfillment requirements, return behavior, and purchasing patterns.

Understanding these differences can support more informed product decisions.

---

# 2. Business Problem

Sales reports often emphasize total revenue and units sold.

However, these measurements do not fully explain product performance.

A business may experience:

- Strong sales for products with low margins.
- High product views but limited purchases.
- Frequent discounts that reduce profitability.
- Returns that affect realized revenue.
- Seasonal demand fluctuations.
- Uneven performance across product categories.
- Product categories that contribute revenue but require disproportionate resources.

Without a structured product performance framework, businesses may struggle to determine which products support sustainable growth.

### Central Business Question

**How can Shop the Evolution™ use product sales, cost, margin, return, and demand data to evaluate product performance and make evidence-based decisions about pricing, merchandising, and product portfolio management?**

---

# 3. Project Objectives

1. Evaluate product sales volume.
2. Analyze product revenue.
3. Calculate gross profit and gross margin.
4. Examine return rates.
5. Evaluate product category performance.
6. Analyze product mix.
7. Identify sales and demand trends.
8. Compare product performance across periods.
9. Evaluate discount effects.
10. Explore product profitability.
11. Develop product performance dashboards.
12. Practice financial and analytical calculations.
13. Document cost assumptions.
14. Identify business improvement opportunities.
15. Develop evidence-based recommendations.

---

# 4. Product Performance Framework

| Analytical Area | Business Question | Potential Metrics |
|---|---|---|
| Sales Volume | Which products sell most frequently? | Units sold |
| Revenue | Which products generate sales? | Net product revenue |
| Gross Profit | Which products contribute gross profit? | Revenue less COGS |
| Gross Margin | How efficiently do products generate gross profit? | Gross margin percentage |
| Returns | Which products experience returns? | Return rate |
| Product Mix | How is performance distributed across products? | Revenue and unit share |
| Demand | How does purchasing activity change over time? | Units sold by period |
| Discounts | How do promotions affect realized prices? | Discount rate, realized revenue |

### Key Principle

**A product's sales volume, revenue, gross profit, and margin must be evaluated separately.**

---

# 5. Units Sold Analysis

## Purpose

Measure the quantity of products sold during a defined reporting period.

### Potential Metrics

- Gross units sold
- Returned units
- Net units sold
- Units sold by category
- Units sold by month
- Average units per order

### Net Units Sold

**Net Units Sold = Gross Units Sold − Returned Units**

### Illustrative Example

A fictional product records:

- Gross units sold: 150
- Returned units: 10

**Net Units Sold = 150 − 10 = 140**

### Business Questions

- Which products sell the most units?
- Which categories generate the highest volume?
- Are unit sales increasing?
- Which products have low sales activity?

### Reporting Consideration

Canceled orders should be excluded according to the documented sales definition.

---

# 6. Product Revenue Analysis

## Purpose

Evaluate the monetary sales generated by individual products.

### Potential Metrics

- Gross product sales
- Product discounts
- Product refunds
- Net product revenue
- Revenue by category
- Revenue by reporting period

### Simplified Net Product Revenue Formula

**Net Product Revenue = Gross Product Sales − Product Discounts − Product Refunds**

### Illustrative Example

A fictional product records:

- Gross sales: $5,000
- Discounts: $400
- Refunds: $200

**Net Product Revenue = $5,000 − $400 − $200 = $4,400**

This is a hypothetical example.

### Reporting Standard

The treatment of taxes, shipping, refunds, and adjustments must be documented.

---

# 7. Gross Profit Analysis

## Purpose

Evaluate how much revenue remains after the cost of goods sold.

### Formula

**Gross Profit = Net Product Revenue − Cost of Goods Sold**

### Illustrative Example

A fictional product generates:

- Net product revenue: $4,400
- Cost of goods sold: $2,200

**Gross Profit = $4,400 − $2,200 = $2,200**

### Potential Business Questions

- Which products generate the most gross profit?
- Are high-revenue products also high-profit products?
- How does gross profit vary by category?
- Are costs increasing faster than revenue?

### Important Distinction

Gross profit does not include every operating expense.

Marketing, administration, software subscriptions, and other expenses may require separate analysis.

---

# 8. Gross Margin Analysis

## Purpose

Measure gross profit relative to revenue.

### Formula

**Gross Margin % = Gross Profit ÷ Net Product Revenue × 100**

### Illustrative Example

A fictional product generates:

- Net product revenue: $4,400
- Gross profit: $2,200

**Gross Margin = $2,200 ÷ $4,400 × 100 = 50%**

### Analytical Questions

- Which products have the strongest gross margins?
- Which categories have lower margins?
- Do discounts reduce margins significantly?
- Are gross margins changing over time?

### Important Consideration

Gross margin comparisons require consistent cost allocation.

Digital and physical products may have different cost structures.

---

# 9. Product Cost Analysis

Product cost information is essential for accurate margin calculations.

### Potential Cost Categories

**Physical Products**

- Production or supplier cost
- Printing costs
- Packaging costs included in inventory cost
- Inbound freight where applicable
- Other eligible inventory costs

**Digital Products**

- Direct transaction or delivery costs, when classified as cost of sales
- Other directly attributable costs under the selected accounting policy

**Published Products**

- Printing costs
- Distribution-related costs
- Other direct production or fulfillment costs

### Cost Documentation Requirements

- Cost source
- Effective date
- Currency
- Cost classification
- Unit cost
- Allocation methodology
- Known limitations

### Important Principle

**Do not present estimated or unverified product costs as actual business expenses.**

For portfolio practice, synthetic costs must be clearly labeled.

---

# 10. Return Rate Analysis

## Purpose

Evaluate the frequency of product returns.

### Unit Return Rate

**Unit Return Rate = Returned Units ÷ Gross Units Sold × 100**

### Illustrative Example

A fictional product has:

- Gross units sold: 200
- Returned units: 12

**Return Rate = 12 ÷ 200 × 100 = 6%**

### Potential Business Questions

- Which products have higher return rates?
- Are returns concentrated in certain categories?
- Do returns vary by period?
- Are returns affecting realized revenue?

### Important Consideration

Return rates should distinguish returns, refunds, cancellations, and exchanges.

Returns may occur in a later period than the original sale.

---

# 11. Product Mix Analysis

## Purpose

Understand how total business performance is distributed across products and categories.

### Potential Metrics

- Revenue share by category
- Unit share by category
- Gross profit share by category
- Product contribution to total sales

### Revenue Mix Formula

**Product Revenue Share = Product Net Revenue ÷ Total Net Product Revenue × 100**

### Illustrative Example

A fictional product category generates $12,000 of a business's $40,000 in net product revenue.

**Revenue Share = $12,000 ÷ $40,000 × 100 = 30%**

### Analytical Questions

- Which categories generate the largest revenue share?
- Are sales concentrated in a small number of products?
- Which categories generate the most gross profit?
- Is the product mix changing over time?

---

# 12. Product Demand Patterns

## Purpose

Evaluate how product sales change across time periods.

### Potential Metrics

- Units sold by week
- Units sold by month
- Revenue trends
- Seasonal sales patterns
- Category demand trends
- Product launch performance

### Analytical Questions

- Are certain products seasonal?
- Do sales increase during promotional periods?
- Which products show consistent demand?
- Are newer products gaining traction?
- Does demand vary by product category?

### Important Limitation

Observed sales do not always equal underlying demand.

Stockouts, unavailable products, marketing exposure, and pricing may influence recorded sales.

---

# 13. Product Trend Analysis

Product performance can be evaluated over time.

### Potential Reporting Periods

- Weekly
- Monthly
- Quarterly
- Year over year, when comparable history exists

### Potential Analyses

- Revenue growth
- Unit sales growth
- Gross margin trends
- Return rate trends
- Category mix changes

### Period Growth Formula

**Growth Rate = (Current Period Value − Previous Period Value) ÷ Previous Period Value × 100**

### Important Consideration

If the previous period value is zero, percentage growth is undefined and requires separate treatment.

---

# 14. Product Ranking & Contribution Analysis

## Purpose

Identify which products contribute most to business performance.

### Potential Rankings

- Highest units sold
- Highest net revenue
- Highest gross profit
- Highest gross margin
- Highest return rate
- Strongest revenue growth

### Potential Business Questions

- Which products generate the largest share of revenue?
- Which products generate the most gross profit?
- Are top-selling products also the most profitable?
- Which products may require further investigation?

### Analytical Consideration

Product rankings should specify the selected performance metric and reporting period.

---

# 15. Product Pricing Analysis

## Purpose

Explore how pricing relates to revenue, margin, and purchasing activity.

### Potential Metrics

- Listed price
- Average realized selling price
- Discount percentage
- Gross profit per unit
- Gross margin percentage

### Average Realized Selling Price

**Average Realized Selling Price = Net Product Revenue ÷ Net Units Sold**

This calculation requires compatible revenue and unit definitions.

### Potential Business Questions

- Are discounts reducing realized selling prices?
- Which products maintain stronger margins?
- How do product price points differ by category?
- Are pricing changes associated with changes in unit sales?

### Important Limitation

Observed price and sales relationships do not automatically establish price elasticity or causation.

---

# 16. Product Discounts & Promotions

Promotional activity may affect sales volume and realized margins.

### Potential Metrics

- Discount amount
- Discount percentage
- Promotional units sold
- Promotional revenue
- Gross profit during promotions

### Potential Business Questions

- Do promotions increase units sold?
- Are promotional products maintaining positive gross profit?
- Which categories are most frequently discounted?
- Does promotional revenue compensate for lower realized prices?

### Reporting Standard

Promotional effectiveness should account for relevant costs and avoid assuming that all promotional sales are incremental.

---

# 17. Product Profitability

Product Performance Analytics and Product Profitability are related but distinct projects.

| Product Performance Analytics | Product Profitability |
|---|---|
| Units sold | Unit economics |
| Product revenue | Direct and allocated costs |
| Gross margin | Contribution margin |
| Product mix | Break-even analysis |
| Return rates | Profitability scenarios |
| Demand patterns | Financial sustainability |

### Important Principle

Product Performance Analytics provides a broad view of commercial performance.

Product Profitability may provide deeper financial analysis of costs, margins, and pricing decisions.

---

# 18. Product Performance & E-commerce Analytics

Product performance can be connected to online shopping behavior.

### Potential Measures

- Product views
- Add-to-cart activity
- Units sold
- Purchase conversion
- Net product revenue
- Gross margin

### Potential Business Questions

- Which products attract attention but generate limited purchases?
- Are high-view products also high-revenue products?
- Do certain categories have stronger purchase conversion?
- Are product page improvements associated with sales changes?

### Important Limitation

Product views, cart actions, and orders must be linked using consistent reporting definitions.

---

# 19. Product Performance & Customer Analytics

Customer purchasing behavior may influence product performance.

### Potential Measures

- Products purchased by new customers
- Products purchased by returning customers
- Repeat category purchases
- Product combinations
- Customer revenue by category

### Potential Business Questions

- Which products attract first-time customers?
- Which products are purchased by returning customers?
- Are complementary products purchased together?
- Does product category preference change over time?

---

# 20. Evolution Press® Applications

The analytical framework may support future evaluation of publishing products.

### Potential Product Types

- Books
- Workbooks
- Business guides
- Companion resources
- Digital publications

### Potential Analyses

- Units sold by title
- Revenue by publication
- Printing costs
- Gross margins
- Channel comparisons
- Publishing demand trends

### Important Consideration

Publisher royalties, retail sales, and direct-to-consumer sales may use different financial definitions and should not be combined without reconciliation.

---

# 21. Little Bosses™ Applications

The framework may also support future educational product analysis.

### Potential Product Types

- Children's books
- Educational activity books
- Learning workbooks
- Business-themed activities
- Educational kits

### Potential Analyses

- Sales by product type
- Product category demand
- Seasonal purchasing patterns
- Gross margin
- Return rates
- Product bundle performance

These are future analytical applications, not verified product performance results.

---

# 22. Proposed Dataset Structure

| Table | Key Fields | Purpose |
|---|---|---|
| Products | Product ID, category, listed price | Product catalog |
| Orders | Order ID, order date, status | Transaction classification |
| Order Items | Order ID, product ID, quantity, sales amount | Product sales |
| Product Costs | Product ID, effective date, unit cost | Cost analysis |
| Discounts | Order item reference, discount amount | Promotion analysis |
| Returns | Return ID, order item reference, quantity | Return analysis |
| Inventory | Product ID, period, available quantity | Supply context |
| Promotions | Promotion ID, dates, product category | Campaign comparisons |

### Data Modeling Standards

- Use consistent product identifiers.
- Preserve transaction dates.
- Document reporting periods.
- Validate order statuses.
- Reconcile refunds and returns.
- Use effective-dated product costs.
- Avoid duplicate sales.
- Document missing cost information.
- Separate actual and synthetic data.

---

# 23. Proposed Excel Workbook

| Worksheet | Purpose |
|---|---|
| Instructions | Business scenario and learning objectives |
| Product Catalog | Product classifications |
| Sales Transactions | Order-level data |
| Order Items | Product-level sales |
| Product Costs | Unit cost information |
| Returns | Returned products |
| Discounts | Promotional adjustments |
| KPI Calculations | Revenue, margin, and return formulas |
| Product Rankings | Product comparisons |
| Category Analysis | Product mix |
| Trend Analysis | Demand patterns |
| Pricing Analysis | Realized prices and margins |
| Dashboard | Product performance overview |
| Findings | Analytical interpretation |
| Recommendations | Business actions |
| Data Dictionary | Metric definitions |

### Excel Skills to Practice

- Structured tables
- SUMIFS
- COUNTIFS
- XLOOKUP
- IF and IFERROR
- PivotTables
- PivotCharts
- Slicers
- Date grouping
- Revenue calculations
- Gross margin calculations
- Return rate calculations
- Conditional formatting
- Dashboard design

---

# 24. Proposed Product Performance Dashboard

## Executive Overview

- Units sold
- Net product revenue
- Gross profit
- Gross margin percentage
- Return rate

## Product Performance

- Top products by revenue
- Top products by gross profit
- Units sold by product
- Product margin comparison

## Category Performance

- Revenue by category
- Gross profit by category
- Product mix
- Category return rates

## Demand Trends

- Monthly units sold
- Revenue trends
- Seasonal patterns
- Product performance over time

## Pricing & Promotions

- Average realized selling price
- Discounts
- Gross margin trends

### Proposed Filters

- Reporting period
- Product category
- Product
- Sales channel
- Promotion
- Physical versus digital product

---

# 25. Analytical Methodology

1. Define the business problem.
2. Establish product performance objectives.
3. Identify data sources.
4. Define reporting periods.
5. Document sales and cost definitions.
6. Prepare synthetic or authorized data.
7. Validate product records.
8. Reconcile sales transactions.
9. Review returns and refunds.
10. Validate product costs.
11. Calculate units sold.
12. Calculate product revenue.
13. Calculate gross profit.
14. Calculate gross margin.
15. Evaluate return rates.
16. Analyze product mix.
17. Examine demand trends.
18. Compare product categories.
19. Interpret findings.
20. Develop recommendations.
21. Document limitations.
22. Prepare portfolio deliverables.

---

# 26. Potential Business Findings

Actual findings will be documented only after analysis.

Potential questions include:

- Which products generate the most revenue?
- Which products generate the highest gross profit?
- Are top-selling products also high-margin products?
- Which categories experience higher return rates?
- How does product mix change over time?
- Are certain products seasonal?
- Do discounts materially affect margins?
- Which products may require pricing or cost review?

---

# 27. Business Recommendations Framework

| Finding | Potential Recommendation | Business Rationale | Evaluation Metric |
|---|---|---|---|
| [Finding] | [Action] | [Rationale] | [Metric] |

### Potential Recommendations

- Review pricing for low-margin products.
- Evaluate production costs.
- Improve product descriptions.
- Investigate high-return products.
- Review promotional discount levels.
- Adjust merchandising priorities.
- Explore complementary product bundles.
- Improve demand planning.
- Evaluate category profitability.

Recommendations must be supported by completed analysis.

---

# 28. Data Quality & Analytical Limitations

### Potential Data Issues

- Missing product costs
- Inconsistent cost dates
- Duplicate sales records
- Refund timing differences
- Incomplete return information
- Product category changes
- Unavailable inventory data
- Missing discounts
- Inconsistent channel reporting

### Analytical Limitations

- Short sales histories
- Seasonal demand
- Limited product availability
- Promotional influences
- Incomplete cost allocation
- Different physical and digital cost structures
- Differences between sales and royalty reporting

### Reporting Standard

**Gross margin should not be reported as verified when the underlying cost data is incomplete or unverified.**

---

# 29. Privacy & Ethical Reporting

The project will use synthetic data or appropriately authorized business records.

### Data Protection Standards

- Do not publish customer identifying information.
- Avoid exposing confidential supplier agreements.
- Do not disclose restricted cost information.
- Protect order-level customer records.
- Use aggregate reporting where possible.
- Document data permissions.
- Respect platform terms.
- Clearly distinguish actual from synthetic data.

### Important Principle

**Product analytics should support accurate financial and business decisions while respecting customer privacy and commercially sensitive information.**

---

# 30. Project Deliverables

### Foundational Deliverables

- Business problem statement
- Synthetic product sales dataset
- Product KPI dictionary
- Units sold analysis
- Product revenue analysis
- Gross profit calculations
- Gross margin analysis
- Return rate analysis
- Product mix analysis
- Excel dashboard
- Findings and recommendations

### Intermediate Deliverables

- Power Query transformations
- Demand trend analysis
- Product category comparisons
- Power BI product dashboard

### Advanced Deliverables

- SQL product performance reporting
- Python demand analysis
- Multi-source sales and cost integration
- Product demand forecasting
- Product portfolio optimization

---

# 31. Project Completion Checklist

### Setup

- [ ] Business problem defined
- [ ] Data sources selected
- [ ] Reporting periods established
- [ ] Product categories documented
- [ ] KPI definitions completed

### Data Preparation

- [ ] Product catalog validated
- [ ] Sales records reviewed
- [ ] Product costs documented
- [ ] Returns reconciled
- [ ] Discounts reviewed

### Analysis

- [ ] Units sold calculated
- [ ] Product revenue calculated
- [ ] Gross profit calculated
- [ ] Gross margin calculated
- [ ] Return rates calculated
- [ ] Product mix evaluated
- [ ] Product rankings completed
- [ ] Demand trends analyzed
- [ ] Pricing effects reviewed

### Reporting

- [ ] Dashboard developed
- [ ] Calculations validated
- [ ] Findings documented
- [ ] Recommendations supported by evidence
- [ ] Limitations disclosed

### Portfolio Documentation

- [ ] README reviewed
- [ ] Supporting files organized
- [ ] Skills demonstrated accurately recorded
- [ ] Lessons learned documented
- [ ] Portfolio Progress updated

---

# 32. Professional Development & Career Alignment

This project is intended to strengthen skills relevant to:

- Business Analyst
- Data Analyst
- Financial Analyst
- E-commerce Analyst
- Product Analyst
- Business Intelligence Analyst
- Sales Analyst
- Reporting Analyst
- Merchandising Analyst

### Intended Competencies

- Product revenue analysis
- Financial KPI calculations
- Gross margin analysis
- Return rate measurement
- Product mix evaluation
- Demand trend analysis
- Data validation
- Excel financial modeling
- PivotTables
- SQL reporting
- Python analysis
- Power BI dashboards
- Analytical communication
- Evidence-based recommendations

These represent intended learning outcomes rather than completed accomplishments.

---

# 33. Long-Term Project Vision

The long-term objective is to develop a repeatable product performance framework that connects sales volume, revenue, cost, profitability, returns, and demand.

For Shop the Evolution™, the framework may eventually support product assortment, pricing, merchandising, and product development decisions.

For Evolution Press®, it may support evaluation of books, workbooks, educational guides, and digital publications.

For Little Bosses™, it may support future analysis of educational resources, children's books, and learning products.

For my Business Analytics portfolio, this project provides an opportunity to combine financial operations knowledge, accounting principles, data analysis, and business intelligence.

**The goal is not simply to identify which products sell the most, but to understand which products contribute to financially sustainable business performance.**

---

## Current Project Status

**Planned — Analytical Framework Defined**

No completed product analysis, validated dataset, dashboard, or verified findings are represented by this README.

All illustrative figures and examples are hypothetical.

Future updates will document completed deliverables, demonstrated technical skills, and evidence-based findings.

---

## Related Documentation

- [Analytical Methodology](../Documentation/Analytical-Methodology.md)
- [Dataset Sources](../Documentation/Dataset-Sources.md)
- [Project Documentation Standards](../Documentation/Project-Documentation-Standards.md)
- [Portfolio Progress](../Documentation/Portfolio-Progress.md)
- [Portfolio Home](../README.md)

---

*This project is intended for educational and professional portfolio development. Proposed analyses do not represent actual product performance, completed analytical work, or verified financial results.*
