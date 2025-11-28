# Equals Money to Freeagent
Equals to FreeAgent Transactions
Convert CSV exports from Equals Money expense cards into a FreeAgent-ready CSV directly in your browser. Everything runs client-side, so it works on GitHub Pages (or any static host) without a server or backend runtime.

## Using the converter
1. Open `index.html` locally or follow this link: https://nalabanana.github.io/Explorers_Accounting_Tools/
2. Upload the CSV exported from Equals Money (Expense Cards > Export CSV).
3. Use the checkboxes to decide which transaction types to omit (internal transfers, card checks, or declined rows) and whether to remove the header row from the export.
4. The page reformats dates from `YYYY-MM-DD HH:MM:SS`to `DD/MM/YYYY`, combines merchant/location columns into the description, and prepares the CSV for FreeAgent.
5. Download the resulting `freeagent-transactions.csv` file and import it into FreeAgent.
