# Voedsel (Food & Nutrition)

15 datasets — 32,412 records

> Browse at [listbase.org/nl/food/](https://listbase.org/nl/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands Restaurants](nl-restaurants.json) | 17,287 | 1707 KB | [CSV](nl-restaurants_NL.csv) | [Excel](nl-restaurants_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants/) |
| [Netherlands Fast food (amenity=fast_food)](nl-fastfoodrestaurants.json) | 8,250 | 811 KB | [CSV](nl-fastfoodrestaurants_NL.csv) | [Excel](nl-fastfoodrestaurants_NL.xlsx) | [View](https://listbase.org/nl/food/nl-fastfoodrestaurants/) |
| [Netherlands Bakeries (shop=bakery)](nl-bakkerijen.json) | 2,857 | 290 KB | [CSV](nl-bakkerijen_NL.csv) | [Excel](nl-bakkerijen_NL.xlsx) | [View](https://listbase.org/nl/food/nl-bakkerijen/) |
| [Slagerijen in Nederland](nl-slagerijen.json) | 1,385 | 143 KB | [CSV](nl-slagerijen_NL.csv) | [Excel](nl-slagerijen_NL.xlsx) | [View](https://listbase.org/nl/food/nl-slagerijen/) |
| [Netherlands OSM: cheese (shop=cheese)](nl-osm-shop-cheese.json) | 573 | 89 KB | [CSV](nl-osm-shop-cheese_NL.csv) | [Excel](nl-osm-shop-cheese_NL.xlsx) | [View](https://listbase.org/nl/food/nl-osm-shop-cheese/) |
| [Groenteboeren in Nederland](nl-groenteboeren.json) | 531 | 56 KB | [CSV](nl-groenteboeren_NL.csv) | [Excel](nl-groenteboeren_NL.xlsx) | [View](https://listbase.org/nl/food/nl-groenteboeren/) |
| [Michelin-restaurants in Nederland](nl-restaurants-michelin.json) | 499 | 568 KB | [CSV](nl-restaurants-michelin_NL.csv) | [Excel](nl-restaurants-michelin_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-michelin/) |
| [Netherlands OSM: wine (shop=wine)](nl-osm-shop-wine.json) | 313 | 49 KB | [CSV](nl-osm-shop-wine_NL.csv) | [Excel](nl-osm-shop-wine_NL.xlsx) | [View](https://listbase.org/nl/food/nl-osm-shop-wine/) |
| [Netherlands OSM: chocolate (shop=chocolate)](nl-osm-shop-chocolate.json) | 258 | 42 KB | [CSV](nl-osm-shop-chocolate_NL.csv) | [Excel](nl-osm-shop-chocolate_NL.xlsx) | [View](https://listbase.org/nl/food/nl-osm-shop-chocolate/) |
| [Netherlands OSM: health food (shop=health_food)](nl-osm-shop-health-food.json) | 245 | 41 KB | [CSV](nl-osm-shop-health-food_NL.csv) | [Excel](nl-osm-shop-health-food_NL.xlsx) | [View](https://listbase.org/nl/food/nl-osm-shop-health-food/) |
| [1-ster-restaurants in Nederland (Michelin)](nl-restaurants-michelin-1-ster.json) | 96 | 114 KB | [CSV](nl-restaurants-michelin-1-ster_NL.csv) | [Excel](nl-restaurants-michelin-1-ster_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-michelin-1-ster/) |
| [Bib Gourmand-restaurants in Nederland (Michelin)](nl-restaurants-bib-gourmand.json) | 75 | 88 KB | [CSV](nl-restaurants-bib-gourmand_NL.csv) | [Excel](nl-restaurants-bib-gourmand_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-bib-gourmand/) |
| [Groene-ster-restaurants in Nederland (Michelin)](nl-restaurants-michelin-groene-ster.json) | 23 | 29 KB | [CSV](nl-restaurants-michelin-groene-ster_NL.csv) | [Excel](nl-restaurants-michelin-groene-ster_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-michelin-groene-ster/) |
| [2-sterren-restaurants in Nederland (Michelin)](nl-restaurants-michelin-2-sterren.json) | 19 | 24 KB | [CSV](nl-restaurants-michelin-2-sterren_NL.csv) | [Excel](nl-restaurants-michelin-2-sterren_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-michelin-2-sterren/) |
| [3-sterren-restaurants in Nederland (Michelin)](nl-restaurants-michelin-3-sterren.json) | 1 | 3 KB | [CSV](nl-restaurants-michelin-3-sterren_NL.csv) | [Excel](nl-restaurants-michelin-3-sterren_NL.xlsx) | [View](https://listbase.org/nl/food/nl-restaurants-michelin-3-sterren/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/food/nl-restaurants.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/food/)
