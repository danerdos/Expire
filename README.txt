EXPIRY TRACKER — HTML/CSS/JavaScript

HOW TO RUN ON YOUR PHONE
1. Extract the ZIP file.
2. Keep index.html, style.css, and script.js in the same folder.
3. Open index.html in a browser that allows local HTML files.

FEATURES
- Expired products card plus 1–10 days left cards.
- Tap any card to view matching product expiry entries.
- Add product name, optional barcode, optional image, and multiple expiry dates.
- Saves data in the current browser's localStorage.

IMPORTANT
- Data is stored ONLY in that browser on that device. Clearing browser/site data may erase it. Some mobile browsers restrict local file storage; if saving doesn't work, serve the folder over HTTPS or localhost.
- The dashboard tracks the 10-day window, but background notifications are NOT implemented. Reliable notifications while the app is closed require a hosted PWA and push infrastructure, particularly on iPhone.
- No server, accounts, cloud synchronization, or barcode scanning is included.

DATA STORAGE (prototype)
Products and photos are now saved to IndexedDB in the browser. Existing products
from the previous localStorage version are imported automatically when opened
under the same browser origin. No Firebase connection is included yet.
Use an HTTP local server or HTTPS website to ensure browser storage works.
Data stays on the same device/browser/origin; clearing site data may erase it.
