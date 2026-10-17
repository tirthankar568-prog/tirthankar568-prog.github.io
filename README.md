# QR Scanner Dispatcher

A lightweight, mobile-first web scanner built to scan and decode compact QR codes (such as those printed on PVC ID cards and badges) and automatically relay the payload to a Google Apps Script backend.

---

## Features

- **Small QR & ID Card Optimized**: Configured with responsive viewfinder bounds and soft HD camera constraints for sharp focus on compact codes.
- **Hardware Acceleration**: Utilizes the native browser `BarcodeDetector` engine on supported devices (such as iOS Safari and Chromium) for low-latency detection.
- **Google Apps Script Bridge**: Dispatches tag IDs to an Apps Script webhook endpoint via cross-origin JSONP with instant visual status indicators.
- **Audio & Haptic Feedback**: Emits a confirmation beep via the Web Audio API and triggers device vibration on successful decode.
- **Recent Scans Ledger**: Displays an in-memory chronological history of recent scans with timestamps and execution statuses.

---

## Tech Stack

- **Frontend**: Plain HTML5, CSS3, Vanilla JavaScript
- **Engine**: [html5-qrcode](https://github.com/mebjas/html5-qrcode)
- **Backend Relay**: Google Apps Script (`exec` Web App)

---

## Deployment & Hosting

Mobile browsers (especially iOS Safari) strictly require an **HTTPS** origin to permit camera access.

### Deploying via GitHub Pages

1. Commit `index.html` to the root of your repository.
2. Open your repository **Settings** tab.
3. Select **Pages** from the left navigation menu.
4. Under **Build and deployment > Branch**, choose `main` (or `master`) and folder `/(root)`.
5. Click **Save**. Your live scanner will be published at:
   ```text
   https://tirthankar568-prog.github.io/tirthankar568-prog.github.io/
