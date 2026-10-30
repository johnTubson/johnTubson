# Hi, I'm John Olatubosun

Software engineer building marketplace, compliance, and payments systems in TypeScript. I work across NestJS
microservices, PostgreSQL/MySQL, Redis, RabbitMQ, and React/Next.js, and I like owning a domain end to end: from a
0-to-1 build through to the profiling and hardening that keep it fast.

Based in Nigeria · open to remote roles worldwide · [johntubson.com](https://johntubson.com)

## What I'm working on

- **Marketplace and compliance platforms (Neoclan Technologies):** 22 NestJS microservices across two products. I built
  a B2B compliance SaaS backend from scratch (gRPC, multi-schema Postgres, SFTP catalogue ingestion, Amazon SP-API,
  LLM-backed document extraction with human review) and an event-driven merchant trust-scoring engine that feeds search
  ranking.
- **E-learning platform (Jacko):** payments with installment plans and idempotent webhooks, a gamification engine, DRM
  video, and query work that brought each mobile screen down to a single SQL statement (23ms median on 500k-row data).

Most of that code is private, so the public repos below are where you can read how I build.

## Public projects

| Project | What it shows | Stack |
| --- | --- | --- |
| [harbor](https://github.com/johnTubson/harbor) | Multi-tenant marketplace: rotating refresh tokens with reuse detection, BFF httpOnly cookies, presigned KYC uploads, Stripe Connect | NestJS 11, Next.js 16, Prisma 7, BullMQ, MinIO |
| [forge](https://github.com/johnTubson/forge) | Event-driven commerce APIs: Redis stock reservations, RabbitMQ saga with compensation, idempotency keys, 39 tests | NestJS, gRPC, RabbitMQ, Redis |
| [vault](https://github.com/johnTubson/vault) | Double-entry wallet ledger: Idempotency-Key on money-moving routes, HMAC webhooks, reconciliation | NestJS, Prisma, Testcontainers |
| [kora-market](https://github.com/johnTubson/kora-market) | Headless storefront with CI-enforced Lighthouse (performance 92-93, accessibility 98-100) | Next.js, Zustand, Vitest, Playwright |
| [stackdesk](https://github.com/johnTubson/stackdesk) | Merchant onboarding and payout reconciliation admin with audit trail | TanStack Start, Drizzle, Zod |
| [pulse](https://github.com/johnTubson/pulse) | 10k-row virtualized fintech operations tables | React, TanStack |

## Toolbox

**Backend:** Node.js, NestJS, Express, gRPC, REST, GraphQL · **Data:** PostgreSQL, MySQL, Prisma, Redis, RabbitMQ,
BullMQ, OpenSearch · **Frontend:** React, Next.js, TanStack, Tailwind · **Payments:** Paystack, Stripe ·
**Platform:** Docker, GitHub Actions, AWS, GCP, Azure · **AI:** Gemini, DeepSeek, provider fallback

## Contact

[johntubson@gmail.com](mailto:johntubson@gmail.com) · [LinkedIn](https://www.linkedin.com/in/john-olatubosun-89411227a) ·
[johntubson.com](https://johntubson.com)
