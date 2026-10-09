# Momo King Washington

Mobile-first static website demo for Momo King's Seattle, Tacoma, and Olympia locations.

## Run locally

From this directory:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173. No build step or package installation is required.

## Files

- `index.html`: page structure, illustrated mountains, mascot, and dialogs
- `style.css`: responsive styling and entrance animation
- `app.js`: momo builder, menu filtering, dish details, and ordering links
- `assets/`: demo imagery

## Before publishing

This is a concept demo. The food image is AI-generated, and the mascot and branding are concepts. Replace placeholders and confirm prices, hours, contact information, social profiles, sauce ingredients, allergens, menu availability, and the owner's story before launch. Seattle currently links to the shared DoorDash location listing rather than a direct store page.

Ordering opens external services; builder selections are not transferred to an external cart. Fonts currently load from Google Fonts. The mountain animation respects reduced-motion preferences.
