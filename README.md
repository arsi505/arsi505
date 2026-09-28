# Muhammad Arslan

**Software Engineering Undergraduate — Sichuan University**

I build practical software systems and use project work to study backend engineering, real-time collaboration, systems programming, and software reliability.

## About Me

I am a Software Engineering student focused on turning engineering concepts into working systems. My projects span full-stack collaboration software, operating-system fundamentals, and failure-aware backend workflows.

## Core Skills

- **Languages:** TypeScript, C++
- **Software Engineering:** Backend Development, REST APIs, Database Design, Authentication & Authorization, Real-Time Systems, Automated Testing
- **Technologies:** Node.js, NestJS, Next.js, PostgreSQL, Prisma, Redis, Socket.IO

## Featured Open-Source Projects

### [RealTimeCollab](https://github.com/arsi505/RealTimeCollab)

A full-stack collaborative workspace built to explore consistent shared state, concurrent editing, and real-time coordination.

- Uses REST for state changes, PostgreSQL and Prisma for durable data, and Socket.IO for committed-update notifications.
- Protects document edits with version-based optimistic concurrency control and explicit conflict responses.
- Tracks distributed, multi-tab presence through Redis and supports cross-instance Socket.IO fan-out.
- Provides JWT authentication, Argon2 password hashing, workspace roles, rooms, documents, comments, and transactional activity history.
- Includes unit and end-to-end tests for access control, concurrency, realtime synchronization, presence, and multi-server behavior.

**Stack:** TypeScript, Next.js, React, NestJS, PostgreSQL, Prisma, Redis, Socket.IO, Vitest

**Engineering focus:** Realtime systems, concurrency control, authorization, transactional consistency, reconnect and resynchronization

### [ArsiShell](https://github.com/arsi505/ArsiShell)

A C++17 command-line shell and process manager built to apply operating-system and systems-programming concepts.

- Implements a staged tokenizer and parser with quoted arguments and syntax validation.
- Supports multi-stage pipelines plus input, overwrite, and append redirection.
- Runs foreground and background processes and tracks pipeline jobs with `jobs`, `fg`, `bg`, and `kill`.
- Persists command history and supports `!!` and `!n` expansion across sessions.
- Provides Win32 and POSIX execution paths; the automated runtime and handle-cleanup tests target Windows 11.

**Stack:** C++17, CMake, Win32 APIs, POSIX process APIs, Python test harnesses

**Engineering focus:** Process creation, IPC, file descriptors and handles, parsing, job management, resource cleanup

### [Reloop](https://github.com/arsi505/Reloop)

A reliability and recovery system for detecting and handling inconsistent order state across e-commerce integrations.

- Ingests signed provider events with durable deduplication, then reconciles normalized cross-system state into recovery cases.
- Coordinates work through Redis Streams while keeping jobs, attempts, leases, workflows, approvals, and audit records in PostgreSQL.
- Uses atomic claims, renewable leases, ownership fencing, retry scheduling, and stale-message recovery to handle worker failures safely.
- Executes dependency-aware recovery workflows with human approval gates and verification before a case can be resolved.
- Exposes tenant-scoped REST APIs, operational dashboards, infrastructure health checks, and realtime invalidation events.

**Stack:** TypeScript, Node.js, NestJS, Next.js, React, PostgreSQL, Prisma, Redis Streams, Socket.IO, Jest

**Engineering focus:** Reliability patterns, idempotency, distributed work coordination, recovery workflows, tenant isolation, observability

> Reloop's V1 recovery writes are simulator-backed. Its Shopify and ShipStation integrations are intentionally read-only.

## Currently Exploring

- Software architecture and distributed systems
- Software reliability and failure recovery
- Intelligent software systems
- Applied generative AI

## Education

**Sichuan University**\
Bachelor's in Software Engineering\
2023–2027\
GPA: **3.23 / 4.00**

## Contact

[GitHub](https://github.com/arsi505)
