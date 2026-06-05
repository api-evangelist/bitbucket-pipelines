# Bitbucket Pipelines (bitbucket-pipelines)

Bitbucket Pipelines is Atlassian's built-in CI/CD service for Bitbucket Cloud, with cloud-hosted and self-hosted runners and YAML-defined pipelines. Pipelines is consumed via the Bitbucket Cloud REST API v2.0 under the /pipelines/ resource family. Atlassian publishes a Swagger 2.0 specification for the full Bitbucket Cloud API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bitbucket-pipelines/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bitbucket-pipelines/refs/heads/main/apis.yml)

## Tags

- DevOps
- CI/CD
- Pipelines
- Atlassian
- Bitbucket
- Hosted
- Self-Hosted Runners

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Bitbucket Cloud REST API v2.0 (Pipelines)

The Pipelines slice of the Bitbucket Cloud REST API v2.0. Endpoint families include /repositories/{workspace}/{repo_slug}/pipelines/, /pipelines/{pipeline_uuid}/steps/, /pipelines_config, deployments, environments, schedules, ssh keys, variables, known hosts, runners and caches. OAuth 2.0, app passwords or workspace access tokens.

- **Human URL:** [https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pipelines/](https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pipelines/)
- **Base URL:** `https://api.bitbucket.org/2.0`

#### Tags

- REST
- v2.0
- Pipelines
- Deployments
- Runners

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pipelines/)
- [API Reference](https://developer.atlassian.com/cloud/bitbucket/rest/intro/)
- [OpenAPI](openapi/bitbucket-pipelines-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitbucket-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitbucket-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Source](https://api.bitbucket.org/swagger.json)
- [Authentication](https://developer.atlassian.com/cloud/bitbucket/rest/intro/#authentication)

## Common Properties

- [Website](https://bitbucket.org/product/features/pipelines)
- [Documentation](https://support.atlassian.com/bitbucket-cloud/docs/get-started-with-bitbucket-pipelines/)
- [Pricing](https://www.atlassian.com/software/bitbucket/pricing)
- [Git Hub](https://bitbucket.org/atlassian/atlassian-pipelines-pipes)
- [Status Page](https://bitbucket.status.atlassian.com/)
- [Plans](plans/bitbucket-pipelines-plans-pricing.yml)
- [Rate Limits](rate-limits/bitbucket-pipelines-rate-limits.yml)
- [Fin Ops](finops/bitbucket-pipelines-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
