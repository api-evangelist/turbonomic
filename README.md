# IBM Turbonomic (turbonomic)

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

IBM Turbonomic is an Application Resource Management (ARM) platform that uses AI-powered automation to continuously analyze and optimize application performance and cloud costs across hybrid and multi-cloud environments. Turbonomic provides a comprehensive REST API enabling programmatic access to resource management data, workload actions, markets, policies, groups, templates, and topology information. The platform integrates with AWS, Azure, GCP, Kubernetes, VMware, and dozens of APM and ITSM tools.

**APIs.json:** [https://www.ibm.com/products/turbonomic](https://www.ibm.com/products/turbonomic)

## Scope

- **Type:** Index

## Tags

- Application Resource Management
- Cloud Cost Optimization
- Cloud Management
- Hybrid Cloud
- IBM
- Kubernetes
- Multi-Cloud
- Workload Optimization

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Turbonomic REST API

The Turbonomic REST API provides programmatic access to the Turbonomic Application Resource Management platform. It enables automation of resource optimization actions, querying of entities (VMs, containers, applications, storage), management of markets and policies, retrieval of statistics and analytics, group management, template administration, and topology exploration across hybrid cloud environments. The API uses bearer token authentication obtained via a login endpoint.

- **Human URL:** [https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints](https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints)
- **Base URL:** `https://{turbonomic_host}/api/v3`

#### Tags

- Actions
- Application Resource Management
- Automation
- Cloud Cost Optimization
- Entities
- Groups
- Markets
- Policies
- Statistics
- Topology
- Workload Optimization

#### Properties

- [Documentation](https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints)
- [Swagger U I](https://try.turbonomic.io/apidoc/)
- [Getting Started](https://www.ibm.com/docs/en/tarm/8.13.0?topic=reference-getting-started-turbonomic-rest-api)
- [Reference](https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints)
- [OpenAPI](openapi/turbonomic-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/turbonomic-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/turbonomic-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Kubernetes C R D](crd/charts.helm.k8s.io_xls.yaml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/turbonomic)
- [Website](https://www.ibm.com/products/turbonomic)
- [Documentation](https://www.ibm.com/docs/en/tarm/8.19.3)
- [Swagger U I](https://try.turbonomic.io/apidoc/)
- [Getting Started](https://www.ibm.com/docs/en/tarm/8.13.0?topic=reference-getting-started-turbonomic-rest-api)
- [GitHub Organization](https://github.com/turbonomic)
- [Blog](https://www.ibm.com/blog/turbonomic/)
- [Pricing](https://www.ibm.com/products/turbonomic/pricing)
- [Marketplace](https://aws.amazon.com/marketplace/pp/prodview-5r3k3snu4ttnm)
- [Support](https://www.ibm.com/mysupport/s/topic/0TO0z000000ZnCCGA0/turbonomic-application-resource-management)
- [Community](https://developer.ibm.com/components/turbonomic/)
- [Terms of Service](https://www.ibm.com/terms)
- [Privacy Policy](https://www.ibm.com/privacy)
- [OpenAPI](openapi/turbonomic-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Kubernetes C R D](crd/charts.helm.k8s.io_xls.yaml)
- [Vocabulary](vocabulary/turbonomic-vocabulary.yml)
- [JSON-LD](json-ld/turbonomic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/turbonomic-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/turbonomic-action-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
