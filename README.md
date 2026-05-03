# Subex (subex)
Subex is a telecom analytics company providing revenue assurance, fraud management, and network analytics through its ROC (Revenue Operations Center) platform. Subex helps telecom operators detect revenue leakage, prevent fraud (SIM swap, IRSF, bypass, roaming), reconcile CDR data, and gain analytics insights.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Telecom, Revenue Assurance, Fraud Management, Analytics, BSS/OSS

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-02

## APIs

### Subex Revenue Assurance & Fraud Management API
Telecom revenue operations API covering leakage detection, fraud case management, subscriber risk scoring, CDR reconciliation, and analytics.

#### Tags:
 - Revenue Assurance, Fraud Management, CDR Reconciliation, Analytics, Telecom

#### Properties

- [Documentation](https://www.subex.com/roc/)
- [OpenAPI](openapi/subex-revenue-assurance-openapi.yml)

## Common Properties

- [Website](https://www.subex.com)
- [ROC Platform](https://www.subex.com/roc/)
- [Blog](https://www.subex.com/blog/)
- [Support](https://www.subex.com/contact-us/)
- [Privacy Policy](https://www.subex.com/privacy-policy/)
- [Spectral Rules](rules/subex-rules.yml)
- [Vocabulary](vocabulary/subex-vocabulary.yml)

## Capabilities

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Revenue Operations Center](capabilities/revenue-operations-center.yaml) | Telecom revenue ops — Leakage Alerts, Fraud Cases, Risk Scoring, Reconciliation, Analytics |

### Shared API Definitions

| API | File |
|---|---|
| Revenue Assurance | [shared/revenue-assurance.yaml](capabilities/shared/revenue-assurance.yaml) |

## JSON Schemas

- [subex-fraud-case-schema.json](json-schema/subex-fraud-case-schema.json) — Telecom fraud case schema

## JSON Structures

- [subex-leakage-alert-structure.json](json-structure/subex-leakage-alert-structure.json) — Revenue leakage alert structure

## JSON-LD

- [subex-context.jsonld](json-ld/subex-context.jsonld)

## Examples

- [List Fraud Cases](examples/subex-list-fraud-cases-example.json)
- [Get Subscriber Risk Score](examples/subex-get-subscriber-risk-score-example.json)

## Key Capabilities

| Feature | Description |
|---|---|
| Revenue Leakage Detection | Identifies unbilled usage, billing errors, and tariff mismatches |
| Fraud Management | Detects SIM swap, IRSF, bypass fraud, Wangiri, and roaming fraud |
| Subscriber Risk Scoring | Real-time risk scores (0-100) for fraud probability assessment |
| CDR Reconciliation | Compares CDR records across network elements and billing systems |
| Analytics | KPI dashboards for revenue assurance and fraud performance |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
