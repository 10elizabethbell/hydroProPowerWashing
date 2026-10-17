---
name: Hydro-Pro Quote Widget
description: A drop-in quote widget that blends into hydropronj.com, shown on a phone-first pitch page where you pressure-wash the owner's own house photo clean.
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
  selection: "#cfe0ff"
  focus-ring: "#7aa7f7"
  wash-fallback: "#6b7458"
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
    fontSize: "clamp(34px, 9.6vw, 72px)"
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
    lineHeight: 1.42
  body:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.12em"
  tel-phone:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 700
  tel:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
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
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.14em"
  hpq-fine:
    fontFamily: "\"Open Sans\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  focus: "6px"
  pre: "12px"
  r: "16px"
  wash-phone: "18px"
  wash: "22px"
  pill: "999px"
  hpq-radius: "10px"
  hpq-card-phone: "14px"
  hpq-card: "16px"
spacing:
  gutter: "20px"
  section-phone: "44px"
  section: "64px"
  card-phone: "22px 18px"
  card: "28px"
  grid-gap-phone: "40px"
  grid-gap: "56px"
  hpq-card-phone: "22px 18px"
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
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.blue-deep}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.blue}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-ghost-hover:
    backgroundColor: "{colors.sky}"
  top-bar-phone:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.blue-ink}"
    typography: "{typography.tel-phone}"
    height: "58px"
  top-bar:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.blue-ink}"
    typography: "{typography.tel}"
    height: "72px"
  wash-phone:
    backgroundColor: "{colors.wash-fallback}"
    rounded: "{rounded.wash-phone}"
  wash:
    backgroundColor: "{colors.wash-fallback}"
    rounded: "{rounded.wash}"
  card-way-phone:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.r}"
    padding: "22px 18px"
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
    padding: "14px"
  hpq-card-phone:
    backgroundColor: "{colors.hpq-bg}"
    textColor: "{colors.hpq-ink}"
    rounded: "{rounded.hpq-card-phone}"
    padding: "22px 18px"
    width: "100%"
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
    height: "56px"
  hpq-send-hover:
    backgroundColor: "{colors.hpq-accent-dark}"
  hpq-alt:
    backgroundColor: "transparent"
    textColor: "{colors.hpq-accent}"
    typography: "{typography.hpq-button}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "56px"
---

# Design System: Hydro-Pro Quote Widget

## Overview

**Creative North Star: "The Clean Stripe"**

Two systems share one file and must stay separate. The **widget** (`#hpq-block`, between `HPQ:BEGIN` and `HPQ:END`) is a guest on someone else's website: it borrows hydropronj.com's language (their blue, a white card, pill buttons, uppercase tracked labels, Open Sans when the host has it) and adds nothing of its own. It is neutral and still, so it reads as if it was always part of their GoDaddy site. The **demo page** around it is the pitch to the owner: the same blue, pushed louder, with heavy uppercase headlines and one physical idea from the trade, a grimy surface coming clean under a pressure-wash stripe, on the owner's own hero photo.

Both systems are built phone first. The base styles are the 360–430px layout and every larger size is an adaptation layered on top, because the owner will open the pitch on a phone and his customers will fill the widget on one. Phone values in this file are the primary steps of each scale; tablet and desktop values come second.

The page is light and cool throughout: a pale blue-white ground, white panels, deep navy for headings and the footer. Depth is soft and blue-tinted. Every bit of motion on the page lives in the wash; the widget only changes state.

**Key Characteristics:**
- Phone first: base CSS is the phone layout; `min-width` queries adapt up.
- One hue (Hydro-Pro blue `#0d57db`) across both systems; everything else is neutral.
- Pill buttons in matched pairs: filled primary, outlined ghost, same 56px height, same 2px outline.
- Uppercase tracked labels name fields, buttons and panels.
- Page headlines shout (800, uppercase, tight tracking); widget headings stay sentence case.
- Ground is never black.
- Signature: the wash canvas, the owner's photo under generated grime, washed by drag or by an idle wand.

## Colors

A single-blue palette over cool, near-white neutrals; the widget uses warm-free greys so it sits on any host page.

### Primary
- **Hydro-Pro Blue** (`blue` / `hpq-accent`): their site's own blue. Page: filled buttons, links, ghost-button text and outline, the accent words in the hero headline, the "Easiest" chip text, the "Copied" confirmation. Widget: the send button, focus border, selected day chip, links, status line.
- **Pressed Blue** (`blue-deep` / `hpq-accent-dark`): hover state of every filled button (hover-capable pointers only). Never used at rest.
- **Harbor Navy** (`blue-ink`): page headlines, section titles, card titles, code text, the wash hint text, and the footer ground. The darkest surface the page ever uses.

### Neutral (demo page)
- **Mist Ground** (`ground`): the page body. Every un-sectioned stretch of page sits on it.
- **Paper** (`paper`): top bar, the "Try it" band, embed cards.
- **Sky Wash** (`sky`): ghost-button hover fill and the "Easiest" chip.
- **Slate Ink** (`ink`): body text. **Slate Soft** (`ink-soft`): secondary copy, section intros, the preview heading.
- **Hairline** (`line`): 1px borders on the top bar, section bands and cards.
- Code blocks sit on a blue-tinted panel (`#eef3fb`). Footer copy is pale blue (`#d7e3fa`, demo note `#a9bfe8`) on navy.

### Intentional one-off literals
These appear once each in the shipped CSS and are deliberate; reuse them for the same job, never as general palette.
- **Selection Blue** (`selection`): `::selection` background, with Harbor Navy text.
- **Focus Ring** (`focus-ring`): the page's global `:focus-visible` outline, 3px, 2px offset, with a 6px corner (`rounded.focus`) so bare links get a soft ring. Components with their own radius (pills, cards) keep it.
- **Wash Fallback** (`wash-fallback`): grime olive painted behind the wash canvas, visible only before the photo and grime load. It is the reason the Never-Black rule holds even in the frame's empty state.
- **Grime palette** (canvas only, never CSS): base `rgba(92,88,70,.82)`; blotch tones `rgb(70,78,46)`, `rgb(112,108,84)`, `rgb(52,58,40)`, `rgb(124,126,92)`, `rgb(96,84,58)`; drip streaks `rgb(44,50,32)`; speckles `rgba(40,44,30,.35)` and `rgba(150,150,120,.22)`; spray droplets `#ffffff` and `#e9f3ff`. These are the dirt, not the brand: they exist to be washed away and never appear outside the canvas.

### Messaging-app mimicry (not palette)
The phone preview and the example text bubble copy a phone's own Messages app so the owner recognizes what lands on his phone. Their greys belong to that imitation, not to this system, and must not leak into page or widget UI.
- Received bubble `#e9e9eb` with `#111` text; placeholder text in the bubble `#5a616d`.
- Thread header `#f6f7f9` over a `#e9ecf1` rule; contact name `#222`; contact sub-line (11px), example label and timestamp (11px) in `#5a616d`, the same grey as the bubble placeholder.
- Avatar disc `#68717f` with white initial; device bezel `#dfe6f1`; screen white.

### Neutral (widget)
- **Charcoal** (`hpq-ink`): all widget text, labels included.
- **Grey Note** (`hpq-muted`): lede, "(optional)", day-chip dates, fine print.
- **Field Stroke** (`hpq-line`): input and unselected day-chip borders. About 3:1 against white, the non-text contrast floor; it must not get lighter.
- **White** (`hpq-bg`, `hpq-field`): card and field fills; separate knobs so a host can tint one without the other.
- **Error Red** (`hpq-error`): invalid field border and error text only.
- Card border `#dadada`; sent-message panel `#f6f6f6`; placeholders `#767676`; selected-chip date `#dbe7ff`.

### Named Rules
**The Never-Black Ground Rule.** The page ground is never black. Body sits on `ground`, bands on `paper`; the darkest surface anywhere is Harbor Navy in the footer. No `#000` or near-black section, card, or overlay; even the wash canvas fallback is grime olive, not black.

**The One Blue Rule.** Blue is the only hue in either system. The page climbs a three-step ladder (blue at rest, pressed blue on hover, navy for type and the footer); the widget uses only the first two. No second accent. Grime olive and messaging greys are depicted materials, not accents.

**The Host Palette Rule.** Widget colors come only from `--hpq-*` variables declared on `#hpq-block`. No demo-page token (`--blue`, `--ink`, `--ground`) is ever referenced inside the block, so pasting it into GoDaddy carries everything it needs and nothing else.

## Typography

**Display Font:** Open Sans (their site's face), with system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial
**Body Font:** same stack
**Label/Mono Font:** ui-monospace, SFMono-Regular, Menlo, Consolas (code blocks only)

**Character:** One sans family, two temperaments. On the page it shouts: heavy, uppercase, tight. Inside the widget it speaks plainly in sentence case, with only labels and buttons tracked out. Neither file loads Open Sans; on the host site it is picked up when present, and on the standalone demo the stack falls through to the system face.

### Hierarchy (demo page), phone first
- **Display** (800, uppercase, `clamp(34px,9.6vw,72px)`, 0.98, -0.02em, balanced wrap): the hero headline only, in navy with the payoff words in blue. On a 360px phone it sets at 34.6px and fills the width in two to three lines; it reaches 72px at desktop. 10px below it on phones, 16px from 900px.
- **Headline** (800, uppercase, `clamp(28px,3.4vw,42px)`, 1.05, -0.01em): one per section; 28px on every phone.
- **Title** (800, uppercase, 20px, -0.01em): card titles in the embed section, all sizes.
- **Pitch** (400, `clamp(17px,1.6vw,20px)`, 1.42, max 36ch): the one-line pitch under the hero headline; 17px on phones.
- **Body** (400, 16px, 1.55): running copy; section intros cap at 60ch. The hero sub-line (44ch) is hidden on phones and appears from 600px.
- **Label** (700, 14px, 0.12em, uppercase): every page button, phone and desktop alike.
- **Phone link** (700, 16px on phones, 17px from 600px, navy, no tracking): the top-bar `tel:` number.
- **Preview heading** (700, uppercase): The preview heading is 13px / 0.14em.
- **Secondary small copy**: preview caption 15px on phones, 14px from 900px; "Copied" confirmation 15px/600 in blue.

### Hierarchy (widget), phone first
The widget type ramp does not change with width; only spacing and layout do.
- **Title** (700, 24px, 1.2, sentence case, no tracking): "Get a fast quote", "Your text is ready".
- **Lede** (400, 15px, muted): one line under the title.
- **Body / Field** (400, 16px, 1.4–1.5): field text. 16px is a floor so iOS does not zoom on focus.
- **Label** (700, 12px, 0.1em, uppercase): field labels and the day legend.
- **Button** (700, 14px, 0.14em, uppercase).
- **Fine** (400, 14px, 1.5, centered, muted): service area, hours. Error messages, status line, the copied-text panel and the text link are also 14px.

### Named Rules
**The Two Voices Rule.** Page headings are 800 uppercase with negative tracking; widget headings are 700 sentence case with zero tracking and explicitly reset `text-transform`. A widget heading that shouts would fight the host site's own headings.

**The Labels Label Rule.** Tracked uppercase small text always names something concrete: a field, a button, a panel, a chip, a footer business name. It never sits above a headline as a kicker.

**The Thumb-Size Text Rule.** Interactive text is 14px or larger on phones: button labels, fine print, links and status lines. Only labels that name a field (12px) and messaging-app mimicry go smaller.

## Layout

Phone first. Base CSS is the 360–430px layout; `min-width:600px` adapts for large phones and small tablets, `min-width:900px` for desktop. The widget carries its own single step at `min-width:481px`. The wash script halves spray density under 520px wide.

**Container:** centered `wrap`, 1180px max, 20px gutters at every width.

**Phones (base):** one column throughout. The hero stacks copy, then the wash, then the action buttons, so the photo is in the first viewport and the buttons follow it. Hero action buttons stack full width with 10px between. Hero padding 18px top / 30px bottom, 16px between hero rows; the wash frame keeps 22px below it for the overlapping example bubble. Sections pad 44px top / 52px bottom. The widget and preview stack with 40px between; the embed cards stack with 20px between. The footer pads 36px top / 40px bottom; there is no sticky bottom bar to clear.

**600px and up:** the hero sub-line appears; hero buttons sit side by side (flex, 12px gap, wrapping); the wash becomes 4:3. Sections open to 64px top (72px bottom on "Try it"); embed cards pad 28px and their buttons shrink to content width. The top bar grows to 72px. The phone mock widens to 310px.

**900px and up:** the hero becomes two columns (copy and actions in `1fr` on the left, wash in `1.15fr` on the right spanning both rows, 48px column gap, 26px row gap, bottom-aligned); hero padding 44/56px. "Try it" becomes the widget (max 560px) beside a sticky phone preview (top 24px), 56px gap. Embed cards go two up, 28px gap. Footer pads 40/48px.

Bands alternate grounds: hero on `ground`, "Try it" on `paper` with hairlines top and bottom, embed back on `ground`, footer on navy.

**Widget, phone (base):** card padding 22px / 18px; name and phone fields stack; day chips run three per row; the phone number is hidden from the "Text us instead" button. **481px and up:** card padding 28px; name and phone sit side by side with a 14px column gap; day chips share one row; the number shows.

Widget rhythm (all widths): 16px between fields, 6px label-to-field, 8px between day chips, 22px below the lede and above the button stack, 10px between buttons, 14px above fine print.

### Named Rules
**The Phone Is The Base Rule.** Write the phone layout as the unqualified CSS and adapt upward with `min-width` queries. A desktop rule undone by a `max-width` query is a regression.

## Elevation & Depth

Soft lift, never hard. Shadows use a negative spread so they pool under an element rather than haloing it, and on the page they are tinted navy (`rgba(3,43,116,…)`), never grey or black. Flat elsewhere: cards and bands separate with 1px hairlines, not shadows.

### Shadow Vocabulary
- **Hero lift** (`0 20px 40px -22px rgba(3,43,116,.45), 0 4px 12px rgba(3,43,116,.12)`): the wash canvas, all widths.
- **Floating bubble** (`0 14px 30px -16px rgba(3,43,116,.55), 0 3px 10px rgba(3,43,116,.14)`): the example text overlapping the photo.
- **Device** (`0 30px 60px -30px rgba(3,43,116,.5), 0 6px 18px rgba(3,43,116,.1)`): the phone mock.
- **Pill hint** (`0 6px 16px -6px rgba(3,43,116,.35)`): the "Swipe to wash it" / "Drag to wash it" hint pill.
- **Widget card** (`0 18px 40px -26px rgba(27,27,27,.35)`): neutral grey, because the widget must sit on any host ground.

### Named Rules
**The Tinted Lift Rule.** Page shadows are navy-tinted, negatively spread, and reserved for things that float over or above the page (the photo, the bubble, the phone). Cards and sections use hairlines.

## Shapes

Round and friendly. Every button is a full pill (999px) with a 2px outline in the accent, filled or not. The radius scale, phone value first:
- **Wash frame:** 18px on phones, 22px from 600px.
- **Widget card:** 14px on phones, 16px from 481px.
- **Page cards:** 16px at all widths. **Code blocks:** 12px.
- **Widget fields and day chips:** one shared 10px radius; the sent-message panel uses it too.
- **Focus ring:** 6px corner on the global page ring.
- **Message bubbles** (mimicry): the messaging tail shape, rounded on three corners with a 6px bottom-left. The example bubble is 16px on phones and 18px from 900px; the preview bubble is 18px.
- **Phone mock:** 44px outer, 34px screen; avatar a full circle.

## Components

### Buttons
Confident pills, always in a matched pair, sized for thumbs.
- **Shape:** full pill, 2px accent outline on every variant.
- **Primary:** filled blue, white uppercase tracked label (14px). Page: 56px tall, 24px side padding, full width when stacked on phones, content width from 600px. Widget: 56px, full width at every size.
- **Ghost / Alt:** transparent with blue text and outline; hover fills with sky (page) or 7% blue (widget).
- **Hover / Press:** hover applies only on hover-capable pointers (`@media (hover:hover)`), so a tap never leaves a stuck hover state; primary darkens to pressed blue (fill and outline). Press scales to 0.97 (page) or 0.98 (widget). Tap highlight is suppressed. Transitions 0.15–0.2s.
- **Focus:** page uses the global focus ring; widget uses a 3px 40%-blue outline, 2px offset.
- **Widget hover outline:** on hover-capable pointers, widget buttons and text links gain a 2px 45%-blue outline at 2px offset, on top of their fill change.
- **Icons:** inline stroke SVG (2px stroke, round caps), 20px on page buttons, 18px in the widget, 10px gap.

### Chips
- **Day chip (widget):** radio styled as a 52px tile, 10px radius, field-stroke border, weekday 14px/600 over a 12px muted date. Three per row on phones, one even row from 481px. Hover (hover-capable pointers) turns the border blue; selected fills blue with white text; keyboard focus shows a 3px 30%-blue ring.
- **Best chip (page):** small sky pill with blue 11px tracked text, inline after a card title.

### Cards / Containers
- **Embed card:** paper, 1px hairline, 16px radius, 22px / 18px padding on phones, 28px from 600px, no shadow.
- **Widget card:** white, `#dadada` 1px border, neutral widget-card shadow, max 560px; 14px radius and 22px / 18px padding on phones, 16px and 28px from 481px.
- **Code block:** blue-tinted panel, 12px radius, 14px padding, navy monospace 13px, wrapping, capped at 420px tall with its own scroll.

### Inputs / Fields
- **Style:** 48px min height (76px textarea), 11px/14px padding, 1px field-stroke border, 10px radius, white fill, 16px text. Select carries an inline chevron SVG at right 14px.
- **Hover** (hover-capable pointers): border turns blue plus a lighter 3px 12%-blue ring.
- **Focus:** border turns blue plus a 3px 22%-blue glow; no outline.
- **Error:** border turns error red; a 14px red message appears below and is linked by `aria-describedby` only while invalid.
- **Text link** (widget, "Edit"-style): 14px/600 blue underlined, 44px min tap height.
- **No email in the widget:** contact inside the widget is text and phone only; the business email appears once, in the page footer.

### Navigation
- **Top bar:** paper with a hairline bottom. Phones: 58px tall, logo 34px, the phone number top right as a 16px/700 navy `tel:` link (44px tap height; underlined blue on hover). From 600px: 72px, logo 44px, number 17px. The number appears only here on the first screen. No sticky bottom bar (removed 2026-10-17, finishing rules).

### Wash Canvas (signature)
The owner's own hero photo (never stock) under a generated grime layer that the visitor pressure-washes clean.
- **Frame:** 16:10 with an 18px radius on phones, 4:3 with 22px from 600px; hero lift shadow; grime-olive fallback ground; crosshair cursor; `touch-action: none` so drags wash in every direction (page scrolls outside the photo); `overscroll-behavior-y: none` on html stops pull-to-refresh; text selection and touch callout disabled.
- **Layers:** photo (`object-position` 50% 45%), grime canvas (grime minus a "clean mask"), spray canvas.
- **Grime:** the grime palette above: an olive-brown base with radial blotches in five tones, 90 dark drip streaks, 2600 speckles. Seeded random, so the grime is identical every load.
- **Opening state:** one clean diagonal double stripe, the classic first pass, so the first viewport is half washed.
- **Tunable constants** (top of the wash IIFE): `BRUSH` 0.075 of width, `BRUSH_STRENGTH` 0.55 (two passes ≈ spotless), `REGRIME_EVERY` 30 frames, `REGRIME_ALPHA` 0.02 (~17s half-life), `IDLE_AFTER` 2200ms, `WAND_SPEED` 1.0, `SPRAY_PER_FRAME` 7 (halved under 520px). The idle wand washes at 70% strength on layered sines.
- **Spray:** white and pale-blue droplets with gravity and drag, capped at 600.
- **Overlays:** the hint pill (white 92%, navy 13px/700) sits top left on phones and bottom left from 900px, reads "Swipe to wash it" on touch and "Drag to wash it" on fine pointers, and lifts away on first touch. The example text bubble overlaps the bottom-right corner: on phones 10px in from the right, 26px below the frame, max 205px, 12px text; from 900px it hangs 18px past the right edge, max 250px, 13px text.
- **Restraint:** pauses off-screen; under reduced motion there is no loop, no spray, no wand, and washing still works by direct drag.

### Phone Preview
A plain messaging mock that mirrors the widget's exact text as the visitor types, driven by the widget's `hpq:change` event. 280px wide with a 300px screen on phones, 310px / 470px from 600px, sticky beside the widget from 900px. Its colors are messaging-app mimicry (see Colors), on purpose.

## Do's and Don'ts

### Do:
- **Do** write phone styles as the base and adapt up with `min-width` (600px, 900px; 481px inside the widget).
- **Do** keep the page ground at Mist Ground and the darkest surface at Harbor Navy; the ground is never black.
- **Do** scope every widget selector under `#hpq-block` and route every widget color through a `--hpq-*` variable, so a restyle is a variable edit.
- **Do** ship buttons as pairs: same 56px height, same 2px outline, filled primary beside outlined ghost.
- **Do** gate hover styles behind `@media (hover:hover)`.
- **Do** set page headings in 800 uppercase with negative tracking and widget headings in 700 sentence case.
- **Do** keep widget field text at 16px or larger and interactive text at 14px or larger.
- **Do** tint page shadows navy with negative spread, and only on elements that float.
- **Do** run the wash over the client's own photo and tune it through the named constants, not by editing the loop.
- **Do** keep field strokes at 3:1 or better against the card; the shipped `hpq-line` sits at that floor, so don't lighten it.

### Don't:
- **Don't** put a black or near-black ground behind any section, card, or overlay.
- **Don't** animate anything inside the widget beyond 0.15s state transitions and the press scale; all motion belongs to the demo page.
- **Don't** reference demo-page tokens or load fonts or assets from inside `#hpq-block`; it must paste into GoDaddy whole.
- **Don't** add a second accent hue to either system, and don't borrow the grime olives or the messaging greys as UI color.
- **Don't** place a tracked uppercase line above a headline as a kicker; tracked labels name things.
- **Don't** use grey or black drop shadows on the page, or hard offset shadows anywhere.
- **Don't** run the wash over stock or generated house imagery.
