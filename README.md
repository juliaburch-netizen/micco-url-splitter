# Flyer Link Splitter

Drop the monthly Flipp Flyer Template workbook (.xlsx) on the page to get three values-only files:

- `<file name> - Harvest Wines.xlsx`
- `<file name> - Rockhead.xlsx`
- `<file name> - Westside.xlsx`

## What it does

- Finds the Links sheet (e.g. `Links-October`) by its Page / SKU / Harvest, RockHead and WestSide ID and Link headers. `Links-Template` is skipped.
- Keeps rows that have a product, SKU, ID or custom link. Empty slots and empty pages at the bottom are removed.
- Copies the page number down onto every row.
- Writes values only (no formulas). Links stay clickable.
- Flags any "Not found" lookups on screen.

Everything runs in the browser. The workbook is never uploaded anywhere.

## Note

The tool reads the values Excel last saved. If a workbook wasn't saved by Excel, open it in Excel, save, and drop it again.
