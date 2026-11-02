# Data Dictionary

**Source:** Synthetic training data for fictional Summit Office Supply.  
**Grain:** One invoice per row.  
**Coverage:** 60 invoices, 12 customers, amounts and notes as of October 31, 2026.  
**Currency:** USD.  
**Excel Table:** `tblInvoices` on Invoice Data.

| Field | Type | Source / calculation | Meaning |
|---|---|---|---|
| Invoice ID | Text | Source | Unique invoice identifier, such as INV-1001 |
| Customer ID | Text | Source | Stable customer identifier; repeated across a customer's invoices |
| Customer Name | Text | Source | Fictional customer name |
| Invoice Date | Excel date | Source | Date the invoice was issued |
| Due Date | Excel date | Source | Contractual due date; invoice is current on this date |
| Invoice Amount | Currency | Source | Original invoice value in USD |
| Payments Received | Currency | Source | Cumulative payment amount applied to this invoice through the cutoff |
| Collection Context | Text | Source | Recorded dispute, payment promise, reminder, or absence of follow-up |
| Outstanding Balance | Currency | Calculated | Invoice Amount minus Payments Received |
| Days Overdue | Whole number | Calculated | Days after Due Date as of the cutoff, floored at zero; paid invoices return zero |
| Aging Bucket | Text category | Calculated | Paid, Current, 1–30, 31–60, 61–90, or 91+ |

## Control

`Start Here!B8` contains the reporting date. It is an actual Excel date value, not a text label. Changing it changes aging, but does not create new payment history or update the dated source notes.

## Data rules

- Invoice IDs must be unique and nonblank.
- Invoice Date must be on or before Due Date.
- Amounts and dates must use numeric Excel values, not currency/date text.
- In this exercise, payments are nonnegative and do not exceed invoice amounts.
- Multiple invoices for a customer are legitimate records, not duplicates.
- Customer Collections uses Customer Name because names are unique in this dataset. Use Customer ID as the grouping key in real data with duplicate or changing names.
- A dispute does not change Outstanding Balance unless an approved credit, write-off, or payment is recorded.
- A payment promise is not a payment.
- No follow-up recorded means no follow-up is documented in this dataset; it is not proof that no contact ever occurred.

## Exclusions

No real customer data, employer data, credit memos, write-offs, tax details, unapplied cash, foreign currencies, credit limits, historical sales ledger, or actual collections outcomes are included. DSO and recovery rates cannot be established from this dataset alone.

## Derived worksheet

Lakeside Review contains an extracted copy of Lakeside's 91+ day invoice details. It is not the authoritative invoice table and must not be used as a second source when totaling AR. Regenerate it from the PivotTable if the source or cutoff changes.
