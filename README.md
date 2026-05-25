# Fluidstack

Fluidstack is an AI cloud platform that builds and operates high-performance, single-tenant GPU clusters for top AI labs, governments, and enterprises. Founded in 2017 out of Oxford University and now headquartered in New York City, Fluidstack manages more than 100,000 GPUs across its global network and has been selected by customers including Anthropic, Meta, Mistral, Poolside, Black Forest Labs, and Character.AI.

The platform combines on-demand bare-metal GPU clusters (including thousands of NVIDIA H200s with InfiniBand) with managed Kubernetes and managed Slurm orchestration layers, Lighthouse observability, and human-on-call site reliability. Developers interact with the platform via a global REST Management API and the `fluidctl` command-line tool.

## APIs

- **[Fluidstack Management API](https://docs.fluidstack.io/api-reference/management-api)** — `v1alpha1` global API at `https://api.atlas.fluidstack.io/api/v1alpha1`. Manages regions, clusters, organizations, members, invitations, instances, and user SSH keys. Bearer token authentication with optional `X-PROJECT-ID` header scoping.

## Artifacts

| Type | Path |
| --- | --- |
| OpenAPI | [openapi/fluidstack-management-api-openapi.yml](openapi/fluidstack-management-api-openapi.yml) |

## Links

- Website: https://www.fluidstack.io
- Documentation: https://docs.fluidstack.io
- API Reference: https://docs.fluidstack.io/api-reference/management-api
- CLI Reference: https://docs.fluidstack.io/cli-reference/fluidctl
- Blog: https://www.fluidstack.io/about-us/blog

## Maintainer

Kin Lane — API Evangelist
