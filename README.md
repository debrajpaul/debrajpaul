# Debraj Paul

**Technical Lead II — Backend / Platform Engineer** — Node.js · TypeScript · AWS
Bengaluru, IN · Open to remote globally · Open to relocation

11+ years designing, building, and operating distributed backend systems across media, fintech, food-tech, and travel. Deep in AWS-native architectures, event-driven platforms, and Backend-for-Frontend GraphQL. Currently shipping privacy-orchestration, multi-brand moderation, and backfill data pipelines for a global content platform supporting Food Network, CNN, Eurosport, Magnolia, Golf Digest, and MotorTrend at Warner Bros. Discovery.

[Portfolio](https://debrajpaul.github.io) · [LinkedIn](https://www.linkedin.com/in/debraj-paul) · [Email](mailto:debraj@debrajpaul.com) · [CV (PDF)](https://debrajpaul.com/assets/Debraj_Paul_CV.pdf)

---

## Highlights

| Metric | Where | Context |
| --- | --- | --- |
| **11+ years** | — | Distributed backends across media · fintech · food-tech · travel |
| **~50% latency reduction** | Swiggy Dineout (formerly Dineout, Times Internet) | POS event pipelines on Kafka + Redis |
| **~25% revenue lift** | Swiggy Dineout (formerly Dineout, Times Internet) | Three enterprise-grade microservices on AWS |
| **~25% conversion lift / ~15% bounce drop** | Swiggy Dineout (formerly Dineout, Times Internet) | Customer segmentation on MongoDB + ElasticSearch |
| **95% credit workflow automation** | PT Tujuh Asia | P2P lending platform with OCR + facial KYC + NLP scoring |
| **6+ microservices** | Warner Bros. Discovery | GDPR / CCPA fan-out orchestrated via OneTrust |
| **10+ POS systems integrated** | Swiggy Dineout (formerly Dineout, Times Internet) | Kafka topic schemas + backward-compatible event evolution |

---

## Currently shipping

At **Warner Bros. Discovery (via Robosoft)** since Aug 2020 — Technical Lead II on a global content platform supporting multiple brands.

- **Privacy / PII Request Orchestrator** — GDPR/CCPA fan-out across 6+ PII-holding microservices via OneTrust. Service-registry-driven routing, two-stream Kafka contract, per-service + aggregate state machine, idempotent on subject-request-ID end-to-end.
- **Multi-Brand Async Moderation Platform** — text, nickname, and image moderation for N consumer surfaces (web + mobile). Migrated text path off a third-party vendor; absorbed image path from a sister team. Two-stream Kafka, hot-reloadable per-brand policy, dual-store (S3 bytes + DynamoDB metadata).
- **Backfill Search-Indexing Pipeline** — lifted a large content corpus from production DynamoDB to OpenSearch without touching read capacity. DDB native S3 export → AWS Glue → Parquet (Snappy) → Node.js Lambda batching → Search Indexing API. SQS FIFO + DLQ for exhausted retries.
- Loosely coupled Node.js/TypeScript microservices on AWS (Lambda, ECS, SNS, SQS) with Infrastructure-as-Code.
- Scalable **GraphQL Backend-for-Frontend** for Food Network with auth, observability, and proactive monitoring.
- REST + GraphQL API conventions standardized across teams; distributed tracing via OpenTelemetry; Redis cache-aside.

---

## Selected experience

- **Warner Bros. Discovery** — Technical Lead II· Aug 2020 – Present · Remote. Global content platform, privacy orchestration, multi-brand moderation, backfill ETL, GraphQL BFF, GDPR/CCPA compliance.
- **Swiggy Dineout** (formerly Dineout, Times Internet) — Senior Software Engineer · Dec 2019 – Jun 2021 · Bengaluru. Event-driven POS integrations, segmentation, marketing pipelines.
- **PT Teknologi Tujuh Asia** — Senior Software Engineer · Nov 2018 – Dec 2019 · Jakarta. P2P lending, KYC automation, NLP-based risk scoring.
- **TripBorn** — Backend Developer · Apr 2018 – Oct 2018 · Bengaluru. GDS reservation + booking workflows.
- **Ekagga Technology** — Software Engineer · May 2017 – Apr 2018 · Bengaluru. Java/Spring Boot enterprise news + analytics platform.
- **CSIR – URDIP (FAO project)** — SDE Intern · Jan 2015 – Jun 2015 · Bengaluru. Neural-network configurations for food import/export analytics in Core Java.

Full timeline and architecture write-ups on the [portfolio](https://debrajpaul.github.io).

---

## Open source & personal projects

- **[Full Budget App](https://github.com/debrajpaul/full-budget-app)** — modular, multi-tenant SaaS budgeting platform (active, solo, MIT-licensed, started Aug 2025). Ingests bank statements (HDFC, SBI, Axis · PDF/CSV), enriches transactions via deterministic NLP rules with an Amazon Bedrock AI fallback, and serves a tenant-aware GraphQL API. pnpm monorepo on AWS serverless (Lambda · DynamoDB · S3 · SQS · DynamoDB Streams), fully provisioned via AWS CDK. Multi-tenant data isolation at the schema level (`tenantId` partition key), event-driven ingestion (zero polling), schema-first GraphQL, refresh-token rotation with reuse detection, and production-grade observability (X-Ray, CloudWatch alarms, Winston, Prometheus `/metrics`).

---

## Tech focus

**Languages & Runtime** — TypeScript · Node.js · JavaScript · Java · Go

**Backend & APIs** — Express · custom Node.js frameworks · GraphQL (BFF) · Spring Boot · Hibernate · Gin · REST · gRPC

**Cloud & DevOps** — AWS (Lambda · ECS · SQS · SNS · S3 · IAM · DynamoDB · RDS · Glue · OpenSearch) · Docker · Jenkins · GitHub Actions · CircleCI · IaC (CDK / CloudFormation)

**Architecture & Design** — Microservices · Event-Driven Systems · Backend-for-Frontend · Distributed Systems · TDD · Service-registry-driven fan-out · Two-stream Kafka contracts · State-machine async fulfillment · Idempotent message handling · Retry with exponential backoff · Cache-aside · Fault isolation via queue decoupling

**Messaging & Streaming** — Kafka · AWS Kinesis · SNS · SQS (Standard · FIFO · DLQ)

**Data Stores** — MongoDB (Mongoose) · DynamoDB · PostgreSQL · MySQL · RDS · Redis · ElasticSearch · OpenSearch · Parquet (Snappy) on S3

**Compliance & Security** — GDPR · CCPA · OneTrust · Subject-rights-request orchestration · Audit trails · Secure data deletion & access controls · JWT · OAuth · IAM

**Observability & Reliability** — Structured logging · OpenTelemetry · CloudWatch monitoring + alerting

**Testing** — Jest · Sinon · Newman · Mocha-Chai · JUnit

---

## Certifications

- **AWS Certified Developer – Associate** (2024–2027) — [Credly](https://www.credly.com/badges/cdcca7ea-6962-4019-919c-650b4fa4778a/linked_in_profile)
- **Apollo GraphQL Developer – Associate** (2025) — [Apollo](https://www.apollographql.com/tutorials/certifications/0fac3218-dfff-4b48-aa1f-8db6cf47aeb6)

---

## Connect

- Portfolio — <https://debrajpaul.com>
- LinkedIn — <https://www.linkedin.com/in/debraj-paul>
- Email — <debraj@debrajpaul.com>
- CV (PDF) — [Download](https://debrajpaul.com/assets/Debraj_Paul_CV.pdf)

---

<sub>Open to senior backend / platform / staff IC roles, remote-first or with relocation support.</sub>