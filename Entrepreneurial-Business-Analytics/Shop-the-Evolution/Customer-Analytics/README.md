# Customer Analytics

## Customer Behavior, Retention, Purchase Frequency & Lifetime Value Analysis

### Shop the Evolution™ | Business Analytics Portfolio

## Project Overview

**Customer Analytics** is a planned Business Analytics portfolio project focused on understanding customer purchasing behavior, repeat purchases, retention, cohort performance, and customer lifetime value.

The project explores how businesses can use transaction data to identify purchasing patterns, evaluate customer relationships over time, and make informed decisions about marketing, product development, and customer retention.

The primary business scenario is based on **Shop the Evolution™**, a commerce initiative within the Evolve with Kiea business ecosystem.

The analytical methods may also apply to publishing, digital products, educational resources, and other product-based businesses.

The initial project will use a realistic synthetic dataset in Microsoft Excel. Future versions may incorporate SQL, Python, Power Query, and Power BI to support more advanced customer analysis.

**Project Status:** Planned — Analytical Framework Defined

**Portfolio Category:** E-commerce Analytics / Customer Analytics / Business Intelligence

**Primary Business Application:** Shop the Evolution™

**Related Initiatives:** Evolution Press®, Little Bosses™, Evolve with Kiea

**Potential Tools:** Microsoft Excel, Power Query, SQL, Python, Power BI

**Initial Deliverable:** Customer purchase behavior and retention analysis workbook

**Future Deliverable:** Interactive customer analytics dashboard

---

# 1. Business Background

Product-based businesses need to understand more than total sales and order volume.

Customer behavior can reveal whether a business is primarily attracting first-time buyers, developing repeat purchasing relationships, or relying on a relatively small number of customers.

For Shop the Evolution™, potential product categories include:

- Planners
- Journals
- Workbooks
- Books and guides
- Digital products
- Educational resources
- Affirmation cards
- Gifts and lifestyle products

Different product categories may have different purchasing patterns.

For example, customers may purchase a digital template once, return for another workbook, or purchase gifts during particular seasons.

These are possible scenarios rather than verified customer behaviors.

Understanding such differences may help businesses evaluate retention opportunities, product relationships, and long-term commercial performance.

---

# 2. Business Problem

Sales reporting explains what customers purchased and how much revenue was generated.

However, sales totals alone do not explain:

- How many customers are purchasing for the first time.
- How frequently customers return.
- How purchasing behavior changes over time.
- Whether customers remain active.
- Which customer cohorts generate repeat purchases.
- How customer value differs across product categories.
- Whether customer acquisition and retention efforts are financially sustainable.

Without customer-level analytical frameworks, businesses may make marketing and product decisions based primarily on short-term sales.

### Central Business Question

**How can Shop the Evolution™ use appropriately protected customer transaction data to understand purchase frequency, repeat purchasing, retention, cohort behavior, and customer value in order to support sustainable business decisions?**

---

# 3. Project Objectives

1. Establish consistent customer analytics definitions.
2. Distinguish new customers from returning customers.
3. Measure purchase frequency.
4. Evaluate repeat purchase behavior.
5. Calculate customer retention.
6. Analyze customer cohorts.
7. Examine customer purchase intervals.
8. Compare purchasing behavior across product categories.
9. Explore customer lifetime value concepts.
10. Identify opportunities for customer retention.
11. Develop customer performance dashboards.
12. Practice Excel, SQL, and Power BI techniques.
13. Apply privacy-conscious analytical methods.
14. Document data limitations and assumptions.
15. Develop evidence-based business recommendations.

---

# 4. Customer Analytics Framework

| Analytical Area | Business Question | Potential Measures |
|---|---|---|
| Customer Acquisition | How many customers make their first purchase? | New customers |
| Repeat Purchasing | How many customers purchase again? | Repeat purchase rate |
| Purchase Frequency | How often do customers place orders? | Orders per customer |
| Retention | How many customers return during a defined period? | Retention rate |
| Cohort Behavior | How do customer groups behave over time? | Cohort retention |
| Purchase Value | How much do customers spend? | Average order value |
| Customer Value | What financial value do customer relationships generate? | Historical customer revenue, CLV estimates |
| Product Relationships | What categories do customers purchase together or over time? | Category overlap, repeat category purchases |

### Key Principle

**Customer acquisition, repeat purchasing, retention, and customer lifetime value are related but different analytical concepts.**

Each requires clear definitions and appropriate data.

---

# 5. New Versus Returning Customers

## Purpose

Distinguish first-time purchasers from customers with previous qualifying purchases.

### Definitions

**New Customer:** A customer making their first recorded qualifying purchase.

**Returning Customer:** A customer making a qualifying purchase after an earlier qualifying purchase.

### Potential Metrics

- New customers
- Returning customers
- Orders from new customers
- Orders from returning customers
- Revenue from each group

### Analytical Questions

- What percentage of purchasing customers are new?
- How many customers return?
- Does the mix of new and returning customers change over time?
- Which product categories attract first-time purchasers?

### Important Consideration

A customer may be new to the available dataset but not new to the business.

Historical coverage must be documented before classifying customers.

---

# 6. Repeat Purchase Analysis

## Purpose

Evaluate how many customers place multiple qualifying orders.

### Repeat Purchase Rate

**Repeat Purchase Rate = Customers With Two or More Qualifying Orders ÷ Customers With at Least One Qualifying Order × 100**

### Illustrative Example

A fictional dataset contains 200 purchasing customers.

Of these, 50 placed at least two qualifying orders.

**Repeat Purchase Rate = 50 ÷ 200 × 100 = 25%**

This is a hypothetical example.

### Analytical Questions

- What proportion of customers purchase more than once?
- Which product categories are associated with repeat purchases?
- How does repeat purchasing change over time?
- Are repeat purchases concentrated among certain customer cohorts?

### Reporting Requirement

The observation window must be specified. Customers acquired recently have had less time to make a second purchase.

---

# 7. Purchase Frequency Analysis

## Purpose

Measure how frequently customers purchase during a defined period.

### Purchase Frequency

**Purchase Frequency = Total Qualifying Orders ÷ Unique Purchasing Customers**

### Illustrative Example

A fictional business records 300 qualifying orders from 200 unique customers.

**Purchase Frequency = 300 ÷ 200 = 1.5 Orders per Customer**

### Potential Metrics

- Orders per customer
- Average purchase frequency
- Median purchase frequency
- Customers with one order
- Customers with two orders
- Customers with three or more orders

### Analytical Questions

- How often do customers purchase?
- Are repeat orders increasing?
- Do purchase patterns differ by product category?
- Are purchases seasonal?

---

# 8. Customer Retention Analysis

## Purpose

Evaluate whether customers return during a defined reporting period.

Retention must be defined carefully because different industries use different approaches.

### Example Period Retention Formula

**Retention Rate = Customers Active in Both the Previous and Current Period ÷ Customers Active in the Previous Period × 100**

### Illustrative Example

A fictional business has 100 purchasing customers in January.

Of those customers, 30 make another qualifying purchase in February.

**January-to-February Retention Rate = 30 ÷ 100 × 100 = 30%**

### Important Consideration

This represents a specific period-to-period purchase retention definition.

It should not automatically be compared with subscription retention or other customer retention methodologies.

### Potential Business Questions

- How many customers return in the next month?
- Does retention vary by acquisition cohort?
- Are certain product categories associated with stronger repeat purchasing?
- How does retention change over longer periods?

---

# 9. Customer Cohort Analysis

## Purpose

Examine how groups of customers behave after their first recorded purchase.

### Cohort Definition

A cohort is a group of customers sharing a defined starting characteristic.

For this project, the primary cohort may be the month of a customer's first qualifying purchase.

### Illustrative Cohorts

- January first-purchase customers
- February first-purchase customers
- March first-purchase customers

### Example Cohort Retention Table

| First Purchase Cohort | Month 0 | Month 1 | Month 2 | Month 3 |
|---|---:|---:|---:|---:|
| January | 100% | 30% | 22% | 18% |
| February | 100% | 28% | 20% | — |
| March | 100% | 35% | — | — |

All values are fictional.

The table assumes each percentage represents the share of the original cohort purchasing in that specific month.

### Analytical Questions

- Which cohorts return most frequently?
- Does repeat purchasing improve over time?
- Are newer cohorts behaving differently?
- Which cohorts generate higher cumulative spending?

### Reporting Standard

Incomplete observation periods should be left blank or clearly marked rather than treated as zero retention.

---

# 10. Time Between Purchases

## Purpose

Measure the interval between qualifying customer orders.

### Potential Metrics

- Days between first and second purchase
- Average days between purchases
- Median days between purchases
- Purchase interval distribution

### Analytical Questions

- How long does it take customers to purchase again?
- Does the interval differ by product category?
- Are repeat purchases clustered around seasonal events?
- Are customers returning for related products?

### Important Limitation

Long purchase intervals may be normal for certain products.

A customer who purchases a planner once per year should not automatically be considered disengaged after several months.

---

# 11. Average Order Value

Average order value measures the average monetary value of qualifying orders.

### Formula

**Average Order Value = Net Sales ÷ Qualifying Orders**

### Illustrative Example

A fictional business records $6,000 in net sales across 200 qualifying orders.

**AOV = $6,000 ÷ 200 = $30**

### Analytical Questions

- Does average order value differ between new and returning customers?
- Which product categories contribute to larger orders?
- Are bundles associated with higher order values?
- Does AOV change over time?

### Important Consideration

The sales definition must be documented, including how discounts, refunds, taxes, and shipping are treated.

---

# 12. Customer Revenue Analysis

## Purpose

Evaluate the historical revenue associated with customer purchasing activity.

### Potential Metrics

- Net sales per customer
- Average revenue per purchasing customer
- Median revenue per customer
- Cumulative customer revenue
- Revenue by customer cohort

### Historical Customer Revenue

**Historical Customer Revenue = Sum of Qualifying Net Sales Associated With a Customer**

### Important Distinction

Historical customer revenue is not the same as projected customer lifetime value.

Historical revenue describes observed transactions.

Lifetime value models attempt to estimate future economic value.

---

# 13. Customer Lifetime Value Concepts

## Purpose

Explore methods for estimating the long-term economic value of customer relationships.

Customer lifetime value, or CLV, may be calculated using different models.

### Introductory Revenue-Based Model

**Estimated Customer Lifetime Revenue = Average Order Value × Expected Annual Purchase Frequency × Expected Customer Relationship Duration**

### Illustrative Example

Assume a fictional customer relationship has:

- Average order value: $30
- Expected annual purchase frequency: 2 orders
- Expected relationship duration: 3 years

**Estimated Lifetime Revenue = $30 × 2 × 3 = $180**

This is a simplified hypothetical estimate of revenue, not profit.

### Financial Considerations

A more financially useful model may incorporate:

- Product contribution margins
- Discounts
- Refunds
- Fulfillment costs
- Customer retention probabilities
- Customer acquisition costs
- Time value of money

### Important Limitation

Expected relationship duration is difficult to estimate for a new business without sufficient historical data.

Early CLV estimates should be presented as scenarios rather than reliable forecasts.

---

# 14. Customer Acquisition Cost

Customer acquisition cost may be evaluated when suitable marketing and acquisition data is available.

### Formula

**Customer Acquisition Cost = Defined Customer Acquisition Spending ÷ New Customers Acquired**

### Illustrative Example

A fictional campaign incurs $500 in eligible acquisition spending and acquires 25 new customers.

**CAC = $500 ÷ 25 = $20**

### Potential Analytical Questions

- How much does customer acquisition cost?
- Does acquisition cost vary by channel?
- Is acquisition spending financially sustainable?
- How does acquisition cost compare with estimated customer contribution?

### Important Consideration

Customer acquisition cost depends on which expenses and customers are included.

It should not be interpreted as a complete profitability measure.

---

# 15. Customer Segmentation

Customer behavior may be grouped using non-identifying characteristics.

### Potential Segments

- New customers
- Returning customers
- One-time purchasers
- Repeat purchasers
- Purchase frequency groups
- Product category preferences
- First-purchase cohorts
- Broad order value bands

### Analytical Questions

- Which segments purchase most frequently?
- Do repeat customers buy different product categories?
- Are certain cohorts associated with higher order values?
- Which segments may benefit from additional product education?

### Privacy Standard

Segments should be aggregated and sufficiently large to avoid identifying individuals.

---

# 16. Product Category Purchasing Behavior

Shop the Evolution™ may offer multiple product categories with different purchasing patterns.

### Potential Categories

- Planners
- Journals
- Workbooks
- Books
- Digital products
- Educational resources
- Gifts

### Potential Analyses

- First-purchase category
- Repeat-purchase category
- Cross-category purchasing
- Category combinations
- Revenue by customer category
- Purchase frequency by category

### Potential Business Questions

- Which categories attract first-time customers?
- Do customers return for complementary products?
- Are digital products associated with later physical purchases?
- Which product combinations appear frequently?

### Important Limitation

Product associations do not automatically establish that one purchase caused another.

---

# 17. Customer Purchase Journey

The project may examine recorded purchasing sequences.

### Illustrative Journey

**First Purchase: Business Workbook → Second Purchase: Planner → Third Purchase: Digital Template**

### Potential Analytical Areas

- First purchased product
- Second purchased product
- Time between purchases
- Product category transitions
- Repeat order value

### Business Questions

- Which products commonly appear in first orders?
- Which products are purchased by returning customers?
- Are complementary products purchased together?
- Does product discovery influence future purchasing patterns?

The example is hypothetical and does not represent actual customer behavior.

---

# 18. Customer Analytics & Marketing Performance

Customer behavior can help evaluate marketing beyond immediate conversions.

### Potential Measures

- New customers by acquisition channel
- Repeat customers by original acquisition channel
- Customer acquisition cost
- Historical customer revenue
- Cohort purchasing behavior
- Estimated CLV

### Potential Business Questions

- Which acquisition channels attract returning customers?
- Do customers from different channels show different purchase patterns?
- Are acquisition costs supported by customer contribution?
- Does marketing attract one-time or repeat purchasers?

### Important Limitation

Attribution models may assign customers to channels differently.

Observed relationships should not automatically be treated as causal.

---

# 19. Customer Analytics & Product Profitability

Customer value analysis should eventually connect purchasing behavior with product economics.

### Potential Measures

- Revenue per customer
- Contribution per customer
- Product margin
- Repeat purchase contribution
- Customer acquisition cost
- Estimated lifetime contribution

### Business Questions

- Do repeat customers generate positive contribution?
- Which product categories support sustainable customer relationships?
- Are discounts affecting customer profitability?
- Are customer acquisition expenses justified by expected contribution?

### Important Principle

**High customer revenue does not necessarily mean high customer profitability.**

---

# 20. Proposed Dataset Structure

| Table | Key Fields | Purpose |
|---|---|---|
| Customers | Anonymous customer ID, first purchase date | Customer identification |
| Orders | Order ID, anonymous customer ID, order date | Purchase history |
| Order Items | Order ID, product ID, quantity | Product-level analysis |
| Products | Product ID, category, price | Product classification |
| Refunds | Refund ID, order reference, amount | Sales adjustments |
| Acquisition Channels | Anonymous customer ID, recorded source | Acquisition analysis |
| Customer Cohorts | Anonymous customer ID, cohort month | Cohort reporting |
| Marketing Costs | Channel, period, spending | Acquisition cost analysis |

### Data Modeling Standards

- Use non-identifying customer keys.
- Preserve order dates.
- Establish consistent purchase definitions.
- Exclude canceled orders where appropriate.
- Handle refunded transactions consistently.
- Avoid duplicate customer counts.
- Document incomplete history.
- Protect original customer records.

### Important Privacy Consideration

Pseudonymous customer identifiers may still represent personal data if they can be linked back to individuals.

Public portfolio datasets should preferably use fully synthetic records.

---

# 21. Proposed Excel Workbook

| Worksheet | Purpose |
|---|---|
| Instructions | Business scenario and learning objectives |
| Customer Data | Synthetic customer identifiers |
| Order Data | Purchase transactions |
| Order Items | Products purchased |
| Product Catalog | Product categories |
| Customer Calculations | Purchase counts and first purchase dates |
| New vs Returning | Customer classification |
| Purchase Frequency | Orders per customer |
| Retention Analysis | Repeat purchasing |
| Cohort Analysis | Monthly customer cohorts |
| Customer Revenue | Historical spending |
| CLV Scenarios | Introductory lifetime value estimates |
| Dashboard | Customer performance overview |
| Findings | Analytical interpretation |
| Recommendations | Business actions |
| Data Dictionary | Definitions and formulas |

### Excel Skills to Practice

- Structured tables
- COUNTIFS
- SUMIFS
- MINIFS
- MAXIFS
- XLOOKUP
- IF and IFERROR
- UNIQUE, where supported
- Date calculations
- PivotTables
- PivotCharts
- Cohort tables
- Conditional formatting
- Slicers
- Dashboard design

---

# 22. Proposed Customer Analytics Dashboard

## Customer Overview

- Total purchasing customers
- New customers
- Returning customers
- Repeat purchase rate

## Purchasing Behavior

- Total orders
- Purchase frequency
- Average order value
- Average time between purchases

## Retention

- Period retention rate
- Repeat purchase trends
- Customer cohort heatmap

## Customer Value

- Historical revenue per customer
- Revenue by cohort
- Illustrative CLV scenarios

## Product Behavior

- First-purchase categories
- Repeat-purchase categories
- Cross-category purchases

### Proposed Filters

- Reporting period
- Customer cohort
- Product category
- Acquisition channel
- New versus returning customer

---

# 23. Analytical Methodology

1. Define the business problem.
2. Establish customer analytics objectives.
3. Identify appropriate data sources.
4. Review privacy requirements.
5. Define qualifying purchases.
6. Establish reporting periods.
7. Prepare synthetic or authorized data.
8. Validate customer and order records.
9. Identify first purchases.
10. Classify new and returning customers.
11. Calculate purchase frequency.
12. Measure repeat purchasing.
13. Analyze retention.
14. Build cohort tables.
15. Evaluate customer revenue.
16. Develop CLV scenarios.
17. Compare purchasing patterns.
18. Interpret findings.
19. Develop recommendations.
20. Document limitations.
21. Prepare portfolio deliverables.

---

# 24. Potential Business Findings

Actual findings will be documented only after analysis.

Potential analytical questions include:

- What percentage of customers purchase more than once?
- Which cohorts have stronger repeat purchase activity?
- How long does it take customers to make a second purchase?
- Do returning customers have higher average order values?
- Which product categories attract first-time customers?
- Are customers purchasing across multiple categories?
- How does customer value differ by acquisition channel?
- What assumptions most influence estimated CLV?

---

# 25. Business Recommendations Framework

| Finding | Potential Recommendation | Business Rationale | Evaluation Metric |
|---|---|---|---|
| [Finding] | [Action] | [Rationale] | [Metric] |

### Potential Recommendations

- Improve post-purchase education.
- Introduce relevant complementary product recommendations.
- Evaluate product bundles.
- Refine customer acquisition priorities.
- Improve customer retention communications.
- Review product pricing.
- Evaluate repeat purchasing by category.
- Monitor cohort performance.

Recommendations should be supported by completed analysis and should respect customer consent and communication preferences.

---

# 26. Data Quality & Analytical Limitations

### Potential Data Issues

- Duplicate customer records
- Incomplete transaction history
- Missing customer identifiers
- Canceled orders
- Refunded purchases
- Guest checkout records
- Inconsistent acquisition data
- Short observation periods

### Analytical Limitations

- Customer identity matching
- Limited historical data
- Seasonal purchasing patterns
- Differences between product categories
- Incomplete acquisition attribution
- Small cohort sizes
- Uncertain customer lifetime assumptions

### Reporting Standard

Retention and CLV estimates should not be presented as precise forecasts when historical data is insufficient.

---

# 27. Privacy & Ethical Reporting

Customer analytics requires careful protection of personal information.

### Privacy Standards

- Use synthetic datasets for public demonstrations.
- Do not publish customer names.
- Do not expose email addresses.
- Do not disclose phone numbers.
- Do not publish shipping or billing addresses.
- Do not expose payment information.
- Do not publish individual purchasing histories from real customers.
- Use aggregated reporting.
- Avoid identifying small customer groups.
- Document data permissions.
- Respect applicable privacy requirements.

### Important Principle

**Customer analytics should support responsible business decisions without compromising customer confidentiality or trust.**

---

# 28. Project Deliverables

### Foundational Deliverables

- Customer analytics problem statement
- Synthetic customer and order dataset
- KPI definitions
- New versus returning customer analysis
- Purchase frequency calculations
- Repeat purchase analysis
- Customer revenue summary
- Excel dashboard
- Findings and recommendations

### Intermediate Deliverables

- Cohort retention analysis
- Purchase interval analysis
- Customer segmentation
- Power Query transformations
- Power BI customer dashboard

### Advanced Deliverables

- SQL customer analytics
- Python cohort analysis
- More advanced CLV modeling
- Customer contribution analysis
- Multi-source customer reporting

---

# 29. Project Completion Checklist

### Setup

- [ ] Business problem defined
- [ ] Data sources selected
- [ ] Customer privacy requirements reviewed
- [ ] Reporting periods established
- [ ] Purchase definitions documented

### Data Preparation

- [ ] Customer records validated
- [ ] Duplicate records reviewed
- [ ] Order history prepared
- [ ] Product categories assigned
- [ ] Refund treatment documented

### Analysis

- [ ] New customers identified
- [ ] Returning customers identified
- [ ] Repeat purchase rate calculated
- [ ] Purchase frequency analyzed
- [ ] Retention measured
- [ ] Cohort analysis completed
- [ ] Customer revenue evaluated
- [ ] CLV scenarios developed
- [ ] Product category behavior reviewed

### Reporting

- [ ] Dashboard developed
- [ ] Findings supported by evidence
- [ ] Recommendations documented
- [ ] Limitations disclosed

### Portfolio Documentation

- [ ] README reviewed
- [ ] Supporting files organized
- [ ] Skills demonstrated accurately recorded
- [ ] Lessons learned documented
- [ ] Portfolio Progress updated

---

# 30. Professional Development & Career Alignment

This project is intended to support career development in:

- Business Analytics
- Customer Analytics
- E-commerce Analytics
- Marketing Analytics
- Financial Analytics
- Business Intelligence

### Potential Career Roles

- Business Analyst
- Data Analyst
- Customer Insights Analyst
- E-commerce Analyst
- Marketing Analyst
- Business Intelligence Analyst
- Reporting Analyst
- Customer Retention Analyst

### Intended Skill Development

- Customer behavior analysis
- Purchase frequency analysis
- Customer retention measurement
- Cohort analysis
- Customer revenue reporting
- Lifetime value concepts
- Data preparation
- Excel formulas
- PivotTables
- Dashboard design
- SQL
- Python
- Power BI
- Analytical communication
- Privacy-conscious reporting

These represent intended learning outcomes rather than completed accomplishments.

---

# 31. Long-Term Project Vision

The long-term objective is to develop a customer analytics framework that connects purchasing behavior, retention, product relationships, and financial performance.

For Shop the Evolution™, the framework may support understanding how customers purchase across different product categories and whether they return for additional resources.

For Evolution Press®, it may help evaluate repeat purchasing across books, workbooks, and digital educational products.

For Little Bosses™, it may support future analysis of educational product purchasing patterns.

For Brand Evolution Marketing Agency, the methods may provide a foundation for future authorized client customer analytics reporting.

For my Business Analytics portfolio, the project offers an opportunity to connect financial analysis, transaction reporting, customer behavior, and business intelligence.

**The goal is not simply to count customers, but to understand purchasing patterns, evaluate customer relationships responsibly, and identify opportunities for sustainable business growth.**

---

## Current Project Status

**Planned — Analytical Framework Defined**

No completed customer analysis, validated dataset, dashboard, or verified findings are represented by this README.

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

*This project is intended for educational and professional portfolio development. Proposed analyses do not represent actual customer behavior, completed analytical work, or verified business results.*
