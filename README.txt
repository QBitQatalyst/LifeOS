Life OS Phase 3.2 — Mobile Width Fixed

Fix:
- Prevents mobile horizontal overflow/clipping.
- Makes tabs and category chips scroll safely inside the screen.
- Reduces mobile padding and forces panels/forms/buttons to fit 100% of the iPhone width.
- Updates the service worker cache version.

GitHub Pages update:
1. Extract this ZIP.
2. Upload/replace:
   index.html
   manifest.json
   sw.js
   icon.svg
   README.txt
3. Commit changes.
4. Open the site using ?v=32 at the end:
   https://yourusername.github.io/life-os-tracker/?v=32

If the old version still appears, remove the Home Screen icon and add it again after opening ?v=32 in Safari.
