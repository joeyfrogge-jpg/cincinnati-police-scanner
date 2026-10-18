# Cincinnati Police Scanner

Exact dark-theme live scanner UI for **Cincinnati, Hamilton County, and Delhi Township, Ohio** only.

## Live App

**[Open Scanner](https://joeyfrogge-jpg.github.io/cincinnati-police-scanner/)**

(Enable GitHub Pages: Settings → Pages → Deploy from branch `main` / root.)

## Features

- Pixel-matched dark UI from the provided design (no emojis — SVG icons only)
- Live free Broadcastify feeds restricted to Cincinnati / Hamilton County / Delhi Township
- Categories: Dispatch (Primary), Police (Law Enforcement), Fire / EMS, Traffic, Metro, Favorites
- Interactive dark map that updates to the selected feed location
- Live waveform, transport controls, volume UI, bottom navigation
- Standalone single-file app (HTML + CSS + JS) — works offline for UI, live audio requires network

## Free Live Feeds Used

| Category | Feed | Broadcastify ID | Notes |
|----------|------|-----------------|-------|
| Dispatch / Police / Traffic / Metro | Hamilton County Police, Fire & EMS Dispatch | 14527 | Primary. Includes Delhi Township PD/FD, Norwood, county law East/West/Central, firegrounds |
| Fire / EMS | Cincinnati Fire | 5184 | City CFD Zone A EMS + Fire Zones B–J |
| Police (secondary) | Cincinnati Police | 32619 | Currently offline / deleted on Broadcastify |

All feeds are free public streams. The dedicated Cincinnati Police feed has been offline for an extended period; law traffic for the city and Delhi is carried on the Hamilton County primary feed (Ohio MARCS-IP).

## Delhi Township

Delhi is covered on the Hamilton County feed:

- Delhi PD — TG 21203 (31 DLHI PD)
- Delhi FD — TG 21204
- Western Law Dispatch (31 LE WEST) covers the Delhi area

## Design Notes

- Layout, colors, spacing, card style, category grid, quick controls, and bottom nav match the attached screenshot
- Map uses CartoDB dark tiles + Leaflet
- Waveform is animated when a live feed is selected
- Play opens the official Broadcastify free player (most reliable free path; static MP3 streams require Broadcastify Premium)

## Disclaimer

For educational and hobby listening only. Do not interfere with emergency communications. Feeds may go offline or channels may become encrypted without notice.

---

Strictly Cincinnati / Hamilton County / Delhi Township focused.
