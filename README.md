### Hey, I'm Mac

![AI Engineering](https://img.shields.io/badge/AI%20Engineering-8A2BE2?style=flat)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

Lately I'm deep in AI-native engineering: coding agents, multi-agent systems, agent harnesses, and the verification layer that makes AI reliable enough for real engineering work, not demos.

I like staying close to the code. I've architected distributed systems on GCP, Alibaba Cloud, and AWS, run self-hosted infra, built backends in Go and Node, shipped frontends in React and React Native, and led engineering teams through recovery, compliance audits, and greenlight-to-production speedruns. I've also built AI agent infra from scratch: realtime voice, RAG, memory, tool calling, subagents.

Right now I'm building the two projects below.

### [mivia-agent](https://github.com/MiviaLabs/mivia-agent)

A terminal coding agent that actually ships code. It reads, searches, and edits your repo, runs your test suite, and drives multi-step workflows in an isolated worktree with a durable run record for every step. Local-first and provider-agnostic: your files stay on your machine, and you bring the model.

<img src="https://raw.githubusercontent.com/MiviaLabs/mivia-agent/dev/docs/mivia-agent-showcase.gif" alt="mivia-agent showcase" width="100%">

### [mivia-ai-sdk](https://github.com/MiviaLabs/mivia-ai-sdk)

A Go SDK for building reliable AI agents and multi-agent workflows out of composable, single-concern blocks. Ed25519-signed envelopes, durable task execution with fenced takeover, deterministic step graphs, and native MCP/A2A protocol support. Standard library only, no dependency surface to audit.

<sub><b>Node.js projects:</b><br>
<a href="https://github.com/MiviaLabs/mivialabs-nestjs-boilerplate">mivialabs-nestjs-boilerplate</a> — NestJS API boilerplate with event sourcing: PostgreSQL, Redis, RabbitMQ, MinIO.<br>
<a href="https://github.com/mac-lisowski/flip-shop-task">flip-shop-task</a> — Two dockerized microservices, two MongoDB instances, Redis, and NATS for inter-service messaging.<br>
<a href="https://github.com/mac-lisowski/mysmarthotel-task">mysmarthotel-task</a> — NestJS API and a background worker talking over RabbitMQ, backed by MongoDB.</sub>
