# My Allotment Planner

A free, offline-friendly static web app with 255 named starter varieties, My Growing List, beds, month/day/year calendar, diary, seed inventory, harvest records, reminders, and JSON backups.

## Publish for free on GitHub Pages
1. Create a new public GitHub repository named `my-allotment-planner`.
2. Upload `index.html`, `plants.json`, `manifest.webmanifest`, `icon.svg`, and `sw.js` to the **root** of the repository (not in a subfolder).
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)`, and Save.
4. Wait for the Pages deployment, then open the URL shown in Settings → Pages.
5. In Chrome on Android, choose **Add to Home screen** / **Install app**.

**Important:** Opening `index.html` directly as a file won't load `plants.json`; it must be hosted. All personal records are stored locally in that browser's `localStorage`, not synced across devices. Export backups regularly.

**Internet search:** Uses Wikipedia's public API to retrieve background text and links, then opens a draft for manual review. It does not automatically obtain or verify detailed cultivar-specific growing data, and Wikipedia may not contain the requested cultivar. RHS search link is included for manual cross-checking. No paid AI API is required.

**Accuracy:** Starter dates are broad UK guidance shared by crop groups, not independently checked cultivar-specific recommendations. Adjust for South West Scotland weather and seed-packet directions. The calendar shows month-level windows even when a day is selected. Reminder entries are in-app only, not push notifications.
