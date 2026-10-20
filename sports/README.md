# Sport (Sports)

11 datasets — 5,651 records

> Browse at [listbase.org/nl/sports/](https://listbase.org/nl/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Eredivisie — wedstrijduitslagen 2018/19–2025/26 (2373)](nl-eredivisie-wedstrijden.json) | 2,373 | 1163 KB | [CSV](nl-eredivisie-wedstrijden_NL.csv) | [Excel](nl-eredivisie-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-wedstrijden/) |
| [Netherlands OSM: sports (shop=sports)](nl-osm-shop-sports.json) | 658 | 100 KB | [CSV](nl-osm-shop-sports_NL.csv) | [Excel](nl-osm-shop-sports_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-osm-shop-sports/) |
| [Eredivisie 2018/19 — wedstrijduitslagen (306)](nl-eredivisie-2018-19-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2018-19-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2018-19-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2018-19-wedstrijden/) |
| [Eredivisie 2020/21 — wedstrijduitslagen (306)](nl-eredivisie-2020-21-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2020-21-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2020-21-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2020-21-wedstrijden/) |
| [Eredivisie 2021/22 — wedstrijduitslagen (306)](nl-eredivisie-2021-22-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2021-22-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2021-22-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2021-22-wedstrijden/) |
| [Eredivisie 2022/23 — wedstrijduitslagen (306)](nl-eredivisie-2022-23-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2022-23-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2022-23-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2022-23-wedstrijden/) |
| [Eredivisie 2023/24 — wedstrijduitslagen (306)](nl-eredivisie-2023-24-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2023-24-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2023-24-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2023-24-wedstrijden/) |
| [Eredivisie 2024/25 — wedstrijduitslagen (306)](nl-eredivisie-2024-25-wedstrijden.json) | 306 | 153 KB | [CSV](nl-eredivisie-2024-25-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2024-25-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2024-25-wedstrijden/) |
| [Eredivisie 2025/26 — wedstrijduitslagen (305)](nl-eredivisie-2025-26-wedstrijden.json) | 305 | 153 KB | [CSV](nl-eredivisie-2025-26-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2025-26-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2025-26-wedstrijden/) |
| [Netherlands OSM: sports hall (leisure=sports_hall)](nl-osm-leisure-sports-hall.json) | 247 | 42 KB | [CSV](nl-osm-leisure-sports-hall_NL.csv) | [Excel](nl-osm-leisure-sports-hall_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-osm-leisure-sports-hall/) |
| [Eredivisie 2019/20 — wedstrijduitslagen (232)](nl-eredivisie-2019-20-wedstrijden.json) | 232 | 117 KB | [CSV](nl-eredivisie-2019-20-wedstrijden_NL.csv) | [Excel](nl-eredivisie-2019-20-wedstrijden_NL.xlsx) | [View](https://listbase.org/nl/sports/nl-eredivisie-2019-20-wedstrijden/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/sports/nl-eredivisie-wedstrijden.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/sports/)
