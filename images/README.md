# Images — Magic Fingers Barbershop

This folder is the swap point for shop-specific photos. Drop replacements with the **same filenames** and the site updates automatically.

## What to swap

### Brand
- `logo-m.svg` — gold "M" placeholder. Replace with the real Magic Fingers logo (PNG with transparent background works best, square-ish aspect ratio).
- `logo-b.png` — leftover from the 080 template, **safe to delete**, no longer referenced.

### Hero
The hero video clips live in `../videos/`. The poster fallback is `p20785318.jpg` — if you want a different bald-man-clipper still as the poster while the video loads, swap this file.

### Sheka portrait
- `sheka.jpg` — drop a portrait shot of Sheka here (4:5 aspect ratio looks best, ideally a moody/dark-background shot to match the design system). If absent, the page shows a stylish gold "Sheka — Foto volgt" placeholder card automatically.

### Haircuts gallery (`haircuts/cut-1.jpeg` through `cut-8.jpeg`)
8 portfolio-style haircut photos. Currently filled with the 080 client photos as visual placeholders. Replace these once you have shots from Magic Fingers' Instagram / WhatsApp portfolio.

Recommended specs:
- 1080–1600px wide
- JPEG, ~150 KB each
- Dark/moody lighting matches the editorial style

### Sfeerbeelden / ambience (`p3998397.jpg`, `p7697200.jpg`, etc.)
Shop interior + atmosphere shots used in the horizontal scroll gallery and image breaks. Either leave these (they're generic enough) or swap with shots of Magic Fingers' actual interior.

### Image breaks
- `p20785318.jpg` — first full-bleed image break (between Haircuts and Meet sections)
- `p17665771.jpg` — second image break (between Services and Sfeerbeelden)

## Cleanup checklist (when going live)

- [ ] Logo swapped (`logo-m.svg` → real logo)
- [ ] Sheka portrait added (`sheka.jpg`)
- [ ] Haircuts gallery has Magic Fingers shots
- [ ] At least 2 ambience shots are real interior photos
- [ ] All `p*.jpg` from the 080 template that aren't reused are deleted
- [ ] All HTML `alt` attributes describe what's actually in the new photo