MVLite Release 1.0

Final additions:
- app version metadata
- startup self-check
- database indexes
- diagnostics panel
- release notes
- /version command
- /diag admin command
- runtime uptime display
- release admin menu

Run:
  cd ~/mvlite_bot
  python app.py

First admin:
  /claim_admin

Admin:
  /admin

Useful commands:
  /version
  /diag
  /analytics
  /security
  /tools
  /backup

Important:
  Set a real token before production:
    export BOT_TOKEN="REAL_BOT_TOKEN"
    python app.py
