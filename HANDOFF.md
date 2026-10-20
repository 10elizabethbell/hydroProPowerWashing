# Hydro-Pro Power Washing — handoff at ~60% (calm revamp)

**Live:** https://10elizabethbell.github.io/hydroProPowerWashing/ · **Widget only:** https://10elizabethbell.github.io/hydroProPowerWashing/?embed · **Repo:** https://github.com/10elizabethbell/hydroProPowerWashing (public; `brief.md` was scrubbed from history before it went public on 2026-10-17, and raw `src-assets/` was never committed) · **Built:** 2026-10-08 from the Muse brief of 2026-10-08 · **Revamped:** 2026-10-19 to the calm band style

Scope is still the brief's: an embeddable quote **widget** plus the page that shows it to the owner. It's not a full site.

## What changed in the revamp (2026-10-19)
- **Look:** the calm band style (`calm-photo-style.md`) replaces the old blue/white look that blended into GoDaddy.
  - Bands: paper #f4f6fb, navy #0a3d99, and deep navy #081f4d with the faint diagonal lines.
  - Colours come from their logo: the navies from its blue, and the logo's gold #f0c24b as the one accent. Gold is a fill only, with navy text on it. Where gold has to be text on a light ground it is the darker #85601a.
  - Their site blue #0d57db is the hover and focus outline on the form.
  - Headings are Cal Sans and body text is the system font at 16/1.7. Buttons are pills and cards have 24px corners.
- **Hero:** the drag-to-wash grime hero is gone (opt-in under the new rules; it's in git history at `d44aebd`).
  - In its place, their own house photo (IMG_2697 from hydropronj.com) sits under a navy overlay. White text measures 9.5:1 or better by pixel sampling at 360, 390 and 1440.
  - Hero contents: the eyebrow "Free estimates, by text", the H1 **"Toms River quotes, straight to your phone."** (it bounces in letter by letter, then turns back into plain text), one promise line, and two buttons: "Try the quote form" (gold) and "See how to add it" (outlined).
- **Widget restyled to match:**
  - a white 24px card
  - tinted, borderless fields
  - Cal Sans labels
  - pill day chips (the selected one is navy)
  - a gold "Text my quote request" button
  - blue outlines on hover and focus
  - It still carries its own `<style>`/`<script>` and `--hpq-*` variables. Its one outside request is Cal Sans (`@import`), which falls back to system fonts if blocked.
- **Removed from the widget:** the "Text us instead" button. It opened the same text as the main button ("no two controls doing the same thing"; Ellie: "too many options").
- **The text is ready panel:** the panel still has "Open in Messages" and "Copy the message".
  - Inside a frame (GoDaddy's HTML section or the `?embed` iframe), it no longer jumps to Messages on its own. It says "Tap Open in Messages to send it." The link uses `target="_top"`, because some browsers block `sms:` jumps from frames.
  - Only the status line is announced to screen readers now, not the whole panel.
- **New:** `?service=Gutter%20Clean%20Outs` pre-selects a service. That lets seasonal Facebook posts link straight to a filled-in form.
- **Phone preview:** it now shows the real message format ("Service: —", "Name: —"…) before anyone types, then fills in word for word. No made-up customer.
- **New sections:**
  - "How it works": three steps on deep navy.
  - "Put it on your site": two embed cards. The iframe height listener now only accepts messages from github.io.
  - A close band with their own tagline "Cleaner homes. Happier spaces.", "family owned & operated", and the biodegradable soap and hot water line.
- **Floating text circle (on, `CONFIG.FLOAT`):** it opens a text to Hydro-Pro. It shows only after the hero, hides while the form is on screen, and is gone without JS.
- **One quiet fade-up** below the first screen. With reduced motion or no JS, everything shows at once.
- **Weight:** the photos and logo moved out of the HTML into `hero.webp` (1000px, 114KB), `hero-1600.webp` (200KB, via `srcset` for big and Retina screens) and `logo.webp`.
  - The page is now 45KB instead of 220KB.
  - The `?embed` frame no longer downloads photos it never shows.
- **Verified** (Playwright, Chromium and WebKit):
  - At 360, 390, 414, 430, 844 (landscape) and 1440:
    - no sideways scroll
    - every tap target is 44px or larger
    - inputs are 16px
    - the first phone screen shows the logo, number, H1, promise and both buttons
  - Motion and fallbacks:
    - the bounce letters are offset at 120ms and settled by 2.5s, at the same height as the plain H1
    - with reduced motion or no JS, the H1 is plain and nothing is hidden
  - Contact and form:
    - the float circle state is right at hero, steps, form and embed
    - the SMS body decodes correctly
    - errors show and focus the first bad field
  - `?embed` renders only the widget.

## What's built
- Header: the Hydro-Pro logo on the left, (732) 288-5941 as tap-to-call on the right. That's the only number on the first screen.
- Hero: see above. There's no Call button and no services list.
- Try it: the widget beside the live phone preview (stacked on phones).
  - Fields: service (all 15 of their services in their wording, grouped, plus "Something else / not sure"), name, phone, job address, preferred day (Flexible plus the next 5 weekdays), and optional details.
  - Submit opens `sms:+17322885941` with everything pre-filled.
- How it works (deep navy), Put it on your site (copy-paste or iframe, each with a copy button), the close band, and a footer with the address, hours, phone and the only email on the page.
- Favicon and home-screen icon from their logo (unchanged); `og-image.jpg` share preview (unchanged).

## Assumptions I made
- **Gold accent:** sampled from the logo's swoosh and lettering, then brightened slightly for fills (#f0c24b).
- **Navies:** their logo/site blue deepened to #0a3d99 and #081f4d, so white text clears AA comfortably.
- **"Free estimates, by text"** (hero eyebrow): "FREE Estimates" is their own promo wording; "by text" describes the widget.
- **"Toms River"** in the H1: their address is in Toms River. Their wider area is Ocean & Monmouth Counties, which appears lower on the page.
- **Audience:** not flagged as 40+ in the brief, so the calm motion is kept. Many Ocean County homeowners are older. If Ellie or the owner says the customers skew 40+, drop the bounce-in and fade-up (`older-audience.md`). The widget itself has no motion.
- **The floating circle** texts Hydro-Pro. On a page addressed to the owner, that only makes sense as a preview of what their customers would get. It isn't part of the pasted widget.
- **Day chips are weekdays only,** matching their posted Mon–Fri hours.
- **Copy-paste is the recommended embed.** I believe GoDaddy's HTML section runs custom code in its own frame; not tested.

## Placeholders and gaps
- No Facebook business page exists (only a personal profile posted their promo), so there is no Facebook link.
- No real before/after pairs. The leaf before/after composite on their site was never inspected or used.
- The brief said "no logo" and "colours unknown"; the logo and blue come from hydropronj.com itself.

## Questions for the owner
- Is (732) 288-5941 the phone that should get quote requests by text?
- Who is Anthony (named in their one review)? Owner name for outreach.
- What's the current fall/holiday offer, if any? The specials in the brief are dated 07/07/2026.
- Do you book Saturdays? Should the day choice also offer morning/afternoon?
- Which services should come first? Any to hide (e.g. Heavy Equipment for homeowners)?
- Do you want photo upload? `sms:` links can't carry files; "text us a photo after" wording could cover it.
- Where should it go: replacing the current "Get a Free Quote" form, or beside it?

## Ideas not built (yours to pick)
- **Impeccable conflicts, kept by house rule:** Impeccable's craft floor and finish reviewer flag the eyebrow pills (hero, widget, embed section), the H1 bounce easing (the overshoot), and the repeating diagonal stripe texture. All three are Ellie's calm-style choices, so they stay. The detector's only non-design-system finding was the stripe texture.
- **Runner-up signature (opt-in):** bring back the drag-to-wash hero. Their house photo sits under grime you pressure-wash clean with a finger, which slowly creeps back. It's in git at `d44aebd`. Under the calm rules it would sit in the hero's photo slot with the H1 over a clear zone.
- Other worlds from the trade: water beading and sheeting off the "How it works" band; a soft-wash foam edge on the close band; holiday lights that switch on along the header in season.
- A "Most requested this season" quick-pick row above the service select (Leaf Clean Up, Gutters, Holiday Lighting) as chips.
- A promo strip in the widget, once the owner confirms a current offer.
- Their one real review (Frank Gallina, chamberofcommerce.com, Apr 9 2024) under the widget.
- The floating text circle shipped as part of the widget code, for their whole site.
- Atkinson Hyperlegible for body text if the audience turns out to be 40+.

## Not verified
- Inside a real GoDaddy HTML section (sandbox flags, iframe height, whether GoDaddy strips the `@import`).
- Real SMS hand-off on iOS and Android, both top-level and from inside a frame (`target="_top"` on Open in Messages).
- Clipboard copy inside Facebook's in-app browser (if it's blocked, the full code appears in the box to select by hand).
- Frame rate of the bounce-in on old phones.
