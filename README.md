# My Allotment Planner V4

Upload all six files to the ROOT of your existing GitHub Pages repository. Keep the same website address to retain browser-local records. Before upgrading, open V3 Settings and **Export JSON backup**.

## Included
All V3 features, plus smart planting-space calculator, succession batches, seed-to-harvest records, adjustable bed grids, crop-family rotation warnings, companion suggestions, plant problem guidance, perennial reminders, seed-saving logs, expense tracking, quick actions, and print / Save as PDF reports. The original `my-allotment-planner-v1` storage key and JSON state structure are retained; new data is additive under `state.v4`.

## Accuracy
The expanded catalogue combines existing named varieties with additional cultivar-name entries. New entries inherit **approximate crop-level guidance**, not independently verified cultivar instructions. Check seed packets, RHS and local frost conditions before planting. The calculator is theoretical, and companion advice is not a guarantee. Weather is optional via Open-Meteo; no background push alerts. Photos and backups remain on your device unless you export them.

## Installation
GitHub repository → Add file → Upload files → Commit. Settings → Pages → deploy from `main` / `(root)`. Refresh after publishing; if a stale service worker remains, open the website in a fresh browser tab. Never clear site storage before exporting a backup.


### Expanded plant index (November 2026)
Added 466 distinct plant groups across flowers, vegetables, fruits and herbs. These are name-index entries, not verified named cultivars. Their planting windows are intentionally blank rather than invented. Use Copy & customise to add verified sowing, flowering and harvest months from RHS or seed packets. Existing saved data key is unchanged.

V4.1: Seed inventory entries can be edited, linked to exact database varieties, and highlighted in database. Legacy seed records retained.


## V4.2 additions
- Beds tab: scale-aware placement map using actual bed length and width, 25 cm grid, tap-to-place and coordinate editing, zoom, and print. Existing 4×4 and V4 grid layouts remain available separately.
- Plant Details: add/remove compressed photographs per variety.
- Seed Inventory: add/remove packet photographs per inventory record.
- Photos and placements are included in JSON backups because they are stored within the existing app state. Export backups regularly; browser storage has size limits and saving many images may fail.
- The scale diagram is a planting aid, not a surveyed CAD plan. Plant circles indicate approximate spacing.


## V4.3 Database Manager
New Database Manager tab: filters for incomplete records, owned seeds, and research queue; public Wikipedia research with review-before-save; five-at-a-time research queue; sources and summaries stored without overwriting existing growing instructions. Adding an unlinked seed can create a new variety and queue it for research. The original localStorage key remains unchanged. Internet access is needed for online research. Verify cultivar-specific horticultural guidance independently. Export a backup before updating.

## V4.4 — easier plant database navigation
- Category tabs for All, Vegetables, Flowers, Fruit and Herbs, with collapsible plant-name groups and progressive loading.
- Saved plant-photo thumbnails and seed-inventory highlights showing packet quantities.
- Month-based indoor sowing, outdoor sowing and transplant filters, plus favourites.
- Filters for sunlight, missing growing information, missing photos, and sorting.
- Select two or three varieties to compare growing requirements.
- Create and assign custom plant collections.
- All V4.3 features remain; the original localStorage key is unchanged. V4.4 preferences are additive in `state.v44`.
- Filter dates use existing plant data only; missing growing dates are never guessed.

## V4.4.1 fix
- Working database category buttons with scrolling category bar.
- Continuous plant list loading while scrolling; no View More button.
- Add to My Seeds directly from a variety, with quantity and dates.
- Existing data key and V4.3 functionality retained.

## V4.5 — New seeds automatically join the plant database
- When adding an unlinked seed, enter the plant name and variety separately. Existing varieties are matched case- and punctuation-insensitively; new varieties are grouped under their existing plant species.
- Unknown plant species are classified as Other until you select the appropriate category. The app does not guess.
- New varieties are linked to the seed packet and queued for internet research.
- When online, a best-effort Wikipedia search runs automatically and saves candidate sources for review in Database Manager. This is not guaranteed to find the exact cultivar.
- Source descriptions are **not** automatically presented as verified sowing months, spacing or growing instructions. Review the sources and fill in verified growing information manually.
- Works offline for seed entry; research can be retried when online.
- Existing saved data remains in `my-allotment-planner-v1`. Export a backup before updating.
