# Makaa — open-fire kitchen (concept site)

A single-file restaurant website for a fictional charcoal-grill restaurant in Nairobi. No build step, no dependencies.

## Features
- Live "open now" badge using Nairobi time
- Menu with category tabs, vegetarian/vegan filters and heat ratings
- "Your table" order builder with running KES total (saved in localStorage)
- Booking form whose time slots follow the opening hours, with validation
- Ember particle canvas, scroll reveals, reduced-motion support

## Run it
Open `index.html` in a browser.

## Deploy on GitHub Pages
Repo **Settings → Pages → Deploy from a branch → main / (root)**.

## Notes
- Concept project: bookings are not sent anywhere.
- Hero background video comes from MotionSites' free backgrounds; the page falls back to the ember canvas if it fails to load. Check MotionSites' terms before using it commercially.
- Restaurant name, address, hours and menu are placeholders.
