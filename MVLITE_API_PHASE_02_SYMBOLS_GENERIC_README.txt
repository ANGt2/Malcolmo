MVLite API Phase 02 - Generic Symbols Mapper

Added:
- GET/POST symbols endpoint
- Query parameters JSON
- POST body JSON
- Generic dotted JSON paths
- List path
- Symbol/name/price/id/quote paths
- API response preview
- Synchronize symbols and prices into SQLite
- Symbols list with pagination
- Search symbols
- Enable/disable each symbol
- Raw JSON viewer
- /symbols admin command

Generic API support:
Works with normal JSON APIs using GET or POST and configurable paths.
Complex signed APIs, WebSocket-only APIs, or custom encryption need adapters.

After applying:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add generic API symbols phase 2"
  git push
