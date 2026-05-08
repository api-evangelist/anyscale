# Anyscale (anyscale)

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
