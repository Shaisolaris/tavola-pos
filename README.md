# Tavola POS — Restaurant Point of Sale

Full-service restaurant POS: floor plan, order building with modifiers, kitchen display, and payment.

**[Live Demo](https://shaisolaris.github.io/tavola-pos/)**

## Features

- **Table floor plan** — free / seated / check-dropped states with covers and seat times; tapping a free table seats it
- **Order builder** — four menu categories, modifier sheets (add-ons with prices, free options) attached to line items, remove lines, live subtotal/tax/total
- **Kitchen display (KDS)** — fire tickets from the order screen, per-ticket age timers that turn red, bump-to-complete flow with server notification
- **Payment** — tip presets recalculating the charge, card/cash settlement that closes the table on the floor plan, split-evenly calculation

## Structure

Single self-contained page covering the full front-of-house loop (seat → order → fire → bump → pay → table freed) with cross-screen shared state. No frameworks, no build step.

## Author

Shai

## License

MIT

## Paired product

This is the restaurant-side admin. The customer-facing half is [Tavola Orders](https://shaisolaris.github.io/tavola-orders/) — QR table ordering with live status.
