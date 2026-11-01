# Dataset Sources

## Public Data Resources, Synthetic Data & Responsible Dataset Selection

### Purpose

This document provides a structured reference for identifying, evaluating, selecting, and documenting datasets used in my Business Analytics learning activities and professional portfolio case studies.

Its purpose is to establish consistent standards for selecting reliable information, assessing data quality, understanding usage permissions, protecting sensitive information, and ensuring that datasets are appropriate for the business questions being investigated.

As I pursue my Associate of Applied Science in Business Analytics at Wake Technical Community College, I am developing practical capabilities in data preparation, financial analysis, business intelligence, reporting, and analytical problem-solving.

My professional background in accounting and financial operations provides relevant business context for evaluating financial transactions, reporting requirements, reconciliations, operational workflows, and performance measures.

This resource supports my development of analytical skills using Microsoft Excel, SQL, Python, Power BI, and related tools.

**Guiding Principle: A dataset should be selected because it supports a meaningful business question—not simply because it is available, large, or convenient to analyze.**

### Scope of This Resource

This document includes:

- Public dataset discovery resources
- Financial and economic data sources
- Business and marketing data opportunities
- Synthetic data development
- Dataset reliability and quality evaluation
- Licensing and permitted-use considerations
- Privacy and ethical data handling
- Data documentation standards
- Dataset selection templates
- Portfolio project applications

Only general source websites are listed here. Individual datasets, exact download links, licenses, access dates, and applicable terms will be recorded in the corresponding project documentation.

**Important:** Inclusion in this directory does not establish that every dataset hosted by a source is accurate, current, unrestricted, or suitable for redistribution. Terms and availability must be reviewed for each selected dataset.

---

# 1. Why Dataset Selection Matters

The reliability of an analysis depends partly on the quality, relevance, and suitability of the information used.

A technically correct calculation can still produce misleading results when the underlying dataset is incomplete, poorly defined, inconsistent, or unrelated to the business question.

### Dataset Selection Objectives

Before beginning an analytical project, I should determine:

1. What business question needs to be answered?
2. Which variables are necessary?
3. What time period is relevant?
4. What does each record represent?
5. Where can suitable information be obtained?
6. Is the source credible?
7. Are the data sufficiently complete?
8. Are usage permissions appropriate?
9. Are there privacy concerns?
10. What limitations could affect the findings?

### Business-First Example

**Business Question:** How have inflation and interest rates changed over time?

**Potential Source:** FRED or another relevant official economic data provider.

**Required Information:** Clearly defined economic indicators, observation dates, units, and reporting frequency.

**Potential Analysis:** Trend analysis and comparison across selected periods.

**Important Limitation:** Observed relationships between economic indicators do not automatically establish causation.

---

# 2. Public Dataset Discovery Resources

The following resources provide access to, or help locate, publicly available datasets.

| Source | Description | Potential Analytical Applications |
|---|---|---|
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Community-contributed datasets covering many subjects | Retail, sales, marketing, customer behavior, financial practice |
| [Data.gov](https://data.gov/) | U.S. government open-data catalog | Public policy, business conditions, economic and operational analysis |
| [U.S. Census Bureau](https://www.census.gov/data.html) | Demographic, population, and economic statistics | Market research, demographic analysis, business planning |
| [FRED](https://fred.stlouisfed.org/) | Economic time-series data maintained by the Federal Reserve Bank of St. Louis | Inflation, employment, interest rates, economic trends |
| [World Bank Open Data](https://data.worldbank.org/) | International development and economic indicators | Country comparisons, economic and development analysis |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | Search engine for discovering datasets hosted by other organizations | Dataset discovery across business and analytical topics |
| [UCI Machine Learning Repository](https://archive.ics.uci.edu/) | Research and educational datasets | Data exploration, classification, statistical practice |
| [SEC EDGAR](https://www.sec.gov/edgar) | Public company regulatory filings | Financial statement analysis, company performance comparisons |
| [U.S. Bureau of Labor Statistics](https://www.bls.gov/data/) | Labor market, employment, price, and productivity statistics | Employment trends, inflation, compensation and productivity analysis |

### Source Selection Considerations

These resources serve different purposes.

For example:

- **Kaggle** may be useful for beginner-friendly datasets and practical exercises, but individual contributors and licenses require evaluation.
- **Government statistical sources** may provide stronger documentation for official economic indicators.
- **SEC EDGAR** may support financial statement analysis, but filings require understanding of accounting definitions and reporting periods.
- **Google Dataset Search** helps locate datasets but does not independently establish the reliability or permitted use of the underlying data.

---

# 3. Financial & Accounting Data Sources

Financial analysis is a primary area of interest because of my professional accounting and financial operations experience.

### Recommended Source Categories

| Source | Potential Use | Important Considerations |
|---|---|---|
| [SEC EDGAR](https://www.sec.gov/edgar) | Public company financial statements | Reporting periods, accounting policies, consolidated statements |
| [FRED](https://fred.stlouisfed.org/) | Interest rates, inflation, economic indicators | Units, frequency, revisions, source attribution |
| [Data.gov](https://data.gov/) | Government financial and economic datasets | Agency definitions, coverage, update frequency |
| [Kaggle](https://www.kaggle.com/datasets) | Synthetic or shared transaction datasets | Data provenance, realism, licenses |
| [World Bank Open Data](https://data.worldbank.org/) | International economic indicators | Country coverage, comparability, missing observations |

### Potential Financial Analysis Projects

- Financial statement comparisons
- Revenue and expense trend analysis
- Profitability analysis
- Financial ratio calculations
- Budget variance exercises
- Accounts receivable aging
- Accounts payable analysis
- Cash flow analysis
- Financial KPI development

### Important Distinction

Public company financial statements are not the same as internal accounting transaction records.

For example, an accounts receivable aging analysis generally requires invoice-level data that may not be available in public financial statements.

Synthetic datasets may therefore be more appropriate for practicing detailed accounting workflows.

---

# 4. Sales, Retail & E-commerce Data

Sales and e-commerce datasets can support practical exercises involving revenue, profitability, product performance, and customer behavior.

### Potential Data Fields

- Order identifier
- Order date
- Product identifier
- Product category
- Quantity sold
- Unit price
- Discount
- Revenue
- Product cost
- Sales channel
- Customer identifier
- Return status

### Potential Analytical Questions

- Which products generate the highest revenue?
- Which categories contribute the strongest gross profit?
- How do sales change across reporting periods?
- What is the average order value?
- Which channels contribute the most orders?
- How do discounts affect reported margins?
- What percentage of customers make repeat purchases?

### Suitable Discovery Resources

- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Google Dataset Search](https://datasetsearch.research.google.com/)

### Dataset Suitability Considerations

Sales datasets should be reviewed for:

- Order-level versus line-item structure
- Returns and refunds
- Discounts
- Currency
- Tax treatment
- Shipping charges
- Product cost availability
- Duplicate transactions
- Missing dates
- Customer identifier consistency

**Analytical Reminder:** Sales revenue is not the same as profit. A dataset without reliable cost information may support revenue analysis but not meaningful profitability calculations.

---

# 5. Marketing & Customer Analytics Data

Marketing datasets can support analysis of campaigns, customer acquisition, conversion, and engagement.

### Potential Data Fields

- Campaign identifier
- Marketing channel
- Campaign dates
- Advertising spend
- Impressions
- Clicks
- Conversions
- Orders
- Attributed revenue
- Customer segment

### Potential Analytical Questions

- Which channels generate the most conversions?
- How do campaign costs compare?
- Which campaigns have the lowest acquisition costs?
- How does conversion rate vary by channel?
- Which customer segments demonstrate repeat purchasing?
- How does attributed revenue compare with advertising spend?

### Potential Data Sources

- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)

### Marketing Data Limitations

Marketing datasets may contain incomplete attribution, inconsistent conversion definitions, missing costs, or limited customer history.

A high number of impressions or clicks does not automatically indicate profitability.

Marketing analysis should distinguish activity metrics from business outcomes.

---

# 6. Economic, Labor Market & Business Environment Data

Economic and demographic datasets can provide useful context for business planning and analytical research.

| Source | Potential Focus |
|---|---|
| [FRED](https://fred.stlouisfed.org/) | Economic time series |
| [U.S. Census Bureau](https://www.census.gov/data.html) | Population and business demographics |
| [Bureau of Labor Statistics](https://www.bls.gov/data/) | Employment, wages, prices, productivity |
| [World Bank Open Data](https://data.worldbank.org/) | International economic comparisons |
| [Data.gov](https://data.gov/) | Public datasets across agencies |

### Potential Projects

- Inflation trend analysis
- Employment trend comparisons
- Wage comparisons by occupation
- Population change analysis
- Regional economic indicators
- Small-business market research
- International economic comparisons

### Evaluation Considerations

Economic data may be revised after initial publication.

Different indicators may use different:

- Units
- Reporting frequencies
- Seasonal adjustments
- Geographic boundaries
- Population definitions
- Base years
- Calculation methods

These differences should be documented before combining or comparing datasets.

---

# 7. Operations & Business Process Data

Operational datasets can support analysis of efficiency, transaction processing, workflow delays, and performance measurement.

### Potential Data Fields

- Transaction identifier
- Process stage
- Start date or timestamp
- Completion date or timestamp
- Assigned department
- Transaction type
- Processing status
- Exception indicator
- Error category

### Potential Analytical Questions

- What is the average processing time?
- Which workflow stages experience delays?
- How frequently do exceptions occur?
- Does transaction volume change by period?
- Which process categories have the highest error rates?
- How does processing performance vary by department?

### Suitable Data Approaches

Because internal operational data may be confidential, synthetic datasets can provide a safer way to practice business process analysis.

### Potential Portfolio Applications

- Invoice processing analysis
- Payment processing analysis
- Workflow efficiency
- Process cycle time
- Transaction exception analysis
- Operational KPI reporting

---

# 8. Synthetic Data for Analytical Practice

## What Is Synthetic Data?

Synthetic data is artificially generated information designed to represent selected characteristics of a business process, dataset, or analytical scenario.

It can provide a practical learning environment when real business information is unavailable, confidential, or unsuitable for publication.

Synthetic data should be clearly distinguished from actual operational records.

### Potential Applications

- Accounts receivable aging
- Accounts payable transactions
- Retail sales
- Product profitability
- Customer purchasing behavior
- Marketing campaign performance
- Invoice processing
- Budget variance
- Financial reporting

### Example: Synthetic Accounts Receivable Dataset

Potential fields:

| Field | Example |
|---|---|
| Invoice_ID | INV-001 |
| Customer_ID | CUST-101 |
| Invoice_Date | 2026-01-15 |
| Due_Date | 2026-02-14 |
| Invoice_Amount | 1500.00 |
| Balance_Due | 750.00 |
| Payment_Status | Partially Paid |

*These are illustrative values, not actual customer records.*

### Synthetic Data Development Standards

When generating synthetic data:

1. Define the hypothetical business scenario.
2. Identify required fields.
3. Establish realistic business rules.
4. Document assumptions.
5. Define the reporting period.
6. Explain how values were generated.
7. Include realistic variation where appropriate.
8. Validate internal consistency.
9. Identify intentionally introduced data quality issues.
10. Label the dataset as synthetic.

### Important Limitations

Synthetic data may be useful for testing formulas, queries, dashboards, and analytical workflows.

However, results generated from synthetic data should not be presented as evidence of actual business performance.

Artificially generated patterns may reflect the assumptions built into the dataset rather than real-world behavior.

---

# 9. Dataset Licensing & Permitted Use

## Purpose

Before using or publishing a dataset, I should review its applicable license, terms, and restrictions.

Public accessibility does not automatically mean that a dataset can be freely copied, modified, redistributed, or used commercially.

### Licensing Checklist

- [ ] Dataset creator or publisher identified
- [ ] License or terms located
- [ ] Intended analytical use permitted
- [ ] Redistribution requirements reviewed
- [ ] Attribution requirements identified
- [ ] Modification restrictions considered
- [ ] Commercial-use restrictions reviewed where relevant
- [ ] Access date recorded

### Important Distinctions

**Access:** Whether the dataset can be viewed or obtained.

**Use:** Whether the data can be analyzed for the intended purpose.

**Redistribution:** Whether copies can be included in a public GitHub repository.

**Attribution:** Whether the source must be credited.

**Modification:** Whether transformed versions may be shared.

### Practical Portfolio Approach

When redistribution rights are uncertain, document the source and applicable terms rather than uploading a copy of the dataset.

Where permitted, a project can provide instructions explaining how a reader may obtain the data independently.

---

# 10. Source Reliability Evaluation

A dataset should be evaluated according to its origin, documentation, and intended purpose.

### Source Reliability Questions

- Who created the dataset?
- Is the publisher identifiable?
- How was the information collected?
- Is the methodology documented?
- What population or process does it represent?
- When was it collected?
- When was it last updated?
- Are revisions documented?
- Are known limitations disclosed?
- Can important values be verified?

### Reliability Considerations

| Source Characteristic | Evaluation |
|---|---|
| Official Statistical Agency | Review definitions, methodology, revisions |
| Public Company Filing | Review accounting context and reporting period |
| Academic Repository | Review documentation and collection methods |
| Community-Contributed Dataset | Verify creator, source, and permissions |
| Synthetic Dataset | Review generation logic and assumptions |
| Aggregated Dataset | Investigate original sources and transformations |

No source category guarantees suitability for every analytical question.

---

# 11. Dataset Quality Evaluation

## Core Data Quality Dimensions

| Dimension | Evaluation Question |
|---|---|
| Accuracy | Are the values credible and correctly represented? |
| Completeness | Are necessary records and fields present? |
| Consistency | Are formats and definitions uniform? |
| Validity | Do values follow appropriate rules? |
| Uniqueness | Are records appropriately identified? |
| Timeliness | Is the reporting period suitable? |
| Relevance | Does the information answer the research question? |
| Integrity | Are relationships and totals logically consistent? |

### Common Issues

- Missing values
- Duplicate records
- Inconsistent date formats
- Invalid identifiers
- Unexpected negative values
- Incomplete reporting periods
- Undefined fields
- Unclear units
- Inconsistent category labels
- Outliers
- Missing cost information
- Incorrect aggregation levels

### Data Quality Assessment Checklist

- [ ] Record count reviewed
- [ ] Field names understood
- [ ] Data types examined
- [ ] Missing values assessed
- [ ] Duplicate records investigated
- [ ] Date ranges checked
- [ ] Units and currencies identified
- [ ] Outliers reviewed
- [ ] Relevant totals verified where possible
- [ ] Significant limitations documented

---

# 12. Privacy, Confidentiality & Responsible Data Use

Portfolio development should not compromise confidential information or privacy.

### Information Requiring Special Care

- Customer names and contact information
- Employee records
- Bank account information
- Payment details
- Personal financial information
- Confidential invoices
- Internal employer reports
- Proprietary pricing
- Restricted business records

### Responsible Data Practices

- Use public data with appropriate permissions.
- Use synthetic data when real information is restricted.
- Avoid uploading confidential business files.
- Review datasets for personal information.
- Consider re-identification risks.
- Do not assume anonymization establishes permission to publish.
- Avoid exposing sensitive information through screenshots or supporting files.
- Document applicable restrictions.

### Data Handling Principle

**Only publish information that is appropriate and authorized for public distribution.**

---

# 13. Dataset Suitability & Feasibility Assessment

A dataset may be reliable but still unsuitable for a particular analytical project.

### Suitability Questions

1. Does it support the business problem?
2. Are required variables present?
3. Is the reporting period relevant?
4. Is the unit of analysis appropriate?
5. Are important definitions available?
6. Is the dataset sufficiently complete?
7. Can the planned calculations be performed?
8. Are important limitations manageable?
9. Is the dataset appropriate for my current learning level?
10. Can the analysis be documented responsibly?

### Dataset Evaluation Matrix

| Criterion | Evaluation | Notes |
|---|---|---|
| Business Relevance | High / Medium / Low | [Notes] |
| Source Reliability | High / Medium / Low | [Notes] |
| Data Completeness | High / Medium / Low | [Notes] |
| Field Documentation | High / Medium / Low | [Notes] |
| Analytical Suitability | High / Medium / Low | [Notes] |
| Technical Feasibility | High / Medium / Low | [Notes] |
| Permitted Use | Confirmed / Unclear / Restricted | [Notes] |
| Privacy Risk | Low / Medium / High | [Notes] |

This matrix is a qualitative planning aid rather than a validated scoring system.

### Selection Decision

**Dataset Selected:** [Name]

**Reason for Selection:** [Explanation]

**Questions Supported:** [Questions]

**Known Limitations:** [Limitations]

**Additional Data Needed:** [Description]

---

# 14. Dataset Documentation Template

Use the following template in each analytical project.

```markdown
## Dataset Information

**Dataset Name:** [Name]

**Publisher / Creator:** [Source]

**Source Website:** [Website]

**Exact Dataset Link:** [URL]

**Date Accessed:** [Date]

**License / Terms:** [Terms]

**Scenario Type:** Public / Synthetic / Authorized

**Reporting Period:** [Period]

**Record Count:** [Count]

**Field Count:** [Count]

**Unit of Analysis:** [Description]

**Key Fields:** [Fields]

**Data Description:** [Description]

**Collection Method:** [Method, if known]

**Source Reliability:** [Assessment]

**Data Quality Issues:** [Issues]

**Privacy Considerations:** [Considerations]

**Redistribution Permission:** [Status]

**Known Limitations:** [Limitations]

**Reason for Selection:** [Explanation]

**Research Questions Supported:** [Questions]
```

---

# 15. Data Dictionary Template

A data dictionary documents the meaning, type, and intended use of dataset fields.

| Field Name | Description | Data Type | Example | Analytical Purpose |
|---|---|---|---|---|
| [Field] | [Meaning] | [Type] | [Example] | [Purpose] |

### Data Dictionary Checklist

- [ ] Important fields defined
- [ ] Data types identified
- [ ] Date formats documented
- [ ] Units explained
- [ ] Identifiers described
- [ ] Calculated fields distinguished
- [ ] Missing-value conventions identified
- [ ] Relevant business rules documented

---

# 16. Dataset Selection Workflow

### Step 1 — Define the Business Question

Identify what the analysis should answer.

### Step 2 — Identify Required Fields

Determine the variables, reporting period, and unit of analysis.

### Step 3 — Search Appropriate Sources

Use public data catalogs, official statistical resources, educational repositories, or synthetic data.

### Step 4 — Evaluate Source Reliability

Review publisher information, documentation, collection methods, and limitations.

### Step 5 — Review Licensing & Privacy

Confirm that the intended use and publication approach are appropriate.

### Step 6 — Assess Data Quality

Examine completeness, consistency, validity, and suitability.

### Step 7 — Select the Dataset

Explain why the dataset supports the analytical objective.

### Step 8 — Document the Selection

Record the exact source, access date, license, key fields, and limitations.

### Step 9 — Begin Data Preparation

Follow the established analytical methodology.

### Step 10 — Preserve Source Information

Retain appropriate documentation so that the analysis can be understood and reproduced where feasible.

---

# 17. Beginner-Friendly Dataset Selection Strategy

As I develop analytical skills, I intend to begin with manageable datasets and gradually progress toward more complex analytical scenarios.

### Foundational Projects

**Dataset Characteristics**

- Limited number of fields
- Clear variable definitions
- Manageable record counts
- Straightforward business questions
- Simple calculations

**Potential Tools**

- Excel
- PivotTables
- Basic charts

**Example Projects**

- Monthly sales analysis
- Expense summaries
- Basic profitability calculations

### Intermediate Projects

**Dataset Characteristics**

- Multiple categories
- Larger record counts
- More complex calculations
- Additional cleaning requirements
- Related tables

**Potential Tools**

- Excel
- Power Query
- SQL
- Python
- Power BI

**Example Projects**

- Accounts receivable aging
- Customer purchasing analysis
- Financial KPI reporting

### Advanced Projects

**Dataset Characteristics**

- Multiple related sources
- More complex transformations
- Larger reporting requirements
- Time-based comparisons
- Additional validation needs

**Potential Tools**

- SQL
- Python
- Power BI
- Integrated analytical workflows

**Example Projects**

- Financial performance dashboards
- Multi-source business intelligence reports
- Operational performance analysis

This progression represents intended learning development rather than completed work.

---

# 18. Proposed Portfolio Dataset Applications

| Proposed Project | Potential Dataset | Business Focus |
|---|---|---|
| Accounts Receivable Aging | Synthetic invoice records | Overdue balance analysis |
| Accounts Payable Analysis | Synthetic vendor invoices | Payment and workflow reporting |
| Sales Performance | Retail transaction data | Revenue trends |
| Product Profitability | Sales and cost records | Margin analysis |
| Budget Variance | Synthetic budget and actuals | Financial performance |
| Marketing Performance | Campaign metrics | Channel comparisons |
| Customer Purchasing | Transaction-level customer data | Repeat purchase patterns |
| Economic Trends | Official economic indicators | Trend analysis |
| Public Company Financial Analysis | SEC filings | Financial statement comparisons |
| Operational Efficiency | Synthetic process records | Cycle time and exceptions |

These are proposed analytical exercises and should not be represented as completed projects.

---

# 19. Dataset Evaluation Checklist

Before using a dataset in a portfolio project:

### Source

- [ ] Publisher identified
- [ ] Original source recorded
- [ ] Collection method reviewed
- [ ] Reporting period understood
- [ ] Relevant definitions available

### Permissions

- [ ] License or terms reviewed
- [ ] Intended use permitted
- [ ] Redistribution permission confirmed if uploading
- [ ] Attribution requirements documented

### Quality

- [ ] Important fields present
- [ ] Missing values assessed
- [ ] Duplicates investigated
- [ ] Units and formats understood
- [ ] Significant limitations identified

### Suitability

- [ ] Business question supported
- [ ] Research questions answerable
- [ ] Required calculations feasible
- [ ] Dataset complexity appropriate
- [ ] Additional data needs considered

### Documentation

- [ ] Exact dataset link recorded
- [ ] Date accessed documented
- [ ] Data dictionary prepared
- [ ] Scenario type identified
- [ ] Limitations disclosed

---

# 20. Professional Development & Career Alignment

Dataset evaluation supports multiple competencies relevant to my long-term career interests.

### Relevant Career Areas

- Financial Analyst
- Financial Data Analyst
- Accounting Analyst
- Business Analyst
- Data Analyst
- Business Intelligence Analyst
- Business Systems Analyst
- Operations Analyst
- Reporting Analyst

### Competencies Developed Through Dataset Work

- Data sourcing
- Source reliability evaluation
- Business requirements analysis
- Data quality assessment
- Data documentation
- Data preparation
- Privacy awareness
- Analytical reasoning
- KPI development
- Reproducibility
- Professional communication

As future projects are completed, the corresponding evidence will document which competencies have been applied in practice.

---

# 21. Long-Term Data Development Objectives

### Foundational Development

- Identify reliable data sources.
- Practice reading dataset documentation.
- Understand field definitions.
- Evaluate basic data quality.
- Use manageable datasets in Excel.

### Intermediate Development

- Work with larger datasets.
- Practice SQL data retrieval.
- Use Python for data preparation.
- Develop Power BI reports.
- Document data cleaning and validation.

### Advanced Development

- Evaluate multiple related datasets.
- Develop repeatable analytical workflows.
- Strengthen data modeling.
- Improve data governance awareness.
- Produce more complex financial and operational analyses.

Progress will be documented through actual completed work rather than assumed technical proficiency.

---

## Current Status

**Dataset Sources — Reference Framework Established**

This document provides a general directory of potential data sources and a structured framework for responsible dataset selection.

It does not establish that specific datasets have been downloaded, analyzed, or incorporated into completed projects.

Each future case study will document its exact dataset, source, applicable permissions, quality considerations, and analytical limitations.

---

## Related Documents

- [Project Documentation Standards](Project-Documentation-Standards.md)
- [Analytical Methodology](Analytical-Methodology.md)
- [Business Case Studies](../Business-Case-Studies/README.md)
- [Documentation Home](README.md)

---

*This resource is intended for educational and portfolio development. Source availability, licenses, access requirements, and permitted uses may change. Each dataset must be evaluated independently before use or redistribution.*
