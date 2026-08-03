# Anyscale (anyscale)

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

Anyscale provides a managed Ray platform for distributed Python, ML training, and large-scale inference. Built by the creators of Ray, the Anyscale Platform API and CLI expose programmatic control over workspaces, jobs, services, clusters, compute configurations, container images, and clouds (Hosted and Bring-Your-Own-Cloud).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/anyscale/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=anyscale-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, Distributed Computing, Ray, ML Platform, Inference, GPU

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Anyscale Workspaces API | Cloud-hosted GPU development environments preconfigured with Ray. |
| Anyscale Jobs API | Submits, monitors, and manages Ray Jobs (batch / scheduled). |
| Anyscale Services API | Production Ray Serve deployments with autoscaling and rollouts. |
| Anyscale Clusters API | Provisions and manages autoscaling Ray clusters. |
| Anyscale Compute Configs API | Reusable compute templates (head/worker types, region). |
| Anyscale Container Images API | Custom container images for Ray runtime environments. |
| Anyscale Clouds API | Hosted and BYOC cloud connections to AWS / GCP. |
| Anyscale Projects API | Project-level grouping with shared access controls. |
| Anyscale Organizations API | Organizations, IAM, roles, and billing. |
| Anyscale Logs and Monitoring API | Logs, metrics, and Ray dashboard access. |

## Common Properties

- [Website](https://www.anyscale.com/)
- [Documentation](https://docs.anyscale.com/)
- [Plans](plans/anyscale-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/anyscale-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/anyscale-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/anyscale-plans-pricing.yml` | Hosted hourly rates (CPU, T4, L4, A10G, A100, H100, H200), BYOC, Enterprise. |
| Rate Limits | `rate-limits/anyscale-rate-limits.yml` | Pending - bounded primarily by AWS / GCP quotas. |
| FinOps | `finops/anyscale-finops.yml` | FOCUS-aligned, instance-hour meters per GPU class; BYOC dual-provider notes. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
