# Ezra Wu (`qwertyboy0325`)

Backend / distributed-systems engineer. I care about **messaging reliability, correctness under concurrency, and designs whose guarantees are backed by tests** — not by claims in a README.

I work mostly in **.NET / C#** and **TypeScript**, with a strong bias toward Domain-Driven Design, Clean Architecture, and treating cross-boundary reliability (outbox / inbox / idempotency / dead-letter) as a first-class concern.

---

### Featured work

- **[modulith-reliability-kit](https://github.com/qwertyboy0325/modulith-reliability-kit)** — .NET 8 modular-monolith reference for DB↔messaging reliability: transactional outbox, idempotent inbox, `FOR UPDATE SKIP LOCKED` multi-worker safety, dead-letter reprocessing, and an opt-in NATS JetStream transport. Every guarantee links to the code that enforces it and the test that pins it, and it ships a deterministic red→green case study of a stale-failure write race I found and fixed.

- **[echlub-front](https://github.com/qwertyboy0325/echlub-front)** — TypeScript music-collaboration / DAW frontend built on Clean Architecture: bounded contexts, CQRS, event sourcing, undo/redo, and Tone.js audio + WebRTC real-time collaboration.

- **[echlub_backend](https://github.com/qwertyboy0325/echlub_backend)** — TypeScript backend for EchLub: Express 5 + Socket.IO real-time collaboration rooms with WebRTC signaling relay, JWT auth, TypeORM, and a DDD module layout.

- **[vox-proof](https://github.com/qwertyboy0325/vox-proof)** — Rust, local-first, evidence-backed transcript QA (early stage; scope and status stated honestly in the repo).

---

### Toolbox

`C#` · `.NET 8` · `EF Core` · `TypeScript` · `Node.js` · `Rust` · `PostgreSQL` · `NATS JetStream` · `Docker` · `Testcontainers` · DDD · CQRS · Event Sourcing

---

I try to state project status honestly — if something isn't verified end-to-end yet, the repo says so.
