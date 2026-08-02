<div align="center">

# Hi, I'm Edogawa Tr 👋

### Product Person 

I design products as systems with **modern and powerful tech stack** (I call **Gen-Z Stack**) — from the user experience and API contracts<br />
to asynchronous workflows, infrastructure, delivery, and observability.

## 🚀 Current Development Stack
### Programming Language
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
### Backend & API
[![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)](https://expressjs.com/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Apollo GraphQL](https://img.shields.io/badge/Apollo-311C87?logo=apollographql&logoColor=white)](https://www.apollographql.com/)
[![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)](https://graphql.org/)
### Database & Cache
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)](https://redis.io/)
### Background Jobs
[![BullMQ](https://img.shields.io/badge/BullMQ-EA4C89?logo=redis&logoColor=white)](https://bullmq.io/)
### Infrastructure & Observability
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)](https://grafana.com/)
[![Loki](https://img.shields.io/badge/Loki-F46800?logo=grafana&logoColor=white)](https://grafana.com/oss/loki/)

## 💻 Supported Operating Systems
[![Ubuntu-Linux](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Arch-Linux](https://img.shields.io/badge/Arch_Linux-1793D1?logo=archlinux&logoColor=white)](https://archlinux.org/)
[![Debian-Linux](https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=white)](https://www.debian.org/)

</div>

---

## About me

I'm a product-minded architect who enjoys turning ambitious ideas into reliable, operable platforms. My work sits at the intersection of **product thinking, application architecture, and infrastructure engineering**.

I care about the full path from concept to production:

- shaping a product into clear services and boundaries;
- building type-safe experiences and APIs;
- choosing the right data store for each workload;
- moving expensive work into resilient asynchronous pipelines;
- automating delivery with containers and Kubernetes; and
- making systems understandable through logs, dashboards, and alerts.

```text
Product intent → System design → Working software → Reliable operations
```

## What I build

| Focus | How I approach it |
|---|---|
| **Product architecture** | Translate product requirements into clear domains, services, data flows, and technical trade-offs |
| **Full-stack platforms** | Build SSR experiences and typed APIs with Next.js, TypeScript, Express, and GraphQL |
| **Cloud-native systems** | Package services with Docker and operate them on lightweight Kubernetes with k3s |
| **Event-driven workflows** | Keep interactive paths responsive by moving heavy work into Redis-backed BullMQ workers |
| **Data platforms** | Combine document, relational, cache, queue, and media storage around workload needs |
| **Developer experience** | Create repeatable local environments and automated build, test, and deployment pipelines |
| **Observability** | Treat structured logging, aggregation, dashboards, and alerts as part of the architecture |
| **AI integration** | Connect AI clients to internal capabilities through deliberate, controlled MCP tools |

## Flagship project · The Blue Whale

> A production-grade, Kubernetes-orchestrated, GraphQL-powered, event-driven web platform.

**The Blue Whale** represents how I think about modern product infrastructure: the frontend, backend, background processing, data layer, delivery pipeline, AI integration, and operations should work as one coherent system.

### System at a glance

```mermaid
flowchart LR
    PRODUCT["Product experience<br/>Next.js · SSR · TypeScript"]
    API["Application platform<br/>Express · Apollo · GraphQL"]
    ASYNC["Async workloads<br/>BullMQ · Redis"]
    DATA["Purpose-fit data<br/>MongoDB · PostgreSQL · Cloudinary"]
    PLATFORM["Runtime platform<br/>Docker · k3s · Traefik"]
    DELIVERY["Continuous delivery<br/>GitHub Actions"]
    OPS["Observability<br/>Winston · Loki · Grafana"]
    AI["AI workflows<br/>Claude Desktop · MCP"]

    PRODUCT --> API
    API --> ASYNC
    API --> DATA
    ASYNC --> DATA
    DELIVERY --> PLATFORM
    PLATFORM --> PRODUCT
    PLATFORM --> API
    API -. telemetry .-> OPS
    ASYNC -. telemetry .-> OPS
    AI --> API

    classDef product fill:#eff6ff,stroke:#2563eb,color:#172554
    classDef app fill:#f5f3ff,stroke:#7c3aed,color:#2e1065
    classDef infra fill:#ecfdf5,stroke:#059669,color:#064e3b
    classDef operate fill:#fff7ed,stroke:#ea580c,color:#7c2d12
    class PRODUCT product
    class API,ASYNC,AI app
    class DATA,PLATFORM,DELIVERY infra
    class OPS operate
```

### Delivery philosophy

```mermaid
flowchart LR
    IDEA["Product idea"] --> DESIGN["Architecture"]
    DESIGN --> BUILD["Typed implementation"]
    BUILD --> TEST["Automated verification"]
    TEST --> SHIP["Rolling deployment"]
    SHIP --> OBSERVE["Logs · dashboards · alerts"]
    OBSERVE --> LEARN["Product learning"]
    LEARN --> IDEA
```

## Currently exploring

- Event-driven and queue-based architectures for real-world workloads
- Practical AI-assisted workflows through MCP
- Lightweight, self-managed infrastructure tools: Kubernetes / Harbor / Prometheus / Thanos

---

<div align="center">

### Let's build products that are useful, scalable, and operable.

<sub>Product thinking in the front. Platform discipline underneath.</sub>

</div>
