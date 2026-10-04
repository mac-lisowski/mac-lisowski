### 👋 Hey, I'm Mac

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

I'm a Node.js & TypeScript engineer focused on backends and distributed systems that hold up in production. I've architected platforms on GCP, Alibaba Cloud, and AWS, run self-hosted infra, and led engineering teams through recovery and compliance audits. I've also shipped frontends in React and React Native, and taken products from greenlight to production fast.

Day to day that's the Node.js ecosystem: NestJS services with CQRS and event sourcing, PostgreSQL and MongoDB, Redis for caching and rate limiting, RabbitMQ / Kafka / NATS for messaging, and test suites that run in CI. I care about tenant isolation, typed error handling, and event-driven flows you can replay when things go wrong.

---

## 🟢 Node.js projects

### [node-monorepo-boilerplate](https://github.com/MiviaLabs/node-monorepo-boilerplate)

Production-oriented Nx + pnpm monorepo starter. The NestJS API ships with CQRS, multi-tenant guards, and a transactional outbox that publishes to Kafka — dead-letter queue and replay included. Around it: Next.js web and admin apps, an Expo mobile app, and 22 shared packages covering auth, encryption, queues, storage, OPA policies, and observability. Full local stack on Docker Compose (PostgreSQL, Redis, Kafka, MinIO, MailHog), and a real test pyramid: Jest units, Testcontainers e2e, Playwright.
