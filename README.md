<h1 align="center">Muhammad Arslan</h1>

<p align="center">
  Software Engineering Undergraduate · Sichuan University
</p>

<p align="center">
  Reliable Systems · Distributed Software · AI for Software Engineering
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Software-Engineering-2563EB?style=flat-square" alt="Software Engineering">
  <img src="https://img.shields.io/badge/Open-Source-2E7D32?style=flat-square" alt="Open Source">
  <img src="https://img.shields.io/badge/Master%27s-Study-6B4FB3?style=flat-square" alt="Master's Study">
</p>

---

## ◇ About Me

I am a Software Engineering undergraduate at **Sichuan University**, expected to graduate in **June 2027**. My interests are centered on reliable software systems, distributed computing, software reliability, systems software, and AI for Software Engineering.

Through projects such as **RepoRAG, Reloop, RealTimeCollab, and ArsiShell**, I am strengthening my practical understanding of distributed coordination, failure recovery, concurrency, process management, and repository-level code intelligence.

I am currently preparing for **Master's study for the 2027 intake** and exploring graduate opportunities where I can further develop my research and engineering skills in these areas.

## ◇ Core Skills

| Area | Focus |
| --- | --- |
| **Languages** | `TypeScript` · `C++` · `Python` |
| **Software Engineering** | Backend Development · REST APIs · Database Design · Authentication & Authorization · Real-Time Systems · Automated Testing |
| **Systems** | Distributed Coordination · Reliability Patterns · Concurrency · Failure Recovery · Process Management |
| **AI & Retrieval** | RAG Systems · Vector Retrieval · BM25 · Hybrid Search · Reranking · Grounded LLM Generation |
| **Technologies** | `Node.js` · `NestJS` · `Next.js` · `FastAPI` · `PostgreSQL` · `Prisma` · `Redis` · `Socket.IO` |

## ◆ Featured Engineering Projects

### 01 / RepoRAG

**Repository-aware AI code assistant**

An AI-for-Software-Engineering project for asking questions about software repositories and receiving grounded answers backed by exact source evidence.

[View Repository →](https://github.com/arsi505/RepoRAG)

**Key Engineering Work**

- Built ingestion for local Git repositories and public GitHub repositories with reproducible repository metadata.
- Implemented structural code-aware chunking with deterministic fallback coverage.
- Supports Vector semantic retrieval, BM25 lexical retrieval, Hybrid Vector + BM25 retrieval using Reciprocal Rank Fusion, and optional cross-encoder reranking.
- Added evidence scoping for **All**, **Code**, and **Docs** to control the context supplied to the generation layer.
- Generates grounded repository answers with file-, symbol-, and line-level source evidence plus citation validation.
- Integrates **DeepSeek, Gemini, and OpenAI** through a shared generation interface.
- Provides a local **FastAPI** backend and responsive **Next.js + TypeScript** interface with expandable source-code evidence.
- Improved large-repository support through adaptive embedding batching and reusable local indexes.
- Released as **RepoRAG v1.0.0** with automated tests, documentation, screenshots, and an MIT license.

**Stack:** `Python` · `FastAPI` · `Tree-sitter` · `PyTorch` · `Sentence Transformers` · `NumPy` · `Next.js` · `React` · `TypeScript`

**Engineering focus:** AI for Software Engineering, repository understanding, information retrieval, hybrid search, grounded generation, reproducibility

---

### 02 / Reloop

**Failure-aware workflows for cross-system consistency**

A reliability and recovery system for detecting and handling inconsistent order state across e-commerce integrations.

[View Repository →](https://github.com/arsi505/Reloop)

**Key Engineering Work**

- Ingests signed provider events with durable deduplication, then reconciles normalized cross-system state into recovery cases.
- Coordinates work through Redis Streams while keeping jobs, attempts, leases, workflows, approvals, and audit records in PostgreSQL.
- Uses atomic claims, renewable leases, ownership fencing, retry scheduling, and stale-message recovery to handle worker failures safely.
- Executes dependency-aware recovery workflows with human approval gates and verification before a case can be resolved.
- Exposes tenant-scoped REST APIs, operational dashboards, infrastructure health checks, and real-time invalidation events.

**Stack:** `TypeScript` · `Node.js` · `NestJS` · `Next.js` · `React` · `PostgreSQL` · `Prisma` · `Redis Streams` · `Socket.IO` · `Jest`

**Engineering focus:** Software reliability, idempotency, distributed work coordination, recovery workflows, tenant isolation, observability

> **Note:** Reloop's V1 recovery writes are simulator-backed. Its Shopify and ShipStation integrations are intentionally read-only.

---

### 03 / RealTimeCollab

**Real-time collaboration with durable shared state**

A full-stack collaborative workspace built to explore consistent shared state, concurrent editing, and real-time coordination.

[View Repository →](https://github.com/arsi505/RealTimeCollab)

**Key Engineering Work**

- Uses REST for state changes, PostgreSQL and Prisma for durable data, and Socket.IO for committed-update notifications.
- Protects document edits with version-based optimistic concurrency control and explicit conflict responses.
- Tracks distributed, multi-tab presence through Redis and supports cross-instance Socket.IO fan-out.
- Provides JWT authentication, Argon2 password hashing, workspace roles, rooms, documents, comments, and transactional activity history.
- Handles reconnect and resynchronization by restoring authoritative workspace state after network interruption.
- Includes automated tests for access control, concurrency, real-time synchronization, presence, and multi-server behavior.

**Stack:** `TypeScript` · `Next.js` · `React` · `NestJS` · `PostgreSQL` · `Prisma` · `Redis` · `Socket.IO` · `Vitest`

**Engineering focus:** Distributed state, real-time systems, concurrency control, authorization, transactional consistency, reconnect and resynchronization

---

### 04 / ArsiShell

**Process execution, IPC, and shell mechanics in C++**

A C++17 command-line shell and process manager built to apply operating-system and systems-programming concepts.

[View Repository →](https://github.com/arsi505/ArsiShell)

**Key Engineering Work**

- Implements a staged tokenizer and parser with quoted arguments and syntax validation.
- Supports multi-stage pipelines plus input, overwrite, and append redirection.
- Runs foreground and background processes and tracks pipeline jobs with `jobs`, `fg`, `bg`, and `kill`.
- Persists command history and supports `!!` and `!n` expansion across sessions.
- Provides Win32 and POSIX execution paths with explicit process and resource cleanup.
- Includes automated runtime testing for process and handle behavior.

**Stack:** `C++17` · `CMake` · `Win32 APIs` · `POSIX Process APIs` · `Python Test Harnesses`

**Engineering focus:** Systems programming, process creation, IPC, parsing, job management, resource cleanup

## ↗ Master's Study Direction

I am currently preparing for **Master's applications for the 2027 intake** in Software Engineering and systems-related areas.

**Research interests**

`Reliable Distributed Systems` · `Cloud & Networked Systems` · `Systems Software`  
`Software Reliability` · `AI for Software Engineering`

I am particularly interested in building software systems that remain **reliable, recoverable, and understandable** as they become more distributed and intelligent.

## ◇ Education

**Sichuan University**  
Bachelor's in Software Engineering  
2023–2027 · Expected Graduation: June 2027  
GPA: **3.23 / 4.00**
