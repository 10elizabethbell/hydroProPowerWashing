# Hydro-Pro Power Washing — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/hydroProPowerWashing (private) · **Built:** 2026-10-08 from Muse brief (BRIEF.md, 2026-10-08)

## What's built
- **The widget** (`#hpq-block`, between `HPQ:BEGIN` / `HPQ:END`): service dropdown (all 15 of their services in their wording, grouped "This season / Washing / Restoration / Other", plus "Something else / not sure"), name, phone, address, preferred day (Flexible + next 5 weekdays), optional details. Submit validates inline, then opens an SMS to +17322885941 with everything prefilled (`sms:+17322885941?&body=…`). A "your text is ready" state follows with Open again / Copy message / email-it fallbacks for desktops. "Text us instead" button is a plain `sms:` link. Self-contained: its own `<style>` (all selectors scoped under `#hpq-block`, colors in `--hpq-*` vars) and `<script>` IIFE. No network, no tracking.
- **Neutral look** matched to their GoDaddy site: their blue `#0d57db`, white card, pill buttons with uppercase tracked labels, Open Sans if present.
- **Embed:** instructions in the comment at the top of the file. Option A (paste the block into a GoDaddy HTML section) has a "Copy widget code" button that copies the pristine block (`window.HPQ_SOURCE`). Option B: `?embed` shows only the widget, for an iframe.
- **Demo page around it (the pitch):** benefit headline to the owner ("Quotes that text you."), their logo, and the signature element: **their own hero photo under a layer of grime that you pressure-wash clean** by dragging (mouse or finger), with spray droplets; an idle wand keeps washing on its own and the grime slowly creeps back. Beside the widget, a phone mock shows the exact text the owner would receive, updating as you type.
- An "Example request" text bubble overlaps the photo's corner so the first screen shows the product (sample data, no real address).
- Footer with their details and "Demo one-pager — free sample."

## Assumptions I made
- **Copy-paste is the recommended embed.** GoDaddy Website Builder's HTML section runs custom code in its own iframe, so a self-contained block should work without hosting. Not tested inside GoDaddy.
- **Day chips are weekdays only** (Mon–Fri), because their posted hours are Mon–Fri. If they work Saturdays, change the `if (d.getDay() === 0 || d.getDay() === 6)` line.
- **Grouping "This season"** = leaf clean up, gutters, holiday lighting, permanent lighting, because the brief says fall cleanup + holiday lighting promos are running. No promo terms shown (we don't know them).
- Their existing site actually has a GoDaddy contact form (name/email/phone/address/attachments, SMS consent line). The pitch is speed + service + day + it lands on their phone as a text, not "you have no form". Worth saying it that way in outreach.
- Hero photo is their own site photo (IMG_2697.jpg from hydropronj.com). No people, plates, or house numbers visible. Logo also from their site.
- The widget's text is customer-initiated SMS, so no consent checkbox; their existing form's consent line is about Hydro-Pro texting customers.

## Placeholders and gaps
- Option B iframe URL is `https://example.com/quote.html?embed`: needs a real host if they go that route. The frame code includes a one-line listener; the `?embed` page posts its height (on resize, input, click, submit), so the frame grows for error messages and the sent panel (tested headless: 997px → 1105px).
- No real before/after pairs were in the brief; the wash effect is a generated grime layer over their clean photo, not a real before.
- Muse revised the brief mid-build (brief.md, 07:38; same file as BRIEF.md on macOS). Changes picked up: texts confirmed, Ocean & Monmouth Counties, "Free estimates" and "Family owned & operated" wording. Not used yet, see Ideas.
- Brief says "no logo found" and "colors unknown": I pulled the logo (`hydropro.png`) and blue `#0d57db` straight from hydropronj.com.
- Brief says they have no quote form; their site does have a generic GoDaddy contact form (name/email/phone/address/attachments). Frame the pitch as faster + lands as a text, not "you have no form".

## Questions for the owner
- (732) 288-5941 takes texts (per your promo). Is that the phone that should get quote requests?
- Who is Anthony (named in a review)? Owner name for the outreach.
- What's the current fall/holiday offer, if any?
- Do you book Saturdays? Should "preferred day" be days, or "morning/afternoon" too?
- Which services do you want first in the list? Any to hide (e.g. Heavy Equipment for residential visitors)?
- Want a photo upload? (Their current form allows attachments; SMS links can't carry files. Could add "text us a photo after" wording.)
- Where on the site should it go: replacing the current "Get a Free Quote" form, or beside it?

## Review round (done once)
Finish reviewer fixes applied: frame auto-height, error text linked via `aria-describedby` only once a field is invalid, `role="img"` on the wash, phone copy says "just below the form", shorter empty phone mock on phones, half-washed opening state with grey-brown grime, example bubble in the hero, and sent-state copy that no longer claims Messages is already open (it says "Tap Open in Messages"). Its other notes: no seeded concept roll was run for the direction (code-led build); and the water lives only in the hero, while your taste file asks for wave dividers carrying the motion through the page. Both are yours to decide.
On phones the "Your photo, hydropronj.com" caption is hidden so the drag hint and example bubble don't collide.

## Ideas not built (yours to pick)
- Animated water/spray dividers between sections (carry the wash motion past the hero).
- Preview bubble "arrives" like a sent text (slide + delivered tick) instead of swapping text.
- **Promo chip in the widget** using their specials ("$100 OFF House Soft Washing", "15% OFF Paver Restoration / Roof Soft Washing / Window Cleaning", "FREE Trash Can Cleaning with any service over $650"). These are from a promo dated 07/07/2026 and may have expired, so they're left out. Confirm the current fall/holiday offer with the owner first.
- **Their one real review** on the demo page: "Anthony did a great job power washing my pavers. He was extremely detailed and took his time to be sure the job was done right!…" (Frank Gallina, chamberofcommerce.com, Apr 9 2024). Left out because the widget isn't a proof surface.
- **Leaf before/after** (`leagcleanBeforeAfter.jpg` on their site) as a real before/after under the wash hero. Not inspected yet.
- Their tagline "Cleaner Homes. Happier Spaces." as the widget's sign-off line.
- Runner-up signature: a water-ripple/sheen surface on the "What lands on your phone" mock instead of the grime wash.
- Real before/after slider from their FB promo photos (Muse: grab pairs from the Toms River Connections posts).
- Multi-select services (checkbox chips) instead of a single dropdown.
- Pre-select a service via URL (`?service=Gutter%20Clean%20Outs`) so seasonal FB posts can link straight to a prefilled widget.
- Auto-height for the iframe option via `postMessage`.
- Tune: grime opacity/colors, `BRUSH`, `REGRIME_ALPHA`, `WAND_SPEED` constants at the top of the wash IIFE.

## Not verified
- Inside an actual GoDaddy HTML section (sandbox flags, iframe height, whether GoDaddy strips anything).
- Real SMS handoff on iOS and Android (body prefill with newlines; `?&body=` form chosen for both). Inside GoDaddy's sandboxed HTML section, the automatic jump to Messages on submit may be blocked; the sent panel's "Open in Messages" link (a real tap) and the copy/email fallbacks cover it, but test on real phones via the published GoDaddy page.
- Real-device touch on the wash canvas (horizontal drag washes, vertical drag scrolls via `touch-action: pan-y`); frame rate on old phones.
- Clipboard copy on `file://` (falls back to `execCommand`).
