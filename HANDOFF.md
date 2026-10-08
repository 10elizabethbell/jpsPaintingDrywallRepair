# JPS Painting & Drywall Repair LLC — handoff at ~60%

**Live file:** index.html (single file, ~86 KB, ~30 KB of it the seal image) · **Repo:** https://github.com/10elizabethbell/jpsPaintingDrywallRepair · **Built:** 2026-10-08 from Muse brief of 2026-10-08 (Facebook group post, "NJ Seeking Contractors")

## What's built
- **World: a stirred can of wet paint** in the seal's own colors (navy, brush-handle wood, plaster cream). Ground is plaster cream; dark sections are deep navy `#13294a`, not black.
- **Signature motion:** the hero ends in a band of marbled paint on canvas: four navy layers with a soft wet sheen, plus wood and cream streaks that swell, pinch to nothing and cross under and over them. Mouse or finger shoves and drags the paint, it springs back with a wobble, and a hard upward flick throws droplets that fall back in and dent the surface. The real JPS seal floats in the paint, bobbing and tilting with the surface (two canvases, so paint laps over its base).
- **Carried everywhere:** section dividers are live paint edges. Navy drips grow, drop a bead and pull back, and the pointer sways them. Rising wavy edges lead into the navy sections.
- **Sections:** hero ("Fresh paint. Smooth walls.", pitch line, "10% off for small businesses" pill, Call + Text) → services (4 rows; each whole row is a pre-filled text) + **drywall demo** (a damaged wall you roll fresh paint over; one auto-stroke plays the first time it scrolls into view) → how it works (a paint-chip card, three one-line steps) → local to Barnegat (owner, license, bonded and insured, phone, big seal) → close (Call / Text / Facebook) → footer with "Demo one-pager — free sample."
- **Contact:** `tel:+16093123091` is primary everywhere; `sms:` with pre-filled bodies per service is secondary; Facebook page link in the close. On phones a sticky Call | Text bar appears once the hero buttons scroll away and hides at the close section.
- Tunables are at the top of the script in `CFG` (speed, swell, push radius and force, spring, drip count and length, roller size).

## Found beyond the brief (verify with the owner)
Muse couldn't read the Facebook page. The crawler user agent could: the profile picture is a **photo of their sign**, and the page bio opens "Hi, I'm Joseph Sullivan!". Taken from that:
- **Phone 609-312-3091**: printed on the sign. Used as the main contact. Brief said phone unknown.
- **LIC# 13VH14131900**: printed under the seal. The 13VH prefix looks like an NJ Home Improvement Contractor registration (inferred, not checked against the NJ lookup).
- **Owner Joseph Sullivan**: page bio (truncated after "I've been working in the home improvement…").
- **Logo/colors**: the seal itself. The page uses a crop of that photo, unsquashed from a slight angle, as the logo (`src-assets/seal.webp`, sidecar `seal.webp.json` holds provenance; `src-assets/` is gitignored).

## Assumptions I made
- **Colors** sampled by eye from a photo of a sign: navy `#1e3a5c`, wood `#c58d52`, plaster `#f1ebdf`. The real vector logo may differ.
- **Texts accepted?** Unknown. Call is primary; text is the secondary option on every pair.
- **Service descriptions** are plain definitions, not their words: "Inside your home or business", "The outside of your house or storefront", "Holes, cracks and dings patched, then painted to match". The fourth row, "Small-business makeovers", comes from their post ("Have a small business and thinking about a makeover paint job").
- **10% off** comes from one group post (2026-10-08) aimed at small-business owners ("Have a small business and thinking about a makeover paint job, Receive 10% off any job"). The page scopes it to small businesses. Confirm it's still running and whether homeowners get it too.
- **Area:** only "Barnegat, NJ" (no towns invented). The street address from BuildZoom is left off; it looks like a home address.
- **Headline** "Fresh paint. Smooth walls." is mine.
- How-it-works is titles only (Call or text / Free estimate / Fresh walls). No claims about site visits or turnaround times.

## Placeholders and gaps
- **No photos of their work.** The only post photo is login-walled. The drywall demo fills the proof slot and is labeled "Try it" (it's an obvious illustration). **Photos wanted**, especially before/after drywall patches.
- No reviews, prices, hours, years in business or email: the page says nothing about them.
- The logo is a photo crop with levels adjusted so the sign's grey reads as cream. A clean vector of the seal would sharpen the hero and top bar.

## Questions for the owner
1. Is 609-312-3091 OK to text, or calls only?
2. Is the 10% off still running? For everyone or small businesses only?
3. Which towns besides Barnegat do you cover (Manahawkin, Waretown, Forked River, LBI…)?
4. Can you send 5–10 job photos, ideally before/after pairs of drywall patches?
5. Do you have the logo file (vector or high-res)?
6. Hours, and an email for a quote form?
7. Anything else you do: ceilings, trim, cabinets, power washing, wallpaper removal? (Not listed on the page because it's not confirmed.)

## Ideas not built (yours to pick)
- **Runner-up world: drywall mud & trowel.** A wall of cracks in the hero that your finger skims smooth with joint compound, and wet mud ridges as dividers. Closer to the "repair" half and more unusual, but less colorful than the paint can.
- Before/after sliders in the services rows once photos exist (taste §4 recipe).
- `book.html` estimate form composed into a text (needs an email/phone confirmation of texting).
- Splatter into the "Got a wall" headline when droplets fly near it; paint "bleeding" up into the hero text on a strong drag.
- Color-swatch picker on the drywall demo (roll the wall in navy, wood, cream).
- The phone seal is fairly deep in the paint (about 55% visible). Raise it if the logo should read more on the first screen; it has to clear the Text button above it.
- The finish reviewer noted the drops from the divider drips just vanish. They could land and pool instead.
- Google Business Profile setup: they have no Maps listing, which is a bigger lead source than the site. Worth pitching alongside it.

## Review round
One Impeccable finish review (2026-10-08). Applied all 8 material fixes:
- The sticky bar was unreadable (navy on navy).
- The 10% claim was broader than the post.
- The wood headline failed contrast (now `--wood-ink` #9c6531).
- The seal touched the Text button and didn't ride the paint.
- Drops landed as stray dots in headings.
- The seal asset read grey.
- The steps were template filler.
- The paint band read as waves, not paint (marbling and sheen added).

## Not verified
- Real-device touch (iOS Safari, Android Chrome, Facebook in-app browser): tested only with simulated touch events in headless Chrome.
- `sms:` pre-filled body on real iOS/Android; `tel:` handoff.
- Frame rate on older phones (hero ~30 points × 7 ribbons per frame + 2 SVG dividers on phones).
- Headless desktop screenshots drop the hero canvas (known quirk), so desktop motion was captured through an iframe instead. The sticky bar was checked with its transition switched off, because headless doesn't finish CSS transitions under virtual time.
- Impeccable detector ran in degraded regex mode (parser modules missing), so its clean result is an undercount.
