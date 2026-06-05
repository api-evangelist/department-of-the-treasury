# Department of the Treasury (department-of-the-treasury)

The U.S. Department of the Treasury manages federal finances, public debt, Treasury securities, U.S. currency production, tax administration, financial sanctions, and economic-statistical reporting. Treasury bureaus publish several public APIs, anchored by the Bureau of the Fiscal Service's Fiscal Data API and the Office of Foreign Assets Control's Sanctions List Service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Finance
- Debt
- Sanctions

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### Treasury Fiscal Data API

Standardized federal-finance datasets from the Bureau of the Fiscal Service - Debt to the Penny, Daily and Monthly Treasury Statements, auctions, interest rates, exchange rates, and federal spending.

- **Human URL:** [https://fiscaldata.treasury.gov/api-documentation/](https://fiscaldata.treasury.gov/api-documentation/)
- **Base URL:** `https://api.fiscaldata.treasury.gov/services/api/fiscal_service`

#### Tags

- Finance
- Debt
- Open Data

#### Properties

- [Documentation](https://fiscaldata.treasury.gov/api-documentation/)
- [OpenAPI](openapi/fiscal-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fiscal-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiscal-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/treasury-debt-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/debt-to-penny-example.json)
- [Datasets](https://fiscaldata.treasury.gov/datasets/)

### OFAC Sanctions List Service API

Specially Designated Nationals (SDN) and Consolidated Sanctions lists from the Office of Foreign Assets Control, with structured search.

- **Human URL:** [https://sanctionslistservice.ofac.treas.gov/](https://sanctionslistservice.ofac.treas.gov/)
- **Base URL:** `https://sanctionslistservice.ofac.treas.gov/api`

#### Tags

- Sanctions
- Compliance

#### Properties

- [Documentation](https://ofac.treasury.gov/sanctions-list-service)
- [OpenAPI](openapi/ofac-sdn-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ofac-sdn-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ofac-sdn-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sanctioned-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/sanctioned-entity-example.json)
- [Reference](https://ofac.treasury.gov/specially-designated-nationals-and-blocked-persons-list-sdn-human-readable-lists)

### TreasuryDirect Securities API

Public reference data on marketable Treasury securities (auctions, results, security details) published via TreasuryDirect.

- **Human URL:** [https://www.treasurydirect.gov/TA_WS/securities/announced](https://www.treasurydirect.gov/TA_WS/securities/announced)

#### Tags

- Securities
- Auctions

#### Properties

- [Documentation](https://www.treasurydirect.gov/webapis/webapisindex.htm)
- [Reference](https://www.treasurydirect.gov/instit/instit.htm)
- [Postman Collection](collections/fiscal-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiscal-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ofac-sdn-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ofac-sdn-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Entity Management API

Federal Service for Award Management (SAM) entity registration, exclusions, and assistance-listings data published via api.data.gov.

- **Human URL:** [https://open.gsa.gov/api/entity-api/](https://open.gsa.gov/api/entity-api/)

#### Tags

- Procurement
- Awards

#### Properties

- [Documentation](https://open.gsa.gov/api/entity-api/)
- [Reference](https://sam.gov/)
- [Postman Collection](collections/fiscal-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiscal-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ofac-sdn-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ofac-sdn-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IRS Public APIs

The Internal Revenue Service exposes select public datasets and tools through download endpoints, including Tax-Exempt Organization Search.

- **Human URL:** [https://www.irs.gov/charities-non-profits/tax-exempt-organization-search](https://www.irs.gov/charities-non-profits/tax-exempt-organization-search)

#### Tags

- Tax
- Charities

#### Properties

- [Documentation](https://www.irs.gov/charities-non-profits/tax-exempt-organization-search)
- [Postman Collection](collections/fiscal-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiscal-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ofac-sdn-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ofac-sdn-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/US-Department-of-the-Treasury)
- [LinkedIn](https://www.linkedin.com/company/us-treasury)
- [Portal](https://home.treasury.gov/)
- [Documentation](https://fiscaldata.treasury.gov/api-documentation/)
- [Reference](https://ofac.treasury.gov/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
