# ListBase CDN — Nederlands (nl)

Open dataset collection for **Nederlands** (Dutch).
475 datasets across 20 categories with 970,657 total records.

> Browse and download at [https://listbase.org/nl/](https://listbase.org/nl/)

## Categories

| Category | Datasets |
|----------|----------|
| [Cultuur en religie (Culture & Religion)](culture/) | 10 |
| [Economie (Economy)](economy/) | 1 |
| [Onderwijs (Education)](education/) | 53 |
| [Entertainment](entertainment/) | 2 |
| [Milieu (Environment)](environment/) | 9 |
| [Financiën en handel (Finance & Trade)](finance/) | 35 |
| [Voedsel (Food & Nutrition)](food/) | 15 |
| [Geografie (Geography)](geography/) | 46 |
| [Gezondheid (Health)](health/) | 5 |
| [Taal (Language)](language/) | 1 |
| [Muziek (Music)](music/) | 1 |
| [Politiek (Politics)](politics/) | 1 |
| [Referentie (Reference)](reference/) | 218 |
| [Wetenschap (Science)](science/) | 2 |
| [Maatschappij (Society)](society/) | 3 |
| [Sport (Sports)](sports/) | 11 |
| [Technologie (Technology)](tech/) | 1 |
| [Tijd en kalender (Time & Calendar)](time/) | 11 |
| [Toerisme (Tourism)](tourism/) | 16 |
| [Vervoer (Transport)](transport/) | 34 |

## Usage

### Browse on the web
Visit [listbase.org/nl/](https://listbase.org/nl/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.nl.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.nl.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.nl.listbase.org/geography/th-central-provinces_NL.xlsx
curl -O https://cdn.nl.listbase.org/geography/th-central-provinces_NL.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.nl.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.nl.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_NL.csv   # CSV download
│   └── {dataset}_NL.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
