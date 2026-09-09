### 👋 Hey, I'm Mac

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![AI Engineering](https://img.shields.io/badge/AI%20Engineering-8A2BE2?style=flat)

I'm a Node.js & TypeScript engineer focused on backends and distributed systems that hold up in production. I've architected platforms on GCP, Alibaba Cloud, and AWS, run self-hosted infra, shipped frontends in React and React Native, and led engineering teams through recovery, compliance audits, and greenlight-to-production speedruns.

Day to day that means the Node.js ecosystem: NestJS services with CQRS and event sourcing, PostgreSQL and MongoDB, Redis for caching and rate limiting, RabbitMQ / Kafka / NATS for messaging, and test suites that actually run in CI. I care about tenant isolation, typed error handling, and event-driven flows you can replay when things go wrong.

Lately I've also been deep in AI-native engineering: coding agents, multi-agent systems, agent harnesses, and the verification layer that makes AI reliable enough for real engineering work, not demos. Still close to the code either way.

---

## 🟢 Node.js projects

### [node-monorepo-boilerplate](https://github.com/MiviaLabs/node-monorepo-boilerplate)

Production-oriented Nx + pnpm monorepo starter. NestJS API with CQRS, multi-tenant guards, and a transactional outbox that publishes to Kafka (dead-letter queue + replay included), Next.js web and admin apps, an Expo mobile app, and 22 shared packages: auth, encryption, queues, storage, OPA policies, observability. Full local stack on Docker Compose (PostgreSQL, Redis, Kafka, MinIO, MailHog) and a real test pyramid: Jest units, Testcontainers e2e, Playwright.

### [flip-shop-task](https://github.com/mac-lisowski/flip-shop-task)

Two dockerized microservices, two MongoDB instances, Redis, and NATS for inter-service messaging.

### [mysmarthotel-task](https://github.com/mac-lisowski/mysmarthotel-task)

NestJS API and a background worker talking over RabbitMQ, backed by MongoDB.

## 🤖 AI engineering projects

### [mivia-agent](https://github.com/MiviaLabs/mivia-agent)

A terminal coding agent that actually ships code. It reads, searches, and edits your repo, runs your test suite, and drives multi-step workflows in an isolated worktree with a durable run record for every step. Local-first and provider-agnostic: your files stay on your machine, and you bring the model.

<img src="https://raw.githubusercontent.com/MiviaLabs/mivia-agent/dev/docs/mivia-agent-showcase.gif" alt="mivia-agent showcase" width="100%">

### [mivia-ai-sdk](https://github.com/MiviaLabs/mivia-ai-sdk)

A Go SDK for building reliable AI agents and multi-agent workflows out of composable, single-concern blocks. Ed25519-signed envelopes, durable task execution with fenced takeover, deterministic step graphs, and native MCP/A2A protocol support. Standard library only, no dependency surface to audit.
