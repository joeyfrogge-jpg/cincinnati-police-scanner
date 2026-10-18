# Cincinnati Police Scanner

Exact dark-theme live scanner for **Cincinnati, Hamilton County, and Delhi Township, Ohio** only.

## Open the app

**[https://joeyfrogge-jpg.github.io/cincinnati-police-scanner/](https://joeyfrogge-jpg.github.io/cincinnati-police-scanner/)**

(If the link 404s: Repo → Settings → Pages → Deploy from branch `main` / root → Save.)

## How to hear live audio

Broadcastify no longer allows third-party audio embeds. Free listening works like this:

1. Select a channel (Dispatch, Police, Fire/EMS, or **Delhi Township**).
2. The official Broadcastify player loads in the player card.
3. Tap **LISTEN LIVE — TAP TO HEAR** (or the circular play button) to open the free live stream.
4. A short ad may play first on free feeds; then live radio starts.

## Delhi Township

Delhi is fully covered on the free **Hamilton County** feed (Broadcastify ID **14527**):

| Channel | Talkgroup | How to select in app |
|---------|-----------|----------------------|
| Delhi PD | 21203 (31 DLHI PD) | **Police → Delhi Township PD** or **Dispatch → Delhi Township** |
| Delhi Fire | 21204 | **Fire / EMS → Delhi Township Fire** |

Selecting any Delhi channel centers the map on Delhi Township (39.0923° N, 84.6233° W) and loads the same live Hamilton County stream that carries those talkgroups.

## Free feeds used (Cincinnati area only)

| Feed | ID | Status |
|------|-----|--------|
| Hamilton County Police, Fire & EMS Dispatch | 14527 | Online — primary (includes Delhi) |
| Cincinnati Fire | 5184 | Online |
| Cincinnati Police | 32619 | Offline on Broadcastify |

## Features

- Design matched to the provided screenshot (SVG icons only, no emojis)
- Working dark map (Leaflet + Carto dark tiles) that moves with the selected feed
- Categories: Dispatch, Police, Fire/EMS, Traffic, Metro, Favorites
- Explicit Delhi Township entries under Dispatch, Police, and Fire/EMS
- Standalone single-file app for GitHub Pages

## Disclaimer

Educational and hobby listening only. Do not interfere with emergency communications. Feeds may go offline or become encrypted without notice.
