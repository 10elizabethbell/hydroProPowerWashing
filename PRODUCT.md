# Product: Hydro-Pro quote widget (pitch page)

- **Platform:** web
- **Stack:** static single-file HTML/CSS/JS; the widget is a self-contained block (style + markup + script) that can be pasted into a GoDaddy Website Builder "HTML" section or iframed (`?embed`). Only external resource: Cal Sans from Google Fonts.

## Users
1. **The owner of Hydro-Pro Power Washing LLC** (Toms River, NJ), who sees this page first, unsolicited. Has a GoDaddy site (hydropronj.com) whose quote path is a generic contact form ("drop us a line").
2. **Their customers**, homeowners and storefronts around Toms River, on phones, wanting a quote for a specific job.

## Purpose
Turn "drop us a line" into a 20-second quote request that lands on the owner's phone as a text with everything needed to quote: service, name, phone, address, preferred day, notes.

## Positioning
Not a new website. A drop-in upgrade to the site they already have. Since the 2026-10-19 revamp it wears the house calm band style (paper and navy bands, gold accent, Cal Sans, pill buttons, 24px cards), coloured from their own logo (blue and gold).

## Capabilities and constraints
- No backend: submit opens the customer's messages app with an SMS to +1 732-288-5941 prefilled. "Open in Messages" and "Copy the message" fallbacks for desktops where `sms:` does nothing; the number shows as plain text there.
- `?service=<name>` pre-selects a service (inferred use: links from seasonal posts).
- No tracking, no analytics, no prices.
- Works opened from disk, on GitHub Pages, and embedded.

## Brand commitments (from their site and brief)
- Name: Hydro-Pro Power Washing LLC. Phone (732) 288-5941. Info@hydropronj.com. 704 Batchelor Street, Toms River, NJ. Hours Mon–Fri 9am–5pm.
- Services, in their wording: Roof Soft Wash, House Soft Wash, Concrete/Pavers, Retaining Walls/Fences, Heavy Equipment, Store Fronts, Shrink Wrapping, Cedar Shake/Wood Restoration, Gutter Clean Outs, Window Cleaning (Exterior + Interior), Deck Staining/Painting, Paver Restoration (Sand + Seal), Leaf Clean Up/Removal, Holiday Lighting Packages, Permanent Lighting.
- Their site states: "All power washing services are done with a biodegradable soap and hot water."
- Area: Ocean & Monmouth Counties (their promo). Texts accepted: yes ("Call or Text: 732-288-5941").
- Their own words: "FREE Estimates", "Family Owned & Operated", "Cleaner Homes. Happier Spaces."
- Logo colours: blue (their site uses #0d57db) and gold (sampled; the page uses #f0c24b).

## Evidence on hand
- Logo and hero house photo (IMG_2697.jpg) from hydropronj.com; no people, plates or house numbers.
- One real review (Frank Gallina, chamberofcommerce.com, Apr 9 2024) and promo specials dated 07/07/2026 are in the brief; neither is on the page (see HANDOFF.md).

## Principles
- Facts only; inferences marked in HANDOFF.md.
- The widget is the product; the page around it shows the owner what it does and how to add it.
