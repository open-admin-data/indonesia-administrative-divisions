# Indonesia Administrative Divisions / Indonesia

Open dataset of Indonesia's complete administrative hierarchy — from provinces (provinsi) down to villages (desa/kelurahan). This repository provides structured, bilingual (Indonesian + English) reference data for all four levels of Indonesian administrative divisions, including postal codes and geographic coordinates at every level. Designed for developers, researchers, government agencies, and AI agents.

Licensed under CC-BY-4.0. Browse the hierarchy through GitHub's folder navigation, download aggregate files in JSON/CSV/NDJSON, or integrate directly via raw URLs.

## Overview

| Item | Details |
|------|---------|
| Province | 34 |
| Regency/City | 514 |
| District | 7,215 |
| Village | 80,534 |
| Coordinates | ✅ Included (all levels) |
| Postal Codes | ✅ Included (village level) |
| Formats | JSON, NDJSON, CSV |
| License | CC-BY-4.0 |
| Last Updated | 2026-05-16 |

## Browse by Province

| # | Province | Regency/Citys | Districts | Villages | Link |
|---|----|----|----|----|------|
| 1 | Aceh | 23 | 289 | 6,509 | [Browse](divisions/aceh-11/) |
| 2 | Sumatera Utara (North Sumatra) | 33 | 448 | 6,102 | [Browse](divisions/north-sumatra-12/) |
| 3 | Sumatera Barat (West Sumatra) | 19 | 179 | 1,160 | [Browse](divisions/west-sumatra-13/) |
| 4 | Riau | 12 | 169 | 1,876 | [Browse](divisions/riau-14/) |
| 5 | Jambi | 11 | 141 | 1,562 | [Browse](divisions/jambi-15/) |
| 6 | Sumatera Selatan (South Sumatra) | 17 | 236 | 3,263 | [Browse](divisions/south-sumatra-16/) |
| 7 | Bengkulu | 10 | 128 | 1,515 | [Browse](divisions/bengkulu-17/) |
| 8 | Lampung | 15 | 228 | 2,642 | [Browse](divisions/lampung-18/) |
| 9 | Kepulauan Bangka Belitung (Bangka Belitung Islands) | 7 | 47 | 366 | [Browse](divisions/bangka-belitung-islands-19/) |
| 10 | Kepulauan Riau (Riau Islands) | 7 | 70 | 395 | [Browse](divisions/riau-islands-21/) |
| 11 | Dki Jakarta (Jakarta) | 6 | 44 | 254 | [Browse](divisions/jakarta-31/) |
| 12 | Jawa Barat (West Java) | 27 | 627 | 5,832 | [Browse](divisions/west-java-32/) |
| 13 | Jawa Tengah (Central Java) | 35 | 573 | 8,008 | [Browse](divisions/central-java-33/) |
| 14 | Di Yogyakarta (Yogyakarta) | 5 | 78 | 414 | [Browse](divisions/yogyakarta-34/) |
| 15 | Jawa Timur (East Java) | 38 | 666 | 7,856 | [Browse](divisions/east-java-35/) |
| 16 | Banten | 8 | 155 | 1,501 | [Browse](divisions/banten-36/) |
| 17 | Bali | 9 | 57 | 653 | [Browse](divisions/bali-51/) |
| 18 | Nusa Tenggara Barat (West Nusa Tenggara) | 10 | 116 | 1,062 | [Browse](divisions/west-nusa-tenggara-52/) |
| 19 | Nusa Tenggara Timur (East Nusa Tenggara) | 22 | 307 | 3,202 | [Browse](divisions/east-nusa-tenggara-53/) |
| 20 | Kalimantan Barat (West Kalimantan) | 14 | 174 | 2,073 | [Browse](divisions/west-kalimantan-61/) |
| 21 | Kalimantan Tengah (Central Kalimantan) | 14 | 136 | 1,537 | [Browse](divisions/central-kalimantan-62/) |
| 22 | Kalimantan Selatan (South Kalimantan) | 13 | 152 | 1,971 | [Browse](divisions/south-kalimantan-63/) |
| 23 | Kalimantan Timur (East Kalimantan) | 10 | 103 | 1,002 | [Browse](divisions/east-kalimantan-64/) |
| 24 | Kalimantan Utara (North Kalimantan) | 5 | 53 | 466 | [Browse](divisions/north-kalimantan-65/) |
| 25 | Sulawesi Utara (North Sulawesi) | 15 | 171 | 1,790 | [Browse](divisions/north-sulawesi-71/) |
| 26 | Sulawesi Tengah (Central Sulawesi) | 13 | 175 | 1,953 | [Browse](divisions/central-sulawesi-72/) |
| 27 | Sulawesi Selatan (South Sulawesi) | 24 | 307 | 2,975 | [Browse](divisions/south-sulawesi-73/) |
| 28 | Sulawesi Tenggara (Southeast Sulawesi) | 17 | 222 | 2,301 | [Browse](divisions/southeast-sulawesi-74/) |
| 29 | Gorontalo | 6 | 77 | 722 | [Browse](divisions/gorontalo-75/) |
| 30 | Sulawesi Barat (West Sulawesi) | 6 | 69 | 639 | [Browse](divisions/west-sulawesi-76/) |
| 31 | Maluku | 11 | 118 | 1,180 | [Browse](divisions/maluku-81/) |
| 32 | Maluku Utara (North Maluku) | 10 | 116 | 1,155 | [Browse](divisions/north-maluku-82/) |
| 33 | Papua Barat (West Papua) | 13 | 217 | 1,732 | [Browse](divisions/west-papua-91/) |
| 34 | Papua | 29 | 567 | 4,866 | [Browse](divisions/papua-94/) |

## Data Files

| File | Format | Description |
|------|--------|-------------|
| [all-province.json](data/all-province.json) | JSON | All 34 province records |
| [all-regency.json](data/all-regency.json) | JSON | All 514 regency/city records |
| [all-district.json](data/all-district.json) | JSON | All 7,215 district records |
| [village-by-province/](data/village-by-province/) | JSON | 80,534 villages split by province |
| [all-flat.json](data/all-flat.json) | JSON | Levels 1-3 flat array |
| [all-flat.ndjson](data/all-flat.ndjson) | NDJSON | Streaming format |
| [all-flat.csv](data/all-flat.csv) | CSV | Spreadsheet format |
| [hierarchy.json](data/hierarchy.json) | JSON | Nested tree |
| [schema.json](data/schema.json) | JSON Schema | Data schema |

## Quick Start

### Python

```python
import json

with open("data/all-province.json", "r", encoding="utf-8") as f:
    data = json.load(f)

for r in data:
    print(f"{r['name']['local']} ({r['name']['en']}) — {r['children_count']['regency']} regency/citys")
```

### JavaScript

```javascript
import { readFileSync } from "fs";

const data = JSON.parse(readFileSync("data/all-province.json", "utf-8"));
console.log(`Total: ${data.length} provinces`);
```

## Schema

| Field | Type | Description |
|-------|------|-------------|
| `id` | string | Unique identifier |
| `level` | integer | 1=province, 2=regency/city, 3=district, 4=village |
| `level_name` | object | Level label (local + English) |
| `name.local` | string | Name in local script |
| `name.en` | string | English name |
| `name.slug` | string | URL-safe slug |
| `parent` | object/null | Parent division reference |
| `ancestors` | array | Full ancestor chain |
| `children_count` | object | Count of children per level |
| `zip_codes` | array | Postal codes (where available) |
| `geo.lat` | string | Latitude (WGS84) |
| `geo.lon` | string | Longitude (WGS84) |

Full schema: [data/schema.json](data/schema.json)

## Hierarchy Browse

```
divisions/{province-slug}/
divisions/{province-slug}/{regency-slug}/
divisions/{province-slug}/{regency-slug}/{district-slug}/
```

Villages are listed inline in each district's README.

## AI Integration

- [llms.txt](docs/llms.txt) — Quick reference for AI agents
- [llms-full.txt](docs/llms-full.txt) — Summary with per-province links
- [Per-province data](docs/llms-full/) — Full data by province

## Citation

```
Indonesia Administrative Divisions Dataset (CC-BY-4.0)
URL: https://github.com/open-admin-data/indonesia-administrative-divisions
```

See [CITATION.cff](CITATION.cff) for machine-readable citation.

## License

- **Data**: [CC-BY-4.0](LICENSE)

## Related

- [ListBase](https://www.listbase.org) — Structured reference data for every country
- [open-admin-data](https://github.com/open-admin-data) — Open administrative data for ASEAN countries
- [thailand-administrative-divisions](https://github.com/open-admin-data/thailand-administrative-divisions) — Thailand dataset
