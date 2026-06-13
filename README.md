# Aserto

Fine-grained, cloud-native authorization platform providing policy-based access
control for applications and APIs.

## Overview

Aserto was a cloud-native authorization service built on Open Policy Agent (OPA)
and a Google Zanzibar-inspired relationship directory. The platform provided
sub-millisecond authorization decisions through a hybrid architecture — a hosted
control plane managing policies and a local or edge Authorizer evaluating
decisions in-process. The commercial SaaS control plane was wound down in May
2025; the open-source Topaz project continues as the community successor.

## APIs

| API | Description | Docs |
|-----|-------------|------|
| Authorizer API | Real-time /is, /query, /decisiontree policy evaluation | [Docs](https://docs.aserto.com/docs/authorizer-guide/overview) |
| Directory API | CRUD for users, groups, objects, and relations | [Docs](https://docs.aserto.com/docs/api-reference) |
| Decision Logs API | Audit trail of authorization decisions | [Docs](https://docs.aserto.com/docs/api-reference) |
| Control Plane API | Policy and Edge Authorizer lifecycle management (historical) | [Docs](https://docs.aserto.com/docs/api-reference) |

## SDKs

- Go: [aserto-dev/go-aserto](https://github.com/aserto-dev/go-aserto)
- Node.js: [aserto-dev/aserto-node](https://github.com/aserto-dev/aserto-node)
- Python: [aserto-dev/aserto-python](https://github.com/aserto-dev/aserto-python)
- .NET: [aserto-dev/aserto-dotnet](https://github.com/aserto-dev/aserto-dotnet)
- JavaScript (SPA): [aserto-dev/aserto-spa-js](https://github.com/aserto-dev/aserto-spa-js)

## Links

- Website: https://www.aserto.com/
- Documentation: https://docs.aserto.com/docs
- GitHub: https://github.com/aserto-dev
- Blog: https://www.aserto.com/blog
- LinkedIn: https://www.linkedin.com/company/aserto-com
- X: https://x.com/aserto_com
- OpenAPI Specs: https://github.com/aserto-dev/openapi-directory
- Topaz (successor): https://www.topaz.sh/

## Files

- `apis.yml` — APIs.json 0.19 provider index
- `plans/aserto-plans-pricing.yml` — API Commons Plans 0.1
- `rate-limits/aserto-rate-limits.yml` — API Commons Rate Limits 0.1
- `finops/aserto-finops.yml` — FinOps Framework 1.0 FOCUS-aligned profile

## Maintainer

Kin Lane — kin@apievangelist.com
