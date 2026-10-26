# Department of the Treasury (department-of-the-treasury)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
