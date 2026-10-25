# Velvet — Android-inspired PWA

Velvet is a browser-based phone simulation with an original midnight-lilac and mint design. This package is prepared as a Progressive Web App (PWA).

## Files
- `index.html` — app interface
- `manifest.webmanifest` — install name, icon and standalone display settings
- `sw.js` — service worker for offline caching
- `icons/velvet.svg` — app icon

## Install on Android
1. Upload the contents of this folder to a static web host that serves HTTPS (for example, GitHub Pages, Netlify, or Cloudflare Pages).
2. Open the deployed HTTPS URL in Chrome on your Android phone.
3. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
4. Launch Velvet from the new home-screen icon.

## Important
- A PWA must be served from HTTPS (or localhost) for service-worker/offline support. Opening `index.html` directly from a file manager does not provide the full install/offline experience.
- The browser simulation cannot replace Android's system lock screen or read private photos automatically.
- Notes are saved in local browser storage on the device.
- This project has been prepared for deployment, but it has **not** been uploaded or hosted online by this package-generation step.

## Customise
Edit the CSS variables in `index.html` to change colours, and edit the `templates` object to customise the mini-app screens.
