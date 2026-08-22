# Tetrate (tetrate)

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
