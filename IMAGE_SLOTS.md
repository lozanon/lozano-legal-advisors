# Lozano Legal Advisors — Website Image Slots

Photographer brief reference. Every photo position on the firm site, what it needs to show, aspect ratio, display dimensions, and alt text.

The photographer brief in Master Strategy Part 10 specifies 10+ edited deliverables. This document maps each deliverable to a site location.

---

## Slot inventory (10 positions, 6 unique shots)

### Slot A — Hero portrait (tight crop)
- **Used on:** About (top of page, anchoring the credentials section)
- **Shot type:** Head and shoulders, direct eye contact, neutral thoughtful expression
- **Aspect ratio:** 4:5 portrait
- **Display dimensions:** 480 × 600 (desktop), scales down responsively
- **Source file:** Photographer delivers 4000 × 5000 (5000px on long edge per brief)
- **Alt text:** "Norris Lozano, founder of Lozano Legal Advisors PLLC"
- **Filename target:** `norris-portrait-hero.jpg`

### Slot B — Editorial three-quarter
- **Used on:** Home (mid-page, after the six-practice-areas section, before "How we work")
- **Shot type:** From chest up, slight off-axis, more candid read than Slot A
- **Aspect ratio:** 4:5 portrait
- **Display dimensions:** 400 × 500
- **Source file:** 4000 × 5000
- **Alt text:** "Norris Lozano"
- **Filename target:** `norris-portrait-editorial.jpg`

### Slot C — Environmental at desk
- **Used on:** About (mid-page, anchoring the "How I work" section); Home (alternate to Slot B if a wider visual reads better in layout)
- **Shot type:** Half figure at desk or bookshelf, reviewing document — context shot
- **Aspect ratio:** 3:2 landscape
- **Display dimensions:** 900 × 600
- **Source file:** 5000 × 3333
- **Alt text:** "Norris Lozano at work"
- **Filename target:** `norris-environmental-desk.jpg`

### Slot D — Environmental at bookshelf
- **Used on:** Practice area pages (Tax Resolution and Corporate & Partnership benefit most from a library / book-lined backdrop)
- **Shot type:** Standing or seated at a bookshelf, holding or referencing a volume — gravitas shot
- **Aspect ratio:** 3:2 landscape
- **Display dimensions:** 720 × 480
- **Source file:** 5000 × 3333
- **Alt text:** "Norris Lozano, Lozano Legal Advisors"
- **Filename target:** `norris-environmental-bookshelf.jpg`

### Slot E — Utility shot (standing)
- **Used on:** Practice area pages that don't get an environmental (Estate Planning, Real Estate, Business Entities, Tax Credits) — one utility shot rotated across them, or each gets the same shot for consistency
- **Shot type:** Standing, hands in pockets or arms crossed, clean background, three-quarter length
- **Aspect ratio:** 4:5 portrait
- **Display dimensions:** 400 × 500
- **Source file:** 4000 × 5000
- **Alt text:** "Norris Lozano"
- **Filename target:** `norris-utility-standing.jpg`

### Slot F — Square crop (for Google Business Profile + social)
- **Used on:** GBP profile photo, OG meta image, future social channels
- **Shot type:** Tight head-and-shoulders, can be a crop of Slot A or its own composition
- **Aspect ratio:** 1:1 square
- **Display dimensions:** 600 × 600 (GBP recommends min 720 × 720 — order higher)
- **Source file:** 2400 × 2400 minimum, 4000 × 4000 preferred
- **Alt text:** "Norris Lozano"
- **Filename target:** `norris-square.jpg`

---

## Where each slot lands on the site

| Page | Slot used | Position on page |
|------|-----------|------------------|
| Home (index.html) | Slot B | Mid-page, after six-practice-areas grid, before "How we work" |
| About (about.html) | Slot A | Top, anchoring credentials |
| About (about.html) | Slot C | Mid-page, "How I work" section |
| Tax Resolution | Slot D | Mid-page, after the four-arguments section |
| Estate Planning | Slot E | Mid-page, after the services list |
| Real Estate | Slot E | Mid-page, after the services list |
| Business Entities | Slot E | Mid-page, after the services list |
| Corporate & Partnership | Slot D | Mid-page, after the services list |
| Tax Credits | Slot E | Mid-page, after the track-record section |
| Contact | — | No portrait — keep page minimal |
| GBP / OG meta | Slot F | Profile photo, social-share preview |

That's 10 slot positions filled by 6 unique source images. Slot E reuses one shot across four pages, which is acceptable — they're four different practice areas, a user typically only sees one at a time.

---

## Color and B&W deliverables

Per Master Strategy Part 10, photographer delivers color AND B&W versions of each. The site uses color throughout. B&W versions are held for:
- Press / PR placements where a publication requires monochrome
- Possible alternate aesthetic on `thelawyerdeveloper.com` (separate authority brand)
- Future print collateral

---

## Insertion sequence after delivery

1. Photographer delivers edited high-res files (TIFF or high-quality JPEG, 5000px longest edge per brief)
2. Process to web-sized JPGs (max 1600px long edge, ~75–85% quality) — keep originals archived
3. Add `<img>` tags at the positions tabulated above, with the specified alt text
4. Test responsive scaling on mobile (especially Slot A on About — the hero needs to remain legible at narrow widths)
5. Update Google Business Profile with Slot F
6. Update OG meta tags site-wide with Slot F URL

---

## What this document is NOT

It is not the photographer brief itself. The full brief — assignment, styling, background, lighting, technical, budget — lives in Master Strategy Part 10. This document is the *site mapping* the brief feeds into, so the photographer knows which deliverable serves which purpose.
