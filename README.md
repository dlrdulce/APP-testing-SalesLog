# Daily Sales Log

Phone web app to record daily store sales per payment channel (POS 1/2 cash, Grab, foodpanda, GCash, QRPH, PayMaya, Pandago, gift certificates), record channel payouts, and reconcile them against bank credits.

- Single static page (`index.html`), no build step. Data is stored in the browser (localStorage).
- Installable PWA (manifest + service worker, works offline).
- Use "Copy backup" / "Restore" in the Check tab to move data between devices.

## Deploy
GitHub Pages: Settings > Pages > Deploy from branch > `main` / root.
