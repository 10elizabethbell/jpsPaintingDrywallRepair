---
name: JPS Painting & Drywall Repair
description: Phone-first pitch one-pager that is a stirred can of wet paint in the JPS seal's colors.
colors:
  navy: "#1e3a5c"
  navy-mid: "#2a4b72"
  navy-deep: "#13294a"
  ink: "#172f4d"
  ink-2: "#47607d"
  wood: "#c58d52"
  wood-lt: "#e0b27a"
  wood-ink: "#9c6531"
  plaster: "#f1ebdf"
  plaster-2: "#e5dac6"
  cream: "#efe6d4"
  on-navy: "#f1ebdf"
  on-navy-2: "#c9d3df"
typography:
  display:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.7rem, 13.2vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  title:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.25rem, 6vw, 1.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "0"
  lede:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(16px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.4
  body:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 800
    letterSpacing: "0.05em"
rounded:
  card: "18px"
  focus: "10px"
  pill: "999px"
  round: "50%"
spacing:
  gutter: "16px"
  gutter-desk: "32px"
  gap: "12px"
  stack: "14px"
  block: "22px"
  section: "70px"
components:
  button-primary:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.plaster}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.navy-mid}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.navy}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "56px"
  button-primary-on-navy:
    backgroundColor: "{colors.wood}"
    textColor: "{colors.navy-deep}"
    rounded: "{rounded.pill}"
    height: "52px"
  button-primary-on-navy-hover:
    backgroundColor: "{colors.wood-lt}"
  button-secondary-on-navy:
    backgroundColor: "transparent"
    textColor: "{colors.on-navy}"
    rounded: "{rounded.pill}"
    height: "52px"
  offer-pill:
    backgroundColor: "{colors.plaster-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "7px 14px 7px 8px"
  offer-pill-badge:
    backgroundColor: "{colors.wood}"
    textColor: "{colors.navy-deep}"
    rounded: "{rounded.pill}"
    height: "30px"
  sticky-bar:
    backgroundColor: "{colors.navy-deep}"
    padding: "10px 16px"
  paint-chip-card:
    rounded: "{rounded.card}"
    padding: "22px 20px"
---

# Design System: JPS Painting & Drywall Repair

## Overview

**Creative North Star: "The Stirred Can"**

The page is wet paint, not a brochure about paint. Its whole palette is lifted from the JPS seal (navy, brush-handle wood, plaster cream) and poured into one can: the hero ends in a living band of marbled paint the visitor can push with a finger, every navy section is joined to the plaster page by a paint edge that drips or rises, and the steps sit on a paint-chip card. The real seal floats in the paint, bobbing and tilting with the surface.

It is built for a thumb inside Facebook's in-app browser on cellular: one file, system fonts, no raster except the inlined seal, everything sized for a phone first and adapted upward at 560px and 900px. The voice is plain and heavy: uppercase 900-weight headings in a rounded system face echo the seal's lettering; body copy is short and set large (17px).

Depth comes from paint, not chrome. Grounds alternate plaster and deep navy; the only shadows are soft, navy-tinted and long. There is no black anywhere in the palette.

**Key Characteristics:**
- Two grounds only: plaster (light) and navy-deep (dark), joined by animated paint edges.
- Wood is the accent: emphasis words, the offer badge, primary buttons on navy, focus rings.
- Heavy uppercase rounded system sans for every heading; tabular numerals for the phone number.
- Pill buttons in a primary/secondary pair that share outline and height.
- One shared pointer and one rAF loop drive all paint motion; everything springs back.

## Colors

A three-material palette (navy, wood, plaster) sampled from the seal, with navy carrying structure and wood carrying the call to act.

### Primary
- **Seal Navy** (`navy`): headings on plaster, primary button fill on plaster, button outlines, the call icon ring, the paint band's top and middle bands, the third paint-chip step, text selection.
- **Deep Can Navy** (`navy-deep`): every dark section ground (services, about, footer, sticky bar), the paint band's bottom fill, and the `data-fill` of every drip/rise divider. This is the darkest value in the system.
- **Stirred Navy** (`navy-mid`): primary button hover on plaster, a mid band in the paint.

### Secondary
- **Brush-Handle Wood** (`wood`): primary button fill on navy, the 10% offer badge, focus outline (3px), service-row arrow on hover, caret, roller handle, the second paint band.
- **Light Wood** (`wood-lt`): primary-on-navy hover, the service-row arrow color, the "10% off any job" emphasis on navy, a thin paint streak.
- **Wood Ink** (`wood-ink`): the only wood dark enough for text on plaster; used for the emphasized half of the hero headline.

### Neutral
- **Plaster** (`plaster`, also `on-navy`): page ground, `theme-color`, text on navy, paint-chip footer strip.
- **Plaster Shade** (`plaster-2`): the offer pill ground.
- **Cream** (`cream`): a paint streak in the hero band and its fallback gradient.
- **Ink** (`ink`): body text on plaster.
- **Ink Muted** (`ink-2`): secondary text on plaster (brand subline, chip footer).
- **Navy Mist** (`on-navy-2`): secondary text on navy (ledes, row descriptions, fact labels, footer list), secondary button outline on navy; at 18% alpha it is the hairline divider between rows and facts.

### Named Rules
**The Never-Black Rule.** The darkest ground is `navy-deep`. No `#000`, no near-black, no grey grounds. Shadows are tinted `rgba(19,41,74,…)`.

**The Wood-Means-Act Rule.** On navy, the primary action is always wood on navy-deep; on plaster it is navy on plaster. Wood text on plaster must use `wood-ink`.

## Typography

**Display Font:** ui-rounded / SF Pro Rounded (system stack falling back to system-ui, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** same stack

**Character:** One rounded system family at two extremes: 900-weight uppercase for anything that names something, 400 sentence case for everything that explains. The system stack is a product constraint (no font downloads in the FB in-app browser on cellular); the uppercase heavy setting is the house style that ties it to the seal's lettering.

### Hierarchy
- **Display** (900, clamp(2.7rem, 13.2vw, 6rem), 0.92, uppercase): hero headline only, navy with the second clause in wood-ink.
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), 0.98, uppercase, balanced): section h2s. The closing h2 steps up to clamp(2.3rem, 10.5vw, 4.8rem).
- **Title** (900, clamp(1.25rem, 6vw, 1.6rem) in service rows, 1.5rem in paint chips, uppercase, 0 tracking): h3s.
- **Lede** (400, clamp(16px, 4.6vw, 20px), 1.4, max 34–44ch): hero pitch, closing paragraph, section ledes (ledes on navy use body size in navy-mist).
- **Body** (400, 17px, 1.55): default; row and chip descriptions drop to 16px/1.45.
- **Label** (700–800, 12–14px, 0.04–0.06em, uppercase): fact terms, the brand subline, the paint-chip footer strip, the demo's "Try it" tag.
- **Button** (800, 17px; 16px in the sticky bar, 0.01em).

### Named Rules
**The Shout-Then-Talk Rule.** Headings are 900 uppercase with tight leading (≤0.98); body is never bold-uppercase. Bold (800) inside body is reserved for facts the visitor must catch (bonded & insured, 10% off).

**The Tabular Number Rule.** The phone number and license always carry `font-variant-numeric: tabular-nums`.

## Layout

Phone is the base stylesheet. Content sits in a 1180px max container with a 16px gutter (32px from 900px). Stacks are single-column on phones.

- **560px:** button pairs go from full-width stacked to two auto-width buttons side by side.
- **900px:** top nav appears and the call icon becomes a pill with the number; the paint band grows (band 200px to 300px, head 60px to 90px) and the seal grows from 124px to 300px, riding the band at the right of the container; services splits 1.05fr / 1fr with the drywall demo sticky at top 30px; the paint chip becomes three columns; about splits 1.2fr / 1fr; the sticky bar is removed.

Rhythm: 12px gaps between paired controls, 14px between heading and lede, 22px before lists and button rows. Sections run roughly 36–44px vertical padding on phones and 70px on desktop; plaster sections sit flush on their dividers (top padding 0) and carry 70–110px bottom padding so the rise edge has room.

## Elevation & Depth

Depth is paint layering first: the hero band draws on two canvases with the seal sandwiched between them, so paint laps over the seal's base. Shadows are few, soft, long, and navy-tinted.

### Shadow Vocabulary
- **Card** (`--shadow: 0 18px 40px -18px rgba(19,41,74,.45)`): the paint-chip card.
- **Seal** (`0 14px 30px -12px rgba(19,41,74,.6)`): the seal disc wherever it floats (removed in the top-bar brand).
- **Bar lift** (`0 -12px 30px -14px rgba(19,41,74,.7)`): the sticky phone bar, casting upward.

### Named Rules
**The Paint-Is-Depth Rule.** New layering comes from paint over or under an object, not from new shadows or borders.

## Shapes

Everything a finger touches is a pill (999px): buttons, the offer pill and its badge, the reset button, the demo tag. Containers use one soft radius (18px): the paint chip and the drywall frame. The seal, call icon, and row arrows are circles. Edges between grounds are never straight: they are the animated drip or rise path. Focus rings round to 10px.

## Components

### Buttons
Thick, confident pills; one component in two roles.
- **Shape:** full pill (999px), 2px outline on both variants, min height 56px (52px in the sticky bar), 22px side padding, 20px stroke icon + label, 10px gap.
- **Primary (on plaster):** navy fill, plaster text; hover navy-mid.
- **Secondary (on plaster):** transparent, navy text and outline; hover 8% navy wash.
- **On navy:** primary becomes wood fill with navy-deep text and wood outline (hover wood-lt); secondary becomes plaster text with navy-mist outline (hover 8% plaster wash).
- **Press:** scale(.97), 0.2s `cubic-bezier(.2,.8,.2,1)`. Hover styles only under `(hover:hover)`.
- **Pairing:** Call is always primary, Text is always secondary, Call first. Text links are `sms:` with a pre-filled body from `data-msg`.

### Service Rows
Full-width tap rows on navy: h3 + one line in navy-mist, a 44px circular arrow at right in light wood on a 10% plaster wash. Hairline dividers (navy-mist at 18%). Hover slides the arrow 4px and fills it wood; press scales it to .92. Each row texts JPS with a service-specific message.

### Paint-Chip Card
The steps list styled as a paint sample card: 18px radius, card shadow, three swatches graded light to dark (`#dfe5ec`, `#7d93ad` with `#0f2340` text, then navy) each with a 900-weight tabular step number, and a plaster footer strip with uppercase labels. Stacked on phones, three columns at 900px.

### Offer Pill
Plaster-shade pill with a wood badge holding the figure ("10%") in 900 weight; 800-weight label.

### Sticky Phone Bar
Fixed bottom bar on navy-deep with Call (primary) and Text (secondary) in two equal columns, safe-area padded. Hidden (translateY 110%) while the hero buttons or closing buttons are on screen; slides in over 0.35s otherwise; removed at 900px. When hidden its links leave the tab order.

### Navigation
Phone: seal (44px) + two-line wordmark (900 uppercase 14px, subline 12px ink-muted) and a 48px circular call button. Desktop: 52px seal, inline 800-weight text nav (underline on hover), call button widens to a pill with the number.

### Signature: Hero Paint Band
A stirred can drawn on two canvases from one simulation. `BANDS` (top to bottom) is `[color, highlight, thickness share, wave amp, wavenumber, speed]`: navy, wood, navy-mid, cream, navy, wood-lt, navy-deep (the last fills to the bottom). Bands 1, 3, 5 are **streaks**: ribbons whose thickness swells and pinches to nothing as they cross the navy. Each band is a vertical gradient from its highlight into its color; non-streak bands get a **wet sheen**: two broad soft strokes (20px and 9px at 10% light-blue alpha) 12px under the crest. Back canvas draws bands 0–1, front draws 2, 3, 4, 6, 5, so paint covers the seal's base.
- **Pointer:** a shared pointer (mouse move, touch) pushes each surface point within `PUSH_R` and **carries** paint along with the pointer's velocity; per-point springs (`STIFF`, `DAMP`) pull it back. Offsets clamp at ±90px.
- **Splash:** when the top surface is flicked upward faster than `SPLASH_V`, a navy (75%) or wood (25%) droplet is thrown, falls under gravity, and dents the surface where it lands (max 40 drops, 50ms cooldown).
- **Floating seal:** the seal bobs (70% of local surface offset) and tilts (40% of local slope) with band 2.
- **No-JS fallback:** a static striped gradient of the same colors with a wavy top.

### Signature: Drip / Rise Dividers
SVG paths rebuilt each frame wherever a navy section meets plaster. **Drip** hangs below a navy section (navy-deep fill, base at 20% of height): a gently waving edge with `DRIPS` teardrop drips that grow over 85% of a cycle up to `DRIP_MAX`, release a drop that falls, then retract; the pointer sways them. **Rise** climbs into the next navy section from below (base at 55%, waves the opposite way, no drips), positioned absolutely at the section bottom. Both use the same spring edge as the hero band. Default height 74px.

### Signature: Drywall Roller Demo
A 4:3 canvas in an 18px frame showing procedurally drawn damaged drywall (hole with torn paper rim, cracks, nail pops, peeling seam tape, scuffs; seeded so it is identical every load). Dragging rolls a stippled fresh-paint stroke `ROLLER` px wide with a drawn roller (cream cover, grey frame, wood handle). Once coverage passes `DONE_AT`, the caption turns into the call to action; "Reset wall" clears it. The first time it is 60% in view, one slow demo stroke rolls across by itself.

### Tunables (`CFG` at the top of the script)
`SPEED` and `SWELL` (ambient speed and wave height), `STEP_PHONE/DESK` (surface point spacing 14/12px), `PUSH_R_PHONE/DESK` (reach 70/120px), `PUSH` (2600), `CARRY` (9), `STIFF`/`DAMP` (34/5.2; lower damp = more wobble), `SPLASH_V` (230), `DRIPS_PHONE/DESK` (4/7), `DRIP_MAX` (46px), `ROLLER_PHONE/DESK` (46/64px), `DONE_AT` (0.86). Change these before touching the simulation code.

### Reduced Motion
Under `prefers-reduced-motion: reduce` the loop never starts: the band and every divider render one still frame (t = 2.3) and redraw on resize; the demo stroke does not autoplay (dragging still paints); CSS transitions on buttons, arrows, and the bar are removed; smooth scrolling is off. Off-screen canvases and dividers stop animating via IntersectionObserver.

## Do's and Don'ts

### Do:
- **Do** reuse the hero paint band, the drip/rise dividers, and their spring behavior exactly on any new page, driven by the same `CFG`, shared pointer, and single loop. Don't fork the simulation per page.
- **Do** join every navy section to plaster with a drip (navy above) or rise (navy below) divider filled `navy-deep`.
- **Do** keep Call primary and Text secondary, in that order, with pre-filled `sms:` bodies.
- **Do** design at phone width first; add only `min-width: 560px` and `min-width: 900px` adaptations.
- **Do** keep every tap target at least 44px (buttons 52–56px).
- **Do** keep a still, non-JS fallback for any new paint surface and a single-frame render under reduced motion.

### Don't:
- **Don't** use black or grey grounds, black text, or black shadows; the darkest value is `navy-deep`.
- **Don't** draw thin light highlight lines on paint crests or edges; wet sheen is broad and soft (9px+ strokes at about 10% alpha) or a gradient stop.
- **Don't** separate sections with straight edges or rules; the boundary is paint.
- **Don't** add a second accent color or a web font; the palette is the seal's and the type is the system stack.
- **Don't** put wood text directly on plaster except `wood-ink`.
- **Don't** add stock photography, icon-card grids, or testimonial carousels; the only image is the seal.
