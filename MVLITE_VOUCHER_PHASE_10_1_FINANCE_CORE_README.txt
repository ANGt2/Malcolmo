MVLite Voucher Phase 10.1 - Finance Core

Added:
- finance_transactions ledger
- profit_snapshots
- finance_logs
- finance fields on orders
- automatic accounting when an order is completed
- automatic refund ledger entry
- order sales/cost/fee/profit snapshots
- finance dashboard: today/yesterday/week/month/year/all
- finance transaction pagination
- finance rebuild for old completed orders
- CSV and JSON finance exports
- /finance admin command

Important:
- Profit and purchase-cost data are admin-only.
- Existing completed orders can be imported with:
  Admin > Finance Center > Rebuild Finance
- Refund entries are idempotent and recorded only once.

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add finance core phase 10.1"
  git push

Run locally:
  cd ~/mvlite_bot
  python app.py
