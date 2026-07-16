# Te Ika-a-Māui / North Island Tracks

An interactive hiking guide to ten North Island (New Zealand) walks, built as a single static page with real maps and licensed photography. Facts last checked **16 July 2026** — always confirm alerts, fees and access with the linked official sources before travelling.

## Run locally

Any static file server works:

```
python -m http.server 8080
# then open http://localhost:8080
```

## Deploy

The site is fully static (`index.html` + `assets/`). Deploy the folder as-is to GitHub Pages, Netlify, Cloudflare Pages, or any static host.

## Data & licence attributions

- **Base maps (loaded at runtime):** © OpenStreetMap contributors; topo style © [OpenTopoMap](https://opentopomap.org) (CC-BY-SA); satellite tiles © Esri — Source: Esri, Maxar, Earthstar Geographics, and the GIS User Community.
- **Track geometry (`assets/tracks/*.geojson`):**
  - Department of Conservation Tracks open data (via the DOC ArcGIS `DTO/WalkingAndTramping` service), licensed CC-BY 4.0 — Tongariro Alpine Crossing, Tama Lakes, Mangorei (Pouākai), Duke's Nose/Wairakau, Wairere Falls, Ōtaki Forks–Field–Kime, Holdsworth–Powell, Castlepoint Lighthouse Walk. Retrieved 16 Jul 2026 and filtered to each track's bounding box.
  - © OpenStreetMap contributors (ODbL) — Paekākāriki Escarpment Track, Mercer Bay Loop, Deliverance Cove Track. Retrieved 16 Jul 2026 via Overpass API.
- **Photographs:** hotlinked from Wikimedia Commons; each image is credited in-page with photographer, licence and a link to its Commons file page (CC BY 2.0 / CC BY-SA 2.0 / CC BY-SA 4.0 / public domain).
- Guide text and elevation profiles are original; profiles are approximate illustrations, not survey data.

## Disclaimer

This site is a planning aid, not a navigation device, and does not replace official Department of Conservation track information, MetService forecasts, or your own preparation and judgement.
