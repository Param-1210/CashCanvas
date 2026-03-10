# CashCanvas

A finance dashboard that parses bank statements (CSV/PDF) and gives you visual spending insights, customizable categories, and interactive savings planning.

## Features

- **Upload & Parse** — CSV and PDF bank statement support
- **Spending Insights** — Pie charts, bar charts, monthly trends
- **Recurring Detection** — Identifies subscriptions and fixed payments
- **Custom Categories** — Reclassify transactions with keywords or per-transaction
- **Savings Planner** — Set goals, pick where to cut, get a personalized plan

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173).

## Deploy to Vercel

```bash
npm i -g vercel
vercel
```

## Tech Stack

- React 18 + Vite
- Recharts for visualizations
- PapaParse for CSV parsing
- PDF.js for PDF text extraction
- Claude API fallback for complex PDFs

## Privacy

All data is processed locally in the browser. No data is sent to any server (except when the Claude AI PDF fallback is used for complex statements).
