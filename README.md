# Anyscale

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

Anyscale provides a managed Ray platform for distributed Python, ML training, and large-scale inference. Built by the creators of Ray, the Anyscale Platform API and CLI expose programmatic control over workspaces, jobs, services, clusters, compute configurations, container images, and clouds (Hosted and Bring-Your-Own-Cloud).

**Areas:** Artificial Intelligence · Distributed Computing · Ray · ML Platform · Inference · GPU

## Anyscale on APIs.io

Everything profiled for Anyscale is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anyscale/](https://apis.io/providers/anyscale/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Anyscale Workspaces API](https://apis.io/apis/anyscale/anyscale-workspaces-api/) — Manages Anyscale Workspaces - cloud-hosted, GPU-backed development environments preconfigured with Ray for interactive development and debugging.
- [Anyscale Jobs API](https://apis.io/apis/anyscale/anyscale-jobs-api/) — Submits, monitors, and manages Ray Jobs - one-off or scheduled batch runs of Python applications on managed Ray clusters.
- [Anyscale Services API](https://apis.io/apis/anyscale/anyscale-services-api/) — Deploys and manages production Ray Serve applications as long-running, autoscaling, multi-version services with traffic-shifted rollouts and HTTP/gRPC ingress.
- [Anyscale Clusters API](https://apis.io/apis/anyscale/anyscale-clusters-api/) — Provisions and manages Ray clusters - autoscaling fleets of CPU / GPU nodes underlying Workspaces, Jobs, and Services.
- [Anyscale Compute Configs API](https://apis.io/apis/anyscale/anyscale-compute-configs-api/) — Defines reusable compute templates (head node type, worker types, autoscaling, AWS/GCP region) for clusters, workspaces, jobs, and services.
- [Anyscale Container Images API](https://apis.io/apis/anyscale/anyscale-container-images-api/) — Builds, tags, and manages container images that bundle Python, system, and Ray dependencies for reproducible runtime environments.
- [Anyscale Clouds API](https://apis.io/apis/anyscale/anyscale-clouds-api/) — Manages Hosted and Bring-Your-Own-Cloud (BYOC) cloud connections to AWS and GCP accounts where Anyscale provisions Ray clusters.
- [Anyscale Projects API](https://apis.io/apis/anyscale/anyscale-projects-api/) — Groups workspaces, jobs, services, and resources into projects with shared access controls, dashboards, and quotas.
- [Anyscale Organizations API](https://apis.io/apis/anyscale/anyscale-organizations-api/) — Manages organizations, users, roles, IAM, and billing relationships at the tenancy level.
- [Anyscale Logs and Monitoring API](https://apis.io/apis/anyscale/anyscale-logs-api/) — Retrieves cluster, job, and service logs, metrics, and Ray dashboard data for observability and debugging.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/anyscale/](https://apis.io/graphqls/anyscale/anyscale-graphql/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Anyscale Domain Security](https://apis.io/security/anyscale/anyscale-domain-security/)
- [Anyscale Trust Center](https://apis.io/security/anyscale/anyscale-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Anyscale Plans Pricing](https://apis.io/plans/anyscale/anyscale-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Anyscale Rate Limits](https://apis.io/rate-limits/anyscale/anyscale-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Anyscale Finops](https://apis.io/finops/anyscale/anyscale-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.anyscale.com/)
- [Documentation](https://docs.anyscale.com/)
- [Pricing](https://www.anyscale.com/pricing)
- [GitHub](https://github.com/anyscale)

## API Evangelist rating

**Kin Score 21.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 16.0 |
| Access clarity | 50.0 |

**Agent readiness 3.9** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anyscale/](https://apis.io/providers/anyscale/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Anyscale: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anyscale/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
