# 🎭 Theatre ERP — Standalone Web App

This package includes:
- `index.html` → the full ERP web app (ready for GitHub Pages)
- `README.md` → setup instructions
- `theatre-erp-sample.sqlite` → sample database (import inside the app)

## How to Use
1. Upload all three files (`index.html`, `README.md`, `theatre-erp-sample.sqlite`) to your repo root.
2. Enable GitHub Pages in your repo settings.
3. Visit your Pages link (https://USERNAME.github.io/REPO/).
4. Inside the app, click **Import DB** and select `theatre-erp-sample.sqlite` to explore demo data.

## Notes
- The app runs entirely in the browser using sql.js (SQLite WASM).
- Data is saved in IndexedDB by default; use Export/Import for backups.
