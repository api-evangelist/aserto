# Aserto

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
