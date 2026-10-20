# Milieu (Environment)

9 datasets — 9,196 records

> Browse at [listbase.org/nl/environment/](https://listbase.org/nl/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands Named Water Bodies (natural=water)](nl-meren-en-plassen.json) | 6,465 | 635 KB | [CSV](nl-meren-en-plassen_NL.csv) | [Excel](nl-meren-en-plassen_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-meren-en-plassen/) |
| [Energiecentrales in Nederland](nl-energiecentrales.json) | 780 | 398 KB | [CSV](nl-energiecentrales_NL.csv) | [Excel](nl-energiecentrales_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-energiecentrales/) |
| [Netherlands OSM: tree (natural=tree)](nl-osm-natural-tree.json) | 558 | 88 KB | [CSV](nl-osm-natural-tree_NL.csv) | [Excel](nl-osm-natural-tree_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-tree/) |
| [Netherlands OSM: peak (natural=peak)](nl-osm-natural-peak.json) | 422 | 65 KB | [CSV](nl-osm-natural-peak_NL.csv) | [Excel](nl-osm-natural-peak_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-peak/) |
| [Netherlands OSM: wetland (natural=wetland)](nl-osm-natural-wetland.json) | 303 | 49 KB | [CSV](nl-osm-natural-wetland_NL.csv) | [Excel](nl-osm-natural-wetland_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-wetland/) |
| [Netherlands OSM: heath (natural=heath)](nl-osm-natural-heath.json) | 222 | 36 KB | [CSV](nl-osm-natural-heath_NL.csv) | [Excel](nl-osm-natural-heath_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-heath/) |
| [Netherlands OSM: beach (natural=beach)](nl-osm-natural-beach.json) | 207 | 34 KB | [CSV](nl-osm-natural-beach_NL.csv) | [Excel](nl-osm-natural-beach_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-beach/) |
| [Netherlands OSM: wood (natural=wood)](nl-osm-natural-wood.json) | 168 | 27 KB | [CSV](nl-osm-natural-wood_NL.csv) | [Excel](nl-osm-natural-wood_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-osm-natural-wood/) |
| [Elektriciteitscentrales in Nederland](nl-elektriciteitscentrales.json) | 71 | 30 KB | [CSV](nl-elektriciteitscentrales_NL.csv) | [Excel](nl-elektriciteitscentrales_NL.xlsx) | [View](https://listbase.org/nl/environment/nl-elektriciteitscentrales/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/environment/nl-meren-en-plassen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/environment/)
