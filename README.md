# My Allotment Planner — Version 3

Free static offline-capable web app for GitHub Pages. Upload the six files **index.html, plants.json, sw.js, icon.svg, manifest.webmanifest, README.md** to the root of the existing repository. Keep the same GitHub Pages address to preserve browser-local records.

## Improvements
Dashboard, seasonal and plant-specific checklists, 4×4 bed visual planner, expanded variety index, calendar, shopping list, harvest weight comparisons, compressed photo diary, optional Open-Meteo seven-day forecast, and local rolling recovery snapshots.

## Data safety
The app deliberately retains the `my-allotment-planner-v1` localStorage key and previous JSON backup schema. Export a backup before updating. Browser storage is device/browser-specific and can be erased; use **Settings → Export JSON backup** regularly. Recovery snapshots are local, not cloud backups. Photos increase storage use. No accounts, subscriptions or paid APIs.

## Accuracy and limitations
Plant dates are approximate crop-level UK monthly windows, NOT verified individual cultivar instructions. Added varieties inherit their crop's timings pending verification. Companion planting claims vary in evidence. Calendar daily views display month-wide windows, not day-specific predictions. Wikipedia import produces an editable draft; the app does not claim to automatically extract reliable sowing dates from web pages. Weather requires an internet connection and uses a manually selected regional location. The bed map is a conceptual 4×4 grid, not a scale drawing. Notifications are in-app checklists, not push alerts.
