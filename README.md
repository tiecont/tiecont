<div align="center">

# Hi, I'm Tiecont 👋

### Backend Engineer · TypeScript / NestJS · Go

**Building backend systems that remain correct when things go wrong.**

![Profile Views](https://komarev.com/ghpvc/?username=tiecont\&style=flat\&label=Profile+Views)
![GitHub Followers](https://img.shields.io/github/followers/tiecont?style=flat\&logo=github\&label=Followers)

</div>

---

## 👨‍💻 About Me

I'm a **Backend Engineer** focused on building reliable, maintainable, and production-ready backend systems.

My work goes beyond implementing CRUD APIs. I regularly deal with problems around:

* business invariants and data consistency
* authentication and authorization
* transactional workflows
* concurrent processing
* idempotency
* background jobs
* retry and recovery
* distributed locking
* database migrations
* API contract evolution
* production debugging
* automated testing

My primary backend stack is **TypeScript / Node.js / NestJS**, with growing experience building backend services in **Go**.

---

## ⚙️ What I Work With

### Backend Engineering

* **TypeScript**
* **Node.js**
* **NestJS**
* **Express**
* **Go**
* **Fiber**
* **TypeORM**
* **GORM**

### Data

* **PostgreSQL**
* **MySQL**
* **MongoDB**
* **Redis**

### Messaging & Async Processing

* **RabbitMQ**
* **Kafka**
* Background jobs
* Scheduled workflows
* Retry / backoff
* Stale-job recovery
* Idempotent processing

### Infrastructure & Tooling

* **Docker**
* **Linux**
* **Git / GitHub**
* CI-oriented development workflows
* PostgreSQL-backed integration environments

---

## 🧠 Backend Engineering Focus

```text
Production Backend Engineering
│
├── API Design
│   ├── REST APIs
│   ├── Validation
│   ├── Stable contracts
│   ├── Pagination & filtering
│   └── Error mapping
│
├── Data Integrity
│   ├── PostgreSQL
│   ├── Transactions
│   ├── Database migrations
│   ├── Constraints
│   └── Idempotency
│
├── Authentication & Authorization
│   ├── SSO
│   ├── RBAC
│   ├── Permission systems
│   ├── Guards
│   └── Resource-scoped access
│
├── Reliability
│   ├── Background jobs
│   ├── Retry / Backoff
│   ├── Crash recovery
│   ├── Partial failure handling
│   └── Failure isolation
│
├── Concurrency
│   ├── Atomic job claiming
│   ├── Duplicate prevention
│   ├── Distributed locks
│   └── PostgreSQL advisory locks
│
└── Verification
    ├── Unit tests
    ├── Integration tests
    ├── PostgreSQL E2E
    ├── Concurrency tests
    └── Volume tests
```

---

## 🛠 Tech Stack

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,go,express" alt="Backend Stack" />
</p>

### Databases & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,docker,kubernetes" alt="Infrastructure Stack" />
</p>

### Engineering Environment

<p>
  <img src="https://skillicons.dev/icons?i=git,github,linux,bash" alt="Engineering Tools" />
</p>

`NestJS` · `TypeORM` · `PostgreSQL` · `Redis` · `Docker` · `Go` · `Fiber` · `GORM` · `MySQL` · `MongoDB` · `RabbitMQ` · `Kafka`

---

## 🔐 Authentication & Authorization

I have practical experience working with backend authorization systems involving:

* SSO authentication flows
* RBAC
* permission matrices
* route guards
* resource-level authorization
* team/project scoped access
* identity mapping
* external authentication services

I care about enforcing authorization at the **business boundary**, not only at the controller level.

---

## 🔄 Reliable Background Processing

A significant part of my backend work involves workflows that cannot simply fail and disappear.

I work with patterns such as:

```text
PENDING
   │
   ▼
PROCESSING
   │
   ├──── success ────► COMPLETED
   │
   └──── failure
            │
            ▼
          RETRY
            │
       ┌────┴────┐
       │         │
    recover   max attempts
       │         │
       ▼         ▼
 PROCESSING    FAILED
```

Including:

* atomic job claiming
* retry with backoff
* stale processing recovery
* terminal failure states
* distributed locking
* duplicate prevention
* partial delivery recovery
* crash-safe workflows
* bounded batch processing

---

## 🗄 Database Engineering

I regularly work with PostgreSQL beyond basic ORM operations.

Areas include:

* schema design
* migrations
* foreign keys
* unique and partial indexes
* constraints
* transactions
* transaction boundaries
* concurrency
* advisory locks
* query optimization
* bulk loading
* avoiding N+1 queries
* database-backed integration testing
* production migration safety

---

## 🧪 Testing Philosophy

For important backend workflows, a happy-path unit test is not enough.

I try to verify systems under scenarios such as:

```text
Normal execution
Concurrent execution
Duplicate requests
Partial failure
Process crash
Retry
Stale state recovery
Database rollback
High-volume processing
```

Testing approaches I work with include:

* Unit testing
* Integration testing
* PostgreSQL-backed E2E
* Docker-based test infrastructure
* Concurrency testing
* Recovery testing
* Volume testing

---

## 🧩 How I Approach Problems

When something breaks, I prefer asking:

> **Which invariant was violated?**

rather than:

> **Which line should I patch?**

My preferred approach is:

```text
Understand business rule
        ↓
Identify invariant
        ↓
Find failure modes
        ↓
Design state transitions
        ↓
Protect data integrity
        ↓
Handle concurrency
        ↓
Test failure scenarios
        ↓
Ship
        ↓
Observe & improve
```

---

## 📊 GitHub Activity & Rank

<div align="center">

<img
height="180"
src="https://github-stats-extended.vercel.app/api?username=tiecont&show_icons=true&include_all_commits=true&show=reviews,prs_merged,prs_merged_percentage&hide_border=true&theme=transparent&rank_icon=default"
alt="Tiecont GitHub Stats"
/>

<img
height="180"
src="https://github-stats-extended.vercel.app/api/top-langs/?username=tiecont&layout=compact&langs_count=8&size_weight=0.5&count_weight=0.5&hide_border=true&theme=transparent"
alt="Tiecont Top Languages"
/>

</div>

<p align="center">
  <sub>
    Rank is calculated by GitHub Stats Extended from GitHub activity signals.
    It is not an official GitHub developer ranking.
  </sub>
</p>

---

## 📈 Contribution Activity

<div align="center">

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=tiecont&theme=github-compact&hide_border=true&area=true"
width="95%"
alt="Tiecont GitHub Contribution Graph"
/>

</div>

---

## 🎯 Engineering Interests

I'm particularly interested in:

* Backend architecture
* Distributed systems
* Concurrency
* Database correctness
* System design
* Event-driven architecture
* Background processing
* Production reliability
* Performance engineering
* Go backend development
* Open-source engineering

---

## 🌱 Current Direction

I'm currently focusing on deepening my knowledge of:

**Distributed Systems**

**System Design**

**Go**

**Database Internals**

**Production Reliability**

**Open Source**

My goal is not to collect technologies.

My goal is to become better at designing systems that are:

```text
Correct
Reliable
Observable
Recoverable
Maintainable
Scalable
```

---

<div align="center">

### Build systems that survive production.

**TypeScript · NestJS · PostgreSQL · Redis · Go**

</div>
