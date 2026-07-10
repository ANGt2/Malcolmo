MVLite API Phase 03 - Product Binding / Online Price Rules

Added:
- fixed and online product price modes
- bind each product to an active API symbol
- multiplier
- profit percentage
- fixed fee
- minimum price
- maximum price
- fallback price
- live price calculation in product display
- live price calculation at checkout
- coupon discount based on effective current price
- manual recalculate/store button
- paginated symbol picker

Formula:
  base = API symbol price * multiplier
  final = base + profit percent + fixed fee
  then min/max limits are applied

Deploy:
  cd ~/mvlite_bot
  git add .
  git commit -m "Add API product binding phase 3"
  git push
