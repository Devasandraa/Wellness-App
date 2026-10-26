WellSense
========

This package contains the complete mobile-first PWA for the seminar project.

Files included:
- index.html
- manifest.json
- service-worker.js
- README.txt
- icons/

How to open it:
1. Extract the zip folder containing WellSense.
2. Open the folder and either:
   - open index.html directly in a mobile browser for a quick test, or
   - run a static server from the folder.
3. Example local server:
   - Python: python -m http.server 8080
   - Then open http://localhost:8080/WellSense
4. On Android: open in Chrome and choose "Add to Home Screen".
5. On iPhone/iPad: open in Safari, tap Share, then tap "Add to Home Screen".

Important notes:
- All data is stored locally in browser storage (localStorage).
- The app is installable and offline-capable through the service worker.
- USDA FoodData Central lookup only works when a valid API key is entered in Settings.
- Demo data can be turned on or off in Settings.

Not a medical device.
