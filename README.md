# Wages-control-account
Payroll Data Transformation for Xero

This Excel-based project was created to support the monthly journal entry of payroll costs into Xero, based on reports exported from Payroll Manager. The client required visibility by department, which is not readily available in the source software, and therefore this spreadsheet consolidates and transforms the data into a department-level format for manual input.

🧾 Purpose
To automate and simplify the process of transferring payroll data from Payroll Manager to Xero by:

Extracting department-level breakdowns from multiple reports

Consolidating costs (gross wages, pensions, taxes, NIC, etc.)

Preparing a manual journal entry format compatible with Xero

📂 File Structure
wages HMRC control
This is the main control sheet.

Columns B to F: Final journal figures for manual input into Xero

Other columns contain calculations and notes used during processing

All values are automatically calculated using Excel formulas, based on data from other sheets

Dep extended, Dep Additions, Dep Pension contributions, Dep Tax and NIC
These sheets contain raw data pasted directly from Payroll Manager reports

Each sheet reflects a specific component of payroll:

Dep extended: Base payroll and departmental breakdown

Dep Additions: Additional earnings (e.g. bonuses)

Dep Pension contributions: Employer/employee pension contributions

Dep Tax and NIC: Tax and National Insurance details

⚙️ How It Works
Data is copied and pasted into the respective Dep ... sheets every month

The main wages HMRC control sheet automatically uses LOOKUP, INDEX/MATCH, SUMIFS, and other formulas to:

Find values from pasted reports

Consolidate them by account and department

Present the final journal-ready figures in a clear format

✅ Key Features
Departmental breakdown for every payroll component

No need to manually recalculate or re-summarise data — just paste and review

Easy-to-follow layout for accountants handling manual journals in Xero

📌 Notes
This is an internal-use tool, built for speed and clarity for the person managing payroll — not intended as a client-facing deliverable

Can be extended to support additional payroll items or cost centres as needed

