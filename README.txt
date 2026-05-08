Life OS Phase 3.1 — Buttons Fixed

Issue fixed:
- Previous Phase 3 had a JavaScript syntax error in generated click handlers.
- That stopped all buttons/tabs from responding.
- This version fixes the error and updates the service worker cache version.

GitHub Pages update:
1. Extract this ZIP.
2. Upload/replace these files in your GitHub Pages repo:
   index.html
   manifest.json
   sw.js
   icon.svg
   README.txt
3. Commit changes.
4. Open your website with ?v=31 at the end, for example:
   https://yourusername.github.io/life-os-tracker/?v=31

If iPhone still shows old version:
- Safari > reload the page
- or remove the Home Screen icon and add it again
- or Settings > Safari > Clear History and Website Data only if needed

