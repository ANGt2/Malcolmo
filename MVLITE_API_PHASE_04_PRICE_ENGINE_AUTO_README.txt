MVLite API Phase 04 - Automatic Price Engine

Added:
- automatic background API sync
- configurable sync interval
- configurable maximum price age
- stale price policies:
  last     = use last cached price
  fallback = use product fallback price
  block    = stop purchase when price is stale
- recalculate all online products after sync
- price history
- sync logs
- manual sync
- manual bulk recalculation
- /priceengine admin command

Recommended initial settings:
- Auto Sync: ON
- Interval: 300 seconds
- Max Age: 900 seconds
- Policy: last
- Recalculate after sync: ON
- History: ON

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add automatic price engine phase 4"
  git push
