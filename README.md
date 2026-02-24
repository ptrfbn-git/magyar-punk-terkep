# Magyar Punk Térkép 🗺️

An interactive map of Hungarian punk concerts from the **punkportal.hu** archive, covering 2002–2021.

**[→ Open the map](https://ptrfbn-git.github.io/magyar-punk-terkep/)**

---

## What it is

11 980 concerts, geocoded and placed on a map of Hungary and surrounding regions. Each dot represents a venue; clicking it shows the concerts that took place there. The data comes from the punkportal.hu concert archive, which documented the Hungarian punk, hardcore, and ska scene for two decades.

Features:
- Search by band name — see every concert they played, on the map and in a list
- Filter by year with a slider
- Browse by city or venue
- 314 concerts link directly to photo galleries on punkportal.fw.hu, with thumbnails
- A random gallery concert is shown in the corner on each page load ("Erre emlékszel?")
- Fully responsive — works on desktop, tablet, and mobile

## How to use

Open `index.html` in any modern browser. No server, no dependencies, no installation — it's a single self-contained file.

The only external connections made at runtime are:
- [Leaflet.js](https://leafletjs.com/) — map library (via CDN)
- [OpenStreetMap](https://www.openstreetmap.org/) — map tiles
- Google Fonts (Space Mono + Barlow Condensed)
- Photo thumbnails from punkportal.fw.hu (only for concerts with gallery links)

## Data

All concert data is sourced from [punkportal.hu](http://punkportal.hu) — a Hungarian punk community archive. The coordinates were geocoded from venue names and cities. A small number of events with ambiguous or missing location data are excluded from the map.

## License

The code and map interface are released under the [MIT License](LICENSE). Concert data and photos belong to their respective authors at punkportal.hu.
