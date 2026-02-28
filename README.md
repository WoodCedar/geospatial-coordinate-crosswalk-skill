# geospatial-coordinate-crosswalk-skill

A reusable GIS skill for projected/geographic coordinate conversion with strict round-trip verification.

## Included
- `skills/geospatial-coordinate-crosswalk/SKILL.md`
- `marketplace.json`
- `.claude-plugin/plugin.json`

## Install (Marketplace URL)
After pushing this repo to GitHub:

```bash
/plugin marketplace add https://github.com/WoodCedar/geospatial-coordinate-crosswalk-skill
/plugin
```

## What this skill covers
- Projected CRS <-> geographic CRS conversion workflow
- Round-trip validation (`max|dX|`, `max|dY|`, `max2D`)
- Failure signatures (datum/zone/OCR errors)

## License
MIT
