# Analytical Methodology

1. **Define the decision.** State who needs the answer, what they must decide, and the reporting period.
2. **Inspect the data.** Identify row grain, stable keys, units, source permissions, missing values, duplicates, and date coverage.
3. **Prepare only what is needed.** Preserve original source meaning, document cleaning decisions, and keep calculations inspectable.
4. **Analyze.** Select metrics that answer the question. State formulas, filters, assumptions, and denominators.
5. **Validate.** Reconcile source to output, independently spot-check results, test relevant boundaries, and distinguish missing data from zero.
6. **Communicate.** Use clear charts, labels, units, and a short explanation of the business implications.
7. **Recommend.** Tie each proposed action to evidence. Do not present a simulated finding as an actual business outcome.
8. **Document and review.** Include reproduction and refresh instructions, limitations, data provenance, and remaining checks.

## Applied example

In AR analysis, a dispute changes the follow-up action but does not automatically reduce the outstanding balance. A payment promise is not cash received. Use a fixed reporting cutoff for a historical aging snapshot.

See the [AR project methodology](../Excel-Projects/Financial-Analysis/AR-Collections-Analysis/METHODOLOGY.md) for the actual formulas and checks used.

[Documentation](README.md)
