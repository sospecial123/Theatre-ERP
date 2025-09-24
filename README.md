# 🎭 Theatre ERP — Standalone Web App (Auto-load Sample)

This package auto-loads `theatre-erp-sample.sqlite` on first visit and saves it to your browser (IndexedDB).

## Files
- `index.html` — web app (GitHub Pages ready), auto-loads sample DB on first visit.
- `theatre-erp-sample.sqlite` — sample database with productions, events, volunteers, accounts, budgets, and transactions.
- `README.md` — setup instructions.

## Deploy
1. Upload all three files to your GitHub repo root.
2. Enable GitHub Pages (Branch: main → Folder: /).
3. Open `https://USERNAME.github.io/REPO/`.

## Use
- First visit: app fetches `theatre-erp-sample.sqlite` and stores it in your browser.
- Later visits: it uses your saved data from the browser.
- Use **Export DB** to download a portable `.sqlite` backup.
- Use **Import DB** to load any `.sqlite` file.
- **Reset (New DB)** clears the browser copy and re-fetches the sample on next load.
