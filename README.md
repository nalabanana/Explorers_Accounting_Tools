# equalstofreeagent
Equals to FreeAgent Transactions

Convert CSV exports from Equals Money expense cards into a FreeAgent-ready CSV directly in your browser. Everything runs client-side, so it works on GitHub Pages (or any static host) without a server or backend runtime.

## Using the converter
1. Open `index.html` locally (double-click or use any static file host) or visit your published GitHub Pages URL.
2. Upload the CSV exported from Equals Money (Expense Cards > Export CSV).
3. Use the checkboxes to decide which transaction types to omit (internal transfers, card checks, or declined rows) and whether to remove the header row from the export.
4. The page reformats dates (from either `DD/MM/YYYY` or `YYYY-MM-DD HH:MM:SS`) to `DD/MM/YYYY`, combines merchant/location columns into the description, and prepares the CSV for FreeAgent.
5. Download the resulting `freeagent-transactions.csv` file and import it into FreeAgent.

## Host on GitHub Pages
1. Commit `index.html` to your repository.
2. In **Settings → Pages**, choose the `main` branch and the `/ (root)` folder, then save.
3. Wait for the deployment to finish; your site will be available at the URL shown in the Pages settings.

## Local development options
- Open `index.html` directly in your browser.
- Or serve it with any static server, e.g. `python -m http.server 8000` and browse to `http://localhost:8000`.
