# Fluidstack (fluidstack)

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

Fluidstack is an AI cloud platform that builds and operates high-performance, single-tenant GPU clusters for top AI labs, governments, and enterprises. Founded in 2017 out of Oxford University and now headquartered in New York City, Fluidstack manages more than 100,000 GPUs across its global network and has been selected by customers including Anthropic, Meta, Mistral, Poolside, Black Forest Labs, and Character.AI. Its core offering combines on-demand bare-metal GPU clusters (including thousands of NVIDIA H200s with InfiniBand) with managed Kubernetes and managed Slurm orchestration layers, Lighthouse observability, and human-on-call site reliability. Fluidstack exposes a global REST Management API (api.atlas.fluidstack.io/api/v1alpha1) and the fluidctl CLI for managing organizations, projects, regions, clusters, instances, members, invitations, and SSH keys. The platform is GDPR, SOC 2 Type 2, and ISO 27001 certified, and was awarded ClusterMAX Gold by SemiAnalysis.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fluidstack/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fluidstack/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- GPU
- Cloud
- Compute
- Infrastructure
- Machine Learning
- Foundation Models
- Training
- Inference
- Kubernetes
- Slurm
- Bare Metal
- NVIDIA
- InfiniBand
- Data Centers

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Fluidstack Management API

The global Fluidstack Management API (v1alpha1) for managing GPU cloud resources. Exposes regions, clusters, organizations, members, invitations, instances, and user SSH keys. Uses bearer token authentication, optional X-PROJECT-ID header scoping for instance listings, and is served from https://api.atlas.fluidstack.io/api/v1alpha1.

- **Human URL:** [https://docs.fluidstack.io/api-reference/management-api](https://docs.fluidstack.io/api-reference/management-api)
- **Base URL:** `https://api.atlas.fluidstack.io/api/v1alpha1`

#### Tags

- AI
- GPU
- Cloud
- Compute
- Clusters
- Instances
- Management

#### Properties

- [Documentation](https://docs.fluidstack.io/api-reference/management-api)
- [OpenAPI](openapi/fluidstack-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fluidstack-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fluidstack-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://docs.fluidstack.io/redocusaurus/management-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.fluidstack.io)
- [Portal](https://docs.fluidstack.io)
- [Documentation](https://docs.fluidstack.io/getting-started/overview)
- [Getting Started](https://docs.fluidstack.io/getting-started/overview)
- [Documentation](https://docs.fluidstack.io/projects/overview)
- [Documentation](https://docs.fluidstack.io/kubernetes/overview)
- [Documentation](https://docs.fluidstack.io/slurm/overview)
- [Documentation](https://docs.fluidstack.io/lighthouse/overview)
- [Documentation](https://docs.fluidstack.io/api-reference/management-api)
- [SDK](https://docs.fluidstack.io/cli-reference/fluidctl)
- [About](https://www.fluidstack.io/about-us/about)
- [Blog](https://www.fluidstack.io/about-us/blog)
- [Careers](https://www.fluidstack.io/about-us/careers)
- [Contact](https://www.fluidstack.io/contact)
- [LinkedIn](https://www.linkedin.com/company/fluidstack)
- [Twitter](https://twitter.com/fluidstackio)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
