# Reserve Requirements (reserve-requirements)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
