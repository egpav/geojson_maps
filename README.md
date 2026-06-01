# geojson_maps

GeoJSON region boundary files for map visualizations.

## Files

### `europe_countries.geojson`
49 European countries, clipped to the continent (overseas territories, Russia,
and Türkiye excluded). Source: Eurostat GISCO (`CNTR_RG_20M_2024_4326`).

Properties:
- `NAME_ENGL` — English country name (e.g. `Germany`, `United Kingdom`)
- `ISO3_CODE` — ISO 3166-1 alpha-3 (e.g. `DEU`, `GBR`)
- `CNTR_ID` — Eurostat code (e.g. `DE`, `UK`; note Greece is `EL`)

### `canada_provinces.geojson`
13 provinces and territories. Source: simplemaps.com.

Properties:
- `code` — 2-letter province/territory code (e.g. `BC`, `ON`, `QC`)
- `name` — full name (e.g. `British Columbia`)
- `id` — simplemaps identifier (e.g. `CABC`)
