# ISSF General Regulations Rule Finder — App v1

Offline phone app (PWA) for the ISSF General Regulations (3.1–3.14) and Annexes, in English and Arabic.
ISSF Rule Book Ed. 2025, Third Print 10/2026 (eff. 19 Oct 2026); Arabic per A-GENERAL REGULATIONS 2026 V3.

Prepared by International Judge Tarek Sharara.

## Publish on GitHub Pages
1. Upload all files in this folder to the root of a repository (e.g. `gr-rules-finder`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Open `https://<user>.github.io/gr-rules-finder/` once while online.

## Install on a phone
- iPhone (Safari): Share → *Add to Home Screen*.
- Android (Chrome): ⋮ menu → *Install app* / *Add to Home screen*.

After the first visit it works with no internet.

## Search tips
- Rule number: `3.7.4`
- Annex: `Annex J`, `Annex CE 2.4`, `ملحق P`
- Words in English or Arabic: `junior`, `الرسوم`

## Updating
After changing `index.html`, edit `sw.js` and raise `VERSION` (e.g. `v1` → `v2`) so phones pick up the new copy.
