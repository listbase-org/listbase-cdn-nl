# Cultuur en religie (Culture & Religion)

10 datasets — 9,015 records

> Browse at [listbase.org/nl/culture/](https://listbase.org/nl/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Dutch church buildings (Kerkgebouwen in Nederland)](nl-kerkgebouwen.json) | 2,780 | 20441 KB | [CSV](nl-kerkgebouwen_NL.csv) | [Excel](nl-kerkgebouwen_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-kerkgebouwen/) |
| [Kastelen in Nederland](nl-kastelen.json) | 1,969 | 17321 KB | [CSV](nl-kastelen_NL.csv) | [Excel](nl-kastelen_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-kastelen/) |
| [Molens in Nederland (Windmills and Watermills in the Netherlands)](nl-molens.json) | 1,682 | 2343 KB | [CSV](nl-molens_NL.csv) | [Excel](nl-molens_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-molens/) |
| [Theatres in the Netherlands](nl-theaters.json) | 684 | 70 KB | [CSV](nl-theaters_NL.csv) | [Excel](nl-theaters_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-theaters/) |
| [Musea in Nederland (Museums in the Netherlands)](nl-musea.json) | 661 | 146 KB | [CSV](nl-musea_NL.csv) | [Excel](nl-musea_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-musea/) |
| [Kloosters in Nederland](nl-kloosters.json) | 556 | 185 KB | [CSV](nl-kloosters_NL.csv) | [Excel](nl-kloosters_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-kloosters/) |
| [Netherlands OSM: art (shop=art)](nl-osm-shop-art.json) | 370 | 57 KB | [CSV](nl-osm-shop-art_NL.csv) | [Excel](nl-osm-shop-art_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-osm-shop-art/) |
| [Cinemas in the Netherlands](nl-bioscopen.json) | 207 | 22 KB | [CSV](nl-bioscopen_NL.csv) | [Excel](nl-bioscopen_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-bioscopen/) |
| [Synagogen in Nederland](nl-synagoges.json) | 96 | 33 KB | [CSV](nl-synagoges_NL.csv) | [Excel](nl-synagoges_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-synagoges/) |
| [Werelderfgoed van UNESCO in Nederland](nl-werelderfgoed-unesco.json) | 10 | 12 KB | [CSV](nl-werelderfgoed-unesco_NL.csv) | [Excel](nl-werelderfgoed-unesco_NL.xlsx) | [View](https://listbase.org/nl/culture/nl-werelderfgoed-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/culture/nl-kerkgebouwen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/culture/)
