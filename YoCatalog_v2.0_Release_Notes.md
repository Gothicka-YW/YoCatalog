# YoCatalog v2.0.0 — Release Notes (2025‑12‑06)

This release graduates YoWishlist‑50 from a capture helper into a miniature publishing studio. Version 2.0 layers a reusable signature builder, home‑link manager, holiday styling, and UI polish onto the core “first N cards” workflow that thousands of YoWorld players already rely on.

## Highlights
- Signature Builder: Craft BBCode signatures with live previews, personalized colors, and embedded home links, then copy them in one click.
- Home Link Manager: Save multiple YoWorld profile/home URLs, switch between them instantly, and import/export the list in JSON for backups.
- Seasonal Themes: Christmas Lights and Valentine Blush join the lineup, while Velvet Red becomes the default theme for a rich start.
- Popup Refinements: Lists tab inputs no longer overlap action buttons, avatar filters share consistent widths, and a new “Buy Me a Coffee” button offers a tip jar.
- Documentation Pass: CHANGELOG, README, HOW_TO_USE, Help Guide, and in‑app text now describe every 2.0 feature.

## Why this matters
Players can now capture wishlists, quote them, and promote their home links without leaving the extension. The signature builder keeps BBCode consistent, the home‑link manager eliminates retyping URLs, and holiday themes keep screenshots fresh for seasonal markets. It’s a complete toolchain for YoWorld forum posts and fan‑group sales threads.

## Signature Builder Quick Start
1. Open the Images tab and locate “Signature Builder”.
2. Pick or create a home link in the drop‑down (URL + friendly label).
3. Write optional intro/outro lines, toggle emojis, and select a theme color that matches your post.
4. Watch the BBCode preview update live; when ready, click “Copy Signature”.
5. Paste the BBCode into the YoWorld Forums or Facebook groups — it includes your chosen home link and formatting.

### Managing Home Links
- **Add**: Enter a label + URL, then click Save. It becomes selectable for captures and signatures.
- **Edit/Delete**: Select a saved link, adjust fields, and click Save or Delete.
- **Backup/Restore**: Use the JSON Import/Export controls to move your link list (and existing YoWishlist data) across browsers.

## Theme + UI Changes
- Velvet Red is the default popup palette.
- New Christmas Lights and Valentine Blush themes are available via the Themes tab.
- Avatars tab filters (“All”, “Search”, “Name A‑Z”) share the same width to reduce UI jitter.
- Lists tab “Save Title” input is narrowed so the “Save” and “Delete” buttons remain visible on compact popups.
- Support button opens the project’s Buy Me a Coffee page in a new tab.

## Changes in 2.0.0
- Added Signature Builder section in Images tab with live preview + copy actions.
- Added persistent home‑link manager with JSON import/export/reset support.
- Updated storage schema to include home links while staying backward compatible with prior saved lists.
- Added two holiday themes and set Velvet Red as default.
- Polished popup layout (inputs, filters, button row) for consistency.
- Updated manifest, README, HOW_TO_USE, YoCatalog Help Guide, and CHANGELOG to describe the new workflow.

## Compatibility
- Chrome/Brave/Edge (desktop): Load as unpacked extension.
- Android: Kiwi Browser remains the recommended mobile option for running unpacked extensions.

## Install or Update
- Enable “Developer mode” in chrome://extensions → “Load unpacked” → choose the `YoWishlist-50` folder.
- Upgrading from 1.x keeps your saved lists automatically. Export your JSON first if you also want to carry over existing home links from test builds.

## Known issues / tips
- Signature Builder relies on `chrome.storage.sync`; very large image libraries plus many links can approach the quota. Export regularly if you maintain dozens of entries.
- When importing JSON, double‑check that `homeLinks` objects include both `label` and `url` fields to avoid skipped entries.
- Catbox fallback uploads still require the Images tab to stay open during large transfers.

## Version
- Extension version: 2.0.0
- Date: 2025‑12‑06

---
Fan tool. Not affiliated with YoWorld or Big Viking Games. Feedback/Bugs: https://github.com/Gothicka-YW/YoWishlist-50/issues
