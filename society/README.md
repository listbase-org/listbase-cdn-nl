# Maatschappij (Society)

3 datasets — 2,889 records

> Browse at [listbase.org/nl/society/](https://listbase.org/nl/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands OSM: social facility (amenity=social_facility)](nl-osm-amenity-social-facility.json) | 2,300 | 383 KB | [CSV](nl-osm-amenity-social-facility_NL.csv) | [Excel](nl-osm-amenity-social-facility_NL.xlsx) | [View](https://listbase.org/nl/society/nl-osm-amenity-social-facility/) |
| [Politiebureaus in Nederland](nl-politiebureaus.json) | 428 | 48 KB | [CSV](nl-politiebureaus_NL.csv) | [Excel](nl-politiebureaus_NL.xlsx) | [View](https://listbase.org/nl/society/nl-politiebureaus/) |
| [Netherlands OSM: charity (shop=charity)](nl-osm-shop-charity.json) | 161 | 27 KB | [CSV](nl-osm-shop-charity_NL.csv) | [Excel](nl-osm-shop-charity_NL.xlsx) | [View](https://listbase.org/nl/society/nl-osm-shop-charity/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/society/nl-osm-amenity-social-facility.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/society/)
