# Hardware Shop

A browser-based hardware shop billing and stock tool.

## Run locally

Open `index.html` in a modern browser. The app uses this browser's local storage for products, stock, cashier drafts, invoices, purchases, and settings. Data is not synced between devices.

## Features

- Five independent cashier billing tabs and printable invoices
- Product, stock, and locally generated Code 128 barcode labels
- Supplier purchase records that add received quantities to shared stock
- Customer invoice history and sales reports
- JSON backup and restore with a 30-day backup reminder

## Privacy and backups

Shop records stay in the browser where they were entered. Download a JSON backup from Settings regularly. Clearing browser site data removes local records unless a backup has been saved.

Code 128 symbol patterns and licensing details are in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
