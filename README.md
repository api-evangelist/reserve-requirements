# Reserve Requirements (reserve-requirements)

Reserve Requirements refers to the Federal Reserve's Regulation D framework governing reserve requirement ratios for depository institutions. As of March 26, 2020, the Federal Reserve reduced all reserve requirement ratios to zero percent, eliminating reserve requirements for all depository institutions. The Federal Reserve provides data access through FRED (Federal Reserve Economic Data), the H.6 Money Stock Measures release, and the federalreserve.gov data download program for historical reserve and monetary base data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Reserve Requirements
- Federal Reserve
- Banking Regulation
- Monetary Policy
- Regulation D
- Finance

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### FRED API - Reserve Data

The Federal Reserve Economic Data (FRED) API provided by the Federal Reserve Bank of St. Louis offers programmatic access to reserve requirement data, monetary base data, and historical H.3 and H.6 statistical release data. FRED provides a comprehensive REST API with API key authentication for accessing economic time series data.

- **Human URL:** [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/)
- **Base URL:** `https://api.stlouisfed.org/fred`

#### Tags

- Federal Reserve
- Economic Data
- Reserve Requirements
- Monetary Base
- Time Series

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/openapi/fred-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-schema/fred-series-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-schema/fred-observation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-structure/fred-series-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-ld/reserve-requirements-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/rules/reserve-requirements-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/vocabulary/reserve-requirements-vocabulary.yml)
- [Postman Collection](collections/fred.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fred.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Federal Reserve Data Download Program

The Federal Reserve Board's Data Download Program provides structured access to Federal Reserve statistical releases including Regulation D reserve requirement data, H.6 Money Stock Measures, and historical reserve data through a web-based data download interface.

- **Human URL:** [https://www.federalreserve.gov/datadownload/](https://www.federalreserve.gov/datadownload/)

#### Tags

- Federal Reserve
- Statistical Releases
- Regulation D
- Reserve Requirements
- Data Download

#### Properties

- [Documentation](https://www.federalreserve.gov/datadownload/)
- [About](https://www.federalreserve.gov/monetarypolicy/reservereq.htm)
- [Postman Collection](collections/fred.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fred.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.federalreserve.gov/monetarypolicy/reservereq.htm)
- [Documentation](https://www.federalreserve.gov/monetarypolicy/reservereq.htm)
- [Policy](https://www.federalreserve.gov/monetarypolicy/reservereq.htm)
- [Regulation](https://www.ecfr.gov/current/title-12/chapter-II/subchapter-A/part-204)
- [Data Download](https://www.federalreserve.gov/datadownload/)
- [F R E D](https://fred.stlouisfed.org/categories/32217)
- [H6 Release](https://www.federalreserve.gov/releases/h6/)
- [GitHub Organization](https://github.com/federalreserve)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
