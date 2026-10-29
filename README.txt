HOW TO USE
1. Keep all files together (index.html, manifest.json, sw.js, icons/).
2. Upload the whole folder to HTTPS hosting (GitHub Pages, Netlify, Vercel, Firebase Hosting).
   PWAs do not install from file:// - they need https:// (or http://localhost).
3. Open the site on a phone/PC: use "Install app" / "Add to Home Screen".
Test locally: python3 -m http.server 8000  then open http://localhost:8000
