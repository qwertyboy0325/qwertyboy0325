# Ezra Wu (`qwertyboy0325`)

**Backend / full-stack engineer — PostgreSQL & time-series data, event-driven reliability, architecture decisions.**
Taiwan (UTC+8) · async-first · open to remote roles · [LinkedIn](https://www.linkedin.com/in/ezra-wu-b96a1828a/) · [Blog](https://qwertyboy0325.hashnode.dev/) · `ezra40907@gmail.com`

## What I've built

- **Multi-tenant fleet platform (Jasslin, 2025–2026).** Primary platform owner in a two-person team; about 18,000 registered vehicles reporting at 1 Hz.
  - .NET 8 modular monolith, NATS JetStream, TimescaleDB, PostgreSQL row-level security, and a React dashboard.
  - Representative production chart queries went from 10–60+ s to 1–3 s.
  - Nightly 3–4 hour reports were replaced by incremental computation about 2–3 minutes behind live data.
- **Real-time surgical-video inference (Smart Surgery, 2023–2025).** NVIDIA Holoscan inference core and operators, integrated with C# via P/Invoke, plus a later C++/TensorRT pipeline delivered as a contract.

## How I work

Decisions go into ADRs and implementation plans with acceptance criteria before code. AI agents do most of the implementation; I own scope, architecture, tests as acceptance gates, and diff review. Model output is not accepted as evidence by itself.

## Selected public work

### [Handoff Semantics](https://github.com/qwertyboy0325/handoff-semantics) — C# / .NET 8 · PostgreSQL · NATS JetStream · Testcontainers
A test-backed reference for database-to-message reliability: transactional outbox, idempotent inbox, `FOR UPDATE SKIP LOCKED` workers, retry/dead-letter, and a deterministic red-to-green reproduction of a concurrency race.

### [Titan-S Realtime Go Case Study](https://github.com/qwertyboy0325/titan-s-realtime-go-case-study) — Go
Bounded-queue backpressure, semaphore-limited workers, capped backoff, and ID-based dedupe, with race-tested CI. A small demo, not a production system.

## Writing

- [FOR UPDATE SKIP LOCKED Was Not Enough: A Stale Failure Write Race in an Inbox Processor](https://qwertyboy0325.hashnode.dev/)

## Experiments

- [VoxProof](https://github.com/qwertyboy0325/vox-proof) — Rust transcript-QA prototype; an example of keeping AI-assisted work behind explicit review boundaries.
- [Gargantua Relativistic Renderer](https://github.com/qwertyboy0325/blackhole-rust) — Rust research renderer with deterministic, validated artifacts.
- [Personal site](https://qwertyboy0325.github.io/personal-site/) — no-framework, single-page site with unit and end-to-end tests.
