# Methodology

## Data Sources

This dataset is compiled from multiple open sources:

- **Wilayah Administratif Indonesia** (edwardsamuel/Wilayah-Administratif-Indonesia) — BPS codes and names for all 4 admin levels, licensed under ODbL v1.0
- **cahyadsn/wilayah** — Province and regency coordinates, elevation, timezone, area, and population data, licensed under MIT
- **ArrayAccess/Indonesia-Postal-And-Area** — District-level coordinates and postal codes, licensed under MIT
- **tackulmine/indonesia** — Village-level coordinates, from Google Maps geocoding
- **indo.rent** — Supplementary village coordinates via structured data
- **OpenStreetMap Nominatim** — Fallback geocoding for missing coordinates

All data is anchored on Indonesia's BPS (Badan Pusat Statistik) administrative code system, as defined by Kemendagri (Ministry of Home Affairs).

## Processing

1. Source data is parsed, normalized, and merged by BPS code
2. Parent references, ancestor chains, and children counts are computed
3. English slugs are generated for URL-safe folder naming
4. Multi-format export: JSON, NDJSON, CSV
5. Hierarchy folder structure with READMEs generated via EJS templates

## Code System

Indonesia uses a hierarchical numeric code: province (2-digit) → regency/city (4-digit) → district (7-digit) → village (10-digit). Example: `11.01.01.2001` = Aceh → Kab. Simeulue → Teupah Selatan → Keude Bakongan.

## Update Frequency

Data is updated when BPS/Kemendagri releases new administrative code editions.

## Accuracy

- All division names, codes, and hierarchy relationships come directly from BPS source data
- Coordinates coverage: Province 100%, Regency 100%, District 99.1%, Village 99.6%
- Postal code coverage: 99.9% at village level
- Statistics are computed from data, never hardcoded
- Build script is idempotent: same input always produces same output