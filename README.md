# IBM Turbonomic

IBM Turbonomic is an Application Resource Management (ARM) platform that uses AI-powered
automation to continuously analyze and optimize application performance and cloud costs across
hybrid and multi-cloud environments. It provides a comprehensive REST API enabling programmatic
access to resource management data, workload actions, markets, policies, groups, templates,
and topology information.

**Website:** https://www.ibm.com/products/turbonomic

**APIs.yml:** https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Application Resource Management
- Cloud Cost Optimization
- Cloud Management
- Hybrid Cloud
- IBM
- Kubernetes
- Multi-Cloud
- Workload Optimization

## APIs

### Turbonomic REST API

The Turbonomic REST API provides programmatic access to the ARM platform via `/api/v3`. It enables
automation of optimization actions, entity querying, market analysis, and policy management.

- **Base URL:** `https://{turbonomic_host}/api/v3`
- **Authentication:** Bearer token (obtained via POST /api/v3/login)
- **Documentation:** https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints
- **Swagger UI:** https://try.turbonomic.io/apidoc/
- **OpenAPI Spec:** [openapi/turbonomic-rest-api-openapi.yml](openapi/turbonomic-rest-api-openapi.yml)

**Key Endpoints:**
| Resource | Description |
|---|---|
| `POST /login` | Authenticate and obtain bearer token |
| `GET /entities` | List all managed entities (VMs, containers, apps) |
| `GET /markets/Market/actions` | Get pending optimization actions |
| `GET/POST /groups` | Manage entity groups |
| `GET/POST /policies` | Manage automation policies |
| `GET /targets` | List discovery targets |
| `GET /templates` | List resource templates |
| `GET /topology` | Explore infrastructure topology |

## Kubernetes CRDs

Turbonomic ships with a Kubernetes Operator defining the `Xl` Custom Resource for deploying
the Turbonomic platform on Kubernetes.

- **CRD:** [crd/charts.helm.k8s.io_xls.yaml](crd/charts.helm.k8s.io_xls.yaml)
- **Source:** https://github.com/turbonomic/t8c-install

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/turbonomic-rest-api.yaml](capabilities/shared/turbonomic-rest-api.yaml) | Complete Turbonomic REST API consumed definition |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/resource-optimization.yaml](capabilities/resource-optimization.yaml) | Full resource optimization workflow (14 REST + MCP tools) |

## Schemas

### JSON Schema

| File | Description |
|---|---|
| [json-schema/turbonomic-entity-schema.json](json-schema/turbonomic-entity-schema.json) | Entity schema (VMs, containers, apps) |
| [json-schema/turbonomic-action-schema.json](json-schema/turbonomic-action-schema.json) | Optimization action schema |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/turbonomic-entity-structure.json](json-structure/turbonomic-entity-structure.json) | Entity field structure |
| [json-structure/turbonomic-action-structure.json](json-structure/turbonomic-action-structure.json) | Action field structure |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/turbonomic-context.jsonld](json-ld/turbonomic-context.jsonld) | Linked data context for Turbonomic resources |

## Examples

| File | Description |
|---|---|
| [examples/turbonomic-loginUser-example.json](examples/turbonomic-loginUser-example.json) | Login and obtain bearer token |
| [examples/turbonomic-getEntities-example.json](examples/turbonomic-getEntities-example.json) | List managed VMs |
| [examples/turbonomic-getMarketActions-example.json](examples/turbonomic-getMarketActions-example.json) | Get pending optimization actions |
| [examples/turbonomic-createGroup-example.json](examples/turbonomic-createGroup-example.json) | Create a dynamic entity group |
| [examples/turbonomic-getEntityStats-example.json](examples/turbonomic-getEntityStats-example.json) | Get entity statistics |

## Rules

| File | Description |
|---|---|
| [rules/turbonomic-rest-api-rules.yml](rules/turbonomic-rest-api-rules.yml) | Spectral ruleset for Turbonomic API conventions |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/turbonomic-vocabulary.yml](vocabulary/turbonomic-vocabulary.yml) | Domain vocabulary for ARM concepts |

## GitHub Organization

https://github.com/turbonomic — Includes kubeturbo, t8c-install, turbo-api, and more.

## Integrations

AWS, Azure, GCP, Kubernetes, VMware vSphere, HashiCorp Terraform, ServiceNow, IBM Kubecost

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
