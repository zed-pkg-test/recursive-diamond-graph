# Test plan

- Verify recursive diamond resolution, shared transitive CAS materialization, and deterministic lockfiles across the supported happy-path states and canonical fixtures.
- Verify recursive diamond resolution, shared transitive CAS materialization, and deterministic lockfiles under retries, interruption, concurrency, offline operation, or partial failure.
- Verify recursive diamond resolution, shared transitive CAS materialization, and deterministic lockfiles preserves authorization, idempotency, integrity, observability, and actionable failure classification.

## Classification

- product regression
- blocked dependency
- harness regression
