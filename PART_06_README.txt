MVLite Part 06 Stock / Auto Delivery / Reports

Added:
- product code stock table
- import product codes line-by-line
- preview available codes
- clear available codes
- product stock mode: code
- automatic delivery from imported codes
- stock count display
- low-stock report
- sales report
- top-selling products report

Run:
  cd ~/mvlite_bot
  python app.py

Admin:
  /admin

Usage:
  1) Admin -> Products -> Product -> Stock Mode -> code
  2) Admin -> Stock Codes -> Select Product -> Import Codes
  3) User buys product; bot delivers first available code automatically.
