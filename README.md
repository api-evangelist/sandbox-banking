# Sandbox Banking

Sandbox Banking (now nCino Integration Gateway) is an Integration Platform as a Service (iPaaS) purpose-built for financial institutions. The platform enables banks and credit unions to connect core banking systems (Fiserv, Jack Henry, FIS, and 14+ other cores) with fintech applications, loan origination systems, CRMs, KYC/AML providers, and 50+ financial services solutions. Glyue, the core integration framework, provides low-code workflow automation with Python extensibility, audit trails, role-based access control, and regulatory compliance support for CFPB Section 1033, GLBA, and FFIEC guidelines.

**URL:** [Glyue Integration Gateway Documentation](https://glyue.docs.sandboxbanking.com/)

## Tags

API Integration, Banking, Core Banking, Credit Unions, Financial Services, Fintech, Integration Platform, iPaaS, Open Banking

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-02

## APIs

### Glyue Integration Gateway API

The Glyue Integration Gateway API provides programmatic access to the Sandbox Banking integration platform for building, managing, and monitoring banking integrations including service requests, field mappings, value mappings, validation rules, run execution, and audit run history. Base URL: `https://{tenant}.sandboxbanking.com/api`.

#### Tags

Audit, Banking Integration, Core Banking, Field Mapping, Glyue, Integration, iPaaS, Workflow

#### Properties

- [Documentation](https://glyue.docs.sandboxbanking.com/)
- [Documentation](https://glyue.docs.sandboxbanking.com/reference/integration_anatomy) — Integration Anatomy Reference
- [OpenAPI](openapi/sandbox-banking-glyue-openapi.yml) — Glyue Integration Gateway API

### Mock Bank API

A sandbox environment for testing and developing banking integrations without connecting to production core banking systems.

#### Tags

Banking, Mock API, Sandbox, Testing

#### Properties

- [Documentation](https://mockbank.docs.sandboxbanking.com/reference/introduction)

## Common Properties

- [Documentation](https://glyue.docs.sandboxbanking.com/) — Glyue Documentation
- [Documentation](https://www.ncino.com/solutions/integrations) — nCino Integration Gateway
- [Documentation](https://mockbank.docs.sandboxbanking.com/) — Mock Bank API
- [Website](https://sandboxbanking.com/) — Sandbox Banking

## OpenAPI Specifications

- [openapi/sandbox-banking-glyue-openapi.yml](openapi/sandbox-banking-glyue-openapi.yml) — Glyue Integration Gateway API (integrations, service requests, field mappings, value mappings, run history, adapters)

## Rules

- [rules/sandbox-banking-rules.yml](rules/sandbox-banking-rules.yml) — Sandbox Banking API Spectral Rules

## Capabilities

### Shared Definitions

- [capabilities/shared/glyue.yaml](capabilities/shared/glyue.yaml) — Glyue Integration Gateway API (integrations, service requests, field mappings, value mappings, run history, adapters)

### Workflow Capabilities

- [capabilities/banking-integration-management.yaml](capabilities/banking-integration-management.yaml) — Banking Integration Management (integration lifecycle, execution, field mapping, audit, adapters)

## JSON Schema

- [json-schema/sandbox-banking-integration-schema.json](json-schema/sandbox-banking-integration-schema.json) — Integration Definition

## JSON Structure

- [json-structure/sandbox-banking-integration-structure.json](json-structure/sandbox-banking-integration-structure.json) — Integration Field Hierarchy

## JSON-LD

- [json-ld/sandbox-banking-context.jsonld](json-ld/sandbox-banking-context.jsonld) — Sandbox Banking JSON-LD Context

## Examples

- [examples/sandbox-banking-list-integrations-example.json](examples/sandbox-banking-list-integrations-example.json) — List Integrations Request/Response
- [examples/sandbox-banking-run-integration-example.json](examples/sandbox-banking-run-integration-example.json) — Run Integration Request/Response

## Vocabulary

- [vocabulary/sandbox-banking-vocabulary.yml](vocabulary/sandbox-banking-vocabulary.yml) — Sandbox Banking Vocabulary

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
