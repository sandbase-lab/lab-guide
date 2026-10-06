# Lab project standard

## Repository boundaries

Each independent agent application has its own repository, dependencies, evaluations, releases, and deployment guidance. Extract a shared package only when multiple projects actually need it.

## Experimental

- Explain the real task and show an actual result.
- Provide runnable code, pinned dependencies, and example environment variables without secrets.
- Document clean-environment setup, example inputs, and expected outputs.
- State model, API, and sandbox dependencies, billing requirements, and limitations.
- Provide fixtures or mock mode and distinguish simulated from real results.
- Include a license. Apache-2.0 is suggested for code; review data and third-party asset licenses separately.

## Preview

Meet Experimental requirements and add:

- Multiple evaluation inputs, acceptance criteria, and failure cases.
- Deployment instructions, timeouts, retries, error feedback, and budget controls.
- Measurement conditions, dates, and sample sizes for success rate, latency, and cost.
- As applicable, async status, cancellation, idempotency, and result persistence.

## Production-ready

Meet Preview requirements and add:

- Supported workloads, concurrency, data scale, and service dependencies.
- Evaluation and load evidence in the target environment, including known failure boundaries.
- Permissions, secret management, log redaction, and data retention policies.
- Monitoring, recovery, rollback, and maintenance responsibilities.
- Explicit authorization and duplicate-execution controls for external actions such as sending, publishing, or purchasing.

Stages describe available evidence. A single successful demo does not establish production readiness.

## Directory fields

Name, task, repository, preview, stage, setup instructions, service dependencies, cost evidence, maintainer, and last validation date.

Unimplemented projects belong in the candidate list and must not claim working demos or deployments.
