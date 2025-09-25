# 🎭 Theatre ERP — Full ERP Build (Config, Categories, Transactions, Maintenance, Rates & Banks)

Files:
- `index.html` — full browser-only ERP (sql.js/SQLite) with:
  - Right-side **Config** drawer
  - **Categories** manager (lists used in all forms)
  - **Rates** & **Bank Details**
  - **Maintenance → Wipe Sample Data** and **Delete ALL Transactions**
  - **Transactions** edit & delete (Income/Expenses screens)
- `theatre-erp-sample.sqlite` — demo DB that auto-loads on first visit and persists to IndexedDB.

Deploy:
1) Upload all files to your repo root.
2) Enable GitHub Pages.
3) Visit your Pages URL (append `?empty=1` if you want to start with an empty DB, then click **Reset (New DB)**).

Tips:
- Use **⚙️ Config** to manage lists (categories), rates, bank details.
- **Export DB** for backups.  Use **Maintenance → Wipe Sample Data** to clear the demo content.
