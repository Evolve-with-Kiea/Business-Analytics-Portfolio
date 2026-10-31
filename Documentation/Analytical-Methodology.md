# Analytical Methodology

## Purpose

This document describes the repeatable process I use for every project. It keeps analysis focused, transparent, and easy to review.

## Why Analysis Begins With the Business Problem

Analysis should start with the business problem, not with a software tool. Tools are means, not goals. If I choose a tool first, I risk producing impressive-looking output that does not answer anything useful. Starting with the problem helps me:

- Decide what data is actually needed
- Choose methods that fit the question
- Avoid analyzing what is easy to measure instead of what matters
- Communicate findings in terms the audience cares about
- Recognize when a simpler tool, or no new analysis, is enough

The right tool depends on the question. Excel may suit a small, one-time analysis, SQL may suit data stored in a database, Python may suit repeatable data work, and Power BI may suit ongoing reporting.

## The Twelve Steps

### 1. Understand the business question

Clarify the problem, the decision, and who will use the results.

**Questions to ask**

- What decision will this analysis inform?
- Who is the audience?
- What does success look like?

**Output:** A clearly stated business question

### 2. Define the analytical objective

Translate the business question into specific, answerable analytical questions.

**Questions to ask**

- What measures or comparisons will answer the question?
- What period and scope apply?

**Output:** A list of analytical questions and objectives

### 3. Identify relevant data

Determine which data is needed and where it can be found.

**Questions to ask**

- What fields and time span are required?
- Is suitable public or synthetic data available?
- Do the license and privacy terms allow my use?

**Output:** A dataset selection with source and license recorded

### 4. Evaluate data quality

Examine completeness, accuracy, consistency, and relevance before analysis.

**Questions to ask**

- Are there missing values, duplicates, or outliers?
- Do totals reconcile with any known figures?
- Are definitions consistent?

**Output:** A data quality assessment

### 5. Clean and prepare the data

Correct or handle problems, and reshape data for analysis.

**Questions to ask**

- What was changed and why?
- How many records were affected?

**Output:** A cleaned dataset and a record of every change

### 6. Select appropriate analytical methods

Choose methods that fit the question and the data.

**Questions to ask**

- Is a summary, comparison, trend, or relationship needed?
- What assumptions does the method require?

**Output:** A justified method choice

### 7. Perform the analysis

Carry out calculations, queries, and visualizations carefully.

**Questions to ask**

- Are results checked against a simple manual calculation?
- Can another person reproduce the steps?

**Output:** Results with documented steps

### 8. Interpret the results

Explain what the results mean in business terms.

**Questions to ask**

- What patterns appear, and what could explain them?
- Do any results contradict expectations?

**Output:** Findings supported by evidence

### 9. Develop recommendations

Connect findings to actions.

**Questions to ask**

- What should be done, and why?
- What risks or alternatives exist?

**Output:** Recommendations linked to findings

### 10. Communicate findings

Present results for the intended audience.

**Questions to ask**

- Is the message clear without technical background?
- Do visuals support the main points?

**Output:** A report, dashboard, or summary

### 11. Identify limitations

State what the analysis cannot show.

**Questions to ask**

- What data weaknesses exist?
- Which assumptions matter most?
- Where could the conclusions be wrong?

**Output:** A limitations and assumptions section

### 12. Evaluate the outcome

Review whether the analysis answered the question and what to improve.

**Questions to ask**

- Did the work meet the objectives?
- What would I do differently?

**Output:** Lessons learned and possible next steps

## Process Summary

| Phase | Steps |
|---|---|
| Define | 1 to 3 |
| Prepare | 4 and 5 |
| Analyze | 6 to 8 |
| Recommend and communicate | 9 and 10 |
| Review | 11 and 12 |

The steps are not strictly linear. Findings in step 7 may reveal data problems that send me back to step 5, or may change the questions in step 2. When that happens, I document what changed and why.

## Matching Tools to Questions

| Situation | Tool that may fit | Reason |
|---|---|---|
| Small dataset, one-time summary | Excel | Fast and visible; easy to review |
| Data in related tables | SQL | Retrieves and combines data efficiently |
| Repeatable cleaning or larger data work | Python | Steps can be scripted and repeated |
| Ongoing monitoring for an audience | Power BI | Interactive reports that refresh |

This table is a starting guide, not a rule.

## Good Analytical Habits

- Check results with a simple manual calculation.
- Keep a record of every data change.
- Report results that do not match expectations.
- Distinguish correlation from causation.
- Describe uncertainty honestly.
- Share limitations alongside conclusions.

## Related Documents

- [Project Documentation Standards](Project-Documentation-Standards.md)
- [Dataset Sources](Dataset-Sources.md)
- [Business Case Studies](../Business-Case-Studies/README.md)
- [Documentation home](README.md)
