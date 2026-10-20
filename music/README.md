# Muziek (Music)

1 datasets — 195 records

> Browse at [listbase.org/nl/music/](https://listbase.org/nl/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands OSM: music (shop=music)](nl-osm-shop-music.json) | 195 | 31 KB | [CSV](nl-osm-shop-music_NL.csv) | [Excel](nl-osm-shop-music_NL.xlsx) | [View](https://listbase.org/nl/music/nl-osm-shop-music/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/music/nl-osm-shop-music.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/music/)
