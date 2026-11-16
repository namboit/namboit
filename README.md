### Nam Kim
**Backend & Systems Engineer** &middot; Go &middot; PostgreSQL &middot; Distributed Systems

Backend engineer specialized in high-performance Go services, multi-tenant relational databases, and real-time payment infrastructure. Currently architecting core backend engines, WebSocket event streaming, and financial reconciliation pipelines across multi-property hospitality and venue operations.

---

### Featured Systems & Open Source

#### 🚀 [khqr-go](https://github.com/namboit/khqr-go)
**High-performance, offline Go implementation of the EMVCo Bakong KHQR payment specification.**
* **Zero Network Latency:** 100% offline generation and validation eliminating the 100 req/day API rate limit of the official SDK.
* **Extreme Throughput:** Benchmarked at **~8.7 µs** to build dynamic QR codes and **~1.8 µs** to validate and parse payloads (500,000+ ops/sec per core).
* **Spec Compliant:** Full Tag-Length-Value (TLV) engine, CRC-16/CCITT-FALSE calculation, dynamic bill expiry, and pure Go PNG label rendering for venue POS printers.
* **Bank-Grade Quality:** 100% test vectors matching the National Bank of Cambodia standard.

#### ⚡ inView Enterprise Engine *(Production Core)*
**Multi-tenant Go backend powering hotel PMS (Folio), restaurant POS (Cater), and HRMS (Talent).**
* **Scalable Data Layer:** 145+ PostgreSQL schema migrations with strict multi-tenant data isolation and automated nightly disaster recovery backups.
* **Real-Time State Sync:** WebSocket infrastructure broadcasting live order events to kitchen display systems (KDS) and front-desk reservation calendars with sub-50ms latency.
* **Automated Financial Rails:** End-to-end payment gateway engine processing dynamic Bakong KHQR codes and ABA PayWay webhook reconciliation with idempotent transaction guards.
* **High Availability:** 99.9% uptime SLA managed via Linux daemons, PM2 process trees, and zero-downtime hotfix deployments.

#### 🛠️ [helpdesk-labs](https://github.com/namboit/helpdesk-labs)
**Lightweight, self-hosted Telegram IT ticketing system and mobile MiniApp.**
* Built with FastAPI, HTMX, and SQLite WAL mode to deliver instant, reactive mobile triage without heavy client-side JavaScript.

---

### Core Competencies

* **Languages:** Go (Golang), TypeScript, Python, SQL (PostgreSQL, SQLite)
* **Backend & Systems:** RESTful APIs, WebSockets, Concurrency & Channels, Microservices, Event-Driven Architecture
* **Databases & Storage:** PostgreSQL (Indexing, Constraints, 145+ Migrations), SQLite WAL mode, Data Isolation
* **Fintech & Protocols:** EMVCo QR Specifications, CRC-16/CCITT, Banking Webhook Reconciliation, Idempotency
* **DevOps & Infrastructure:** Linux Server Administration, PM2 Daemons, Bash Scripting, CI/CD, SSL/TLS, Automated Backups

---

📫 **Connect:** [LinkedIn](https://linkedin.com/in/thenamkim) &middot; [Email](mailto:namyoung93333@gmail.com)
