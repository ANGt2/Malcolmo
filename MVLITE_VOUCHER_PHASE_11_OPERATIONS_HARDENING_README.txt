MVLite Voucher Phase 11 - Operations / Hardening

Added:
- automated SQLite backups
- backup retention
- backup list/detail/send/delete
- restore with checksum verification
- pre-restore safety backup
- database integrity and quick checks
- optimize/analyze/reindex/vacuum maintenance
- automatic maintenance scheduler
- centralized system error tracking
- error resolution center
- final release audit
- full system export package
- /ops admin command

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add operations and hardening phase 11"
  git push

Run locally:
  cd ~/mvlite_bot
  python app.py
