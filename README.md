# Feral Ascension Personal Interface — Book 1 Complete

GitHub Pages-ready, mobile-first HUD companion for **Feral Assention**. Canon archive synchronized through **Book 1, Chapter 60** from the supplied 550-page manuscript.

## Root-only repository
Upload these files directly to repository root:
- `index.html`
- `style.css`
- `app.js`
- `archive.json`
- `manifest.json`
- `README.md`

No project subfolders are required. Images remain intentionally unimplemented.

## Chapter Sync
Reader Mode gates records by first safe chapter. Archive Mode reveals the complete Book 1 database. Progress is stored locally in the browser.

## Canon vs flavor stats
System/book facts are archived as canon. Height, weight, habitat, role, and threat fields marked with `*` in the Dex are companion-app flavor estimates unless the manuscript explicitly supplies them.


## Feral Dex artwork files
The Dex now loads one root-level WebP image per observed Feral. Keep the image files beside `index.html`; do not create an image folder. Filenames are stored in each Feral record's `image` field in `archive.json` (for example `feral-cinderkit.webp`). If an image has not been added yet, the HUD automatically shows a System-style fallback instead of a broken image icon.

The Book 1 Dex count is explicitly **observed records**, not the total number of Feral species in the world. The world total remains unknown.
