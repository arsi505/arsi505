<h1 align="center">Muhammad Arslan</h1>

<p align="center">
  Software Engineering Undergraduate · Sichuan University
</p>

<p align="center">
  Backend Systems · Real-Time Software · Software Reliability
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Software-Engineering-2563EB?style=flat-square" alt="Software Engineering">
  <img src="https://img.shields.io/badge/Open-Source-2E7D32?style=flat-square" alt="Open Source">
  <img src="https://img.shields.io/badge/Graduate-Study-6B4FB3?style=flat-square" alt="Graduate Study">
</p>

---

## ◇ About Me

I build software systems to explore real engineering problems in concurrency, systems programming, backend architecture, and reliability.

I am also strengthening my academic foundations in preparation for graduate study.

## ◇ Core Skills

- **Languages:** TypeScript, C++
- **Software Engineering:** Backend Development, REST APIs, Database Design, Authentication & Authorization, Real-Time Systems, Automated Testing
- **Technologies:** Node.js, NestJS, Next.js, PostgreSQL, Prisma, Redis, Socket.IO

---

## ◆ Featured Engineering Projects

### 01 / [RealTimeCollab](https://github.com/arsi505/RealTimeCollab)

**Real-time collaboration with durable shared state**

A full-stack collaborative workspace built to explore consistent shared state, concurrent editing, and real-time coordination.

- Uses REST for state changes, PostgreSQL and Prisma for durable data, and Socket.IO for committed-update notifications.
- Protects document edits with version-based optimistic concurrency control and explicit conflict responses.
- Tracks distributed, multi-tab presence through Redis and supports cross-instance Socket.IO fan-out.
- Provides JWT authentication, Argon2 password hashing, workspace roles, rooms, documents, comments, and transactional activity history.
- Includes unit and end-to-end tests for access control, concurrency, real-time synchronization, presence, and multi-server behavior.

> **Stack** · TypeScript, Next.js, React, NestJS, PostgreSQL, Prisma, Redis, Socket.IO, Vitest
>
> **Engineering focus** · Real-time systems, concurrency control, authorization, transactional consistency, reconnect and resynchronization

---

### 02 / [ArsiShell](https://github.com/arsi505/ArsiShell)

**Process execution, IPC, and shell mechanics in C++**

A C++17 command-line shell and process manager built to apply operating-system and systems-programming concepts.

- Implements a staged tokenizer and parser with quoted arguments and syntax validation.
- Supports multi-stage pipelines plus input, overwrite, and append redirection.
- Runs foreground and background processes and tracks pipeline jobs with `jobs`, `fg`, `bg`, and `kill`.
- Persists command history and supports `!!` and `!n` expansion across sessions.
- Provides Win32 and POSIX execution paths; the automated runtime and handle-cleanup tests target Windows 11.

> **Stack** · C++17, CMake, Win32 APIs, POSIX process APIs, Python test harnesses
>
> **Engineering focus** · Process creation, IPC, file descriptors and handles, parsing, job management, resource cleanup

---

### 03 / [Reloop](https://github.com/arsi505/Reloop)

**Failure-aware workflows for cross-system consistency**

A reliability and recovery system for detecting and handling inconsistent order state across e-commerce integrations.

- Ingests signed provider events with durable deduplication, then reconciles normalized cross-system state into recovery cases.
- Coordinates work through Redis Streams while keeping jobs, attempts, leases, workflows, approvals, and audit records in PostgreSQL.
- Uses atomic claims, renewable leases, ownership fencing, retry scheduling, and stale-message recovery to handle worker failures safely.
- Executes dependency-aware recovery workflows with human approval gates and verification before a case can be resolved.
- Exposes tenant-scoped REST APIs, operational dashboards, infrastructure health checks, and real-time invalidation events.

> **Stack** · TypeScript, Node.js, NestJS, Next.js, React, PostgreSQL, Prisma, Redis Streams, Socket.IO, Jest
>
> **Engineering focus** · Reliability patterns, idempotency, distributed work coordination, recovery workflows, tenant isolation, observability

> Reloop's V1 recovery writes are simulator-backed. Its Shopify and ShipStation integrations are intentionally read-only.

---

## ↗ Graduate Study Direction

I am currently preparing for Master's applications in Software Engineering and related areas while strengthening my academic and engineering foundations.

My academic interests include:

- Software Architecture
- Distributed Systems
- Software Reliability
- Intelligent Software Systems
- Applied Generative AI

I am developing these areas through structured study and practical engineering projects.

## ◇ Education

**Sichuan University**\
Bachelor's in Software Engineering\
2023–2027\
GPA: **3.23 / 4.00**
