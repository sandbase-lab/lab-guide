# Production checklist

Use this checklist to identify remaining work. Completing it does not automatically prove production readiness. Link each item to implementation, evaluation, or operating evidence; explain items that do not apply.

## Quality and scope

- [ ] Define users, delivered artifacts, acceptance criteria, and unsupported tasks.
- [ ] Evaluate representative inputs, failures, empty data, and unexpected tool responses.
- [ ] Record sample sizes, dates, model and code versions, success rates, and human review methods.
- [ ] Distinguish real runs, mock results, and recorded demos.

## Cost and reliability

- [ ] Measure latency and cost; enforce per-task budgets and call limits.
- [ ] Configure timeouts and retryable errors without blindly repeating uncertain results.
- [ ] Define concurrency and rate limits; handle unavailable services and interrupted tasks.
- [ ] Track async status and support cancellation, persistence, and recovery where needed.
- [ ] Use appropriate idempotency or deduplication for external writes.

## Permissions and data

- [ ] Grant minimum permissions, store secrets server-side, and redact logs.
- [ ] Prevent untrusted inputs or tool results from expanding permissions or granting authorization.
- [ ] Define authorization requirements for publishing, sending, purchasing, and similar actions.
- [ ] Document storage location, retention, and deletion.
- [ ] Bound sandbox network access, resources, and file access for the task.

## Deployment and operations

- [ ] Validate startup, health checks, and configuration in the target environment.
- [ ] Correlate logs, tool calls, and results with task identifiers.
- [ ] Monitor quality, latency, failures, and budget anomalies.
- [ ] Validate recovery, rollback, and dependency upgrades.
- [ ] Define maintainers, supported versions, and incident response.

## Release evidence

Link evaluations, deployment guidance, limitations, and the last validation date in the README. Production-ready claims must state validated workloads and environments; do not extend conclusions to untested conditions.
