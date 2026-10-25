# School & Bus Fee Manager
1. Create a GitHub repository.
2. Extract this ZIP and upload all files and folders to the repository root, including `.github/workflows/build-windows.yml`.
3. Open Actions → Build Windows EXE → Run workflow.
4. When successful, open the run and download artifact `SchoolBusFeeManager-Windows`.
5. Extract the artifact ZIP and run `SchoolBusFeeManager.exe`. Node.js is used only on GitHub's build runner; no local install is needed.

Features: dashboard graph, student records, school fee structure (tuition/annual/other), bus route and stop-specific fee, school/bus payments, printable receipts, CSV report, JSON backup/restore, offline local storage.

Limitations: Automatic daily Google Drive upload is not configured; it needs Google OAuth and Drive API setup. Data is stored in local app browser storage; export backups regularly. This starter does not calculate a full month-by-month outstanding ledger, discounts, or installment rules. Late fine is recorded once per student, fee type and month when a payment is entered after the 10th. Test with sample data before official use.
