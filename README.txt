Life OS Phase 2 PWA Package

Why this package exists:
iPhone often opens local .html files inside Files/ChatGPT preview/Quick Look. In that preview, JavaScript buttons and local storage may not work. Hosting this folder as a small website fixes that.

Files:
- index.html: main Life OS tracker
- manifest.json: mobile/PWA info
- sw.js: offline cache support after hosting
- icon.svg: app icon

Best free hosting options:
1. Netlify Drop:
   - Go to app.netlify.com/drop on a computer
   - Drag this whole folder or the ZIP contents onto the page
   - Open the generated link on iPhone Safari
   - Tap Share > Add to Home Screen

2. GitHub Pages:
   - Create a GitHub repo
   - Upload these files
   - Enable GitHub Pages
   - Open the generated link on iPhone Safari
   - Tap Share > Add to Home Screen

Important:
The data saves in the browser on the device where you use it. Use Export JSON backup regularly.
