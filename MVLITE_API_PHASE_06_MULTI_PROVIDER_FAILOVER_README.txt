MVLite API Phase 06 - Multi Provider / Failover

Added:
- multiple API providers at the same time
- save current API config as provider
- primary and backup roles
- provider priorities
- health checks
- latency measurement
- test all providers
- automatic failover
- sync from best healthy provider
- enable/disable each provider
- delete/load provider
- provider event logs
- /providers admin command

Recommended setup:
1) Install/configure one API profile.
2) Save current API as Provider.
3) Configure another API and save it too.
4) Set one provider as Primary.
5) Enable Multi Provider and Failover.
6) Run Test All.

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add multi provider failover phase 6"
  git push
