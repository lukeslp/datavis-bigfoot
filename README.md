# BIGFOOT

3,797 Bigfoot sightings from the BFRO database, drawn as footprints across North America. Two visualization styles show sighting patterns from 1869 to present.

## Visualizations

1. **big-foot.html** - Individual footprints for each sighting
2. **big-feet.html** - Clustered footprint patterns

Both versions let you pan, zoom, and click individual sightings for details (date, location, description).

## Features

- **3,797 sightings**: Complete BFRO database
- **Geographic accuracy**: Lat/lon coordinates
- **Interactive map**: Pan, zoom, click for details
- **Timeline**: 150+ years of sightings (1869-2023)
- **Clustering**: Reveals hotspots (Pacific Northwest, Appalachia)

## Technical Stack

- **D3.js v7**: Geographic projections
- **Canvas/SVG**: Hybrid rendering
- **Vanilla JavaScript**: No frameworks
- **Inter + JetBrains Mono fonts**: Clean monospace aesthetic

## Files

- `big-foot.html` - Individual footprints view
- `big-feet.html` - Clustered footprints view
- `data/bigfoot.json` - BFRO sightings database
- `big-foot-social.png` - Social card (individual view)
- `big-feet-social.png` - Social card (clustered view)

## Data Structure

```json
{
  "date": "2023-05-15",
  "latitude": 47.6062,
  "longitude": -122.3321,
  "state": "Washington",
  "county": "King",
  "description": "..."
}
```

## Local Development

```bash
python3 -m http.server 8000
# Visit http://localhost:8000/big-foot.html
# Visit http://localhost:8000/big-feet.html
```

## Data Source

Bigfoot Field Researchers Organization (BFRO)
https://www.bfro.net/

## Author

Luke Steuber
https://lukesteuber.com
