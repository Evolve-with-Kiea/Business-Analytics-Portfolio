# Power BI Projects

## Business Intelligence, Data Modeling, DAX, Interactive Dashboards & KPI Reporting

### Business Analytics Portfolio | Microsoft Power BI

## Project Overview

**Power BI Projects** is a dedicated section of my Business Analytics portfolio focused on transforming raw business data into accurate, interactive, and meaningful business intelligence reports.

This section will document projects that demonstrate the complete Power BI reporting process, from defining a business question and preparing source data to developing data models, creating DAX measures, designing visualizations, and communicating analytical findings.

The goal is to understand how business intelligence solutions are developed, validated, documented, and used to support decision-making.

My professional background in accounting, financial operations, reconciliations, and business systems provides a foundation for understanding business transactions, reporting requirements, financial accuracy, and operational performance.

Through my ongoing Business Analytics studies, I intend to expand that experience into Power BI development, data modeling, DAX, interactive reporting, and performance management.

Projects will use public or synthetic datasets and follow consistent standards for analytical methodology, data quality, technical documentation, accessibility, and responsible interpretation.

**Portfolio Category:** Power BI / Business Intelligence / Data Analytics / Reporting

**Current Status:** Planned — Project Frameworks Established

**Primary Tool:** Microsoft Power BI Desktop

**Supporting Tool:** Microsoft Excel

**Potential Future Tools:** Power Query, SQL, Python

**Data Approach:** Public, synthetic, or appropriately authorized and protected data

**Primary Learning Goal:** Develop practical Power BI projects that demonstrate data preparation, data modeling, DAX calculations, dashboard development, KPI reporting, and business interpretation.

**Primary Deliverables:** Power BI report files, data model diagrams, DAX measure references, dashboard screenshots, validation documentation, and project READMEs.

---

# 1. Purpose

Businesses generate information through sales, financial transactions, customer activity, marketing campaigns, and operational processes.

However, raw data is not automatically useful for decision-making.

Business intelligence tools help organize this information into consistent models, measures, reports, and visualizations.

Power BI provides opportunities to explore how data can be transformed into reports that answer specific business questions.

### Central Business Question

**How can organizations use Power BI to transform raw business data into reliable, interactive reports that monitor performance, explain trends, and support informed business decisions?**

### Supporting Business Questions

- What business problem should the report address?
- Who will use the report?
- Which data sources are appropriate?
- How should the data be cleaned?
- What relationships are required?
- Which DAX measures should be developed?
- How should KPIs be defined?
- Which visuals best communicate the results?
- How can users interact with the report?
- How can calculations be validated?
- What limitations should be documented?

---

# 2. Power BI Project Directory

This section is organized into two primary project areas.

| Project Area | Analytical Focus | Directory |
|---|---|---|
| Business Dashboards | End-to-end Power BI reporting, from data importing and modeling to interactive report design | [Business Dashboards](Business-Dashboards/README.md) |
| KPI Reporting | Performance measurement, actual-versus-target comparisons, trends, variances, and executive scorecards | [KPI Reporting](KPI-Reporting/README.md) |

Each folder contains its own learning objectives, technical framework, potential projects, and documentation requirements.

These areas represent planned educational work rather than completed Power BI reports.

---

# 3. How the Two Project Areas Connect

Business Dashboards and KPI Reporting share many technical foundations but serve different analytical purposes.

| Area | Primary Question | Reporting Focus |
|---|---|---|
| Business Dashboards | How can users explore and understand business performance? | Broad interactive analysis |
| KPI Reporting | How does performance compare with defined objectives and targets? | Performance monitoring and accountability |

### Illustrative Business Scenario

A hypothetical retail company wants to understand sales performance.

A Business Dashboard may display revenue trends, product category comparisons, regional performance, and customer purchasing patterns.

A KPI Report may compare monthly revenue, gross margin, and average order value with established targets.

Together, these reports can provide both analytical detail and concise performance monitoring.

**The goal is to understand how Power BI can support both exploratory business analysis and structured performance reporting.**

---

# 4. Learning Objectives

Projects in this section are intended to strengthen the ability to:

1. Define business reporting requirements.
2. Identify the intended reporting audience.
3. Select appropriate data sources.
4. Import data into Power BI.
5. Clean and transform data using Power Query.
6. Understand data grain.
7. Organize fact and dimension tables.
8. Build basic star schemas.
9. Create table relationships.
10. Understand cardinality.
11. Understand filter direction.
12. Develop foundational DAX measures.
13. Understand filter context.
14. Define business KPIs.
15. Compare actual performance with targets.
16. Analyze trends and variances.
17. Select appropriate visualizations.
18. Design interactive reports.
19. Configure filters and slicers.
20. Validate calculations.
21. Test report interactions.
22. Apply accessibility principles.
23. Document technical decisions.
24. Communicate business findings.
25. Present completed projects professionally.

---

# 5. Power BI Development Lifecycle

Power BI projects should follow a consistent development process.

| Stage | Primary Focus | Expected Documentation |
|---|---|---|
| Business Requirements | Define reporting objectives | Audience, questions, KPIs |
| Data Acquisition | Select and import source data | Source, format, permissions |
| Data Transformation | Prepare data in Power Query | Cleaning steps and rationale |
| Data Modeling | Organize analytical tables | Fact tables, dimensions, grain |
| Relationships | Connect model tables | Keys, cardinality, filter direction |
| DAX Development | Create calculations | Measures, definitions, validation |
| Visualization | Select report visuals | Chart purpose and design choices |
| Interactivity | Configure user controls | Slicers, filters, drill-down |
| Validation | Test accuracy | Reconciliations and checks |
| Reporting | Interpret results | Findings and limitations |
| Documentation | Prepare portfolio evidence | README, screenshots, model diagram |

---

# 6. Business Requirements & Reporting Audience

## Purpose

Identify what the report should accomplish before developing visuals.

### Potential Audiences

- Business owners
- Financial analysts
- Accounting managers
- Sales managers
- Marketing managers
- Operations managers
- Executive decision-makers

### Requirements to Document

- Business problem
- Intended audience
- Reporting objectives
- Primary KPIs
- Supporting metrics
- Required dimensions
- Reporting period
- Expected filters
- Decisions the report should support

### Important Principle

**A Power BI report should be designed around a defined business need rather than the availability of charts or data fields.**

---

# 7. Data Sources

Projects should use public, synthetic, or appropriately authorized and protected datasets.

### Potential Sources

- Excel workbooks
- CSV files
- Public business datasets
- Synthetic financial transactions
- Synthetic sales records
- Synthetic customer datasets
- Synthetic operational records
- SQL databases in future projects

### Documentation Requirements

Each dataset should include:

- Source name
- Source location
- File format
- Data scope
- Date accessed, where applicable
- License or usage conditions
- Privacy considerations
- Known limitations

### Documentation Reference

[Dataset Sources](../Documentation/Dataset-Sources.md)

---

# 8. Data Importing

## Purpose

Bring source data into Power BI for transformation and modeling.

### Initial Learning Areas

- Importing Excel files
- Importing CSV files
- Reviewing source columns
- Identifying data types
- Understanding connection settings
- Recognizing refresh considerations

### Future Learning Areas

- SQL database connections
- Multi-source reporting
- More advanced connectivity options

### Important Consideration

Data connection methods should be selected according to source requirements, reporting needs, and available technical resources.

---

# 9. Power Query Data Transformation

## Purpose

Clean and prepare source data before analysis.

### Potential Transformations

- Change data types.
- Remove duplicates.
- Handle missing values.
- Standardize column names.
- Filter unnecessary records.
- Split columns.
- Merge queries.
- Append tables.
- Create transformation columns.
- Remove irrelevant fields.

### Documentation Requirements

Each significant transformation should explain:

- What changed.
- Why it was necessary.
- Which fields were affected.
- How the result was validated.

### Important Principle

**Data preparation should support accurate, consistent, and reproducible reporting.**

---

# 10. Understanding Data Grain

## Purpose

Define what one row represents in each dataset.

### Examples

| Table | Possible Grain |
|---|---|
| Sales | One row per transaction |
| Order Lines | One row per product within an order |
| Customers | One row per customer |
| Products | One row per product |
| Calendar | One row per date |
| Targets | One row per KPI per reporting period |

### Important Consideration

Combining tables with incompatible grains can cause duplicated totals or misleading measures.

---

# 11. Data Modeling

## Purpose

Organize business data into a structure that supports reliable analysis.

### Common Table Types

**Fact Tables**

Contain measurable business events.

Examples:

- Sales transactions
- Expenses
- Orders
- Fulfillment records

**Dimension Tables**

Contain descriptive attributes used to group and filter facts.

Examples:

- Date
- Product
- Customer
- Region
- Department

### Important Principle

A well-designed model simplifies DAX calculations and supports consistent filtering.

---

# 12. Star Schema Fundamentals

A star schema commonly organizes a central fact table alongside related dimensions.

### Illustrative Structure

```text id="d5yg5j"
           DimDate
              |
DimProduct—FactSales—DimCustomer
              |
           DimRegion
```

### Potential Benefits

- Clearer relationships
- Consistent filtering
- Easier measure development
- More understandable reports
- Better model maintainability

### Important Consideration

The actual model should reflect the dataset's grain and reporting requirements.

---

# 13. Table Relationships

## Purpose

Define how tables connect within the semantic model.

### Relationship Concepts

- Primary keys
- Foreign keys
- Cardinality
- Filter direction
- Active relationships
- Inactive relationships

### Common Cardinality Types

- One-to-many
- Many-to-one
- One-to-one
- Many-to-many

### Important Principle

**Incorrect relationships can produce misleading totals even when individual DAX formulas appear correct.**

---

# 14. Filter Context

## Purpose

Understand how report selections affect calculations.

### Potential Filters

- Reporting period
- Product category
- Department
- Region
- Customer segment

### Example

A Total Revenue measure may show overall revenue.

When a product category is selected, the same measure may display revenue for that category.

### Important Consideration

Unexpected results may be caused by relationship configuration, DAX logic, or filter context.

---

# 15. DAX Fundamentals

DAX stands for **Data Analysis Expressions**.

It is used to create analytical calculations in Power BI semantic models.

### Initial Functions

- SUM
- AVERAGE
- COUNTROWS
- DISTINCTCOUNT
- DIVIDE
- CALCULATE
- SELECTEDVALUE

### Potential Measures

- Total Revenue
- Total Orders
- Average Order Value
- Total Expenses
- Gross Profit
- Gross Margin
- Revenue Target
- Target Variance

### Important Principle

**DAX measures should be based on documented business definitions and validated against known values.**

---

# 16. Illustrative DAX Measures

These examples assume an appropriately configured data model.

### Total Revenue

```dax id="d1z0gi"
Total Revenue =
SUM(FactSales[NetRevenue])
```

### Total Orders

```dax id="mfxs72"
Total Orders =
DISTINCTCOUNT(FactSales[OrderID])
```

### Average Order Value

```dax id="cb1bap"
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

### Total Expenses

```dax id="oswo9g"
Total Expenses =
SUM(FactExpenses[ExpenseAmount])
```

### Revenue Variance

```dax id="ngy77u"
Revenue Variance =
[Total Revenue] - [Revenue Target]
```

### Revenue Variance Percentage

```dax id="71zmds"
Revenue Variance % =
DIVIDE([Revenue Variance], [Revenue Target])
```

### Important Consideration

These examples are illustrative. Actual calculations must be adapted to the dataset and validated.

---

# 17. Measures Versus Calculated Columns

## Measures

Calculated dynamically based on report filter context.

### Example Uses

- Revenue totals
- Expense totals
- Profit margins
- KPI variances

## Calculated Columns

Computed at the row level and stored in the model.

### Example Uses

- Row classifications
- Certain derived attributes
- Supporting model fields

### Important Consideration

Measures are generally appropriate for aggregations that must respond to user selections.

---

# 18. Date Tables & Time Intelligence

## Purpose

Support consistent reporting across time periods.

### Potential Date Attributes

- Date
- Year
- Quarter
- Month
- Month Number
- Year-Month

### Potential Measures

- Monthly Revenue
- Year-to-Date Revenue
- Prior-Year Revenue
- Year-over-Year Growth

### Important Consideration

Time-intelligence measures require suitable date relationships and reporting definitions.

---

# 19. KPI Development

## Purpose

Translate business objectives into measurable indicators.

### Potential KPI Categories

| Category | Example KPIs |
|---|---|
| Sales | Revenue, orders, average order value |
| Financial | Gross margin, operating margin, expense ratio |
| Marketing | Conversion rate, CPA, ROAS |
| Operations | Cycle time, error rate, on-time rate |
| Customer | Retention, repeat purchases, estimated CLV |

### KPI Documentation

Each KPI should include:

- Name
- Business definition
- Formula
- Data source
- Reporting period
- Target, if applicable
- Unit
- Validation method
- Interpretation
- Limitations

---

# 20. Actual Versus Target Reporting

## Purpose

Compare business performance with defined goals.

### Potential Measures

- Actual value
- Target value
- Absolute variance
- Percentage variance
- Target attainment

### Formula

**Absolute Variance = Actual − Target**

### Percentage Variance

**Variance % = (Actual − Target) ÷ Target × 100**

### Important Consideration

Positive variances are not always favorable.

Interpretation depends on whether higher or lower values are desirable for the KPI.

---

# 21. Trend Analysis

## Purpose

Evaluate changes in business performance over time.

### Potential Comparisons

- Daily
- Weekly
- Monthly
- Quarterly
- Year-over-year

### Potential Questions

- Is revenue increasing?
- Are expenses changing?
- Are operational results improving?
- Are KPIs consistently meeting targets?

### Important Consideration

Trend analysis should account for seasonality, incomplete periods, and changes in data definitions.

---

# 22. Visualization Selection

Different visuals support different business questions.

| Visual | Appropriate Use |
|---|---|
| KPI Card | Display a primary measure |
| Line Chart | Show trends |
| Bar Chart | Compare categories |
| Column Chart | Compare periods |
| Matrix | Present detailed summaries |
| Table | Display supporting values |
| Scatter Chart | Explore relationships |
| Waterfall Chart | Explain changes |
| Slicer | Filter reports |

### Important Principle

**Visualizations should communicate information accurately rather than simply improve appearance.**

---

# 23. Interactive Reporting

## Purpose

Allow users to explore business information.

### Potential Features

- Slicers
- Page filters
- Visual filters
- Drill-down
- Drill-through
- Tooltips
- Bookmarks
- Report navigation

### Testing Requirements

- Confirm intended filtering.
- Validate measure results.
- Test multiple selections.
- Review interactions.
- Confirm navigation behavior.

### Important Consideration

Interactivity should support the report's business purpose.

---

# 24. Dashboard & Report Design

## Purpose

Create reports that are readable, organized, and useful.

### Design Principles

- Clear report titles
- Defined reporting periods
- Prominent primary KPIs
- Logical visual hierarchy
- Consistent typography
- Appropriate spacing
- Readable number formats
- Accessible contrast
- Minimal unnecessary clutter

### Important Principle

**Effective report design makes business information easier to understand and act upon.**

---

# 25. Power BI Reports Versus Dashboards

Power BI distinguishes between reports and dashboards.

### Power BI Report

A collection of one or more pages containing visuals based on a semantic model.

### Power BI Dashboard

A single-page canvas in the Power BI service containing pinned tiles.

### Portfolio Convention

This section uses the term *business dashboards* broadly for business intelligence reporting projects.

Individual projects should accurately identify whether the deliverable is a Power BI Desktop report, a published report, or a Power BI service dashboard.

---

# 26. Accessibility Standards

Accessible reports should consider:

- Readable text sizes
- Sufficient contrast
- Descriptive titles
- Clear labels
- Meaningful alternative text where supported
- Keyboard navigation
- Avoiding reliance on color alone

### Important Principle

Accessibility is part of professional report quality.

---

# 27. Data Validation & Quality Assurance

## Purpose

Verify that the report accurately represents source data.

### Potential Checks

- Reconcile source totals.
- Validate unique counts.
- Confirm relationship keys.
- Review duplicate records.
- Validate DAX calculations.
- Compare results with Excel.
- Test slicer behavior.
- Confirm reporting periods.
- Review blank values.
- Check number formats.

### Important Principle

**A report should not be considered complete until calculations, relationships, and interactions have been tested.**

---

# 28. Report Performance & Maintenance

## Purpose

Understand how model and report design affect performance.

### Potential Topics

- Unnecessary columns
- Large imported tables
- Model complexity
- Relationship design
- DAX efficiency
- Excessive visualizations
- Data refresh considerations

### Important Consideration

A Power BI Desktop file does not automatically establish a deployed, scheduled-refresh reporting solution.

Deployment and refresh functionality should only be documented after configuration and verification.

---

# 29. Data Privacy & PBIX File Safety

Power BI files can contain embedded data.

### Important Requirements

Before publishing a `.pbix` file:

- Confirm that the data is public or synthetic.
- Verify dataset licensing.
- Review embedded tables.
- Remove confidential records.
- Review sensitive columns.
- Check for exposed credentials or connection information.
- Confirm that no private customer information is included.
- Review supporting files and screenshots.

### Important Consideration

Removing sensitive fields from visible report pages does not necessarily remove them from the underlying model.

The full report file must be reviewed before public distribution.

---

# 30. Proposed Project File Structure

Each completed project should have its own subfolder.

### Illustrative Structure

```text id="u5ymcv"
Power-BI-Projects/
│
├── README.md
│
├── Business-Dashboards/
│   ├── README.md
│   └── Example-Sales-Dashboard/
│       ├── README.md
│       ├── data/
│       ├── reports/
│       ├── screenshots/
│       └── documentation/
│
└── KPI-Reporting/
    ├── README.md
    └── Example-KPI-Scorecard/
        ├── README.md
        ├── data/
        ├── reports/
        ├── screenshots/
        └── documentation/
```

### Potential Files

- Power BI report file (`.pbix`)
- Public or synthetic dataset
- Data dictionary
- Data model diagram
- DAX measure reference
- Dashboard screenshots
- Validation notes
- Project README

### Important Consideration

This structure is illustrative. Project folders should be created as work is completed.

---

# 31. Project Documentation Requirements

Each completed project should include:

- Project title
- Business problem
- Intended audience
- Objectives
- Dataset description
- Data source
- Data preparation steps
- Power Query transformations
- Data model
- Relationship definitions
- DAX measures
- KPI definitions
- Report screenshots
- Validation checks
- Findings
- Recommendations
- Limitations
- Skills demonstrated
- Lessons learned
- Project status

### Documentation Reference

[Project Documentation Standards](../Documentation/Project-Documentation-Standards.md)

---

# 32. Analytical Methodology

Each project should follow a consistent process.

1. Define the business question.
2. Identify the reporting audience.
3. Establish project objectives.
4. Select relevant KPIs.
5. Choose a dataset.
6. Document data sources.
7. Import data into Power BI.
8. Clean data in Power Query.
9. Define data grain.
10. Build the data model.
11. Create relationships.
12. Develop DAX measures.
13. Validate calculations.
14. Design report visuals.
15. Configure interactivity.
16. Test filters and interactions.
17. Interpret findings.
18. Identify limitations.
19. Document recommendations.
20. Update portfolio progress.

### Methodology Reference

[Analytical Methodology](../Documentation/Analytical-Methodology.md)

---

# 33. Potential Project Ideas

These are future learning opportunities, not completed projects.

## Project 1: Retail Sales Dashboard

**Folder:** Business Dashboards

**Difficulty:** Beginner

### Potential Tasks

- Import sales data.
- Prepare records in Power Query.
- Create relationships.
- Develop basic DAX measures.
- Build sales visualizations.
- Add slicers.
- Validate totals.
- Document findings.

### Intended Skills

- Data importing
- Power Query
- Data modeling
- DAX fundamentals
- Report design

---

## Project 2: Customer Overview Dashboard

**Folder:** Business Dashboards

**Difficulty:** Beginner to Intermediate

### Potential Tasks

- Import synthetic customer data.
- Prepare customer and order tables.
- Calculate customer measures.
- Compare purchasing patterns.
- Build interactive visuals.
- Validate calculations.

### Intended Skills

- Customer analytics
- Data modeling
- DAX
- Dashboard development

---

## Project 3: Executive KPI Scorecard

**Folder:** KPI Reporting

**Difficulty:** Beginner to Intermediate

### Potential Tasks

- Import synthetic performance data.
- Import target data.
- Create KPI measures.
- Calculate variances.
- Build performance indicators.
- Analyze trends.
- Validate results.

### Intended Skills

- KPI development
- DAX
- Variance analysis
- Executive reporting

---

## Project 4: Operational KPI Report

**Folder:** KPI Reporting

**Difficulty:** Intermediate

### Potential Tasks

- Import synthetic workflow data.
- Define operational KPIs.
- Calculate processing measures.
- Compare results with targets.
- Build interactive visuals.
- Document findings.

### Intended Skills

- Operational analytics
- DAX
- Performance reporting
- Business interpretation

---

# 34. Business Findings & Recommendations

Completed projects should explain what the report reveals.

### Recommended Framework

| Component | Documentation Expectation |
|---|---|
| Business Question | What was the report intended to answer? |
| KPI | Which measure is relevant? |
| Finding | What does the data show? |
| Supporting Evidence | Which values support the finding? |
| Interpretation | Why might the result matter? |
| Limitation | What remains uncertain? |
| Recommendation | What should be investigated next? |

### Important Principle

**Power BI reports should support evidence-based interpretation rather than unsupported conclusions about business performance.**

---

# 35. Potential Applications Across My Business Ecosystem

The methods developed in this section may eventually support business intelligence reporting across the Evolve with Kiea business ecosystem.

### Shop the Evolution™

Potential applications:

- E-commerce sales dashboards
- Product performance reporting
- Revenue trends
- Customer purchasing analysis
- Sales KPI scorecards

### Evolution Press®

Potential applications:

- Publishing sales reports
- Book performance dashboards
- Revenue tracking
- Publishing KPI reporting

### Evolve with Kiea

Potential applications:

- Content performance reporting
- Digital product analytics
- Audience engagement dashboards
- Marketing performance reporting

### Brand Evolution Marketing Agency

Potential future applications:

- Client business dashboards
- Campaign performance reports
- Marketing KPI scorecards
- Financial performance dashboards
- Custom reporting services

These are potential applications and do not represent completed projects, deployed systems, or professional client work.

---

# 36. Professional Development & Career Alignment

This section supports my ongoing development toward roles such as:

- Power BI Analyst
- Business Intelligence Analyst
- Data Analyst
- Business Analyst
- Reporting Analyst
- Financial Data Analyst
- Operations Analyst
- Marketing Analyst
- Business Performance Analyst

### Intended Skills

- Power BI Desktop
- Power Query
- Data preparation
- Data modeling
- Star schema fundamentals
- Table relationships
- DAX measures
- KPI development
- Variance analysis
- Interactive reporting
- Dashboard design
- Data validation
- Technical documentation
- Analytical communication

These represent intended learning outcomes rather than completed competencies.

---

# 37. Project Completion Checklist

### Portfolio Foundation

- [x] Define Power BI project areas
- [x] Establish folder organization
- [x] Identify technical learning topics
- [x] Establish documentation requirements
- [x] Define data privacy expectations

### Data Preparation

- [ ] Select initial Power BI dataset
- [ ] Document data source
- [ ] Import data
- [ ] Apply Power Query transformations
- [ ] Validate cleaned data

### Data Modeling

- [ ] Define fact and dimension tables
- [ ] Document data grain
- [ ] Create relationships
- [ ] Validate cardinality
- [ ] Review filter direction

### DAX Development

- [ ] Create foundational measures
- [ ] Document formulas
- [ ] Validate calculations
- [ ] Test filter context

### Report Development

- [ ] Build KPI visuals
- [ ] Create business charts
- [ ] Add slicers
- [ ] Test interactions
- [ ] Review accessibility
- [ ] Validate report totals

### Portfolio Documentation

- [ ] Save Power BI report file
- [ ] Capture screenshots
- [ ] Document data model
- [ ] Create project README
- [ ] Document findings
- [ ] Explain limitations
- [ ] Update Portfolio Progress

---

# 38. Long-Term Learning Vision

The long-term objective of this section is to develop practical Power BI projects demonstrating how raw data can be transformed into accurate, interactive business intelligence reports.

These projects will provide opportunities to strengthen data preparation, data modeling, DAX calculations, KPI development, visualization, validation, and analytical communication.

As my technical skills develop, I intend to expand selected projects using SQL, advanced DAX, and additional business intelligence techniques.

For my professional development, this section supports the development of analytical skills applicable to accounting, financial reporting, marketing, operations, e-commerce, and business performance management.

**The goal is to move beyond creating attractive dashboards toward developing accurate, well-documented reporting solutions that help organizations understand performance, investigate business questions, and make informed decisions.**

---

## Current Status

**Planned — Power BI Project Framework Established**

No Power BI projects have been completed in this section yet.

The Business Dashboards and KPI Reporting folders define areas for future learning and portfolio development.

Completed reports, validated calculations, dashboards, and demonstrated skills will be documented as projects are developed.

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

*This section is intended for educational and professional portfolio development. Proposed projects do not represent completed Power BI reports, validated business findings, deployed reporting systems, or demonstrated technical competencies until supporting work has been completed and documented.*
