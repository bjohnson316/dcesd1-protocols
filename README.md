# Denton County ESD 1 & 2 EMS Protocols 2026 — Mobile App

A self-contained, installable, **offline** field reference for the Denton County
ESD 1 & 2 (BEST EMS) Treatment Protocols, effective July 1, 2026 (Medical Director
Robert J. Hancock, DO FACEP). Runs on iPhone and Android as an installable web app
(PWA). Every page is shown as a faithful image of the official PDF, so drug doses
and layout are never re-typed or rearranged.

## What's in the folder
- `index.html` — the app
- `data.js` — protocol index + search text
- `images/` — 218 page images (the actual protocols)
- `icons/`, `manifest.webmanifest`, `sw.js` — app icon + offline support

## How to put it on your phone (GitHub Pages)
1. Create a new GitHub repo (or use an existing Pages repo) and upload the entire
   contents of this folder so `index.html` sits at the repo root.
2. In the repo: **Settings → Pages →** set Source to your main branch / root, Save.
3. Wait a minute, then open the published URL on your phone.
4. **Add to Home Screen:**
   - **iPhone (Safari):** Share → *Add to Home Screen*.
   - **Android (Chrome):** ⋮ menu → *Install app* / *Add to Home Screen*.
5. Open it from the new home-screen icon. It now runs full-screen like a native app.

## Make it work with no signal
On the home screen, tap **"Save for offline."** It downloads all 218 pages into the
app (about 25 MB). After that the whole protocol set works with **zero cell service**.

## Using it
- **Search** — type a drug, protocol, or complaint (e.g. *ketamine*, *bradycardia*,
  *chest pain*). Searches titles **and** the full text of every page, and jumps you
  to the right page.
- **Sections** — six color-coded tiles: General Information, Adult Medical,
  Pediatric Medical, Trauma, Skills & Procedures, and Medications. Tap a tile,
  then a protocol.
- **Reader** — pinch to zoom, swipe left/right or use Prev/Next to flip pages, tap
  the page counter to jump to any page number.
- **Bookmark** — tap the star on any page to save it; bookmarks live on the home
  screen for fast access. Recently viewed pages are remembered too.

## Note
This app is a convenience reference. The **official approved BEST EMS protocols
govern** in all cases. Verify against the current signed document and your medical
director's direction. Protocols are not to be copied or distributed without written
consent from BEST EMS.
