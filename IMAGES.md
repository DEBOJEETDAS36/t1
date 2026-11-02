# Adding your images

Drop files into `public/images/` using the names below. No code changes needed — each spot shows your image automatically
and falls back to the current placeholder when a file is missing. Any of png, jpg, jpeg, webp, avif, svg or gif works.
Rebuild (or restart `npm run dev`) after adding files.

| What | File name | Tip |
|---|---|---|
| Logo (navbar + footer) | `logo.png` / `logo.svg` | Transparent background, about 3:1 wide. Shown at 36px tall. |
| Logo for light theme (optional) | `logo-light.png` | Use if your logo is white/light — `logo.*` is used on the dark theme, this one on the light theme. |
| Hero picture (arch on home page) | `hero.jpg` | Portrait, about 900 × 1100. |
| Partner logos | `partners/<any-name>.png` | Every file in this folder appears in the scrolling strip. Use transparent PNG/SVG; they show as white (dark theme) / grey (light theme) and turn colour on hover. Name a file `something-color.png` to always show its original colours. |
| Package cards (home) | `tours/<tour-slug>.jpg` | About 800 × 500. Slugs for the home page: bali-nusa-penida, dubai-abu-dhabi, blissful-japan, vietnam-unfolded, jewel-of-the-nile, scenic-new-zealand |
| Destination tiles | `destinations/southeast-asia.jpg`, `dubai.jpg`, `italy.jpg`, `kerala.jpg`, `south-africa.jpg` | The big first tile is southeast-asia (about 900 × 700). |
| Blog cards | `blogs/bali-beyond-the-beaches.jpg`, `japan-in-autumn.jpg`, `planning-an-egypt-cruise.jpg` | About 800 × 500. |
| About panel (home) | `about.jpg` | Replaces the route map; about 800 × 960. |
| Testimonial photos | `testimonials/ananya-sen.jpg`, `rohan-mehta.jpg`, `priya-das.jpg` | Square, about 200 × 200. |

All tour slugs (for future use): kerala-backwaters-hills, royal-rajasthan, magical-ladakh, amazing-arunachal, goa-beach-escape, andaman-island-hopping, darjeeling-sikkim, kashmir-paradise, himachal-highlands, corbett-ranthambore-safari, bali-nusa-penida, dubai-abu-dhabi, thailand-island-trails, maldives-overwater-bliss, blissful-japan, vietnam-unfolded, swiss-alps-paris, jewel-of-the-nile, scenic-new-zealand, kenya-safari

For a favicon, add `app/icon.png` (any square PNG).
