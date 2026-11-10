# Project Documentation Standards

## One project, one folder

Choose the primary tool, then create a descriptive folder when work begins. Keep the workbook or code, data documentation, methods, findings, and preview together. Link from subject indexes rather than copying the same project into several areas.

The existing AR project lives at `Excel-Projects/Financial-Analysis/AR-Collections-Analysis/`.

## Project Standard

Individual project READMEs use the [canonical project template](Project-README-Template.md): Project Title, Demo Link, optional Table of Contents, Business Understanding, Data Understanding, Screenshots of Visualizations/Results, Technologies, Setup, Approach, Status, and Credits. Additional professional sections: KPIs, Findings, Business Recommendations, Validation & Limitations, Skills & Lessons Learned. AI projects also document baseline and model evaluation. Portfolio and category READMEs remain navigation indexes, not fictional completed case studies. Keep missing demos and results labeled pending.

## Required content

| Deliverable | Minimum content |
|---|---|
| README | Business question, audience, status, tools, actual results, file links, and limitations |
| Workbook / code / report | Inspectable calculations and the work needed to reproduce the findings |
| Data documentation | Source, license/permission, reporting cutoff, grain, units, key fields, and limitations |
| Methods | Cleaning decisions, calculations, filters, assumptions, and validation performed |
| Findings | Evidence, meaning, and recommendations; distinguish proposed actions from achieved outcomes |
| Preview | Readable image or report that matches the saved deliverable |

Use separate Markdown files when the project needs them; small exercises may keep these sections in one README.

## Before sharing

- [ ] Open and run/refresh the deliverable in its intended tool.
- [ ] Reconcile main totals and review meaningful boundary cases.
- [ ] Check all relative links and previews.
- [ ] Verify data permissions and remove confidential information from files and metadata.
- [ ] State assistance, assumptions, and remaining limitations honestly.
- [ ] Update Portfolio Progress based on checks actually performed.

Changing files on the default branch does not remove old versions from Git history. Review history separately before changing repository visibility if sensitive information has ever been committed. This cleanup does not rewrite history or certify it free of sensitive data.

[README template](Project-README-Template.md) · [Documentation](README.md)
