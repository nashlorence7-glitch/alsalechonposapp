Alsa Lechon POS - installable app (PWA)

1. Upload this whole folder to any HTTPS host (Vercel, Netlify, Cloudflare Pages, GitHub Pages).
2. Open the site on the phone/tablet:
   - Android (Chrome): menu > Install app / Add to Home screen
   - iPhone/iPad (Safari): Share > Add to Home Screen
3. It then opens full-screen like a normal app and works offline.

To ship an update, change VERSION in sw.js (e.g. alsa-pos-v2) and re-upload.
NOTE: data saved in the old file lives in that browser's storage and does not move to the new web address.
