MVLite API Phase 05 - Iranian Profiles Fixed

Iranian profiles:
- Nobitex: ready
- Bitpin: manual template
- Wallex: manual template
- AbanTether: manual template
- Bit24: manual template

Other ready profiles:
- Binance
- CoinGecko

Why some Iranian profiles are manual:
No unverified or guessed endpoints were embedded. Their official API documentation or a real JSON response should be supplied before marking them ready.

Custom JSON configuration remains available.

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add Iranian API profiles phase 5"
  git push
