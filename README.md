# Cart Total Calculator

Calculates subtotal, discount, tax, and total for a list of cart items.

## How to Run in VSCode

1. Open this folder in VSCode (`File > Open Folder...`).
2. Make sure [Node.js](https://nodejs.org) is installed. Check by opening a terminal (`` Ctrl+` ``) and running:
   ```
   node -v
   ```
3. In the VSCode terminal, run the script:
   ```
   node script.js
   ```
4. The sample cart summaries will print in the terminal.

## Functions

- `calculateSubtotal(items)` — sums `price * quantity` for all items.
- `calculateDiscount(subtotal, discountPercent)` — returns the discount amount.
- `calculateTax(amountAfterDiscount, taxPercent)` — returns the tax amount, computed after the discount is applied.
- `createCartSummary(items, discountPercent, taxPercent)` — returns `{ subtotal, discount, tax, total }`.
## Project URL
https://roadmap.sh/projects/js-cart-total-calculator
