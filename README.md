# Keyboard Shortcuts Website

## Description
Keyboard Shortcuts is a Progressive Web App (PWA) designed to help users quickly find and learn useful keyboard shortcuts for various platforms and applications. The app works offline once installed on your device and provides a smooth, app-like experience on both desktop and mobile devices.

## Features
- Offline support with Service Worker caching
- Clean and simple UI
- Standalone app experience (no browser UI when launched from home screen)
- Supports installation on iOS and Android devices
- Quick access to commonly used keyboard shortcuts

## Files Cached for Offline Use
The following files are cached by the service worker to enable offline functionality:

- `/index.html` – Main HTML page
- `/manifest.json` – Web app manifest
- `/styles.css` – Stylesheet for layout and design
- `/1.png` – Apple touch icon
- `/favicon.ico` – Browser favicon

## Service Worker (`sw.js`)
The service worker caches all the above files during installation and serves them from cache to provide offline access.

### How to run locally
1. Serve your site over HTTPS or use a local server (e.g., `live-server`, `http-server`).
2. Open the site in a modern browser that supports service workers.
3. Add the site to your home screen on mobile devices for an app-like experience.
4. Use the site offline after the first visit.

## Installation
To add the app to your mobile device:
- Open the site in your mobile browser.
- Tap “Add to Home Screen” (usually found in the browser menu).
- Launch the app from your home screen without needing internet.

---

## Contact
For questions or contributions, please contact [your email or website].

