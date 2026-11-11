# Rental Property Analyzer — Red Beard Investments

A single-page, browser-only rental property calculator: cash flow, NOI, cap rate, cash-on-cash, DSCR (two methods), loan-type comparison (conventional, DSCR, interest-only, ARM, FHA house hack, seller financing, cash, BRRRR), 5-year tax and debt-paydown estimates, amortization, and a 30-year projection with IRR.

**Estimates only, not a rate quote, loan approval, tax or financial advice. Confirm terms with a lender and tax advisor.** Loan defaults are example assumptions, not offered rates.

## Privacy
Runs entirely in your browser. No network requests, cookies, analytics, or form submissions. Inputs are saved only in this browser's localStorage (key `rbi-rental-analyzer-v1`); use **Clear my data** to remove them.

## Use
Open the page, enter the property, rents, expenses and loan terms, and pick a loan program. Use **Download PDF** to print or save a report.

## Known limits
- Does not model capital-gains tax, depreciation recapture, prepayment-penalty dollars, or the FHA 3–4 unit self-sufficiency test.
- The loan comparison uses each program's default terms, not overrides entered for the selected loan.
- In the comparison table at desktop width (about 1280px), long program names are truncated in the closed dropdown; the open menu shows the full name.
