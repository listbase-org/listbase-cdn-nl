# Wetenschap (Science)

2 datasets — 1,141 records

> Browse at [listbase.org/nl/science/](https://listbase.org/nl/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Dierenartsen in Nederland](nl-dierenartsen.json) | 679 | 75 KB | [CSV](nl-dierenartsen_NL.csv) | [Excel](nl-dierenartsen_NL.xlsx) | [View](https://listbase.org/nl/science/nl-dierenartsen/) |
| [Netherlands OSM: parking space (amenity=parking_space)](nl-osm-amenity-parking-space.json) | 462 | 73 KB | [CSV](nl-osm-amenity-parking-space_NL.csv) | [Excel](nl-osm-amenity-parking-space_NL.xlsx) | [View](https://listbase.org/nl/science/nl-osm-amenity-parking-space/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/science/nl-dierenartsen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/science/)
