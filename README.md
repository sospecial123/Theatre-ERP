# 🎭 Theatre ERP — Standalone Web App

This is a fully self-contained Theatre ERP system built with **SQLite in the browser (sql.js)**.  
It runs entirely client-side and can be hosted on **GitHub Pages** or any static web server.

## 🚀 Features
- Config (categories, payment methods, event kinds)
- Accounts (Chart of Accounts)
- Productions (with budgets)
- Events (rehearsals, performances, meetings)
- Volunteers (roster + availability)
- Income / Expenses (transactions)
- Reports: P&L, Balance Sheet, Budget vs Actual, Income by Production

## 📦 How to Use
1. Upload `index.html` to your GitHub repo root.
2. Enable **GitHub Pages** in your repo settings (branch: `main`, folder: `/`).
3. Visit the link GitHub provides to launch the app.

## 💾 Data
- Data is saved in your browser (IndexedDB).
- Use **Export DB** to download a `.sqlite` backup file.
- Use **Import DB** to restore from a saved backup.

## 🧪 Demo
Click **Load Sample Data** inside the app to explore with test entries.

## 📜 Notes
- Everything runs offline in the browser — no backend required.
- Currency display is in USD by default (editable in `money()` function).
