# Modal (modal)

Modal is a serverless cloud platform optimized for AI, data, and Python workloads. The Modal SDK and API let developers deploy GPU-accelerated functions, batch jobs, sandboxed code execution, web endpoints, and scheduled tasks with sub-second cold starts and pay-per-second billing.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/modal/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=modal-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, Serverless, Compute, Python, Inference, GPU

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Modal Functions API | Serverless Python functions with per-function GPU/CPU/memory and autoscaling. |
| Modal Apps API | Logical grouping/versioning of functions and resources. |
| Modal Sandboxes API | Isolated GPU-capable sandboxes for untrusted code (LLM agents). |
| Modal Images API | Container image build/cache pipeline (pip/conda/apt/Dockerfile). |
| Modal Volumes API | Distributed persistent volumes for weights/datasets. |
| Modal Network File Systems API | Shared mountable file systems across functions. |
| Modal Secrets API | Encrypted secrets injected as env vars. |
| Modal Web Endpoints API | HTTP / WebSocket / ASGI / WSGI endpoints. |
| Modal Cron API | Scheduled function runs with retries and history. |
| Modal Queues API | Distributed FIFO queues for async workloads. |
| Modal Dicts API | Distributed key-value state store. |
| Modal Tunnels API | Port forwarding for dev / hybrid networking. |
| Modal Environments API | Multi-env isolation (dev/staging/prod). |
| Modal Token / Workspace API | Workspace, token, and member management. |

## Common Properties

- [Website](https://modal.com/)
- [Documentation](https://modal.com/docs)
- [Plans](plans/modal-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/modal-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/modal-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/modal-plans-pricing.yml` | Starter / Team / Enterprise + per-second compute (CPU, memory, GPU classes T4..B200, storage). |
| Rate Limits | `rate-limits/modal-rate-limits.yml` | Tier-based concurrency caps (containers / GPUs / seats). |
| FinOps | `finops/modal-finops.yml` | FOCUS-aligned, second-granularity meters per CPU/memory/GPU class + storage. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
