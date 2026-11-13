# Whyalla Futures Research

The public website for Whyalla Futures Research, part of the ARC DECRA project
Hydrogen Hub Futures (DE250100024), led by Dr Kari Dahlgren at Monash University.

Live at https://whyallafutures.com (GitHub Pages, custom domain set in `CNAME`).

## Files
- `index.html`: the page
- `tokens.css`: colours, type and spacing (Saltbush & Ember scheme)
- `whyalla.css`: page styles
- `episodes.js`: Voices from Whyalla episodes (edit this to add an episode)
- `whyalla.js`: podcast player
- `assets/`: photos, podcast title card, portrait
- `documents/`: PDFs linked from the page
- `_saved/`: pages held back for later (folders starting with `_` are not published)

## Adding a podcast episode
Add a line to `episodes.js` with the YouTube video ID, title and description.

## Saved pages
- `_saved/get-involved/`: participant recruitment page, to restore once ethics
  approval covers recruitment. Private artifact copy: "Whyalla Get Involved".
- `_saved/ethics/`: ethics information page (MUHREC Project ID 49310).
  Private artifact copy: "Whyalla Ethics Page".

To restore one, move its `index.html` to `get-involved/index.html` or
`ethics/index.html` at the top level, fill in its remaining placeholders, link it
from `index.html`, and add it to `sitemap.xml`.
