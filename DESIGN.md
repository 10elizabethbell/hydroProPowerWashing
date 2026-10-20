---
name: Hydro-Pro Power Washing quote widget
description: A drop-in text-me-a-quote widget for hydropronj.com, shown on a calm paper-and-navy pitch page coloured from the Hydro-Pro logo.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  ink: "#0b2457"
  body: "#2a3a4f"
  soft: "#4a5870"
  navy: "#0a3d99"
  deep: "#081f4d"
  on-dark: "#f4f7fc"
  on-dark-soft: "#cbd8ee"
  gold: "#f0c24b"
  gold-2: "#f6d272"
  gold-ink: "#85601a"
  blue: "#0d57db"
  error: "#b3261e"
  placeholder: "#5f6b80"
  on-ink-soft: "#dbe4f5"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-widget:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "30px"
    fontWeight: 400
    lineHeight: 1.08
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 400
    lineHeight: 1.08
  title-sm:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.08
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  title-xs:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.3
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  eyebrow:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.2
  code:
    fontFamily: "ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  focus: "6px"
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  card-pad: "24px 20px"
  card-pad-wide: "32px"
  section: "64px"
  section-wide: "96px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  eyebrow:
    backgroundColor: "rgba(11,36,87,.06)"
    textColor: "{colors.ink}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.12)"
    textColor: "{colors.on-dark}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.body}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-pad}"
  field:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  day-chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "6px 10px"
    height: "54px"
  day-chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  step-number:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.title-xs}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-circle:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Hydro-Pro Power Washing quote widget

## Overview

**Creative North Star: "Calm Bands in Their Own Colours"**

The page is Ellie's calm band style (house default since 2026-10-19, after lpmr.co.uk) coloured from the Hydro-Pro logo: full-bleed bands that alternate off-white paper, logo navy and a deeper navy with a faint diagonal line texture, so each new section is obvious without rules or dividers. One warm accent, the logo's gold, is used as a fill: buttons, step numbers, the floating text circle, the eyebrow dot. Everything is soft and borderless: 24px white cards, full pill buttons, tinted 10px fields.

Two systems share `index.html` and stay separate. The **widget** (`#hpq-block`, between `HPQ:BEGIN` and `HPQ:END`) is pasted into the owner's GoDaddy site or iframed, so it carries its own `--hpq-*` tokens, its own fonts declaration and its own `<style>`; it never reads a page variable. The **page** around it uses the `:root` tokens. Both draw the same values, so they read as one brand.

Motion is limited to two moments: the hero H1 letters bounce in once, and content below the first screen fades up 12px. Everything is visible at rest, without JS and under reduced motion. The phone mock in the "What lands on your phone" preview copies iOS Messages greys; those belong to the imitation, not to this system.

**Key Characteristics:**
- Paper, navy, paper, deep navy, navy, deep navy: alternating full-bleed bands.
- Logo gold as fill only; deeper gold ink when gold must be text on light.
- Cal Sans display at weight 400 for every heading, label and button; system stack for running text.
- 24px cards, 999px pills, 10px tinted borderless fields; no strokes at rest.
- Site blue reserved for hover and focus outlines on light grounds.
- One bounce-in (hero H1), one 12px fade-up, one floating 60px text circle.

## Colors

Paper and two navies carry the page; gold is the single warm accent, and the site blue appears only as an outline.

### Primary
- **Logo Gold** (gold): the one accent. Fills only: primary pill buttons, step-number discs, the floating circle, eyebrow dots, text selection. Text on it is always Hydro Ink. On navy and deep bands it may also colour the last phrase of a heading.
- **Pale Gold** (gold-2): hover fill of gold buttons, nothing else.
- **Gold Ink** (gold-ink): gold as text or icon on light grounds (header phone icon and hover, accent phrases on paper), 5.4:1 on paper.

### Secondary
- **Logo Navy** (navy): hero band (under the photo overlay) and the closing band.
- **Deep Navy** (deep): "How it works" band and footer, always with the diagonal line texture. The hero overlay is the same hue at 80–92%.

### Tertiary
- **Site Blue** (blue): hydropronj.com's own blue. Hover and focus outlines on light grounds (page `:focus-visible`, widget fields, chips and buttons), and the widget's caret. Never a fill.

### Neutral
- **Paper** (paper): page ground, field fill, code panel fill. The ground is never black.
- **Card White** (card): cards and the widget surface.
- **Hydro Ink** (ink): headings, labels, text on gold, selected day chip fill. At 6% alpha it is the eyebrow tint and the outlined button's hover.
- **Body Slate** (body): running text on light.
- **Soft Slate** (soft): ledes, notes, secondary text on light.
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): headings and running text on navy bands.
- **Placeholder Slate** (placeholder): field placeholders in the widget.
- **On Ink Soft** (on-ink-soft): the date line inside a selected (ink) day chip.
- **Error Red** (error): widget invalid-field outline and error sentences.

### Named Rules
**The Gold Is a Fill Rule.** Gold never sets text on a light ground; use Gold Ink there. On gold, text is Hydro Ink, never white.

**The Blue Is an Outline Rule.** Site Blue appears only as a 2–3px hover or focus outline (and the caret). On dark bands the focus outline switches to gold.

**The Two Token Sets Rule.** Widget colours live in `--hpq-*` on `#hpq-block` (accent, accent-2, ink, text, muted, field, bg, focus, error) and duplicate the page values by hand. Never make the widget read a `:root` variable; it must survive being pasted alone.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)
**Label/Mono Font:** ui-monospace stack, only in the embed code panels

**Character:** One friendly geometric display face at regular weight carries every heading, field label, step title, button and the header phone number; the system stack does all reading at 16/1.7.

### Hierarchy
- **Display** (400, clamp 40–80px, 1.02): hero H1 only, max 13ch.
- **Headline** (400, clamp 30–48px, 1.08): section H2s. The widget's H2 is a fixed 30px so it fits a host column.
- **Title** (400, 24px / 22px / 21px): embed card titles, the preview heading, step titles (22px from 1024px).
- **Title XS** (400, 20px): footer name, step numbers, header phone on desktop.
- **Button / Label** (Cal Sans 400, 18px / 17px): pill buttons; widget field labels and legends.
- **Lead / Lede** (system, clamp 17–20px, 1.5; clamp 17–19px): the hero promise (34ch) and section ledes (40ch), in Soft Slate or On Dark Soft.
- **Body** (system 400, 16px, 1.7): running text; every input is 16px so iOS does not zoom.
- **Body small** (15px, 1.5): notes, error sentences, the widget fine print, copy status.
- **Eyebrow** (system 500, 14px, 0.02em): eyebrow pills only. Also the "(optional)" tag.
- **Caption / Code** (13px): day-chip dates; embed code panels.

### Named Rules
**The Regular Display Rule.** Cal Sans is always weight 400 with -0.005em tracking and `text-wrap: balance` on headings. No uppercase, no bold display.

**The Place in the H1 Rule.** The hero H1 names the town; its last phrase is the gold accent.

## Layout

Phone first. A single 1160px wrap with a 20px gutter (40px from 760px). Bands pad 64px vertically on phones, 96px from 760px. Section heads are a left-aligned grid (16px gap, max 640px) of eyebrow, H2 and lede. The try section is one column until 1024px, then the 560px widget beside the sticky phone preview (64px gap). Steps go from a stacked list to three columns at 1024px; the two embed cards sit side by side at 1024px. Hero actions stack full width on phones and sit in a row (min 240px each) from 760px. Hover styles are behind `(hover:hover)`. Breakpoints: 481px (widget), 760px, 1024px.

## Elevation & Depth

Flat. Depth comes from band colour changes and white cards on paper, not shadows. The only shadow is the floating text circle's soft navy lift, because it floats over content.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,31,77,.3)`): the floating text circle only.

### Named Rules
**The No Stroke at Rest Rule.** Cards, fields and chips carry no border at rest; a transparent 2px border exists only so hover, focus and error can colour it without layout shift.

## Shapes

Soft and round. Cards 24px, fields and code panels 10px, buttons, chips, eyebrows and step discs fully round. Focus rings use a 6px radius (round on the circle). Deep bands carry a 135° line texture: 1px lines of white at 3.5% every 23px (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`), faint enough never to read as lines through text.

## Components

### Buttons
- **Shape:** full pill (999px), 56px tall, 26px side padding, Cal Sans 18px, 2px border.
- **Primary:** gold fill, ink text, gold border. Hover pale gold.
- **Ghost (on dark):** transparent, On Dark text, 70% On Dark border; hover full white border and 10% white fill.
- **Line (on light):** transparent, ink text and border; hover 6% ink tint.
- **Press:** scale(.98) over 120ms. Widget buttons also take a 2px Site Blue outline on hover and focus.
- At most two buttons in the hero: one gold, one ghost. No Call button; the number lives in the header.

### Eyebrow pills (sanctioned)
- **Style:** 14px system 500 label in a 6% ink pill (12% white on dark), 9px 14px padding, 7px gold dot before it.
- **Use:** above the hero H1, the widget title and a few section heads, never every heading. Marked up as `<span>`/`<p>`, never a heading. No arrow, no hover, no shadow, no full gold fill, so it cannot read as a button.
- Owner's choice (Ellie, calm-photo-style.md, 2026-10-19); the design hook's eyebrow/kicker rules are ignored for `index.html` on that basis.

### Chips (widget day picker)
- **Style:** pill, 54px tall, paper fill, ink 15px 600 day over a 13px muted date.
- **State:** selected fills ink with white text and On Ink Soft date; hover and keyboard focus outline Site Blue.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on paper.
- **Shadow Strategy:** none (see Elevation).
- **Border:** none.
- **Internal Padding:** 24px 20px on phones, 32px from 481px (widget) / 760px (embed cards).

### Inputs / Fields
- **Style:** paper fill, no visible border, 10px radius, 52px min height, 16px text in ink; selects carry an ink chevron.
- **Focus / Hover:** 2px Site Blue border.
- **Error:** 2px Error Red border plus a plain-sentence message below in 15px red.

### Navigation
- Slim paper header: logo left (34px, 44px from 760px), Cal Sans tap-to-call number right with a Gold Ink phone icon, gold-ink on hover. 64px tall (76px from 760px). No menu.

### Hero H1 bounce-in (sanctioned)
Hero H1 only. JS splits letters (words kept `nowrap`); each letter goes from `opacity:0; translateX(50px)` to rest over 1s on `cubic-bezier(.34,1.56,.64,1)`, 20ms apart. The overshoot is the bounce, an owner's choice. The heading carries `aria-label` while split and the plain HTML is restored on the last `animationend`. Skipped entirely under reduced motion and without JS.

### Fade-up
Elements marked to rise that start below the first screen move up 12px and fade in over 400ms ease-out on intersection. Nothing above the fold is ever hidden.

### Floating text circle
60px gold circle with a chat icon, fixed bottom-right (16px plus safe area), opens `sms:` with a prefilled line. Slides in once the hero scrolls away and hides while the quote form is on screen (`tabIndex=-1`, `aria-hidden` when hidden). One circle, never a bottom bar. Transition 350ms `cubic-bezier(.2,.8,.2,1)`.

### Step list
Numbered gold discs (48px, Cal Sans 20px ink) beside a Cal Sans step title and a one-line body, on the deep textured band.

### Phone preview (mimicry)
A 280px (310px desktop) rounded device frame holding an iOS Messages thread that mirrors the widget's text live. Its greys, 44px/34px frame radii, 18px bubble radius and 11–13.5px type copy Messages and are sanctioned only inside this mock.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands (paper, navy, deep navy with the line texture) so each section is obvious.
- **Do** use gold as a fill with ink text, and Gold Ink when gold must be text on light.
- **Do** keep every interactive target 44px or more, every input 16px or more.
- **Do** keep the widget self-contained: its own `--hpq-*` tokens, `@import` for Cal Sans and system fallbacks, no page variables.
- **Do** keep the line texture at 3.5% white or fainter.
- **Do** keep motion to the hero bounce-in and the 12px fade-up, and keep everything visible under reduced motion and without JS.

### Don't:
- **Don't** put white text on gold or gold text on paper.
- **Don't** use Site Blue as a fill or a second accent.
- **Don't** give the letter bounce to any heading but the hero H1.
- **Don't** add borders or shadows to cards, fields or chips at rest.
- **Don't** make an eyebrow look like a button (arrow, hover, shadow, solid gold) or put one above every heading.
- **Don't** use the phone mock's greys or radii anywhere outside the mock.
- **Don't** use a black ground anywhere.
