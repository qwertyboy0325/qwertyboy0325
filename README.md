# Ezra Wu (`qwertyboy0325`)

This is a public index of projects, experiments, and technical notes across the things I build.

I work across backend/platform systems, realtime and edge workflows, data systems, and local-first AI exploration. The projects differ in domain and stack, but the recurring concern is making complex behaviour inspectable: understanding boundaries, failure modes, evidence, and recovery rather than treating a passing demo as proof.

---

## Available for focused contract work

I am open to short, bounded backend/platform engagements where correctness, operational risk, data flow, or system boundaries matter.

Good fits:

- backend reliability audits: worker/queue/retry/idempotency, transactional outbox, idempotent inbox, and failure-mode review
- PostgreSQL/data-system diagnosis: schema, query, index, migration, consistency, and reporting-path risk review
- legacy backend triage: .NET/C# or TypeScript/Node.js systems, first safe intervention, CI/testing baseline, and modernization boundary planning
- internal AI workflow prototypes: local-first or human-in-the-loop review tools with evidence, traceability, and explicit decision records
- realtime/backend product slices: APIs, state synchronization, WebSocket/Socket.IO workflows, and interaction-heavy internal tooling

I prefer scoped diagnostic or first-intervention projects: clear deliverables, written findings, explicit tradeoffs, and implementation where the boundary is well-defined.

---

## Current public work

### Active build

- **[vox-proof](https://github.com/qwertyboy0325/vox-proof)** — An early-stage Rust project exploring local-first, evidence-backed transcript QA. Its starting point is bounded review with traceable evidence and human decisions; later research directions include local semantic and contextual interpretation.

### Reliability reference work

- **[handoff-semantics](https://github.com/qwertyboy0325/handoff-semantics)** — An inspectable, test-backed reference and case study for database-to-message reliability semantics. It is not a drop-in messaging framework or a Dapr replacement; it makes application-level contracts such as event identity, idempotent local effects, concurrent worker state transitions, retry/dead-letter behaviour, and the boundary between local transactions and external delivery explicit and testable. It includes a deterministic red→green reproduction of a stale failure-write race.

---

## Confirmed working areas

### Backend and platform

`C#` · `.NET` · `Go` · `TypeScript` · `Node.js` · `Rust` · `Python`

- API and backend service design
- modular monolith / bounded-module design
- worker, queue, retry, idempotency, and dead-letter handling
- transactional boundaries between database state and external message delivery
- legacy-system triage and safe first-intervention planning

### Data and messaging

`PostgreSQL` · `TimescaleDB` · `PostGIS` · `MySQL` · `NATS JetStream` · `Kafka`

- schema and query review
- migration and reconciliation planning
- reporting-path and historical-data performance diagnosis
- event-driven workflow design with explicit delivery and recovery semantics

### Dev workflow and operations

`Docker` · `GitHub Actions` · `Testcontainers` · `Prometheus` · `Grafana` · `Linux`

- CI/testing baselines
- integration tests against real infrastructure
- containerized development and demo environments
- operational visibility and failure-path verification

### Realtime and product-facing systems

`React` · `Vite` · `WebSocket` · `Socket.IO` · `REST APIs`

- realtime collaboration and state synchronization
- interactive frontend/backend product slices
- internal tools where the UI must expose state, evidence, or decisions clearly

---

Projects here vary in maturity. Their READMEs aim to state current scope, guarantees, and limitations explicitly.