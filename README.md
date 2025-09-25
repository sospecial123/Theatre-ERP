# 🎭 Theatre ERP — Fixed Build

This build adds:
- Missing `escapeSql()` helper (prevents SQL errors)
- Global error toast, so any JS error appears on the page
- Safer init/bootstrapping (works even if `theatre-erp-sample.sqlite` is missing)
- Confirmed nav routing and module rendering

Deploy the three files to your repo root and open the GitHub Pages URL.
