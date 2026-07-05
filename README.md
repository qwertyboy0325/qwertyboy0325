# Ezra Wu (`qwertyboy0325`)

This repository is a lightweight entry point to the public work collected across this GitHub profile.

I work mostly on backend systems and reliability-oriented engineering, with an interest in messaging failure modes, correctness under concurrency, and designs whose guarantees are backed by tests rather than README claims.

My current public work is mostly in **.NET / C#**, **TypeScript**, **Rust**, and **PostgreSQL**.

---

### Featured work

- **[modulith-reliability-kit](https://github.com/qwertyboy0325/modulith-reliability-kit)** — A .NET 8 modular-monolith reference implementation for DB↔messaging reliability: transactional outbox, idempotent inbox handling, `FOR UPDATE SKIP LOCKED` multi-worker coordination, dead-letter reprocessing, and an opt-in NATS JetStream transport. The repository connects its stated guarantees to the code that enforces them and the tests that pin them, and includes a deterministic red→green case study of a stale-failure write race.

- **[vox-proof](https://github.com/qwertyboy0325/vox-proof)** — An early-stage Rust project exploring local-first, evidence-backed transcript QA. Its current scope and limitations are stated in the repository.

---

### Technologies used across selected work

`C#` · `.NET 8` · `EF Core` · `TypeScript` · `Node.js` · `Rust` · `PostgreSQL` · `NATS JetStream` · `Docker` · `Testcontainers` · `CQRS` · `Domain modeling`

---

Project status, guarantees, and known limitations are stated explicitly where possible.
