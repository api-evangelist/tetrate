# Tetrate

Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, and observability across distributed microservice environments, as well as Tetrate Istio Distro (TID), a vetted upstream Istio distribution with FIPS-verified builds.

**Website:** https://tetrate.io/
**Documentation:** https://docs.tetrate.io/
**GitHub:** https://github.com/tetrateio

## APIs

### [Tetrate Service Bridge REST API](https://docs.tetrate.io/service-bridge/reference/rest-api/guide)
Management plane REST API for organizations, tenants, workspaces, clusters, applications, and API lifecycle management. Base URL: `https://tsbhost:8443/v2`. Supports Basic Auth and JWT via `x-tetrate-token`.

**Tags:** Management Plane, Multi-Cluster, REST, Service Mesh

**Properties:**
- [Documentation](https://docs.tetrate.io/service-bridge/reference/rest-api/guide)
- [OpenAPI](openapi/tetrate-service-bridge-openapi.yml)
- [JSON Schema](json-schema/tsb-resource-schema.json)
- [JSON Structure](json-structure/tsb-resource-structure.json)

### [Tetrate Service Bridge Platform API](https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/)
Programmatic management of organizations, tenants, workspaces, and cluster onboarding.

### [Tetrate Service Bridge Gateway API](https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/)
Ingress and egress gateway group configuration for multi-cluster service mesh environments.

### [Tetrate Service Bridge Traffic API](https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/)
Traffic routing, load balancing, failover, retries, and service-to-service routing rules.

### [Tetrate Service Bridge Security API](https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/)
mTLS, authorization policies, and access control between workloads across the mesh.

### [Tetrate Service Bridge Observability API](https://docs.tetrate.io/service-bridge/latest/refs/)
Service metrics, traffic telemetry, and distributed tracing across mesh clusters.

## Artifacts

### OpenAPI Specifications

- [openapi/tetrate-service-bridge-openapi.yml](openapi/tetrate-service-bridge-openapi.yml) — TSB REST management plane API

### Spectral Rules

- [rules/tetrate-service-bridge-rules.yml](rules/tetrate-service-bridge-rules.yml) — Spectral ruleset enforcing TSB API conventions

### Naftiko Capabilities

**Shared Definitions:**
- [capabilities/shared/tetrate-service-bridge.yaml](capabilities/shared/tetrate-service-bridge.yaml) — TSB management plane consumed API

**Workflow Capabilities:**
- [capabilities/service-mesh-management.yaml](capabilities/service-mesh-management.yaml) — Unified service mesh management for platform engineers (12 MCP tools, REST on :8080)

### JSON Schema

- [json-schema/tsb-resource-schema.json](json-schema/tsb-resource-schema.json) — Base schema for TSB resources (Organization, Tenant, Workspace, Cluster, Application, API)

### JSON Structure

- [json-structure/tsb-resource-structure.json](json-structure/tsb-resource-structure.json) — TSB resource hierarchy documentation

### JSON-LD Context

- [json-ld/tetrate-context.jsonld](json-ld/tetrate-context.jsonld) — Linked data context mapping TSB vocabulary to schema.org

### Vocabulary

- [vocabulary/tetrate-vocabulary.yml](vocabulary/tetrate-vocabulary.yml) — TSB domain vocabulary (19 terms covering resource hierarchy, mesh configuration, operational semantics)

### Examples

- [examples/tetrate-service-bridge-list-tenants-example.json](examples/tetrate-service-bridge-list-tenants-example.json)
- [examples/tetrate-service-bridge-create-workspace-example.json](examples/tetrate-service-bridge-create-workspace-example.json)
- [examples/tetrate-service-bridge-create-api-example.json](examples/tetrate-service-bridge-create-api-example.json)

## Common Properties

- [Website](https://tetrate.io/)
- [Documentation](https://docs.tetrate.io/)
- [Getting Started](https://docs.tetrate.io/service-bridge/latest/quickstart/)
- [Blog](https://tetrate.io/blog/)
- [GitHub Organization](https://github.com/tetrateio)
- [Change Log](https://docs.tetrate.io/service-bridge/latest/release-notes/)
- [Support](https://tetrate.io/contact/)
- [Pricing](https://tetrate.io/tetrate-service-bridge/)
- [Community](https://tetrate.io/community/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
