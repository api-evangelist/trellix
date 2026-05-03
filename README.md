# Trellix

Trellix is a cybersecurity company that delivers a comprehensive, open, and native extended detection and response (XDR) platform. The company provides threat detection, investigation, and response capabilities across endpoints, networks, data, and cloud environments.

**Website:** [https://www.trellix.com](https://www.trellix.com)  
**Developer Portal:** [https://developer.manage.trellix.com/](https://developer.manage.trellix.com/)  
**Documentation:** [https://docs.trellix.com/](https://docs.trellix.com/)

## APIs

### Trellix EDR API
Endpoint Detection and Response API for advanced threat hunting, investigation, and automated response capabilities across managed endpoints.
- **OpenAPI:** [openapi/trellix-edr-openapi.yml](openapi/trellix-edr-openapi.yml)

### Trellix ePO SaaS API
Cloud-based ePolicy Orchestrator API for managing devices, events, tags, groups, queries, and response actions.
- **OpenAPI:** [openapi/trellix-epo-saas-openapi.yml](openapi/trellix-epo-saas-openapi.yml)

### Trellix ePO API
McAfee ePolicy Orchestrator REST API for centralized security management, policy enforcement, and reporting.
- **Docs:** [https://docs.trellix.com/bundle/epolicy-orchestrator](https://docs.trellix.com/bundle/epolicy-orchestrator)

### Trellix Insights API
API for accessing threat intelligence, security analytics, and insights from the Trellix threat research platform.
- **Docs:** [https://docs.trellix.com/bundle/trellix-insights-product-guide](https://docs.trellix.com/bundle/trellix-insights-product-guide)

### Trellix Data Exchange Layer (DXL) API
Messaging fabric API for real-time communication between security tools and data sharing across the security ecosystem.
- **Docs:** [https://opendxl.github.io/](https://opendxl.github.io/)

### Trellix Email Security Cloud API
RESTful API for Trellix Email Security Cloud providing advanced threat detection in email.
- **Docs:** [https://docs.trellix.com/bundle/fe-email-cloud-landing](https://docs.trellix.com/bundle/fe-email-cloud-landing)

### Trellix Intelligent Sandbox API
REST API for automated file and URL submission and analysis for malware detection.
- **Docs:** [https://docs.trellix.com/bundle/trellix-intelligent-sandbox-5.0.x-api-reference-guide](https://docs.trellix.com/bundle/trellix-intelligent-sandbox-5.0.x-api-reference-guide)

## Artifacts

| Type | File |
|---|---|
| OpenAPI (EDR) | [openapi/trellix-edr-openapi.yml](openapi/trellix-edr-openapi.yml) |
| OpenAPI (ePO SaaS) | [openapi/trellix-epo-saas-openapi.yml](openapi/trellix-epo-saas-openapi.yml) |
| JSON Schema (Threat) | [json-schema/trellix-threat-schema.json](json-schema/trellix-threat-schema.json) |
| JSON Schema (Device) | [json-schema/trellix-device-schema.json](json-schema/trellix-device-schema.json) |
| JSON Structure (Threat) | [json-structure/trellix-threat-structure.json](json-structure/trellix-threat-structure.json) |
| JSON-LD Context | [json-ld/trellix-context.jsonld](json-ld/trellix-context.jsonld) |
| Spectral Rules | [rules/trellix-spectral-rules.yml](rules/trellix-spectral-rules.yml) |
| Vocabulary | [vocabulary/trellix-vocabulary.yml](vocabulary/trellix-vocabulary.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trellix-edr.yaml](capabilities/shared/trellix-edr.yaml) | EDR (threats, detections, alerts, searches, reactions) |
| [capabilities/shared/trellix-epo-saas.yaml](capabilities/shared/trellix-epo-saas.yaml) | ePO SaaS (devices, events, tags, groups, queries, response actions) |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/endpoint-security-operations.yaml](capabilities/endpoint-security-operations.yaml) | Unified endpoint security operations (threat hunting, incident response, device management) |

## Examples

- [examples/trellix-list-threats-example.json](examples/trellix-list-threats-example.json)

## Common Properties

- [Portal](https://www.trellix.com/)
- [Developer Portal](https://developer.manage.trellix.com/)
- [Documentation](https://docs.trellix.com/)
- [Support](https://www.trellix.com/support/)
- [GitHub (trellix-enterprise)](https://github.com/trellix-enterprise)
- [GitHub (opendxl)](https://github.com/opendxl)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com

## Tags

Cloud Security, Cybersecurity, Endpoint Security, Threat Detection, Threat Intelligence, XDR
