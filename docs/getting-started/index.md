# Getting Started

Welcome to the OpenCDMP documentation. Use the table below to find the right starting point for your role.

| I am… | Start here |
|---|---|
| **A researcher or end user** — I want to create and manage plans | [User Guide](/user-guide/) |
| **A tenant administrator** — I want to configure blueprints, templates, and users | [Admin Guide](/admin-guide/) |
| **A system administrator** — I want to deploy or upgrade OpenCDMP | [Deployment](/getting-started/deployment/) |
| **Setting up authentication** — I need to configure Keycloak | [Keycloak Setup](/getting-started/configuration/keycloak) |
| **Configuring services** — I need to set environment variables | [Configuration](/getting-started/configuration/) |
| **A developer** — I want to integrate with the API or build plugins | [Developers](/developers/) |

---

## What is in this section

This **Getting Started** section is aimed at **system administrators** who are deploying and configuring OpenCDMP. It covers:

- **[Introduction](introduction.md)** — Platform overview, core concepts, and key features
- **[Architecture](architecture.md)** — Microservices architecture and component breakdown
- **[Deployment](deployment/)** — How to deploy OpenCDMP using Docker and how to upgrade
- **[Configuration](configuration/)** — Environment variable reference for all services (backend, frontend, Keycloak, PostgreSQL, RabbitMQ, Elasticsearch)
- **[Common Workflows](getting-started-workflows.md)** — Real-world use cases and workflow examples

:::tip First time deploying?
Start with the [Deployment Guide](deployment/) to get OpenCDMP running, then follow [Keycloak Setup](configuration/keycloak.md) to configure authentication. After that, the [Admin Guide](/admin-guide/) will walk you through setting up blueprints and templates so your users can start creating plans.
:::
