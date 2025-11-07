# Partner Earnings Calculator (Single)

A minimalist earnings calculator with a single card and a subtle Partner Share control. Optimized for GitHub Pages.

## Features
- Single calculator (clients, avg capital, leverage 0–100, trades 1–100)
- Partner Share dropdown (20%, 25%, 30%, 35%, 40%) in a discrete control
- Indian Rupee formatting and Current Earnings input
- 1.5s animated dots before showing result
- Responsive, dark UI

## Calculation
1. Total Capital = Clients × Average Capital per Client
2. Effective Capital = Total Capital × Leverage
3. Monthly Volume = Effective Capital × Trades per Client per Month
4. Total Fees = Monthly Volume × 0.05%
5. Monthly Earnings = Total Fees × Partner Share (dropdown selection)

## Local preview
Open `index.html` in your browser.

## Deploy to GitHub Pages
1. Push these files to a public GitHub repository.
2. Repository Settings → Pages → Source: "Deploy from a branch"; Branch: `main`; Folder: `/(root)`.
3. Visit `https://<username>.github.io/<repo>/`.

## Notes
- The Partner Share control is intentionally subtle (gear icon top-right) to keep the UI focused. Hovering reveals it more clearly.