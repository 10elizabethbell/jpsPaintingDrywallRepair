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
  chip-light: "#dfe5ec"
  chip-blue: "#7898c0"
  chip-blue-ink: "#0f2340"
  photo-paper: "#fbf8f1"
  painters-tape: "rgba(84,126,184,.93)"
typography:
  scale:
    label-sm: "12px"
    label: "13px"
    small: "14px"
    meta: "15px"
    body-sm: "16px"
    body: "17px"
    name: "18px"
    swash: "21px"
    chip-title: "1.5rem"
    chip-numeral: "2.4rem"
  display:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.7rem, min(13.2vw, 15svh), 6rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  headline-close:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.3rem, 10.5vw, 4.8rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  title:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.25rem, 6vw, 1.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "0"
  callout:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.1rem, 5.2vw, 1.4rem)"
    fontWeight: 900
    lineHeight: 1.05
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
  photo: "3px"
  paper: "6px"
  focus: "10px"
  card: "18px"
  pill: "999px"
  round: "50%"
spacing:
  gutter: "16px"
  gutter-desk: "32px"
  tight: "10px"
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
  swash-label:
    backgroundColor: "{colors.wood}"
    textColor: "{colors.navy-deep}"
    padding: "3px 14px 4px"
  fb-callout:
    backgroundColor: "{colors.wood}"
    textColor: "{colors.navy-deep}"
    rounded: "{rounded.card}"
    padding: "14px"
  fb-callout-arrow:
    backgroundColor: "{colors.navy-deep}"
    textColor: "{colors.wood-lt}"
    rounded: "{rounded.round}"
    size: "44px"
  taped-photo:
    backgroundColor: "{colors.photo-paper}"
    rounded: "{rounded.paper}"
    padding: "10px"
  paint-chip-card:
    rounded: "{rounded.card}"
    padding: "22px 20px"
  paint-chip-step-1:
    backgroundColor: "{colors.chip-light}"
    textColor: "{colors.ink}"
  paint-chip-step-2:
    backgroundColor: "{colors.chip-blue}"
    textColor: "{colors.chip-blue-ink}"
  paint-chip-step-3:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
  paint-palette:
    backgroundColor: "{colors.plaster-2}"
    rounded: "{rounded.pill}"
    padding: "10px 7px"
  paint-brush-button:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.plaster}"
    rounded: "{rounded.round}"
    size: "52px"
  paint-brush-button-open:
    backgroundColor: "{colors.wood}"
    textColor: "{colors.navy-deep}"
  sticky-bar:
    backgroundColor: "{colors.navy-deep}"
    padding: "10px 16px"
---

# Design System: JPS Painting & Drywall Repair

## Overview

**Creative North Star: "The Stirred Can"**

The page is wet paint, not a brochure about paint. Its whole palette is lifted from the JPS seal (navy, brush-handle wood, plaster cream) and poured into one can: the hero ends in a living band of marbled paint the visitor can push with a finger, every navy section is joined to the plaster page by a paint edge that drips or rises, and the steps sit on a paint-chip card. The real seal floats in the paint: it surfaces out of it on load, bobs and tilts with the surface, and dunks when tapped. The whole page is a wall the visitor can paint.

It is built for a thumb inside Facebook's in-app browser on cellular: one file, system fonts, no raster except the inlined seal and one of JPS's own job photos, everything sized for a phone first and adapted upward at 560, 720, 900 and 1300px. The voice is plain and heavy: uppercase 900-weight headings in a rounded system face echo the seal's lettering; body copy is short and set large (17px).

Depth comes from paint, not chrome. Grounds alternate plaster and deep navy; the only shadows are soft, navy-tinted and long. There is no black anywhere in the palette.

**Key Characteristics:**
- Two grounds only: plaster (light) and navy-deep (dark), joined by animated paint edges.
- Wood is the accent: emphasis words, the 10% off brushstroke, the Facebook callout card, primary buttons on navy.
- Heavy uppercase rounded system sans for every heading; tabular numerals for the phone number.
- Pill buttons in a primary/secondary pair that share outline and height.
- One shared pointer and one rAF loop drive all paint motion; everything springs back.

## Colors

A three-material palette (navy, wood, plaster) sampled from the seal, with navy carrying structure and wood carrying the call to act. The blues outside the seal (chip blue, painter's tape) are tints of the same navy hue, read as materials, not as a second accent.

### Primary
- **Seal Navy** (`navy`): headings on plaster, primary button fill on plaster, button outlines, the focus ring on plaster, the call icon ring, the brush button, the paint band's top and middle bands, the third paint-chip step, text selection.
- **Deep Can Navy** (`navy-deep`): every dark section ground (services, about, footer, sticky bar), the paint band's bottom fill, the `data-fill` of every drip/rise divider, the daub outlines, the Facebook mark and arrow discs, the paint tip and hint pills. This is the darkest value in the system.
- **Stirred Navy** (`navy-mid`): primary button hover on plaster, a mid band in the paint.

### Secondary
- **Brush-Handle Wood** (`wood`): primary button fill on navy, the 10% off brushstroke, the Facebook callout card, the open brush button, the active wall-demo ring and Done button, service-row arrow on hover, caret, roller handle, the second paint band.
- **Light Wood** (`wood-lt`): the focus ring and text selection on navy, primary-on-navy hover, the service-row and callout arrows, "10% off any job" on navy, the active-daub dot, a thin paint streak.
- **Wood Ink** (`wood-ink`): the only wood allowed as text on plaster, and only at headline/display size: the second clause of the hero h1 and "needs work?" in the closing h2.

### Tertiary
- **Chip Light** (`chip-light`): the first, palest paint-chip step.
- **Chip Blue** (`chip-blue`): the middle paint-chip step, always with `chip-blue-ink` text; also the "light blue" daub in the palette.
- **Chip Blue Ink** (`chip-blue-ink`): text on chip blue only.
- **Painter's Tape** (`painters-tape`): the two strips holding the job photo to the wall.

### Neutral
- **Plaster** (`plaster`, also `on-navy`): page ground, `theme-color`, text on navy, paint-chip footer strip, the ring around the brush button.
- **Plaster Shade** (`plaster-2`): the paint palette pill, the job photo's loading ground.
- **Photo Paper** (`photo-paper`): the print border of the taped job photo.
- **Cream** (`cream`): a paint streak in the hero band, its fallback gradient, and the cream daub.
- **Ink** (`ink`): body text on plaster.
- **Ink Muted** (`ink-2`): secondary text on plaster (brand subline, chip footer, post meta).
- **Navy Mist** (`on-navy-2`): secondary text on navy (ledes, row descriptions, fact labels, footer list and demo line), secondary button and reset outline on navy; at 18% alpha it is the hairline between rows, facts and the footer's demo line.

### Named Rules
**The Never-Black Rule.** The darkest ground is `navy-deep`. No `#000`, no near-black, no grey grounds. Shadows on plaster are tinted `rgba(19,41,74,…)`; the only deeper value is the shadow cast on the navy ground itself (`rgba(8,20,38,.6)`), still navy.

**The Wood-Means-Act Rule.** On navy, the primary action is wood on navy-deep; on plaster it is navy on plaster. Wood as a fill on plaster carries navy-deep text (the 10% brushstroke, the Facebook callout). Wood as text on plaster is `wood-ink`, at headline size only.

**The Ring-Matches-Ground Rule.** Focus is a 3px ring offset 3px: navy on plaster, light wood on navy.

## Typography

**Display Font:** ui-rounded / SF Pro Rounded (system stack falling back to system-ui, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** same stack

**Character:** One rounded system family at two extremes: 900-weight uppercase for anything that names something, 400 sentence case for everything that explains. The system stack is a product constraint (no font downloads in the FB in-app browser on cellular); the uppercase heavy setting is the house style that ties it to the seal's lettering. Weights in use are 400, 700, 800 and 900 only.

### Hierarchy
- **Display** (900, clamp(2.7rem, min(13.2vw, 15svh), 6rem), 0.92, -0.025em, uppercase): hero headline only, navy with the second clause in wood-ink. The 15svh term keeps it on the first screen of a landscape phone.
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), 0.98, uppercase, balanced): section h2s. The closing h2 steps up to the close size (clamp(2.3rem, 10.5vw, 4.8rem)).
- **Title** (900, uppercase, 0 tracking): service-row h3s (clamp(1.25rem, 6vw, 1.6rem)), paint-chip h3s (1.5rem), the Facebook callout title (clamp(1.1rem, 5.2vw, 1.4rem), 1.05).
- **Numeral** (900, 2.4rem, 0.9, tabular): paint-chip step numbers.
- **Lede** (400, clamp(16px, 4.6vw, 20px), 1.4, max 34–44ch): hero pitch, section ledes (ledes on navy use body size in navy mist). The closing paragraph runs clamp(17px, 4.6vw, 20px) at 36ch.
- **Body** (400, 17px, 1.55): default and the hero offer line (800, 1.3). Row, chip, caption and post text drop to 16px/1.45–1.5. Footer runs 15px.
- **Offer swash** (900, 21px, navy-deep on wood): "10% off" only.
- **Meta** (800 15px name / 700 14px source): the Facebook post byline; the footer business name is 900 uppercase 18px.
- **Label** (700–800, 12–14px, 0.04–0.06em, uppercase): fact terms (14px), the brand subline (12px), the paint-chip footer strip (13px), the demo's "Try it" tag and the Wipe tool (12px).
- **Button** (800, 17px; 16px in the sticky bar and wall mode button, 14px reset and tip/hint pills; 0.01em).

### Named Rules
**The Shout-Then-Talk Rule.** Headings are 900 uppercase with tight leading (≤0.98, 1.05 in the callout); body is never bold-uppercase. Bold (800) inside body is reserved for facts the visitor must catch (bonded & insured, free estimates, 10% off).

**The Tabular Number Rule.** The phone number and license always carry `font-variant-numeric: tabular-nums`.

## Layout

Phone is the base stylesheet. Content sits in a 1180px max container whose gutter is the larger of 16px and the safe-area insets (32px and the insets from 900px). Stacks are single-column on phones.

- **560px:** button pairs go from full-width stacked to two auto-width buttons side by side; the band grows (200 to 240px, head 60 to 70px) and the hero seal grows from 124px to 180px.
- **720px:** two-column splits begin: services splits 1.05fr / 1fr (gap 40px) with the drywall demo sticky at top 30px; the paint chip becomes three columns with the footer strip spanning; about splits 1.2fr / 1fr with the seal up to 320px.
- **900px:** top nav appears and the call icon becomes a pill with the number; the band reaches 300px (head 90px) with a 300px seal riding it at the right of the container; the close splits 1.2fr / 1fr (gap 64px) with its left column sticky at top 40px; the sticky bar is removed. Between 900 and 1099px the closing buttons stack (max 420px).
- **1300px:** the paint palette docks in the right margin, clear of the 1180px content.
- **Landscape phones** (max-height 500px): top bar and hero padding tighten and the hero buttons sit 14px under the offer so the first screen keeps the pitch and the buttons.

Rhythm: hero pitch 10px under the h1, offer 12px under the pitch, buttons 22px under the offer. 10px for icon gaps and bar/palette gaps, 12px between paired controls, 14px between heading and lede, 22px before lists and button rows. Sections run 36–44px vertical padding on phones and 70px on desktop; plaster sections sit flush on their dividers (top padding 0) and carry 70–110px bottom padding so the rise edge has room.

## Elevation & Depth

Depth is paint layering first: the hero band draws on two canvases with the seal sandwiched between them, so paint laps over the seal's base; user paint sits on a page canvas under all content. Shadows are few, soft, long, and navy-tinted.

### Shadow Vocabulary
- **Card** (`--shadow: 0 18px 40px -18px rgba(19,41,74,.45)`): the paint-chip card and the Facebook callout.
- **Seal** (`0 14px 30px -12px rgba(19,41,74,.6)`): the seal disc wherever it floats (removed in the top bar and post byline).
- **Taped print** (`0 20px 40px -18px rgba(19,41,74,.5)`): the taped job photo; the tape strips cast `0 2px 4px rgba(19,41,74,.18)`.
- **Float** (`0 14px 30px -12px rgba(19,41,74,.7)`): fixed paint tools: the palette pill, the paint tip, the hint label (the brush button runs .75, the wall mode button .8).
- **Wall frame** (`0 22px 44px -20px rgba(8,20,38,.6)`): the drywall demo, the one shadow cast onto the navy ground.
- **Bar lift** (`0 -12px 30px -14px rgba(19,41,74,.7)`): the sticky phone bar, casting upward.

### Named Rules
**The Paint-Is-Depth Rule.** New layering comes from paint over or under an object, not from new shadows or borders.

## Shapes

Everything a finger touches is a pill (999px) or a circle: buttons, the reset and Done buttons, the palette; the demo tag, paint tip and hint pills match. Containers use one soft radius (18px): the paint chip, the Facebook callout, the drywall frame. The job photo is the exception that proves it is a print: 6px paper corners, 3px photo corners, rotated -1.4deg. The seal, call icon, arrows, brush button and tools are circles. The 10% swash is a ragged brushstroke, not a pill. Edges between grounds are never straight: they are the animated drip or rise path. Focus rings round to 10px.

## Components

### Buttons
Thick, confident pills; one component in two roles.
- **Shape:** full pill (999px), 2px outline on both variants, min height 56px (52px in the sticky bar), 22px side padding, 20px stroke icon + label, 10px gap.
- **Primary (on plaster):** navy fill, plaster text; hover navy-mid.
- **Secondary (on plaster):** transparent, navy text and outline; hover 8% navy wash.
- **On navy:** primary becomes wood fill with navy-deep text and wood outline (hover wood-lt); secondary becomes plaster text with navy-mist outline (hover 8% plaster wash).
- **Press:** scale(.97), 0.2s `cubic-bezier(.2,.8,.2,1)`. Hover styles only under `(hover:hover)`.
- **Pairing:** "Call for a free estimate" is always primary, "Text 609-312-3091" always secondary, Call first; the hero and closing pairs carry the same copy. Text links are `sms:` with a pre-filled body from `data-msg`.

### Offer Swash
"10% off" sits in a ragged tan brushstroke (an inline SVG in `wood` with a lighter streak, rotated -1.5deg) at 900 21px navy-deep, inside an 800-weight 17px offer line. It is a label, not a control. On load it brushes on left to right (0.55s `cubic-bezier(.16,1,.3,1)`, 0.5s delay).

### Service Rows
Full-width tap rows on navy: h3 + one line in navy-mist, a 44px circular arrow at right in light wood on a 10% plaster wash. Hairline dividers (navy-mist at 18%). Hover slides the arrow 4px and fills it wood; press scales it to .92. Each row texts JPS with a service-specific message.

### Paint-Chip Card
The steps list styled as a paint sample card: 18px radius, card shadow, three swatches graded light to dark (chip light with ink, chip blue with chip-blue ink, then navy with plaster) each with a 900-weight tabular step number, and a plaster footer strip with uppercase labels. Stacked on phones, three columns at 720px.

### Facebook Callout and Taped Photo
The closing column's second half. The callout is a wood card (18px, card shadow) on a 46px / 1fr / 44px grid (52px mark at 900): a navy-deep disc with the plaster Facebook mark, a 900 uppercase title with a 16px 700 subline, and a navy-deep arrow disc with a light-wood arrow at rest that slides 4px on hover; press scales .98. Below it, JPS's latest job photo is a print taped to the wall: photo-paper border (10px padding), two painter's-tape strips (80 × 28px at -34deg and 30deg) over the top corners, rotated -1.4deg and straightening on hover, with a seal byline and the post's text.

### Sticky Phone Bar
Fixed bottom bar on navy-deep with Call (primary) and Text (secondary) in two equal columns, safe-area padded. Hidden (translated 100% + 24px) while the hero buttons or closing buttons are on screen. It enters in 0.38s `cubic-bezier(.16,1,.3,1)` and exits faster, 0.2s `cubic-bezier(.4,0,1,1)`; removed at 900px. When hidden its links leave the tab order.

### Navigation
Phone: seal (44px) + two-line wordmark (900 uppercase 14px, subline 12px ink-muted) and a 48px circular call button. Desktop: 52px seal, 16px wordmark, inline 800-weight text nav (underline on hover), call button widens to a pill with the number.

### Signature: Hero Paint Band
A stirred can drawn on two canvases from one simulation. `BANDS` (top to bottom) is `[color, highlight, thickness share, wave amp, wavenumber, speed]`: navy, wood, navy-mid, cream, navy, wood-lt, navy-deep (the last fills to the bottom). Bands 1, 3, 5 are **streaks**: ribbons whose thickness swells and pinches to nothing as they cross the navy. Each band is a vertical gradient from its highlight into its color; non-streak bands get a **wet sheen**: two broad soft strokes (20px and 9px at 10% light-blue alpha) 12px under the crest. Back canvas draws bands 0–1, front draws 2, 3, 4, 6, 5, so paint covers the seal's base.
- **Pointer:** a shared pointer (mouse move, touch) pushes each surface point within `PUSH_R` and **carries** paint along with the pointer's velocity; per-point springs (`STIFF`, `DAMP`) pull it back. Offsets clamp at ±90px.
- **Slosh:** scrolling heaves the surface; the band lags the page and settles, strongest on the top bands.
- **Splash:** when the top surface is flicked upward faster than `SPLASH_V`, a navy (75%) or wood (25%) droplet is thrown, falls under gravity, and dents the surface where it lands (max 40 drops, 50ms cooldown).
- **Floating seal:** the seal starts 70px under the paint and surfaces after 0.35s on load; it bobs (70% of local surface offset) and tilts (40% of local slope) with band 2. A tap dunks it (a spring of 38/4.2), and when it breaks the surface again it throws a splash and dents the paint.
- **No-JS fallback:** a static striped gradient of the same colors with a wavy top.

### Signature: Drip / Rise Dividers
SVG paths rebuilt each frame wherever a navy section meets plaster. **Drip** hangs below a navy section (navy-deep fill, base at 20% of height): a gently waving edge with `DRIPS` teardrop drips that grow over 85% of a cycle up to `DRIP_MAX`, release a drop that falls and thins to nothing before the divider's edge (it is never sliced off), then retract; the pointer sways them. **Rise** climbs into the next navy section from below (base at 55%, waves the opposite way, no drips), positioned absolutely at the section bottom. Both use the same spring edge as the hero band. Default height 74px.

### Signature: Drywall Roller Demo
A 4:3 canvas in an 18px frame (width capped so the whole frame fits the viewport height) showing procedurally drawn damaged drywall (hole with torn paper rim, cracks, nail pops, peeling seam tape, scuffs; seeded so it is identical every load). Dragging rolls a stippled fresh-paint stroke `ROLLER` px wide with a drawn roller (cream cover, grey frame, wood handle). On touch screens the wall is a mode: a navy-deep "Paint this wall" pill starts it (wood ring, drags paint, page holds still) and a wood Done button ends it. Past `DONE_AT` the last specks fill in by themselves over 0.45s and the caption fades into the call to action; "Reset wall" clears it. The first time it is 60% in view, one slow demo stroke rolls across by itself.

### Signature: Paint the Page
The whole site is a wall the visitor can paint.
- **Layer:** one canvas spans the full document height at `z-index:0`, under all content; content blocks sit at `z-index:1`. Paint shows on the plaster and navy grounds, behind text and buttons, so contact actions can't be painted out. The canvas is not allocated until a colour is picked.
- **Palette:** a plaster-shade pill with a 2px navy ring and the float shadow, holding four 44px daubs (paint blobs with a drip, outlined 2px navy-deep): navy, tan (wood), light blue (chip blue), cream. Then Wipe (a 44px circle with a 40% navy ring, 800 12px uppercase), disabled at 40% opacity until something is painted, and a close button shown while a brush is up. The active daub scales 1.18 with a light-wood dot under it.
- **Placement:** from 1300px the palette docks in the right margin, centred vertically, always open, headed by a "Paint" label. Below 1300px it folds into a 52px navy brush button (plaster ring; wood with navy-deep when open) at the bottom right, riding above the sticky bar on phones (24px from the corner at 900px). Opening it squeezes the daubs out bottom-up (0.34s, 35ms stagger). A one-time "Paint the page" hint pill (navy-deep, plaster ring) slides out beside the brush button for 4.5s.
- **Brush mode:** picking a colour turns on `body.painting`, which shows a full-screen catcher (`touch-action:none`) so drags paint instead of scrolling. Close, re-tapping the active colour, or Esc puts the brush down. A navy-deep tip slides down from the top saying how to get scrolling back.
- **Brush look:** a wet body laid underneath with `destination-over`, plus `BRISTLES` continuous flat-ended streaks in light and dark shades of the colour. The brush runs dry over `LOAD_RUN` px: the body stops and bristles drop out into dry streaks, then it reloads on the next stroke. While loaded (over 70%) and moving mostly level, the stroke grows **runs**: up to 8 drips that sag down 20–70px, slow, and stop on a bead.

### Tunables (`CFG` at the top of the script)
`SPEED` and `SWELL` (ambient speed and wave height), `STEP_PHONE/DESK` (surface point spacing 14/12px), `PUSH_R_PHONE/DESK` (reach 70/120px), `PUSH` (2600), `CARRY` (9), `STIFF`/`DAMP` (34/5.2; lower damp = more wobble), `SPLASH_V` (230), `DRIPS_PHONE/DESK` (4/7), `DRIP_MAX` (46px), `ROLLER_PHONE/DESK` (46/64px), `DONE_AT` (0.86), `BRUSH_DESK/PHONE` (34/26px), `BRISTLES` (14), `LOAD_RUN` (1400px), `MAX_PX` (9e6, the page-canvas pixel cap for phones). Change these before touching the simulation code.

### Reduced Motion
Under `prefers-reduced-motion: reduce` the loop never starts: the band and every divider render one still frame (t = 2.3) and redraw on resize; the seal does not surface or dunk; the demo stroke does not autoplay (dragging still paints) and a finished wall fills at once; runs are drawn already settled; the swash and the daub squeeze do not animate. Transitions keep only colour and opacity feedback (0.15s); press scales are removed; smooth scrolling is off. Off-screen canvases and dividers stop animating via IntersectionObserver.

## Do's and Don'ts

### Do:
- **Do** reuse the hero paint band, the drip/rise dividers, and their spring behavior exactly on any new page, driven by the same `CFG`, shared pointer, and single loop. Don't fork the simulation per page.
- **Do** join every navy section to plaster with a drip (navy above) or rise (navy below) divider filled `navy-deep`.
- **Do** keep Call primary and Text secondary, in that order, with pre-filled `sms:` bodies.
- **Do** design at phone width first; adapt only at `min-width` 560, 720, 900 and 1300px.
- **Do** keep every tap target at least 44px (buttons 52–56px).
- **Do** keep a still, non-JS fallback for any new paint surface and a single-frame render under reduced motion.
- **Do** keep the footer's honest demo line: "Demo one-pager — free sample."

### Don't:
- **Don't** use black or grey grounds, black text, or black shadows; the darkest value is `navy-deep`.
- **Don't** draw thin light highlight lines on paint crests or edges; wet sheen is broad and soft (9px+ strokes at about 10% alpha) or a gradient stop.
- **Don't** separate sections with straight edges or rules; the boundary is paint.
- **Don't** add a second accent hue or a web font; the palette is the seal's (plus navy-hued material tints) and the type is the system stack.
- **Don't** put wood text directly on plaster except `wood-ink` at headline size.
- **Don't** add stock photography, icon-card grids, or testimonial carousels; the only images are the seal and JPS's own job photos, taped up as prints.
