# Indian Ishq Collection — Demo

## Run it
1. Extract `indian_ishq_collection_demo.zip`.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. No install or build step is needed.

## Demo features
- Responsive clothing storefront and category/search filters
- Add-to-bag, quantity controls and demo checkout
- Merchant demo login code: `ishq2026`
- Merchant overview, product/stock management and order status updates
- Demo products, cart and orders saved in the current browser using localStorage

## Important limitations
This is a frontend prototype, not a production e-commerce system.
- Customer and merchant data are local to one browser/device and do not sync between devices.
- The merchant code is visible in the source and is not secure authentication.
- Checkout is simulated; no payment is collected and no real notification is sent.
- Product artwork is CSS-generated demo artwork, not real clothing photos.
Before accepting real customers/orders, connect a secure backend/database, implement server-enforced merchant permissions, use real product photos, add privacy/return/shipping policies, and integrate a payment provider if needed.

## Images
- `assets/indian-ishq-hero.jpg` is a generated/cropped visual reference used in the hero banner.
- `assets/website-ui-mockup-collage.jpg` is the full generated UI collage used as temporary image tiles in product cards.
These are prototype visuals, not verified individual product photographs. Replace them with the merchant's actual product photos before launch.

## Merchant storefront customization (demo)
In Merchant workspace > Customize site, the demo merchant can change:
- Store name and tagline
- Hero heading and description
- Primary and accent colours
- Homepage banner image from their device

These changes persist in that browser using localStorage. A chosen banner image is stored locally in that browser. They do NOT sync to customers or other devices until a real backend and image storage are connected. This is not secure merchant authentication.
