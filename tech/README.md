# Technologie (Technology)

1 datasets — 360 records

> Browse at [listbase.org/nl/tech/](https://listbase.org/nl/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands OSM: ferry terminal (amenity=ferry_terminal)](nl-osm-amenity-ferry-terminal.json) | 360 | 62 KB | [CSV](nl-osm-amenity-ferry-terminal_NL.csv) | [Excel](nl-osm-amenity-ferry-terminal_NL.xlsx) | [View](https://listbase.org/nl/tech/nl-osm-amenity-ferry-terminal/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/tech/nl-osm-amenity-ferry-terminal.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/tech/)
