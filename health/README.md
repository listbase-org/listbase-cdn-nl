# Gezondheid (Health)

5 datasets — 8,367 records

> Browse at [listbase.org/nl/health/](https://listbase.org/nl/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Drogisterijen in Nederland](nl-drogisterijen.json) | 2,141 | 202 KB | [CSV](nl-drogisterijen_NL.csv) | [Excel](nl-drogisterijen_NL.xlsx) | [View](https://listbase.org/nl/health/nl-drogisterijen/) |
| [Huisartsen in Nederland](nl-huisartsen.json) | 2,104 | 236 KB | [CSV](nl-huisartsen_NL.csv) | [Excel](nl-huisartsen_NL.xlsx) | [View](https://listbase.org/nl/health/nl-huisartsen/) |
| [Opticiens in Nederland](nl-opticiens.json) | 1,807 | 178 KB | [CSV](nl-opticiens_NL.csv) | [Excel](nl-opticiens_NL.xlsx) | [View](https://listbase.org/nl/health/nl-opticiens/) |
| [Tandartsen in Nederland](nl-tandartsen.json) | 1,787 | 193 KB | [CSV](nl-tandartsen_NL.csv) | [Excel](nl-tandartsen_NL.xlsx) | [View](https://listbase.org/nl/health/nl-tandartsen/) |
| [Klinieken in Nederland](nl-klinieken.json) | 528 | 57 KB | [CSV](nl-klinieken_NL.csv) | [Excel](nl-klinieken_NL.xlsx) | [View](https://listbase.org/nl/health/nl-klinieken/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/health/nl-drogisterijen.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/health/)
