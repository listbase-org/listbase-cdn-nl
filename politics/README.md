# Politiek (Politics)

1 datasets — 648 records

> Browse at [listbase.org/nl/politics/](https://listbase.org/nl/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands OSM: government (office=government)](nl-osm-office-government.json) | 648 | 109 KB | [CSV](nl-osm-office-government_NL.csv) | [Excel](nl-osm-office-government_NL.xlsx) | [View](https://listbase.org/nl/politics/nl-osm-office-government/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/politics/nl-osm-office-government.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/politics/)
