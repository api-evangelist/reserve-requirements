# Reserve Requirements

Reserve Requirements refers to the Federal Reserve's Regulation D framework governing reserve requirement ratios for depository institutions. As of March 26, 2020, the Federal Reserve reduced all reserve requirement ratios to zero percent. The Federal Reserve provides data access through FRED (Federal Reserve Economic Data), the H.6 Money Stock Measures release, and the federalreserve.gov data download program.

**URL:** [https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml)

## Tags

Reserve Requirements, Federal Reserve, Banking Regulation, Monetary Policy, Regulation D, Finance

## APIs

### FRED API - Reserve Data

The Federal Reserve Economic Data (FRED) API from the St. Louis Fed provides programmatic access to reserve balance data, monetary base measures, and historical reserve data. Key series: RESBALNS (reserve balances), BOGMBASE (monetary base).

- **Base URL:** https://api.stlouisfed.org/fred
- **Authentication:** API key (query parameter)
- **Human URL:** [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/)

#### Properties

- [Documentation](https://fred.stlouisfed.org/docs/api/fred/)
- [OpenAPI](openapi/fred-openapi.yml)
- [JSONSchema - Series](json-schema/fred-series-schema.json)
- [JSONSchema - Observation](json-schema/fred-observation-schema.json)
- [JSONStructure - Series](json-structure/fred-series-structure.json)
- [JSONLDContext](json-ld/reserve-requirements-context.jsonld)
- [SpectralRules](rules/reserve-requirements-rules.yml)
- [Vocabulary](vocabulary/reserve-requirements-vocabulary.yml)

### Federal Reserve Data Download Program

Web-based access to Federal Reserve statistical releases.

- **Human URL:** [https://www.federalreserve.gov/datadownload/](https://www.federalreserve.gov/datadownload/)

## Policy Background

- All reserve requirement ratios: **0%** (as of March 26, 2020)
- Reserve exemption amount 2026: **$39.2 million**
- Low reserve tranche 2026: **$674.1 million**
- Governing regulation: Regulation D (12 CFR Part 204)

## Common Properties

- [Policy](https://www.federalreserve.gov/monetarypolicy/reservereq.htm)
- [Regulation](https://www.ecfr.gov/current/title-12/chapter-II/subchapter-A/part-204)
- [DataDownload](https://www.federalreserve.gov/datadownload/)
- [FRED Reserve Category](https://fred.stlouisfed.org/categories/32217)
- [H.6 Release](https://www.federalreserve.gov/releases/h6/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
