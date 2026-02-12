# King County Cities Explorer

**[View Live Site](https://rboenish.github.io/king-county-cities-explorer/)**

An interactive map and data explorer for all 39 incorporated cities in King County, Washington.

![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

A single-page web application that plots every incorporated city in King County on an SVG map with population-scaled markers. Hover for a quick snapshot or click for a comprehensive profile covering demographics, government, leadership, elections, employers, and more.

## Features

- **Interactive SVG map** with King County boundary, Lake Washington, Lake Sammamish, and Puget Sound — fully self-contained, no external tile services
- **Population-scaled markers** color-coded by size tier (see legend)
- **Rich hover cards** showing population, income, home value, government type, mayor, and a demographic breakdown bar
- **Full detail panel** (click any city) with:
  - Key statistics (population, income, home value, area, density, median age, incorporation year)
  - Demographic composition (bar chart + legend)
  - Government & leadership (structure, mayor, city manager, council size, meeting schedule/frequency)
  - Districts & representation (US Congress, WA Legislature, school district)
  - Election information
  - Major employers
  - Notable features and city website
- **Government filter** — toggle between All, Strong Mayor, Council-Manager, and Mayor-Council cities
- **Search** by city name, mayor, employers, or features
- **Pan & zoom** via mouse drag and scroll wheel
- **Responsive** layout for mobile and desktop

## Data Sources

| Data | Source | Vintage |
|------|--------|---------|
| Population | US Census 2020 (official) + WA OFM 2025 estimates | 2020 / 2025 |
| Income & Demographics | ACS 2019–2023 5-Year Estimates | Dec 2024 release |
| Government Officials | Individual city websites, Ballotpedia | Verified Jan 2026 |
| Election Results | King County Elections, Ballotpedia | Through Nov 2025 |
| Geographic Coordinates | Approximate city centers | — |

**Note:** Some cities straddle county lines: Auburn, Bothell, Milton, and Pacific are partially in adjacent counties.

## Getting Started

No build step required. Open `index.html` in any modern browser:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/king-county-cities-explorer.git
cd king-county-cities-explorer

# Open directly
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

Or serve locally:

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deployment

This is a static single-file site. Deploy anywhere that serves HTML:

- **GitHub Pages** — push to `main`, enable Pages in repo settings
- **Netlify / Vercel** — drag-and-drop or connect the repo
- **Any web server** — just serve `index.html`

## Cities Covered

All 39 incorporated cities in King County, WA — from Seattle (pop. ~791k) to Skykomish (pop. ~210):

Algona · Auburn · Beaux Arts Village · Bellevue · Black Diamond · Bothell · Burien · Carnation · Clyde Hill · Covington · Des Moines · Duvall · Enumclaw · Federal Way · Hunts Point · Issaquah · Kenmore · Kent · Kirkland · Lake Forest Park · Maple Valley · Medina · Mercer Island · Milton · Newcastle · Normandy Park · North Bend · Pacific · Redmond · Renton · Sammamish · SeaTac · Seattle · Shoreline · Skykomish · Snoqualmie · Tukwila · Woodinville · Yarrow Point

## License

MIT
