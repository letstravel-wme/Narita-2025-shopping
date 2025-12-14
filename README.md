# Narita-2025-shopping

Single-file Vue + Tailwind app for planning a short Narita trip.

Features
- Itinerary viewer
- Key locations with links to Google Maps
- Spending tracker with totals
- Shopping list with image upload (stored in localStorage)
- Background image support for GitHub Pages

Quick start (web UI)
1. Create a GitHub repo named `Narita-2025-shopping` (public).
2. Create a branch `redo/pages-full`.
3. Add `index.html` to `redo/pages-full` (paste the HTML from the provided file).
4. Upload `assets/window-bg.jpg` to `redo/pages-full`.
5. Open a PR from `redo/pages-full` → `main` and merge.
6. Set Pages source to `main / root` in Settings → Pages.
7. Visit: https://<your-user>.github.io/Narita-2025-shopping/

Notes
- Uploaded shopping images are stored as base64 data URLs in localStorage (client-side only). For lots of photos consider external storage.
- Keep `assets/window-bg.jpg` under ~1–2 MB for faster load on mobile.
