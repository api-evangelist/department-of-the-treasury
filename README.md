# Department of the Treasury

The U.S. Department of the Treasury manages federal finances, public debt, Treasury securities, U.S. currency production, tax administration, financial sanctions, and economic-statistical reporting. Treasury bureaus publish several public APIs, anchored by the Bureau of the Fiscal Service's [Fiscal Data API](https://fiscaldata.treasury.gov/api-documentation/) and the Office of Foreign Assets Control's [Sanctions List Service](https://sanctionslistservice.ofac.treas.gov/).

**APIs.yml:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Finance
- Debt
- Sanctions

## Repository Layout

- [`apis.yml`](apis.yml) — APIs.json/yml index
- [`openapi/`](openapi/) — OpenAPI 3.1 specifications
- [`json-schema/`](json-schema/) — JSON Schemas for core records
- [`json-ld/`](json-ld/) — JSON-LD context aligning Treasury terms to schema.org and Dublin Core
- [`vocabulary/`](vocabulary/) — Controlled vocabulary
- [`capabilities/`](capabilities/) — Capability catalog
- [`rules/`](rules/) — Access, attribution, and compliance rules
- [`examples/`](examples/) — Representative response payloads

## APIs in this Index

### Bureau of the Fiscal Service
- **Treasury Fiscal Data API** — federal-finance datasets (debt, revenue, spending, exchange rates, auctions, interest rates)
- **TreasuryDirect Securities API** — marketable security auctions and results

### Office of Foreign Assets Control (OFAC)
- **OFAC Sanctions List Service API** — SDN and Consolidated sanctions lists with structured search

### Other Bureaus
- **SAM.gov Entity Management API** — federal entity registration and exclusions
- **IRS Public APIs** — Tax-Exempt Organization Search and other public datasets

## Authentication

- **Fiscal Data API** — public, no key required
- **OFAC Sanctions List Service** — public
- **SAM.gov via api.data.gov** — API key
- **TreasuryDirect** — public

## Data License

Datasets exposed by Treasury are works of the U.S. federal government in the public domain. Attribution to the originating bureau is recommended.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
