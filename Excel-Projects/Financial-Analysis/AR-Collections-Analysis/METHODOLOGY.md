# Methodology

## 1. Define the decision and reporting cutoff

The scenario is a fictional office supply business. Management needs a view of unpaid receivables and a defensible starting point for collections follow-up. All calculations use **October 31, 2026**, stored in `Start Here!B8`, rather than a changing TODAY() date.

The data grain is one invoice per row. The dataset contains 60 invoices and 12 customers. Payments Received is cumulative cash applied to each invoice through the reporting cutoff.

## 2. Review source data

The invoice table is named `tblInvoices` and includes eight source fields and three calculated fields. Review invoice ID uniqueness, numeric amounts, valid dates, payment amounts, and customer identifiers before analysis. This dataset has unique invoice IDs and no intentional source-data cleaning defects.

Do not remove repeated customer IDs: a customer can have several valid invoices. Invoice ID is the record key.

## 3. Calculate invoice balances

```excel
=[@[Invoice Amount]]-[@[Payments Received]]
```

Outstanding Balance is the remaining unpaid invoice amount. Payments must be applied to the correct invoice. Credit memos, write-offs, unapplied cash, and overpayments require additional treatment in a real system and are outside this first exercise.

## 4. Calculate days overdue

```excel
=IF([@[Outstanding Balance]]<=0,0,MAX(0,'Start Here'!$B$8-[@[Due Date]]))
```

- Fully paid invoices return 0 days overdue for this analysis.
- Invoices not yet due return 0 rather than a negative number.
- An invoice due exactly on the reporting date is current.
- `$B$8` fixes the reporting-date reference while the formula fills down.

## 5. Classify aging

```excel
=IF([@[Outstanding Balance]]<=0,"Paid",IF([@[Days Overdue]]=0,"Current",IF([@[Days Overdue]]<=30,"1–30",IF([@[Days Overdue]]<=60,"31–60",IF([@[Days Overdue]]<=90,"61–90","91+")))))
```

| Bucket | Rule |
|---|---|
| Paid | Outstanding balance is zero or less; only zero balances occur here |
| Current | Positive balance with 0 days overdue |
| 1–30 | Positive balance with 1 through 30 days overdue |
| 31–60 | 31 through 60 days overdue |
| 61–90 | 61 through 90 days overdue |
| 91+ | More than 90 days overdue |

Paid is tested first, so a paid invoice is not incorrectly grouped as Current.

## 6. Build summaries

### AR Aging Summary

- Rows: Aging Bucket
- Values: Sum of Outstanding Balance
- Display order: Current, 1–30, 31–60, 61–90, 91+, Paid
- Currency: USD with two decimal places

### Customer Collections

- Rows: Customer Name
- Columns: Aging Bucket
- Values: Sum of Outstanding Balance
- Exclusions: Current and Paid
- Sort: Descending customer Grand Total

The stacked bar chart combines customer balance size with age. Chart grand totals are excluded because they would double-count the detail visually. Charts remain connected to native PivotTables.

## 7. Calculate dashboard metrics

| Metric | Formula |
|---|---|
| Total outstanding AR | `=SUM(tblInvoices[Outstanding Balance])` |
| Total overdue AR | `=SUMIFS(tblInvoices[Outstanding Balance],tblInvoices[Days Overdue],">0")` |
| Share of AR overdue | `=D5/A5` |
| 91+ days overdue AR | `=SUMIFS(tblInvoices[Outstanding Balance],tblInvoices[Days Overdue],">90")` |

Dashboard positions are A5, D5, G5, and J5 respectively. Percentage formatting changes display only; 0.80536096 displays as 80.5% with one decimal place. A zero total-AR denominator would require an explicit unavailable/zero-denominator policy before reusing this ratio on an empty dataset.

## 8. Investigate collection priorities

Double-clicking Lakeside's 91+ day PivotTable value reveals the four supporting invoices. The extracted worksheet is a static snapshot. Read Collection Context before proposing action. Recorded disputes and payment promises are operational context, not cash receipts or automatic reductions of AR.

## Validation and limits

- Independently reconciled balances, overdue days, and aging classifications for all 60 source rows.
- Reconciled dashboard totals to the invoice data and PivotTable summaries.
- Checked the four Lakeside 91+ invoices and the disputed amount.
- Preserved the original invoice data, invoice formulas, native Excel tables, and PivotTable cache parts during presentation changes.
- Checked the saved workbook structure and rendered the dashboard for layout review.
- The learner confirmed refresh totals in desktop Excel before the presentation revision. The final revised file has not been interactively reopened in desktop Excel; verify refresh and appearance there before publishing.

The written findings and drill-down are tied to the fixed historical cutoff. They must be reviewed when the dataset changes. This is an invoice-aging prioritization exercise, not a forecast or a claim that collection actions were executed.
