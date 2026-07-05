# Ezra Wu (`qwertyboy0325`)

This is a public index of projects, experiments, and technical notes across the things I build.

I work across systems, realtime and edge workflows, data, and local-first AI exploration. The projects differ in domain and stack, but the recurring concern is making complex behaviour inspectable: understanding boundaries, failure modes, evidence, and recovery rather than treating a passing demo as proof.

---

## Current public work

### Systems and reliability

- **[handoff-semantics](https://github.com/qwertyboy0325/handoff-semantics)** — An inspectable, test-backed reference and case study for database-to-message reliability semantics. It is not a drop-in messaging framework or a Dapr replacement; it makes application-level contracts such as event identity, idempotent local effects, concurrent worker state transitions, retry/dead-letter behaviour, and the boundary between local transactions and external delivery explicit and testable. It includes a deterministic red→green reproduction of a stale failure-write race.

### Local-first AI exploration

- **[vox-proof](https://github.com/qwertyboy0325/vox-proof)** — An early-stage Rust project exploring local-first, evidence-backed transcript QA. Its starting point is bounded review with traceable evidence and human decisions; later research directions include local semantic and contextual interpretation.

---

## Working languages and tools

`C#` · `.NET` · `TypeScript` · `Rust` · `Python` · `PostgreSQL` · `NATS JetStream` · `Docker` · `Testcontainers`

---

Projects here vary in maturity. Their READMEs aim to state current scope, guarantees, and limitations explicitly.