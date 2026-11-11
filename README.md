# Bwonjo storefront starter

A responsive, static landing page for Bwonjo, a Kenyan technology retailer. It gives the brand a focused front door while keeping the live product catalogue, prices, stock, cart, and checkout on [bwonjo.co.ke](https://bwonjo.co.ke/).

## Preview locally

From this folder, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

The site uses plain HTML, CSS, and a small JavaScript file. It has no build step or third-party runtime dependencies.

## Content and links

- Category links point to the existing Bwonjo catalogue.
- Delivery and support links point to the current policies and contact page.
- Product pricing and availability are intentionally not copied into this static page, so the live catalogue remains the source of truth.

## Files

- `index.html` — page content and metadata
- `styles.css` — responsive layout, typography, and illustration
- `script.js` — accessible mobile navigation and current year
- `favicon.svg` — simple Bwonjo brand mark
