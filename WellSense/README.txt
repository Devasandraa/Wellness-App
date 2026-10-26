WellSense
========

This package contains a mobile-first PWA named WellSense for a B.Tech seminar (CDQ 413).

Contents:
- WellSense/index.html
- WellSense/manifest.json
- WellSense/service-worker.js
- WellSense/icons/

How to open it on a phone:
1. Extract the zip in a folder.
2. From the extracted folder, either:
   - open index.html directly in a mobile browser for a quick local test, or
   - run a simple static server in the same folder.
3. For a local server command:
   - Python: python -m http.server 8080
   - then open http://<your-computer-ip>:8080/WellSense or http://localhost:8080/WellSense
4. On Android: open the page in Chrome and choose "Add to Home Screen" from the browser menu.
5. On iPhone/iPad: open in Safari, tap Share, then tap "Add to Home Screen".

Notes:
- This app works fully client-side and stores data locally in localStorage.
- It is installable as a PWA and caches key files for offline use.
- The app includes demo data toggled in Settings for seminar presentations.
- USDA FoodData Central lookup works only when a valid API key is added in Settings.

Not a medical device.
