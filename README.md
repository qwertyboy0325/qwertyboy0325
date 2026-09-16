# Ezra Wu (`qwertyboy0325`)

## Backend / Data Reliability Engineer

I diagnose and harden backend and data systems where failures, concurrency,
migrations, and integrations matter.

My production experience includes fleet telemetry, PostgreSQL/TimescaleDB
modernization, migration and reconciliation, multi-tenant isolation, event
handoff/recovery, and real-time medical-video inference workflows.

`Backend reliability` · `PostgreSQL / TimescaleDB` · `Data migration` · `Async processing` · `System integration`

### Available for

- Remote backend / platform / data-reliability roles.
- Short, scoped engineering engagements around API/integration debugging,
  PostgreSQL performance or migration, async processing/reliability, and
  backend integration of AI/LLM workflows.
- Remediation work where an existing prototype or AI-generated implementation
  needs to be made testable, reliable, and operationally understandable.

Taiwan / UTC+8 · async-friendly · contact: [LinkedIn](https://www.linkedin.com/in/ezra-wu-b96a1828a/) · `ezra40907@gmail.com`

## Production background

- Worked on fleet/telemetry systems supporting roughly 18,000 vehicles, including
  large legacy MySQL data paths and PostgreSQL/TimescaleDB redesign and validation.
- Improved a representative single-vehicle 24-hour history path from 30s+ / stall-prone
  behavior to typically under 1s through time-series aggregation, indexing, and query-path redesign.
- Worked on migration/reconciliation, tenant-isolation boundaries, event delivery/retry,
  and deterministic recovery behavior.
- Built and supported real-time surgical-video inference workflows using Unity/C#,
  Python, NVIDIA Holoscan, ONNX/TensorRT/Triton, and DeepStream.

## Selected public work

### [Handoff Semantics](https://github.com/qwertyboy0325/handoff-semantics)

**C# / .NET · PostgreSQL · NATS JetStream · Testcontainers**

A test-backed reference for database-to-message reliability: transactional outbox,
idempotent inbox, `FOR UPDATE SKIP LOCKED` workers, bounded retry/dead-letter,
operator reprocessing, and a deterministic stale failure-write concurrency case study.

### [Titan-S Realtime Go Case Study](https://github.com/qwertyboy0325/titan-s-realtime-go-case-study)

**Go · bounded concurrency · realtime-data pipeline · deterministic tests**

A clean-room engineering case study for typed ingestion, bounded queues,
semaphore-limited workers, duplicate handling, reconnect/backoff, and deterministic
window summaries using synthetic fixtures.

### [VoxProof](https://github.com/qwertyboy0325/vox-proof)

**Rust · local-first workflow · human review · deterministic persistence research**

A bounded transcript-QA prototype where probabilistic retrieval/ranking cannot
silently overwrite authoritative reviewed output. Useful as evidence of explicit
state ownership, review boundaries, and fail-closed engineering.

## Additional engineering work

- [Gargantua Relativistic Renderer](https://github.com/qwertyboy0325/blackhole-rust) — Rust numerical integration, deterministic artifacts, validation-oriented rendering.
- [EchLub](https://github.com/qwertyboy0325/echlub) — Rust + TypeScript/React/WASM, WebSocket/WebRTC experiments, reproducible browser-performance evidence.

## Working approach

I use AI tooling when it improves throughput, but engineering ownership stays explicit:
constraints, architecture, tests, diffs, and artifacts remain reviewable, and model
output is not accepted as evidence by itself.
