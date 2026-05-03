# VKS Integrations

VKS (Visual Knowledge Share) provides work instruction software for manufacturing with a JSON REST API for managing work orders, guidebooks, operations, and production data. Connect VKS to ERP, MES, QMS, and BI platforms for bi-directional data exchange and real-time floor traceability.

**Human URL:** https://vksapp.com/integrations  
**Documentation:** https://help.vksapp.com/Content/VKS_Features/API/APIInfo.htm  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/vks-integrations/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

ERP Integration, Manufacturing, MES, Operations Management, Quality Management, Work Instructions, Work Orders

## APIs

### VKS API

JSON REST API for pulling guidebook and production data from VKS and managing work orders and operations. Supports up to 50 requests per minute (SaaS).

**Human URL:** https://vksapp.com/integrations

#### Properties

- [Documentation](https://help.vksapp.com/Content/VKS_Features/API/APIInfo.htm)
- [Getting Started](https://vksapp.com/integrations)
- [OpenAPI](openapi/vks-api-openapi.yml)

---

## OpenAPI Specifications

| File | Description |
|---|---|
| [vks-api-openapi.yml](openapi/vks-api-openapi.yml) | Work orders, guidebooks, operations, and production data endpoints |

## Spectral Rules

| File | Description |
|---|---|
| [vks-integrations-rules.yml](rules/vks-integrations-rules.yml) | Spectral ruleset for VKS API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | APIs |
|---|---|
| [shared/vks-api.yaml](capabilities/shared/vks-api.yaml) | VKS API — work orders, guidebooks, operations, production data |

### Workflow Capabilities

| File | Description |
|---|---|
| [manufacturing-operations.yaml](capabilities/manufacturing-operations.yaml) | Unified REST + MCP for ERP/MES integration and floor operations |

## JSON Schema

| File | Description |
|---|---|
| [vks-work-order-schema.json](json-schema/vks-work-order-schema.json) | Work order schema with status, part number, and quantity fields |

## JSON Structure

| File | Description |
|---|---|
| [vks-work-order-structure.json](json-structure/vks-work-order-structure.json) | Field-level structure for VKS Work Order |

## JSON-LD Context

| File | Description |
|---|---|
| [vks-integrations-context.jsonld](json-ld/vks-integrations-context.jsonld) | Linked data context aligned with schema.org/HowTo |

## Examples

| File | Description |
|---|---|
| [vks-api-create-work-order-example.json](examples/vks-api-create-work-order-example.json) | POST /api/workorders — create work order from ERP |

## Vocabulary

| File | Description |
|---|---|
| [vks-integrations-vocabulary.yml](vocabulary/vks-integrations-vocabulary.yml) | VKS terminology: Guidebook, Work Order, Smart Form, ERP, MES, BOM |

## Common Properties

- [Website](https://vksapp.com/)
- [Documentation](https://help.vksapp.com/)
- [Reference](https://help.vksapp.com/Content/VKS_Features/API/APIInfo.htm)
- [Integrations](https://vksapp.com/integrations)
- [Enterprise](https://vksapp.com/products/enterprise)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
