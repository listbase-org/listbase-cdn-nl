# Economie (Economy)

1 datasets — 591 records

> Browse at [listbase.org/nl/economy/](https://listbase.org/nl/economy/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands OSM: employment agency (office=employment_agency)](nl-osm-office-employment-agency.json) | 591 | 98 KB | [CSV](nl-osm-office-employment-agency_NL.csv) | [Excel](nl-osm-office-employment-agency_NL.xlsx) | [View](https://listbase.org/nl/economy/nl-osm-office-employment-agency/) |

## Quick Start

```bash
# List all economy datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="economy") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/economy/nl-osm-office-employment-agency.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/economy/)
