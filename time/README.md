# Tijd en kalender (Time & Calendar)

11 datasets — 6,217 records

> Browse at [listbase.org/nl/time/](https://listbase.org/nl/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Feestdagen in België – Volledige Lijst (1901–2030)](nl-belgie-feestdagen-completos.json) | 1,948 | 958 KB | [CSV](nl-belgie-feestdagen-completos_NL.csv) | [Excel](nl-belgie-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-belgie-feestdagen-completos/) |
| [Dianan di fiesta na Kòrsou — kompletu, 4 idiomanan (1955–2030)](nl-curacao-feestdagen-completos.json) | 905 | 317 KB | [CSV](nl-curacao-feestdagen-completos_NL.csv) | [Excel](nl-curacao-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-curacao-feestdagen-completos/) |
| [Dia di fiesta na Aruba — komplet, 4 idiomanan (1955–2030)](nl-aruba-feestdagen-completos.json) | 779 | 275 KB | [CSV](nl-aruba-feestdagen-completos_NL.csv) | [Excel](nl-aruba-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-aruba-feestdagen-completos/) |
| [Nederlandse feestdagen en gedenkdagen (1966–2030)](nl-feestdagen-en-gedenkdagen.json) | 711 | 373 KB | [CSV](nl-feestdagen-en-gedenkdagen_NL.csv) | [Excel](nl-feestdagen-en-gedenkdagen_NL.xlsx) | [View](https://listbase.org/nl/time/nl-feestdagen-en-gedenkdagen/) |
| [Surinaamse feestdagen — compleet, 2 talen (1972–2030)](nl-suriname-feestdagen-completos.json) | 671 | 174 KB | [CSV](nl-suriname-feestdagen-completos_NL.csv) | [Excel](nl-suriname-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-suriname-feestdagen-completos/) |
| [Sint-Maartense feestdagen — compleet, 2 talen (2011–2030)](nl-sint-maarten-feestdagen-completos.json) | 279 | 73 KB | [CSV](nl-sint-maarten-feestdagen-completos_NL.csv) | [Excel](nl-sint-maarten-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-sint-maarten-feestdagen-completos/) |
| [Sabaanse feestdagen — compleet, 4 talen (2011–2030)](nl-saba-feestdagen.json) | 240 | 89 KB | [CSV](nl-saba-feestdagen_NL.csv) | [Excel](nl-saba-feestdagen_NL.xlsx) | [View](https://listbase.org/nl/time/nl-saba-feestdagen/) |
| [Bonairaanse feestdagen — compleet, 4 talen (2011–2030)](nl-bonaire-feestdagen.json) | 232 | 86 KB | [CSV](nl-bonaire-feestdagen_NL.csv) | [Excel](nl-bonaire-feestdagen_NL.xlsx) | [View](https://listbase.org/nl/time/nl-bonaire-feestdagen/) |
| [Sint-Eustatiaanse feestdagen — compleet, 4 talen (2011–2030)](nl-sint-eustatius-feestdagen.json) | 229 | 85 KB | [CSV](nl-sint-eustatius-feestdagen_NL.csv) | [Excel](nl-sint-eustatius-feestdagen_NL.xlsx) | [View](https://listbase.org/nl/time/nl-sint-eustatius-feestdagen/) |
| [Feestdagen Caribisch Nederland (Bonaire, Saba, Sint Eustatius) — compleet, 4 talen (2011–2030)](nl-caribisch-nederland-feestdagen-completos.json) | 200 | 69 KB | [CSV](nl-caribisch-nederland-feestdagen-completos_NL.csv) | [Excel](nl-caribisch-nederland-feestdagen-completos_NL.xlsx) | [View](https://listbase.org/nl/time/nl-caribisch-nederland-feestdagen-completos/) |
| [Feestdagen en gedenkdagen in Nederland](nl-feestdagen.json) | 23 | 9 KB | [CSV](nl-feestdagen_NL.csv) | [Excel](nl-feestdagen_NL.xlsx) | [View](https://listbase.org/nl/time/nl-feestdagen/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/time/nl-belgie-feestdagen-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/time/)
