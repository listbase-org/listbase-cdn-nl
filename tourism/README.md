# Toerisme (Tourism)

16 datasets — 28,595 records

> Browse at [listbase.org/nl/tourism/](https://listbase.org/nl/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Netherlands Tourist Information Points (tourism=information)](nl-toeristische-informatie.json) | 6,372 | 662 KB | [CSV](nl-toeristische-informatie_NL.csv) | [Excel](nl-toeristische-informatie_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-toeristische-informatie/) |
| [Netherlands Public Artworks (tourism=artwork)](nl-kunstwerken.json) | 5,936 | 595 KB | [CSV](nl-kunstwerken_NL.csv) | [Excel](nl-kunstwerken_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-kunstwerken/) |
| [Netherlands Camp sites (tourism=camp_site)](nl-campings.json) | 3,174 | 328 KB | [CSV](nl-campings_NL.csv) | [Excel](nl-campings_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-campings/) |
| [Netherlands Holiday Chalets (tourism=chalet)](nl-chalets.json) | 2,894 | 277 KB | [CSV](nl-chalets_NL.csv) | [Excel](nl-chalets_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-chalets/) |
| [Netherlands Hotels (tourism=hotel)](nl-hotels.json) | 2,214 | 230 KB | [CSV](nl-hotels_NL.csv) | [Excel](nl-hotels_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-hotels/) |
| [Netherlands Guest Houses (tourism=guest_house)](nl-gastenverblijven.json) | 1,968 | 204 KB | [CSV](nl-gastenverblijven_NL.csv) | [Excel](nl-gastenverblijven_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-gastenverblijven/) |
| [Netherlands Attractions (tourism=attraction)](nl-attracties.json) | 1,752 | 180 KB | [CSV](nl-attracties_NL.csv) | [Excel](nl-attracties_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-attracties/) |
| [Netherlands OSM: museum (tourism=museum)](nl-osm-tourism-museum.json) | 1,282 | 206 KB | [CSV](nl-osm-tourism-museum_NL.csv) | [Excel](nl-osm-tourism-museum_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-museum/) |
| [Netherlands OSM: zoo (tourism=zoo)](nl-osm-tourism-zoo.json) | 482 | 77 KB | [CSV](nl-osm-tourism-zoo_NL.csv) | [Excel](nl-osm-tourism-zoo_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-zoo/) |
| [Netherlands OSM: camp pitch (tourism=camp_pitch)](nl-osm-tourism-camp-pitch.json) | 431 | 69 KB | [CSV](nl-osm-tourism-camp-pitch_NL.csv) | [Excel](nl-osm-tourism-camp-pitch_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-camp-pitch/) |
| [Netherlands OSM: caravan site (tourism=caravan_site)](nl-osm-tourism-caravan-site.json) | 426 | 74 KB | [CSV](nl-osm-tourism-caravan-site_NL.csv) | [Excel](nl-osm-tourism-caravan-site_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-caravan-site/) |
| [Netherlands OSM: travel agency (shop=travel_agency)](nl-osm-shop-travel-agency.json) | 425 | 68 KB | [CSV](nl-osm-shop-travel-agency_NL.csv) | [Excel](nl-osm-shop-travel-agency_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-shop-travel-agency/) |
| [Viewpoints in the Netherlands](nl-uitzichtpunten.json) | 373 | 39 KB | [CSV](nl-uitzichtpunten_NL.csv) | [Excel](nl-uitzichtpunten_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-uitzichtpunten/) |
| [Netherlands OSM: gallery (tourism=gallery)](nl-osm-tourism-gallery.json) | 347 | 56 KB | [CSV](nl-osm-tourism-gallery_NL.csv) | [Excel](nl-osm-tourism-gallery_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-gallery/) |
| [Netherlands OSM: apartment (tourism=apartment)](nl-osm-tourism-apartment.json) | 342 | 56 KB | [CSV](nl-osm-tourism-apartment_NL.csv) | [Excel](nl-osm-tourism-apartment_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-apartment/) |
| [Netherlands OSM: hostel (tourism=hostel)](nl-osm-tourism-hostel.json) | 177 | 30 KB | [CSV](nl-osm-tourism-hostel_NL.csv) | [Excel](nl-osm-tourism-hostel_NL.xlsx) | [View](https://listbase.org/nl/tourism/nl-osm-tourism-hostel/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/tourism/nl-toeristische-informatie.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/tourism/)
