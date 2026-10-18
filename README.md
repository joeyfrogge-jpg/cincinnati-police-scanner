# Cincinnati Area Police Scanner

A focused resource for live police, fire, and EMS radio traffic in the **Cincinnati, Ohio** metropolitan area, strictly limited to Hamilton County agencies with explicit coverage of **Delhi Township**.

This repository aggregates publicly available Broadcastify streams and RadioReference talkgroup data for the Ohio MARCS-IP (Multi-Agency Radio Communications System) P25 trunked system used throughout the region.

> **Disclaimer**: This is for informational and hobbyist listening purposes only. Always respect local laws regarding scanner use. Do not interfere with emergency communications. Some channels may be encrypted or go offline without notice.

## Live Feeds (Broadcastify)

### Primary Recommended Feeds

| Feed | Description | Status Link | Direct Player |
|------|-------------|-------------|----------------|
| **Hamilton County Police, Fire and EMS Dispatch** | Main suburban/county feed covering law (East/West/Central), fire, EMS, and firegrounds. Includes township agencies such as Delhi. | [Feed 14527](https://www.broadcastify.com/listen/feed/14527) | [Web Player](https://www.broadcastify.com/webPlayer/14527) |
| **Cincinnati Fire** | City of Cincinnati Fire & EMS (MARCS Zone A EMS + Fire Zones B-J) | [Feed 5184](https://www.broadcastify.com/listen/feed/5184) | [Web Player](https://www.broadcastify.com/webPlayer/5184) |
| **Cincinnati Police** | CPD Districts (may be intermittent / offline at times) | [Feed 32619](https://www.broadcastify.com/listen/feed/32619) | [Web Player](https://www.broadcastify.com/webPlayer/32619) |

**Note on Cincinnati Police**: Feeds for CPD have historically gone offline periodically. Check Broadcastify Calls for individual talkgroup activity if the linear feed is down.

### How to Listen
1. Click any of the Web Player links above.
2. Or use the [Broadcastify mobile apps](https://www.broadcastify.com/apps) or third-party scanner apps that support Broadcastify.
3. For advanced users: Broadcastify Calls platform provides per-talkgroup audio.

## Delhi Township Coverage

Delhi Township is fully included via the Hamilton County MARCS-IP system.

### Key Talkgroups (from RadioReference)

| DEC | HEX | Alpha Tag | Description | Tag |
|-----|-----|-----------|-------------|-----|
| **21203** | 52d3 | 31 DLHI PD | **Delhi Police** | Law Talk |
| **21204** | 52d4 | 31 DLHI FD | Delhi Fire | Fire-Talk |
| 21205 | 52d5 | 31 DLHI SVC | Delhi Service | Public Works |

Delhi units typically use the standard Hamilton County unit numbering (Western agencies): **8D10–8D99** range for Delhi Township Police.

Delhi Fire stations:
- Station 30 – Rapid Run
- Station 33 – Neeb Road (HQ)
- Station 36 – Greenwell

These talkgroups appear on the main **Hamilton County Police, Fire and EMS Dispatch** feed (14527) when active.

## Hamilton County / Cincinnati Talkgroup Highlights

### Cincinnati Police (CPD)
| DEC | Alpha Tag | Description |
|-----|-----------|-------------|
| 55649 | 31 DIST 1 | District 1 (Downtown / CBD) |
| 55650 | 31 DIST 2 | District 2 |
| 55651 | 31 DIST 3 | District 3 |
| 55652 | 31 DIST 4 | District 4 |
| 55653 | 31 DIST 5 | District 5 |

### Hamilton County Law Dispatch
| DEC | Alpha Tag | Description |
|-----|-----------|-------------|
| 21071 | 31 LE EAST | East Law Dispatch |
| 21072 | 31 LE WEST | West Law Dispatch (includes Delhi area) |
| 21073 | 31 LE CENT | Central Law Dispatch |

### Other Notable Agencies
- Norwood PD: 55905 (31 NORW PD)
- University of Cincinnati PD: 55705 (31 UC POL)
- Xavier University PD: 55904 (31 XU POL)
- Blue Ash, Colerain, Green Township, etc. all operate on MARCS under the 31 prefix.

Full database: [RadioReference – Ohio MARCS-IP](https://www.radioreference.com/db/sid/6643)

## System Information

- **System**: Ohio MARCS-IP (Multi-Agency Radio Communications)
- **Type**: Project 25 Phase I (some Phase II)
- **Primary Control Channels** (Hamilton County / Cincinnati simulcast sites vary):
  - Cincinnati City Simulcast and Hamilton County Simulcast sites
- Encryption: Some tactical and specialized channels are encrypted. Primary dispatch channels have historically been clear but status can change.

## Local Resources

- [Broadcastify Hamilton County](https://www.broadcastify.com/listen/ctid/2070)
- [Broadcastify Cincinnati Metro](https://www.broadcastify.com/listen/mid/93)
- [RadioReference Hamilton County](https://www.radioreference.com/db/browse/ctid/2070)
- Delhi Township Police: [Official Site](http://www.delhi.oh.us) | [@DelhiTwpPolice](https://x.com/DelhiTwpPolice)

## Contributing

Pull requests welcome for:
- Updated feed status notes
- Additional clear talkgroups specific to the Cincinnati area
- Improved documentation or a simple web player page

Please keep the scope **strictly Cincinnati / Hamilton County** (including Delhi Township). Do not expand to surrounding counties unless they share significant mutual-aid traffic relevant to the core area.

---

*Built for local listeners who want clean, focused coverage of the Cincinnati area.*
