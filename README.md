# Sandbox Banking (sandbox-banking)

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

Sandbox Banking (now nCino Integration Gateway) is an Integration Platform as a Service (iPaaS) purpose-built for financial institutions. The platform enables banks and credit unions to connect core banking systems (Fiserv, Jack Henry, FIS, and 14+ other cores) with fintech applications, loan origination systems, CRMs, KYC/AML providers, and 50+ financial services solutions. Glyue, the core integration framework, provides low-code workflow automation with Python extensibility, audit trails, role-based access control, and regulatory compliance features aligned with CFPB Section 1033, GLBA, and FFIEC guidelines.

**APIs.json:** [https://glyue.docs.sandboxbanking.com/](https://glyue.docs.sandboxbanking.com/)

## Tags

- API Integration
- Banking
- Core Banking
- Credit Unions
- Financial Services
- Fintech
- Integration Platform
- iPaaS
- Open Banking

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-19

## APIs

### Glyue Integration Gateway API

The Glyue Integration Gateway API provides programmatic access to the Sandbox Banking integration platform for building, managing, and monitoring banking integrations. The API supports creating and executing integration workflows, managing service request adapters, configuring field mappings, value mappings, validation rules, and accessing run history audit logs.

- **Human URL:** [https://glyue.docs.sandboxbanking.com/](https://glyue.docs.sandboxbanking.com/)
- **Base URL:** `https://{tenant}.sandboxbanking.com/api`

#### Tags

- Audit
- Banking Integration
- Core Banking
- Field Mapping
- Glyue
- Integration
- iPaaS
- Workflow

#### Properties

- [Documentation](https://glyue.docs.sandboxbanking.com/)
- [Documentation](https://glyue.docs.sandboxbanking.com/reference/integration_anatomy)
- [OpenAPI](openapi/sandbox-banking-glyue-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sandbox-banking-glyue.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandbox-banking-glyue.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mock Bank API

The Mock Bank API provides a sandbox environment for testing and developing banking integrations without connecting to production core banking systems. It simulates standard banking operations including account management, transactions, and customer data in a controlled test environment.

- **Human URL:** [https://mockbank.docs.sandboxbanking.com/](https://mockbank.docs.sandboxbanking.com/)

#### Tags

- Banking
- Mock API
- Sandbox
- Testing

#### Properties

- [Documentation](https://mockbank.docs.sandboxbanking.com/reference/introduction)
- [Postman Collection](collections/sandbox-banking-glyue.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandbox-banking-glyue.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sandboxbanking)
- [Documentation](https://glyue.docs.sandboxbanking.com/)
- [Documentation](https://www.ncino.com/solutions/integrations)
- [Documentation](https://mockbank.docs.sandboxbanking.com/)
- [Website](https://sandboxbanking.com/)
- [Spectral Rules](rules/sandbox-banking-rules.yml)
- [JSON Schema](json-schema/sandbox-banking-integration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sandbox-banking-integration-structure.json)
- [J S O N L D Context](json-ld/sandbox-banking-context.jsonld)
- [Example](examples/sandbox-banking-list-integrations-example.json)
- [Example](examples/sandbox-banking-run-integration-example.json)
- [Vocabulary](vocabulary/sandbox-banking-vocabulary.yml)
- [L L Ms Txt](https://glyue.docs.sandboxbanking.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
