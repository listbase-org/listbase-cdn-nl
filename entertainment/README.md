# Entertainment (Entertainment)

2 datasets — 1,332 records

> Browse at [listbase.org/nl/entertainment/](https://listbase.org/nl/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Boekwinkels in Nederland](nl-boekwinkels.json) | 1,135 | 113 KB | [CSV](nl-boekwinkels_NL.csv) | [Excel](nl-boekwinkels_NL.xlsx) | [View](https://listbase.org/nl/entertainment/nl-boekwinkels/) |
| [Nachtclubs in Nederland](nl-nachtclubs.json) | 197 | 20 KB | [CSV](nl-nachtclubs_NL.csv) | [Excel](nl-nachtclubs_NL.xlsx) | [View](https://listbase.org/nl/entertainment/nl-nachtclubs/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.nl.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.nl.listbase.org/entertainment/nl-boekwinkels.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/nl/entertainment/)
