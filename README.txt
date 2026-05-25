Quran Reciter PWA

What changed:
- This version is a PWA package, not just one HTML file.
- It uses full-surah MP3 streams from QuranicAudio, so one surah keeps playing even when your phone screen is locked.
- It includes Media Session API support for lock-screen play/pause/next/previous controls.
- It includes a manifest, service worker, and icons.

Important:
- Opening index.html directly works as a normal website.
- To install it like an app on a phone, upload the folder to HTTPS hosting, for example GitHub Pages, Netlify, Vercel, or Cloudflare Pages.
- Audio still needs internet, because the MP3 files are streamed.
- On iPhone, full-surah playback is much better than ayah-by-ayah playback, but automatic next-surah while locked can still depend on Safari/iOS behavior.
