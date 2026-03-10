# CashCanvas

Your personal finance dashboard — upload a bank statement and instantly see where your money goes.

## What It Does

Drop a CSV or PDF bank statement and CashCanvas will:

- **Categorize every transaction** — groceries, dining, transport, subscriptions, and more — automatically
- **Show visual breakdowns** — pie charts, bar charts, and trend lines so you can spot patterns at a glance
- **Detect recurring charges** — find subscriptions and fixed payments you might have forgotten about
- **Rank your top merchants** — see exactly where you spend the most
- **Help you save** — set a savings goal with a deadline, pick categories to cut back on, and get a personalized weekly budget

## How to Use

1. Go to [cashcanvas.vercel.app](https://cashcanvas.vercel.app) (or run it locally — see below)
2. Drag and drop your bank statement (CSV or PDF)
3. Explore the **Overview** tab for spending charts and trends
4. Check the **Transactions** tab to review and recategorize individual items
5. Visit **Categories** to add custom keywords so future uploads are even more accurate
6. Head to **Savings** to set a goal, choose where to cut, and generate your plan

No account needed. No sign-up. Just upload and go.

## Try It Without a Statement

Click **"Try with sample data"** on the upload screen to explore the full dashboard with six months of realistic demo transactions.

## Privacy

All parsing and analysis happens **in your browser**. Your financial data never leaves your machine — nothing is sent to a server.

## Running Locally

```bash
git clone https://github.com/Param-1210/CashCanvas.git
cd CashCanvas
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Supported File Formats

| Format | Details |
|--------|---------|
| CSV / TSV | Auto-detects date, description, and amount columns from most banks |
| PDF | Extracts transactions from text-based bank statement PDFs |

## Built With

React, Vite, Recharts, PapaParse, PDF.js
