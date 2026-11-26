# Shaker Emad Shaker

**Backend .NET Developer — Cairo, Egypt**

Computer Science graduate (EELU, 2024), trained on .NET at DEPI and on AI at NTI. Currently freelancing: backend work for PaySky and full-stack e-commerce delivery. English B2.

[![Email](https://img.shields.io/badge/Email-anakerolos%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:anakerolos@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shaker--emad1-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaker-emad1)
[![Portfolio](https://img.shields.io/badge/Portfolio-website-0d9488?logo=googlechrome&logoColor=white)](https://shaker-emad1.github.io)

## Tech stack

![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%2010-512BD4?logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![Angular](https://img.shields.io/badge/Angular%2020-DD0031?logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?logo=dotnet&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

## Flagship projects

Enterprise-style systems with full backends (ASP.NET Core 10, EF Core, PostgreSQL), Angular 20 clients with a dark/light design system and dashboards, Docker, CI, tests, and an honest Built vs Roadmap split in every README.

| Project | What it is |
| --- | --- |
| [pharmadesk](https://github.com/Shaker-Emad1/pharmadesk) | Multi-tenant pharmacy management SaaS — batch/FEFO inventory, POS invoicing, low-stock & expiry reports |
| [shoppos-cloud](https://github.com/Shaker-Emad1/shoppos-cloud) | Multi-tenant cloud point of sale — barcode POS, discounts, refunds, Z-report, sales analytics |
| [medicare-hms](https://github.com/Shaker-Emad1/medicare-hms) | Multi-tenant hospital & clinic management — patients, appointments, visits & prescriptions, billing |
| [itdesk](https://github.com/Shaker-Emad1/itdesk) | Multi-tenant IT helpdesk — SLA-tracked tickets, assignment, comments, knowledge base |
| [peoplesuite](https://github.com/Shaker-Emad1/peoplesuite) | Multi-tenant HR & payroll — employees, leave approvals, attendance, payroll runs |
| [flowboard](https://github.com/Shaker-Emad1/flowboard) | Real-time team Kanban — SignalR live sync, drag-and-drop, board membership with owner/editor/viewer roles and invite links |
| [payflow-api](https://github.com/Shaker-Emad1/payflow-api) | Payment processing API — idempotent payments, HMAC-signed webhooks, Hangfire jobs |
| [ledger-service](https://github.com/Shaker-Emad1/ledger-service) | Double-entry bookkeeping API — balanced journals, transfers, financial-statement math |
| [order-events](https://github.com/Shaker-Emad1/order-events) | Event-driven order processing — transactional outbox, RabbitMQ, idempotent consumer |
| [ai-ticket-triage](https://github.com/Shaker-Emad1/ai-ticket-triage) | AI support-ticket triage — LLM classification, priority, summaries, draft replies |
| [suiteerp](https://github.com/Shaker-Emad1/suiteerp) | Multi-tenant ERP — warehouses, append-only stock ledger, purchasing, sales orders, invoicing |
| [edusuite](https://github.com/Shaker-Emad1/edusuite) | Multi-tenant school management — students, classes, gradebook, attendance, fees |
| [estatepms](https://github.com/Shaker-Emad1/estatepms) | Multi-tenant property management — units, leases, rent invoicing with late tracking, maintenance |

## More projects

| Project | What it is |
| --- | --- |
| [fleetcore](https://github.com/Shaker-Emad1/fleetcore) | Multi-tenant fleet management API — vehicles, maintenance schedules, driver assignment, fuel logs |
| [hotelpms](https://github.com/Shaker-Emad1/hotelpms) | Multi-tenant hotel PMS API — rooms, housekeeping pipeline, night-based reservations, folio with checkout gating |

## Working UI demos

Live Angular 20 front-ends for the flagship systems, hosted on GitHub Pages. PharmaDesk and FlowBoard are wired to their hosted APIs (below) and work end-to-end; the rest are front-end previews whose backends run locally with `docker compose up` in each repo.

[PharmaDesk](https://shaker-emad1.github.io/pharmadesk/) · [ShopPOS Cloud](https://shaker-emad1.github.io/shoppos-cloud/) · [Medicare HMS](https://shaker-emad1.github.io/medicare-hms/) · [ITDesk](https://shaker-emad1.github.io/itdesk/) · [PeopleSuite](https://shaker-emad1.github.io/peoplesuite/) · [SuiteERP](https://shaker-emad1.github.io/suiteerp/) · [EduSuite](https://shaker-emad1.github.io/edusuite/) · [EstatePMS](https://shaker-emad1.github.io/estatepms/) · [FlowBoard](https://shaker-emad1.github.io/flowboard/)

## Live backend APIs

Four backends are deployed and reachable, backed by managed PostgreSQL (Neon). Free-tier hosting: containers sleep after ~15 min idle, so the first request after a quiet period waits about a minute while the container wakes.

| API | Base URL | Health |
| --- | --- | --- |
| PharmaDesk | https://pharmadesk-533a5.containers.snapdeploy.app | [/health/ready](https://pharmadesk-533a5.containers.snapdeploy.app/health/ready) |
| FlowBoard | https://flowboard-533a5.containers.snapdeploy.app | [/health/ready](https://flowboard-533a5.containers.snapdeploy.app/health/ready) |
| PayFlow | https://payflow-api-533a5.containers.snapdeploy.app | [/health/ready](https://payflow-api-533a5.containers.snapdeploy.app/health/ready) |
| AI Ticket Triage | https://ai-ticket-triage-533a5.containers.snapdeploy.app | [/health/ready](https://ai-ticket-triage-533a5.containers.snapdeploy.app/health/ready) |

The [PharmaDesk](https://shaker-emad1.github.io/pharmadesk/) and [FlowBoard](https://shaker-emad1.github.io/flowboard/) UI demos are wired to these hosted APIs, so they work end-to-end in the browser. The other UI demos are front-end previews; their backends run locally with `docker compose up`.

## Earlier projects

| Project | What it is |
| --- | --- |
| [RecruitPro](https://github.com/Shaker-Emad1/RecruitPro) | Recruitment management system — ASP.NET Core, Angular 20, Clean Architecture, JWT, Docker |
| [market-pro](https://github.com/Shaker-Emad1/market-pro) | POS & inventory management — ASP.NET Core, Angular 20, EF Core, SQL Server, Docker |
| [CircuitBay](https://github.com/Shaker-Emad1/CircuitBay) | E-commerce backend API — Clean Architecture, EF Core, SQL Server, Redis, Hangfire |
| [ecommerce-Store](https://github.com/Shaker-Emad1/ecommerce-Store) | Full-stack e-commerce platform — ASP.NET Core, React, TypeScript, SQL Server, Docker |

## Live demo sites

Static front-end demos of the flagship systems, served from the [showcase-sites](https://github.com/Shaker-Emad1/showcase-sites) repo via GitHub Pages:

[NilePay](https://shaker-emad1.github.io/showcase-sites/nilepay/) · [Medicare](https://shaker-emad1.github.io/showcase-sites/medicare/) · [PharmaCare](https://shaker-emad1.github.io/showcase-sites/pharmacare/) · [AqarGate](https://shaker-emad1.github.io/showcase-sites/aqargate/) · [EduHub](https://shaker-emad1.github.io/showcase-sites/eduhub/) · [SuiteERP](https://shaker-emad1.github.io/showcase-sites/suiteerp/) · [GovServ](https://shaker-emad1.github.io/showcase-sites/govserv/) · [CairoFreight](https://shaker-emad1.github.io/showcase-sites/cairofreight/) · [PixelForge](https://shaker-emad1.github.io/showcase-sites/pixelforge/)

## What the backend work shows

- **Architecture:** multi-tenant SaaS with EF Core global query filters and JWT tenant claims; event-driven services with the transactional outbox; double-entry accounting invariants
- **Security:** role-based authorization across the APIs (admin-managed accounts, JWT, BCrypt) and per-board membership with owner/editor/viewer roles in FlowBoard
- **Containers:** every backend published as a public Docker image at [hub.docker.com/u/shaker200](https://hub.docker.com/u/shaker200), built by GitHub Actions on every push
- **Data integrity:** transactional writes, idempotency keys, unique constraints, FEFO stock deduction, double-booking and overlap detection
- **Delivery:** Docker one-liner in every repo, GitHub Actions CI, EF Core migrations, Swagger, MIT license, conventional commits
- **Honesty:** every README separates what is built and working from what is on the roadmap

_Last updated: November 26, 2026_
