# Project Documentation Standards

## Purpose

These standards make every portfolio project clear, consistent, and verifiable. A reader, such as an employer, instructor, or collaborator, should be able to understand what I analyzed, why, how, and what the results do and do not show.

## Required Elements

Every completed project documents the sixteen elements below.

| # | Element | What to include |
|---|---|---|
| 1 | Project title | A specific, descriptive name |
| 2 | Project overview | A short summary of what the project is and what it shows |
| 3 | Business problem | The situation or question, and why it matters |
| 4 | Project objectives | Specific goals the analysis should achieve |
| 5 | Analytical questions | The questions the data will be used to answer |
| 6 | Tools and technologies | Software, languages, and versions used |
| 7 | Dataset and source | Origin, license, time period, size, and key fields |
| 8 | Data preparation | Cleaning steps, decisions, and their reasons |
| 9 | Methodology | The analytical approach and why it fits the questions |
| 10 | Analysis | The calculations or queries performed, explained clearly |
| 11 | Findings | What the analysis showed, supported by evidence |
| 12 | Visualizations | Charts or dashboards, with a brief explanation of each |
| 13 | Business recommendations | Actions supported by the findings |
| 14 | Limitations and assumptions | Data weaknesses, assumptions, and scope limits |
| 15 | Skills demonstrated | Skills shown by the work, limited to what it actually shows |
| 16 | Lessons learned | What I would do differently and what I learned |

## Reusable Project Template

Copy the following into a new `README.md` inside the project folder.

```markdown
# [Project Title]

## Project Overview
[Short summary of the project.]

## Business Problem
[Describe the problem or decision.]

## Project Objectives
- [Objective 1]
- [Objective 2]

## Analytical Questions
1. [Question 1]
2. [Question 2]

## Tools and Technologies
- [Tool and version]

## Dataset and Source
- **Source:** [Name and link]
- **License or terms of use:** [Details]
- **Type:** [Public / Synthetic / Anonymized]
- **Time period and size:** [Details]
- **Key fields:** [List]

## Data Preparation
- [Issue found, action taken, and reason]

## Methodology
[Explain the approach and why it was chosen.]

## Analysis
[Describe the calculations, queries, or code and what each step does.]

## Findings
- [Finding 1, with evidence]
- [Finding 2, with evidence]

## Visualizations
[Include images or links, with a short explanation of each.]

## Business Recommendations
| Recommendation | Supporting finding | Considerations |
|---|---|---|
|  |  |  |

## Limitations and Assumptions
- [Limitation]
- [Assumption]

## Skills Demonstrated
- [Skill, supported by the work above]

## Lessons Learned
- [Lesson]

## Files in This Project
- [List of files and their purpose]
```

## Folder and File Conventions

- Create one subfolder per project inside the relevant section, such as `Excel-Projects/Sales-Dashboard/Retail-Sales-Dashboard/`.
- Use hyphens instead of spaces in names, and descriptive names such as `Retail-Sales-Dashboard`.
- Include a `README.md` in every project folder.
- Store images in an `images` subfolder and reference them with relative links.
- Include a data dictionary when the dataset has fields that need explanation.
- Do not store large raw datasets in the repository. Link to the source instead, unless the license allows redistribution and the file is small.

## Writing Standards

- Write in clear, professional language.
- Explain results in business terms, not only technical terms.
- Separate findings (what the data shows) from recommendations (what I suggest).
- Describe results as supported by the data, not proven by it.
- Describe skills only as far as the project demonstrates them. Do not claim proficiency without evidence.
- Do not include fabricated results, accomplishments, or credentials.

## Data Security and Ethical Standards

All projects must use:

- **Public datasets**, with attention to license terms
- **Synthetic datasets**, clearly labeled as synthetic
- **Appropriately anonymized data**, with documentation of how it was anonymized

Never include:

- Confidential employer information
- Private client information
- Customer personal information
- Passwords
- API keys
- Private financial records
- Proprietary business data

Additional requirements:

- Respect applicable privacy laws, licenses, and terms of use.
- Do not attempt to re-identify individuals in anonymized data.
- Remove hidden metadata, comments, and embedded data from Excel and Power BI files before publishing. Check hidden sheets, queries, and connection strings for credentials.
- Never commit credentials. Check code and notebooks for keys and passwords before uploading.
- If real business data is ever used, confirm that I have permission to publish it. Otherwise use synthetic data that mimics its structure.
- Cite data sources and give credit as the license requires.

## Educational Disclaimer

Financial, accounting, and business analyses are educational and are not professional accounting, tax, legal, investment, or financial advice.

## Pre-Publication Checklist

- [ ] All sixteen elements are documented
- [ ] The dataset source and license are recorded
- [ ] The data is public, synthetic, or anonymized
- [ ] No credentials, personal data, or proprietary information are present
- [ ] Calculations were checked
- [ ] Limitations and assumptions are stated
- [ ] Skills listed are supported by the work
- [ ] Relative links work
- [ ] [Portfolio Progress](Portfolio-Progress.md) is updated

## Related Documents

- [Analytical Methodology](Analytical-Methodology.md)
- [Dataset Sources](Dataset-Sources.md)
- [Documentation home](README.md)
