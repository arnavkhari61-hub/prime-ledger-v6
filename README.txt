PRIME LEDGER V6 — LOCAL PROTOTYPE
Open index.html in a modern browser. IndexedDB is used for browser-local storage.
It is designed to handle larger local datasets (including a 1,000-profile target), but no exact
capacity guarantee is possible because available storage varies by device/browser.

Features:
- Dashboard, profile search, monthly estimate
- Append-only transactions: additional principal, principal returned, interest received
- Automatic recalculation and transaction timestamps
- JSON backup export and backup import/restore
- Attempts to migrate records from V5 localStorage key primeLedgerV5 on first launch
- PWA manifest and service worker for installation/offline caching when hosted over HTTPS/localhost

Limitations:
- This is not a production or legally compliant financial/lending system.
- Local browser data is not encrypted, has no account/login, cloud sync, or automatic remote backup.
- Back up regularly; protect exported JSON files. Clearing browser/site data may erase records.
- Monthly interest is a simple estimate on current outstanding principal; past unpaid interest is not accrued automatically.
- Sample profiles are fictional. Do not enter real customer or financial data.
- Consult a qualified adult and legal/financial professional before any real lending activity.
