# Level 2: Intermediate Architecture

[![Main Hub](https://img.shields.io/badge/Central%20Hub-backend--engineering--hub-1F2937?style=flat-square&logo=github)](https://github.com/EmaanHumayun/backend-engineering-hub)
[![Maintainer](https://img.shields.io/badge/Maintainer-Emaan%20Humayun-blue?style=flat-square)](https://github.com/EmaanHumayun)

Five practical backend engineering projects covering authorization, business logic, transactions, relationships, background processing and API integrations.

Part of the **[Backend Engineering Ecosystem](https://github.com/EmaanHumayun/backend-engineering-hub)** maintained by Emaan Humayun (**Software Engineer | DevOps Engineer**).

---

## Ecosystem Navigation

- [Central Architecture Hub](https://github.com/EmaanHumayun/backend-engineering-hub)
- [Level 1: Beginner Projects](https://github.com/EmaanHumayun/backend-beginner-projects)
- [Level 2: Intermediate Projects](https://github.com/EmaanHumayun/backend-intermediate-projects)
- [Level 3: Advanced Projects](https://github.com/EmaanHumayun/backend-advanced-projects)
- [Level 4: Professional Projects](https://github.com/EmaanHumayun/backend-professional-projects)

---

## Projects in this Repository

| Project ID | Project Name | Primary Stack | Core Concepts | Status |
| :---: | :--- | :--- | :--- | :--- |
| **06** | [**Role-Based Access Control System**](./projects/06-role-based-access-control-system/) | Node.js, Express, PostgreSQL | RBAC, granular permissions, access policies, resource ownership verification | `Ready for Practice` |
| **07** | [**E-commerce Backend API**](./projects/07-ecommerce-backend-api/) | Node.js, Express, PostgreSQL | Complex logic, cart state, inventory locking, ACID database transactions, payment sandbox | `Ready for Practice` |
| **08** | [**Blog and Content Management API**](./projects/08-blog-content-management-api/) | Node.js, Express, PostgreSQL | One-to-many, many-to-many relationships, comments, tags, search, soft deletion | `Ready for Practice` |
| **09** | [**Notification Service**](./projects/09-notification-service/) | Node.js, Express, Redis, BullMQ | Background worker jobs, job queues, email delivery, retry mechanisms, failure handling | `Ready for Practice` |
| **10** | [**API Integration and Webhook Platform**](./projects/10-api-integration-webhook-platform/) | Node.js, Express, Axios | Third-party API consumption, webhook receivers, signature verification, rate limiting, retries | `Ready for Practice` |

---

## Standard Project Layout

Every project under `projects/` is organized with clean separation of concerns:

```text
[project-name]/
├── README.md                   # Project overview, installation & API guide
├── PROJECT-SPECIFICATION.md     # 20-point comprehensive engineering specification
├── REQUIREMENTS.md             # Functional and non-functional requirements
├── CHANGELOG.md                # Project version history
├── .env.example                # Configuration parameters template
├── docs/                       # Architecture, API routes & database schemas
├── src/                        # Controllers, services, models, routes, middleware
├── tests/                      # Unit and integration test suites
├── database/                   # Migrations and seed data
└── deployment/                 # Dockerfile and docker-compose.yml
```
