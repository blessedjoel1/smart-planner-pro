SMART PLANNER PRO v2 - MANUAL GITHUB UPDATE

1. Open the live app and export a JSON backup FIRST.
2. GitHub repository > Code > root directory. Upload index.html, manifest.webmanifest, sw.js and README.txt from this ZIP, replacing matching files. Commit changes.
3. Settings > Pages: deploy main branch /(root). Wait for deployment. Hard-refresh the website (Ctrl+Shift+R).
4. If the app was previously in a smart-planner subfolder, this root deployment is a separate browser storage origin/path. Import your exported backup if records do not appear.

New in v2: calendar, due-today and overdue filters, completion insights, CSV report. Previous localStorage key spp_records_v1 retained.

WARNING: Local-only browser storage; PIN is not secure authentication. No cloud database or multi-user access. Do not store sensitive data.
