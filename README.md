# Feral Ascension // Personal Interface

Mobile-first, spoiler-aware companion HUD for the Feral Ascension book series.

## GitHub Pages
1. Upload these files to the repository root (keep `data/` as-is).
2. In GitHub: Settings → Pages → Deploy from a branch → `main` / root.
3. Open the Pages URL on a phone and add it to the home screen for an app-like experience.

## Current prototype
- Reader Mode chapter synchronization (Book 1, Chapters 1–43)
- Archive Mode with spoiler warning
- Feral Dex populated from explicit System scans in the current manuscript
- Inventory archive
- System Log
- Fog-of-war style map shell
- Navigation matching the manuscript's Personal Interface modules
- Progress persists locally on the device

## Updating content
Edit `data/archive.json`. Every record has a `chapter` field. A record is automatically hidden in Reader Mode until that chapter is selected.
