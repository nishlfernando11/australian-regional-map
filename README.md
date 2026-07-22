# Australia Regional Migration Map

**An interactive map for exploring Australian skilled migration regional areas — Category 2 & Category 3 postcodes at a glance.**

> 🚧 **Work in progress** — This project is actively under development and **not publicly live yet**. What you see below is a preview of the tool we are building. More features, refinements, and a public launch are on the way. Stay tuned.

---

## Demo

See the app in action — search, click the map, filter categories, and browse the postcode reference sidebar.

<video controls width="100%" height="auto" autoplay muted playsinline preload="auto">
  <source src="https://rawcdn.githack.com/nishlfernando11/australian-regional-map/0265df28c60af6fa89a38885f723e9234530aa9c/regional-map-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## What is this?

The **Australia Regional Migration Map** is a web application that visualises **Designated Regional Areas** for Australia's skilled migration program — specifically **Category 2** (Cities & Major Regional Centres) and **Category 3** (Regional Centres & Other Regional Areas) as defined by the [Department of Home Affairs](https://immi.homeaffairs.gov.au/visas/working-in-australia/skill-occupation-list/regional-postcodes).

Instead of scrolling through long postcode PDFs, you get a **satellite map of Australia** with colour-coded regional overlays, click-to-identify boundaries, and a searchable postcode reference — all in one place.

---

## Who is it for?

| Audience | How it helps |
| --- | --- |
| **Prospective migrants** | Quickly see whether a suburb or postcode falls under Category 2 or 3 regional benefits |
| **Migration agents & advisors** | Look up postcodes during client consultations without cross-referencing static lists |
| **Employers & HR teams** | Check whether a work location qualifies as regional for visa sponsorship planning |
| **Students & researchers** | Explore regional classification patterns across states and territories |

---

## Features

| Feature | Description |
| --- | --- |
| **Satellite & hybrid map** | Google Maps with satellite, hybrid, terrain, and road views |
| **Category 2 overlays** | Blue postcode-level shading for Cities & Major Regional Centres |
| **Category 3 overlays** | Green shading for Regional Centres & Other Regional Areas |
| **Click to identify** | Click anywhere on the map → reverse geocode → draw the exact postcode boundary with a category tooltip |
| **Filter pills** | Show All, Category 2 only, or Category 3 only — sidebar and map stay in sync |
| **Postcode sidebar** | State-by-state accordion with every regional postcode, filterable, with visa benefit notes |
| **Search** | Find cities, states, or postcodes — the map pans and zooms to your match |
| **State overview** | Toggle a full-state Category 3 overlay for quick regional scanning |
| **Privacy-aware** | Cookie consent before map load; privacy notice for data use |

---

## How it looks

The interface is designed as a focused lookup tool:

- **Header** — brand title, search bar, map type switcher (Map / Terrain / Satellite / Hybrid)
- **Main map** — full-screen interactive map with colour-coded regional overlays and a legend
- **Click instruction** — gentle prompt to click the map and identify a postcode category
- **Postcode sidebar** — collapsible panel listing every regional postcode grouped by state, with filter pills
- **Footer** — data source attribution and link to privacy notice

Dark-theme, responsive layout — built for clarity during fast lookups, not clutter.

---

## How it helps

1. **Instant visual answer** — Is this postcode regional? Blue, green, or grey tells you in seconds.
2. **Accurate boundaries** — Postcode polygons come from official ABS GIS data, not approximations.
3. **Less manual work** — No more Ctrl+F through government PDFs for every client question.
4. **Context on the map** — See how regional areas relate geographically — coastlines, neighbouring towns, state borders.
5. **Reference + exploration** — Use the sidebar as a directory, or the map for discovery.

---

## Data sources

All regional classifications and geographic data come from authoritative public sources:

| Data | Source | Licence |
| --- | --- | --- |
| Category 2 & 3 postcode classification | [Department of Home Affairs — Regional postcodes (LIN 22/022)](https://immi.homeaffairs.gov.au/visas/working-in-australia/skill-occupation-list/regional-postcodes) | Public |
| Postcode boundary polygons (GeoJSON) | [ABS ASGS 2021 — Postal Areas FeatureServer](https://geo.abs.gov.au/arcgis/rest/services/ASGS2021/POA/FeatureServer) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| State boundary GeoJSON | [rowanhogan/australian-states](https://github.com/rowanhogan/australian-states) | MIT |
| Map tiles & geocoding | [Google Maps Platform](https://developers.google.com/maps) | Paid (free tier available) |

Regional categories reflect the Department of Home Affairs designation at the time of the app's data snapshot. Always verify against the latest official list before making migration decisions.

---

## Disclaimer

> **This tool is for general information and exploration only. It is not legal, migration, or professional advice.**

- **Not affiliated** with the Department of Home Affairs, Australian Border Force, or any government agency.
- **Not a substitute** for official guidance, a registered migration agent, or legal counsel.
- **Data may lag** behind official updates — regional postcode lists can change; confirm on [immi.homeaffairs.gov.au](https://immi.homeaffairs.gov.au/) before relying on any result.
- **No warranty** — the app is provided as-is, without guarantee of accuracy, completeness, or availability.
- **Your responsibility** — visa eligibility depends on many factors beyond postcode classification (occupation, visa subclass, points, employer requirements, etc.).

If you are making decisions that affect your visa, employment, or residency status, consult a **registered migration agent** or qualified professional.

---

## Roadmap

We are building toward a full public release. Planned and in-progress work includes:

- Public launch with open access (no login required)
- Additional map layers and export options
- Improved mobile experience
- More frequent sync with official postcode updates
- Performance and accessibility refinements

**The map is under development — not live for public use yet. More features to come.**

---

## Status

| | |
| --- | --- |
| **Stage** | Private beta / active development |
| **Public access** | Not yet available |
| **Last updated** | July 2026 |

---

## Licence

Documentation and project materials in this repository are published for public visibility. Application source code and deployment are maintained separately.

For questions about this project, open an issue in this repository once it is published.

---

<p align="center">
  <sub>Built to make Australian regional migration geography easier to understand — one postcode at a time.</sub>
</p>
