# Explorers Accounting Tools

A collection of lightweight, client-side utilities to streamline accounting tasks. Open `index.html` locally or on a static host to access all tools from the landing page.

## Available tools

### Equals to FreeAgent Converter (`Equalstofreeagent.html`)
Convert CSV exports from Equals Money expense cards into a FreeAgent-ready CSV directly in your browser.

**How to use**
1. Open `Equalstofreeagent.html` or launch it from the landing page (`index.html`).
2. Upload the CSV exported from Equals Money (Expense Cards > Export CSV).
3. Choose which transaction types to omit and whether to remove the header row.
4. Download the generated `freeagent-transactions.csv` file and import it into FreeAgent.

### Stripe Monthly Payout Summary (`stripe-monthly-payout-summary.html`)
Summarize Stripe payout exports by description, with optional grouping by trailing bracketed text (e.g., `(Subs)`).

**How to use**
1. Open `stripe-monthly-payout-summary.html` or launch it from the landing page (`index.html`).
2. Upload the exported Stripe transactions CSV.
3. Choose whether to group similar transactions between bracketed sections and review the per-description totals based on the Net column.
4. Use the Done checkboxes to track cleared categories and see the remaining balance; use selection checkboxes to view subtotals for chosen rows.
5. Download or copy the summarized results as needed.

## Local development
- Open the HTML files directly in your browser.
- Or serve with any static server, e.g. `python -m http.server 8000` and browse to `http://localhost:8000`.
