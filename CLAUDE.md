# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Two visualizations of 3,797 Bigfoot sightings from the BFRO database (1869-2023), rendered as footprints on a D3.js geographic projection of North America.

Live at: https://dr.eamer.dev/datavis/poems/bigfoot/

See `README.md` for feature details and data structure.

## Files

| File | View | Description |
|------|------|-------------|
| `big-foot.html` | Individual footprints | Each sighting as a standalone footprint marker |
| `big-feet.html` | Clustered footprints | Sightings grouped into path-connected clusters |
| `data/bigfoot.json` | Dataset | 3,797 sightings with lat/lon, date, state, county, description |
| `big-foot-social.png` | Social card | OG image for individual view |
| `big-feet-social.png` | Social card | OG image for clustered view |

## Technology

- **D3.js v7**: Geographic projections (Albers USA)
- **Canvas/SVG hybrid**: Rendering
- **Fonts**: Inter (UI), JetBrains Mono (data values)

## Parent Documentation

- `../CLAUDE.md` — Poems collection overview
- `../STYLE_GUIDE.md` — Full design system
