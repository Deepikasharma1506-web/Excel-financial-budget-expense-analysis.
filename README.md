# Financial Budget & Expense Analysis Dashboard (Excel)

## Overview
An Excel portfolio project analyzing a synthetic 2025 transaction dataset with budget benchmarks, monthly spending trends, savings contributions, and payment-method analysis.

## Dataset
- 480 synthetic transactions
- 2025 date range
- INR currency
- Not real personal financial data

## Key features
- Raw and cleaned data sheets
- Monthly category budget table
- Monthly expense and savings summaries
- Expense totals by category and payment method
- KPI cards with month selector
- Charts for monthly trend, category spending, and payment method

## Data cleaning and calculations
- Missing descriptions replaced with `Not specified`.
- Leading/trailing spaces removed from text columns.
- Category budget benchmark mapped to each transaction.
- `Budget_Variance_INR` = monthly category budget benchmark minus transaction amount.
- `Budget_Status` labels savings transactions separately and flags individual transactions above their category's monthly benchmark for review. This flag does **not** mean the full monthly budget was exceeded.

## Workbook tabs
- `Dashboard`: KPI cards and charts; choose month in B4.
- `Raw_Data`: original synthetic transactions.
- `Clean_Data`: cleaned records and calculated columns.
- `Budgets`: monthly category budget assumptions.
- `Analysis`: formula-driven summaries.
- `Start_Here`: usage guide.

## Tools
Microsoft Excel, Excel Tables, SUMIFS, AVERAGEIFS, data validation, charts, conditional formatting.

## How to use
Open `workbook/Financial_Budget_Expense_Dashboard.xlsx` in Excel and allow formulas to recalculate. On Dashboard, select `All` or a month in cell B4.
