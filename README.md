# Tetrate (tetrate)

Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, and observability across distributed microservice environments, as well as Tetrate Istio Distro (TID), a vetted upstream Istio distribution with FIPS-verified builds. TSB exposes a REST management plane API for programmatic control of organizations, tenants, workspaces, clusters, applications, gateways, traffic routing, and security policies.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Enterprise
- Envoy
- Istio
- Kubernetes
- Service Mesh

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Tetrate Service Bridge REST API

The Tetrate Service Bridge (TSB) REST API provides programmatic management of the TSB control plane, including organizations, tenants, workspaces, cluster onboarding, application and API lifecycle management, gateway groups, traffic settings, and security policies. Authentication supports HTTP Basic and JWT token via x-tetrate-token header. The API base path is /v2 on port 8443.

- **Human URL:** [https://docs.tetrate.io/service-bridge/reference/rest-api/guide](https://docs.tetrate.io/service-bridge/reference/rest-api/guide)
- **Base URL:** `https://tsbhost:8443/v2`

#### Tags

- Management Plane
- Multi-Cluster
- REST
- Service Mesh

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/reference/rest-api/guide)
- [OpenAPI](openapi/tetrate-service-bridge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tsb-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tsb-resource-structure.json)

### Tetrate Service Bridge Platform API

The Tetrate Service Bridge (TSB) Platform API provides programmatic management of the TSB control plane, including organizations, tenants, workspaces, and cluster onboarding. It exposes REST and gRPC endpoints for configuring the global service mesh management plane across multi-cluster and multi-cloud environments.

- **Human URL:** [https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/](https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/)
- **Base URL:** `https://docs.tetrate.io/`

#### Tags

- Management Plane
- Multi-Cluster
- REST
- Service Mesh

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/)
- [Reference](https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetrate Service Bridge Gateway API

The TSB Gateway API manages ingress and egress gateway configuration for services in a Tetrate Service Bridge environment. It provides resources for defining gateway groups, IngressGateway, EgressGateway, and Tier1Gateway objects that control traffic entering and leaving the mesh across clusters.

- **Human URL:** [https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/](https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/)
- **Base URL:** `https://docs.tetrate.io/`

#### Tags

- Egress
- Gateway
- Ingress
- Traffic Management

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/)
- [Reference](https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetrate Service Bridge Traffic API

The TSB Traffic API provides configuration resources for managing service-to-service traffic within a Tetrate Service Bridge workspace. It supports traffic groups, TrafficSetting, and ServiceRoute objects that control load balancing, failover, retries, and routing rules for workloads in the mesh.

- **Human URL:** [https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/](https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/)
- **Base URL:** `https://docs.tetrate.io/`

#### Tags

- Load Balancing
- Routing
- Service Mesh
- Traffic Management

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/)
- [Reference](https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetrate Service Bridge Security API

The TSB Security API provides configuration resources for enforcing security policies in a Tetrate Service Bridge environment. It includes security groups, SecuritySetting, and ServiceSecuritySetting objects for controlling mutual TLS, authorization policies, and access control between workloads across the mesh.

- **Human URL:** [https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/](https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/)
- **Base URL:** `https://docs.tetrate.io/`

#### Tags

- Authorization
- mTLS
- Security
- Service Mesh

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/)
- [Reference](https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetrate Service Bridge Observability API

The TSB Observability API exposes metrics, topology, and service observability data for workloads managed by Tetrate Service Bridge. It provides access to service-level metrics, traffic telemetry, and distributed tracing information collected across mesh clusters, enabling monitoring and troubleshooting of distributed applications.

- **Human URL:** [https://docs.tetrate.io/service-bridge/latest/refs/](https://docs.tetrate.io/service-bridge/latest/refs/)
- **Base URL:** `https://docs.tetrate.io/`

#### Tags

- Metrics
- Observability
- Telemetry
- Tracing

#### Properties

- [Documentation](https://docs.tetrate.io/service-bridge/latest/refs/)
- [Postman Collection](collections/tetrate-service-bridge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tetrate-service-bridge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tetrate)
- [Website](https://tetrate.io/)
- [Documentation](https://docs.tetrate.io/)
- [Getting Started](https://docs.tetrate.io/service-bridge/latest/quickstart/)
- [Blog](https://tetrate.io/blog/)
- [GitHub Organization](https://github.com/tetrateio)
- [GitHub Repository](https://github.com/tetrateio/tetrate)
- [Changelog](https://docs.tetrate.io/service-bridge/latest/release-notes/)
- [Support](https://tetrate.io/contact/)
- [Pricing](https://tetrate.io/tetrate-service-bridge/)
- [Community](https://tetrate.io/community/)
- [OpenAPI](openapi/tetrate-service-bridge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/tsb-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tsb-resource-structure.json)
- [JSON-LD](json-ld/tetrate-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/tetrate-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
