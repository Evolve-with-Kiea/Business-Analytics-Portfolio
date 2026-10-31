# Dataset Sources

## Purpose

This document lists reputable places to find public data and explains how to evaluate a dataset before using it. I list site addresses only. I do not list specific dataset links here, because availability and terms change. Each project records the exact dataset, link, and license it uses.

## Public Data Sources

| Source | Description | Typical use |
|---|---|---|
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Community-shared datasets with varying licenses | Practice data for retail, marketing, and finance topics |
| [Data.gov](https://data.gov/) | U.S. government open data catalog | Public sector and economic data |
| [U.S. Census Bureau](https://www.census.gov/data.html) | Demographic, economic, and business statistics | Market and population context |
| [FRED (Federal Reserve Economic Data)](https://fred.stlouisfed.org/) | Economic time series from the Federal Reserve Bank of St. Louis | Inflation, employment, interest rates, and other trends |
| [World Bank Open Data](https://data.worldbank.org/) | Global development and economic indicators | International comparisons |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | A search engine for datasets hosted elsewhere | Finding datasets on a topic |
| [UCI Machine Learning Repository](https://archive.ics.uci.edu/) | Datasets widely used for learning and research | Analysis practice |
| [SEC EDGAR](https://www.sec.gov/edgar) | Public company filings | Financial statement analysis |
| [U.S. Bureau of Labor Statistics](https://www.bls.gov/data/) | Labor, price, and productivity data | Economic and operations context |

## Synthetic Data

Synthetic data is created for practice and does not describe real people or businesses. It is useful when real data is private or unavailable.

- Label synthetic data clearly in the project README.
- Describe how it was generated, including any assumptions.
- Design it to be realistic enough to practice with, but do not draw real-world conclusions from it.
- Never present synthetic results as real performance.

## Evaluating a Dataset

Before using a dataset, I check each item below and record the answers in the project.

### License and Terms of Use

- [ ] What license or terms apply?
- [ ] Does the license permit my use, and does it permit redistribution if I include a copy?
- [ ] What attribution is required?

### Source Reliability

- [ ] Who created or published the data?
- [ ] Is the collection method described?
- [ ] When was it last updated?
- [ ] Is it consistent with other sources?

### Privacy

- [ ] Does the data contain personal or sensitive information?
- [ ] Is it properly anonymized?
- [ ] Could combining it with other data identify individuals?

### Suitability

- [ ] Does the data match the business question?
- [ ] Is the time period relevant?
- [ ] Is the sample large and representative enough?
- [ ] Are the fields defined clearly?
- [ ] Is the quality good enough, with limited missing or inconsistent values?

## Recording a Dataset

Use this format in each project.

```markdown
- **Dataset name:**
- **Publisher or creator:**
- **Link:**
- **Date accessed:**
- **License or terms:**
- **Type:** Public / Synthetic / Anonymized
- **Description and key fields:**
- **Known limitations:**
```

## Related Documents

- [Project Documentation Standards](Project-Documentation-Standards.md)
- [Analytical Methodology](Analytical-Methodology.md)
- [Documentation home](README.md)
