# 🌋 Earth Volcanoes

An interactive web map of global volcanic activity — combining Holocene volcanoes from the Global Volcanism Program and submarine/island volcanism from recent literature.

---

## What's in this map

| Layer | Source | n | Info shown |
|---|---|---|---|
| 🔴 GVP Holocene Volcanoes | Global Volcanism Program, VOTW 5.3.5 (2026) | 1,215 | Name, volcanic arc/region, primary type, last eruption |
| 🔵 Submarine & Volcanic Islands | Maeno, *Bull. Volc.* (2025) | 422 | Name, type, tectonic setting, depth, eruption period, VEI, tsunami, island formation |

Markers are color-coded by **tectonic setting** — warm tones (red–orange) for GVP, cool tones (blue–green–yellow) for Maeno. Both layers can be toggled on/off independently.

---

## How to use

1. **Toggle layers** — click either dataset label in the sidebar to show/hide it
2. **Filter** — narrow by tectonic setting, dataset, or search by name/region/country
3. **Click any marker** — full details appear in the info panel

---

## Files

```
earth-volcanoes/
├── earth_volcanoes_v1.html   # Main map (self-contained, no server needed)
└── README.md
```

The map is a single self-contained HTML file — no dependencies to install, no server required. Just open it in a browser or host it on GitHub Pages.

---

## Data sources

- **Global Volcanism Program** (2026). *Volcanoes of the World (v. 5.3.5)*. Venzke, E (ed.). Smithsonian Institution. [volcano.si.edu](https://volcano.si.edu)
- **Maeno, F.** (2025). Historical submarine and island-forming volcanic eruptions. *Bulletin of Volcanology*, 87. [doi:10.1007/s00445-025-1871-y](https://doi.org/10.1007/s00445-025-1871-y)
