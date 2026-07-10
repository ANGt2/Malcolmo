MVLite API Phase 07 - Provider Backup / Health

Added:
- export provider as JSON
- import provider from JSON
- API key excluded from exported JSON
- clone provider
- provider health dashboard
- automatic periodic health checks
- configurable health interval
- event history
- event retention cleanup
- /providerhealth admin command

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add provider backup and health phase 7"
  git push
