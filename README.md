# Bitbucket Pipelines (bitbucket-pipelines)

Bitbucket Pipelines is Atlassian's built-in CI/CD service for Bitbucket Cloud, with cloud-hosted and self-hosted runners and YAML-defined pipelines. The Pipelines surface is exposed as the `/pipelines/` resource family within the broader Bitbucket Cloud REST API v2.0.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Bitbucket Cloud REST v2.0 (Pipelines slice)** — `https://api.bitbucket.org/2.0` — `/repositories/{workspace}/{repo}/pipelines/`, steps, deployments, environments, schedules, runners, caches, variables, ssh keys, known hosts. OAuth 2.0, app passwords or workspace access tokens.

## OpenAPI (fetched 2026-05-08)
`openapi/bitbucket-pipelines-openapi.json` — Atlassian's published Swagger 2.0 spec for the entire Bitbucket Cloud API. Source: <https://api.bitbucket.org/swagger.json>.

## Tags
DevOps, CI/CD, Pipelines, Atlassian, Bitbucket, Hosted, Self-Hosted Runners

## Common Properties
- [Pipelines feature page](https://bitbucket.org/product/features/pipelines)
- [Docs](https://support.atlassian.com/bitbucket-cloud/docs/get-started-with-bitbucket-pipelines/)
- [API reference](https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pipelines/)
- [Pricing](https://www.atlassian.com/software/bitbucket/pricing)
- [Status](https://bitbucket.status.atlassian.com/)
- [Plans](plans/bitbucket-pipelines-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/bitbucket-pipelines-rate-limits.yml) — reconciled
- [FinOps](finops/bitbucket-pipelines-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Free** — up to 5 users, 50 build min/mo.
- **Standard** — $3.65/user/mo, 2,500 min/mo.
- **Premium** — $7.25/user/mo, 3,500 min/mo, advanced security.
- **Add-on minutes** — 1,000-min pack at $10/mo on every tier.

## Rate Limits (reconciled)
- 60,000 req/h authenticated per workspace/app installation.
- 1,000 req/h unauthenticated per IP.
- Per-step build cap: 120 min.
- 429 with `Retry-After`; `X-RateLimit-*` headers.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
