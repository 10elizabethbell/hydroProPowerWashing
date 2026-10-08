---
name: Hydro-Pro Quote Widget
description: A drop-in quote widget that blends into hydropronj.com, shown on a pitch page where you pressure-wash the owner's own house photo clean.
colors:
  blue: "#0d57db"
  blue-deep: "#073fa3"
  blue-ink: "#032b74"
  ink: "#1f2733"
  ink-soft: "#4a5463"
  line: "#dfe4ec"
  ground: "#f4f7fb"
  paper: "#ffffff"
  sky: "#e8f0fd"
  hpq-accent: "#0d57db"
  hpq-accent-dark: "#073fa3"
  hpq-ink: "#303030"
  hpq-muted: "#5e5e5e"
  hpq-line: "#949494"
  hpq-field: "#ffffff"
  hpq-bg: "#ffffff"
  hpq-error: "#b42318"
typography:
  display:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(38px, 5.6vw, 72px)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(28px, 3.4vw, 42px)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  title:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    letterSpacing: "-0.01em"
  pitch:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 1.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.14em"
  code:
    fontFamily: "ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "13px"
    lineHeight: 1.55
  hpq-title:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0"
  hpq-body:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  hpq-label:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: "0.1em"
  hpq-button:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.14em"
  hpq-fine:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  r: "16px"
  pre: "12px"
  wash: "22px"
  pill: "999px"
  hpq-radius: "10px"
  hpq-card: "16px"
spacing:
  gutter: "20px"
  gutter-phone: "16px"
  section: "64px"
  card: "28px"
  grid-gap: "56px"
  hpq-card: "28px"
  hpq-field-gap: "16px"
  hpq-col-gap: "14px"
  hpq-chip-gap: "8px"
components:
  button-primary:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "52px"
  button-primary-hover:
    backgroundColor: "{colors.blue-deep}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.blue}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "52px"
  button-ghost-hover:
    backgroundColor: "{colors.sky}"
  card-way:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.r}"
    padding: "28px"
  chip-best:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.blue}"
    rounded: "{rounded.pill}"
    padding: "3px 9px"
  code-block:
    backgroundColor: "#eef3fb"
    textColor: "{colors.blue-ink}"
    typography: "{typography.code}"
    rounded: "{rounded.pre}"
    padding: "16px"
  hpq-card:
    backgroundColor: "{colors.hpq-bg}"
    textColor: "{colors.hpq-ink}"
    rounded: "{rounded.hpq-card}"
    padding: "28px"
    width: "560px"
  hpq-input:
    backgroundColor: "{colors.hpq-field}"
    textColor: "{colors.hpq-ink}"
    typography: "{typography.hpq-body}"
    rounded: "{rounded.hpq-radius}"
    padding: "11px 14px"
    height: "48px"
  hpq-day:
    backgroundColor: "{colors.hpq-field}"
    textColor: "{colors.hpq-ink}"
    rounded: "{rounded.hpq-radius}"
    padding: "6px 12px"
    height: "52px"
  hpq-day-selected:
    backgroundColor: "{colors.hpq-accent}"
    textColor: "#ffffff"
  hpq-send:
    backgroundColor: "{colors.hpq-accent}"
    textColor: "#ffffff"
    typography: "{typography.hpq-button}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "54px"
  hpq-send-hover:
    backgroundColor: "{colors.hpq-accent-dark}"
  hpq-alt:
    backgroundColor: "transparent"
    textColor: "{colors.hpq-accent}"
    typography: "{typography.hpq-button}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "54px"
---

# Design System: Hydro-Pro Quote Widget

## Overview

**Creative North Star: "The Clean Stripe"**

Two systems share one file and must stay separate. The **widget** (`#hpq-block`, between `HPQ:BEGIN` and `HPQ:END`) is a guest on someone else's website: it borrows hydropronj.com's language (their blue, a white card, pill buttons, uppercase tracked labels, Open Sans when the host has it) and adds nothing of its own. It is neutral and still, so it reads as if it was always part of their GoDaddy site. The **demo page** around it is the pitch to the owner: the same blue, pushed louder, with heavy uppercase headlines and one physical idea from the trade, a grimy surface coming clean under a pressure-wash stripe, on the owner's own hero photo.

The page is light and cool throughout: a pale blue-white ground, white panels, deep navy for headings and the footer. Depth is soft and blue-tinted. Every bit of motion on the page lives in the wash; the widget only changes state.

**Key Characteristics:**
- One hue (Hydro-Pro blue `#0d57db`) across both systems; everything else is neutral.
- Pill buttons in matched pairs: filled primary, outlined ghost, same height, same 2px outline.
- Uppercase tracked labels name fields, buttons and panels.
- Page headlines shout (800, uppercase, tight tracking); widget headings stay sentence case.
- Ground is never black.
- Signature: the wash canvas, the owner's photo under generated grime, washed by drag or by an idle wand.

## Colors

A single-blue palette over cool, near-white neutrals; the widget uses warm-free greys so it sits on any host page.

### Primary
- **Hydro-Pro Blue** (`blue` / `hpq-accent`): their site's own blue. Page: filled buttons, links, ghost-button text and outline, the accent word in the hero headline, the "Easiest" chip text. Widget: the send button, focus border, selected day chip, links, status line.
- **Pressed Blue** (`blue-deep` / `hpq-accent-dark`): hover state of every filled button. Never used at rest.
- **Harbor Navy** (`blue-ink`): page headlines, section titles, card titles, code text, and the footer ground. The darkest surface the page ever uses.

### Neutral (demo page)
- **Mist Ground** (`ground`): the page body. Every un-sectioned stretch of page sits on it.
- **Paper** (`paper`): top bar, the "Try it" band, embed cards.
- **Sky Wash** (`sky`): ghost-button hover fill and the "Easiest" chip.
- **Slate Ink** (`ink`): body text. **Slate Soft** (`ink-soft`): secondary copy, the top-bar tag, the preview heading.
- **Hairline** (`line`): 1px borders on the top bar, section bands and cards.
- Code blocks sit on a blue-tinted panel (`#eef3fb`). Selection is `#cfe0ff` with navy text. Focus ring is a 3px `#7aa7f7` outline, 2px offset.

### Neutral (widget)
- **Charcoal** (`hpq-ink`): all widget text, labels included.
- **Grey Note** (`hpq-muted`): lede, "(optional)", day-chip dates, fine print.
- **Field Stroke** (`hpq-line`): input and unselected day-chip borders. See Do's and Don'ts: this value is below the 3:1 non-text contrast floor.
- **White** (`hpq-bg`, `hpq-field`): card and field fills; separate knobs so a host can tint one without the other.
- **Error Red** (`hpq-error`): invalid field border and error text only.
- Card border `#dadada`; sent-message panel `#f6f6f6`; placeholders `#767676`.

### Named Rules
**The Never-Black Ground Rule.** The page ground is never black. Body sits on `ground`, bands on `paper`; the darkest surface anywhere is Harbor Navy in the footer. No `#000` or near-black section, card, or overlay; even the wash canvas fallback is grime olive (`#6b7458`), not black.

**The One Blue Rule.** Blue is the only hue in either system. The page climbs a three-step ladder (blue at rest, pressed blue on hover, navy for type and the footer); the widget uses only the first two. No second accent.

**The Host Palette Rule.** Widget colors come only from `--hpq-*` variables declared on `#hpq-block`. No demo-page token (`--blue`, `--ink`, `--ground`) is ever referenced inside the block, so pasting it into GoDaddy carries everything it needs and nothing else.

## Typography

**Display Font:** Open Sans (their site's face), with system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial
**Body Font:** same stack
**Label/Mono Font:** ui-monospace, SFMono-Regular, Menlo, Consolas (code blocks only)

**Character:** One sans family, two temperaments. On the page it shouts: heavy, uppercase, tight. Inside the widget it speaks plainly in sentence case, with only labels and buttons tracked out. Neither file loads Open Sans; on the host site it is picked up when present, and on the standalone demo the stack falls through to the system face.

### Hierarchy (demo page)
- **Display** (800, uppercase, `clamp(38px,5.6vw,72px)`, 0.98, -0.02em, balanced wrap): the hero headline only, in navy with the payoff words in blue.
- **Headline** (800, uppercase, `clamp(28px,3.4vw,42px)`, 1.05, -0.01em): one per section.
- **Title** (800, uppercase, 20px, -0.01em): card titles in the embed section.
- **Pitch** (400, `clamp(17px,1.6vw,20px)`, 1.45, max 34ch): the one-line pitch under the hero headline.
- **Body** (400, 16px, 1.55): running copy; section intros cap at 60ch, hero sub at 44ch.
- **Label** (700, 12–13px, 0.14em, uppercase): buttons, the top-bar tag, the preview panel heading.

### Hierarchy (widget)
- **Title** (700, 24px, 1.2, sentence case, no tracking): "Get a fast quote", "Your text is ready".
- **Lede** (400, 15px, muted): one line under the title.
- **Body / Field** (400, 16px, 1.4–1.5): field text. 16px is a floor so iOS does not zoom on focus.
- **Label** (700, 12px, 0.1em, uppercase): field labels and the day legend.
- **Button** (700, 13px, 0.14em, uppercase).
- **Fine** (400, 13px, 1.5, centered, muted): service area, hours, email fallback.

### Named Rules
**The Two Voices Rule.** Page headings are 800 uppercase with negative tracking; widget headings are 700 sentence case with zero tracking and explicitly reset `text-transform`. A widget heading that shouts would fight the host site's own headings.

**The Labels Label Rule.** Tracked uppercase small text always names something concrete: a field, a button, a panel, a chip, a footer business name. It never sits above a headline as a kicker.

## Layout

Page: centered `wrap` at 1180px max with 20px gutters (16px under 520px). The hero is a two-column grid (copy `1fr`, wash `1.15fr`, 48px gap, vertically centered). The "Try it" band is a grid of the widget (max 560px) and a sticky phone preview (top 24px), 56px gap. Embed options sit in two equal cards, 28px gap. Sections breathe at 64–72px vertical padding (48px on phones); the hero is tighter (44/56px).

Bands alternate grounds: hero on `ground`, "Try it" on `paper` with hairlines top and bottom, embed back on `ground`, footer on navy.

Breakpoints: at 900px every grid collapses to one column and the preview stops sticking; at 520px the hero action buttons go full width, the wash drops to 5:4 and its caption hides. The widget has its own 480px breakpoint: name/phone row stacks, card padding drops to 22/18px, day chips go three per row, the phone number leaves the "Text us instead" button.

Widget rhythm: 28px card padding, 16px between fields, 14px column gap, 6px label-to-field, 8px between day chips, 22px above the button stack, 10px between buttons.

## Elevation & Depth

Soft lift, never hard. Shadows use a negative spread so they pool under an element rather than haloing it, and on the page they are tinted navy (`rgba(3,43,116,…)`), never grey or black. Flat elsewhere: cards and bands separate with 1px hairlines, not shadows.

### Shadow Vocabulary
- **Hero lift** (`0 24px 50px -24px rgba(3,43,116,.45), 0 4px 12px rgba(3,43,116,.12)`): the wash canvas.
- **Floating bubble** (`0 18px 36px -18px rgba(3,43,116,.5), 0 4px 12px rgba(3,43,116,.12)`): the example text overlapping the photo.
- **Device** (`0 30px 60px -30px rgba(3,43,116,.5), 0 6px 18px rgba(3,43,116,.1)`): the phone mock.
- **Pill hint** (`0 6px 16px -6px rgba(3,43,116,.35)`): the "Drag to wash it" pill.
- **Widget card** (`0 18px 40px -26px rgba(27,27,27,.35)`): neutral grey, because the widget must sit on any host ground.

### Named Rules
**The Tinted Lift Rule.** Page shadows are navy-tinted, negatively spread, and reserved for things that float over or above the page (the photo, the bubble, the phone). Cards and sections use hairlines.

## Shapes

Round and friendly. Every button is a full pill (999px) with a 2px outline in the accent, filled or not. Page cards use 16px, code blocks 12px, the wash 22px (18px on phones). Inside the widget, fields and day chips share one 10px radius and the card is 16px (14px on phones). Message bubbles use the messaging tail shape: 18px with a 6px bottom-left corner. The phone mock is 44px outer, 34px screen.

## Components

### Buttons
Confident pills, always in a matched pair.
- **Shape:** full pill, 2px accent outline on every variant.
- **Primary:** filled blue, white uppercase tracked label; 52px tall on the page, 54px full-width in the widget.
- **Ghost / Alt:** transparent with blue text and outline; hover fills with sky (page) or 7% blue (widget).
- **Hover / Press:** primary darkens to pressed blue (fill and outline); press scales to 0.97 (page) or 0.98 (widget). Transitions 0.15–0.2s.
- **Focus:** page uses the global 3px `#7aa7f7` ring; widget uses a 3px 40%-blue outline, 2px offset.
- **Icons:** 18px inline stroke SVG (2px stroke, round caps), 10px gap.

### Chips
- **Day chip (widget):** radio styled as a 52px tile, 10px radius, hairline border, weekday 14px/600 over a 12px muted date. Hover turns the border blue; selected fills blue with white text and `#dbe7ff` date; keyboard focus shows a 3px 30%-blue ring.
- **Best chip (page):** small sky pill with blue 11px tracked text, inline after a card title.

### Cards / Containers
- **Embed card:** paper, 1px hairline, 16px radius, 28px padding (22/18px on phones), no shadow.
- **Widget card:** white, `#dadada` 1px border, 16px radius, 28px padding, neutral widget-card shadow, max 560px.
- **Code block:** blue-tinted panel, 12px radius, 16px padding, navy monospace 13px, wrapping.

### Inputs / Fields
- **Style:** 48px min height, 11px/14px padding, 1px field-stroke border, 10px radius, white fill, 16px text. Select carries an inline chevron SVG at right 14px.
- **Focus:** border turns blue plus a 3px 22%-blue glow; no outline.
- **Error:** border turns error red; a 14px red message appears below and is linked by `aria-describedby` only while invalid.

### Navigation
- **Top bar:** paper with a hairline bottom, 72px tall (60px on phones), their logo at 44px (34px), a small tracked uppercase tag at right. No links; the page is one scroll.

### Wash Canvas (signature)
The owner's own hero photo (never stock) under a generated grime layer that the visitor pressure-washes clean.
- **Frame:** 4:3 (5:4 on phones), 22px radius, hero lift shadow, crosshair cursor, `touch-action: pan-y` so vertical drags still scroll.
- **Layers:** photo, grime canvas (grime minus a "clean mask"), spray canvas.
- **Grime:** olive-brown base `rgba(92,88,70,.82)` with radial blotches from five tones (`70,78,46` / `112,108,84` / `52,58,40` / `124,126,92` / `96,84,58`), 90 dark drip streaks, 2600 speckles. Seeded random, so the grime is identical every load.
- **Opening state:** one clean diagonal double stripe, the classic first pass, so the first viewport is half washed.
- **Tunable constants** (top of the wash IIFE): `BRUSH` 0.075 of width, `BRUSH_STRENGTH` 0.55 (two passes ≈ spotless), `REGRIME_EVERY` 30 frames, `REGRIME_ALPHA` 0.02 (~17s half-life), `IDLE_AFTER` 2200ms, `WAND_SPEED` 1.0, `SPRAY_PER_FRAME` 7 (halved on phones). The idle wand washes at 70% strength on layered sines.
- **Spray:** white and `#e9f3ff` droplets with gravity and drag, capped at 600.
- **Overlays:** "Drag to wash it" white pill (bottom left; top left on phones) that drops away on first touch; a navy 72% caption pill at top right (hidden on phones); the example text bubble overlapping the bottom-right corner.
- **Restraint:** pauses off-screen; under reduced motion there is no loop, no spray, no wand, and washing still works by direct drag.

### Phone Preview
A plain messaging mock (`#dfe6f1` bezel, white screen, grey thread header, grey received bubble) that mirrors the widget's exact text as the visitor types, driven by the widget's `hpq:change` event. Its greys copy a phone's messaging app rather than this palette, on purpose.

## Do's and Don'ts

### Do:
- **Do** keep the page ground at Mist Ground and the darkest surface at Harbor Navy; the ground is never black.
- **Do** scope every widget selector under `#hpq-block` and route every widget color through a `--hpq-*` variable, so a restyle is a variable edit.
- **Do** ship buttons as pairs: same height, same 2px outline, filled primary beside outlined ghost.
- **Do** set page headings in 800 uppercase with negative tracking and widget headings in 700 sentence case.
- **Do** keep widget field text at 16px or larger.
- **Do** tint page shadows navy with negative spread, and only on elements that float.
- **Do** run the wash over the client's own photo and tune it through the named constants, not by editing the loop.
- **Do** keep field strokes at 3:1 or better against the card; the shipped `hpq-line` is `#949494` (about 3:1 on white); don't lighten it.

### Don't:
- **Don't** put a black or near-black ground behind any section, card, or overlay.
- **Don't** animate anything inside the widget beyond 0.15s state transitions and the press scale; all motion belongs to the demo page.
- **Don't** reference demo-page tokens or load fonts or assets from inside `#hpq-block`; it must paste into GoDaddy whole.
- **Don't** add a second accent hue to either system.
- **Don't** place a tracked uppercase line above a headline as a kicker; tracked labels name things.
- **Don't** use grey or black drop shadows on the page, or hard offset shadows anywhere.
- **Don't** run the wash over stock or generated house imagery.
