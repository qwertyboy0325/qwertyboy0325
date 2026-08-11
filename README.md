# Ezra Wu (`qwertyboy0325`)

## Backend / Platform Engineer

I build backend systems where correct state changes survive failure: database
transactions, idempotent workers, retry and recovery paths, and explicit
handoffs to downstream services.

My public work spans C#/.NET and PostgreSQL reliability, Go realtime-data
pipelines, Rust systems engineering, human-reviewed AI workflows, and realtime
protocol experiments.

`Backend reliability` · `Data consistency` · `Go realtime systems` · `Rust systems` · `Human-governed AI workflows`

Open to remote backend / platform engineering roles and focused engineering
engagements.

## Selected public work

### [Handoff Semantics](https://github.com/qwertyboy0325/handoff-semantics)

**C# / .NET · PostgreSQL · NATS JetStream · Testcontainers**

A test-backed reference implementation for the database-to-message boundary.
It makes transactional outbox/inbox behavior, idempotent local effects,
`FOR UPDATE SKIP LOCKED` workers, retries, dead letters, and bounded delivery
guarantees concrete. Integration tests reproduce and prevent a stale
failure-write race between concurrent workers.

### [Titan-S Realtime Go Case Study](https://github.com/qwertyboy0325/titan-s-realtime-go-case-study)

**Go · bounded concurrency · realtime-data pipeline · deterministic tests**

A clean-room, offline case study for typed market-data ingestion, bounded
queues, semaphore-limited workers, store-scoped duplicate handling, and
deterministic time-series summaries. It is an engineering demonstration with
synthetic fixtures, not a trading product or a production reliability claim.

### [VoxProof](https://github.com/qwertyboy0325/vox-proof)

**Rust · local-first transcript QA · human review**

A bounded prototype for reviewing existing subtitle transcripts. It preserves
the source and evidence for each candidate, and produces reviewed output only
after explicit human decisions. Experimental retrieval and ranking are kept
separate from the authoritative review path.

### [Gargantua Relativistic Renderer](https://github.com/qwertyboy0325/blackhole-rust)

**Rust · numerical integration · deterministic artifacts**

An offline renderer for inspectable light paths in a Kerr spacetime. Its CPU
`f64` geodesic path, typed ray outcomes, and validation artifacts keep physical
results distinct from display presentation. It is a research renderer, not an
*Interstellar* reproduction or a realtime GPU product.

### [EchLub](https://github.com/qwertyboy0325/echlub)

**Rust · TypeScript / React · WebSocket / WebRTC research**

An experimental music-systems foundation with deterministic musical state,
transport-independent protocol boundaries, a React/WASM lab UI, and
browser-performance evidence. It is technical evidence, not a production
DAW or an established product thesis.

## Working approach

Some projects use substantial AI assistance. I keep engineering ownership
inspectable by defining constraints, reviewing diffs, and tying claims to code,
tests, or reproducible artifacts; model output is not accepted automatically.

Projects here vary in maturity; each README states its scope, evidence, and
limitations directly.
