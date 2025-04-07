# EcclesiaERP (Monorepo)

This repository contains the initial structure for a modular and scalable Church Management ERP system.  
It follows a microservices-based architecture and is designed to support best practices in backend development such as DDD, Clean Architecture, Hexagonal Architecture, TDD, and event-driven communication.

> ⚠️ This project is a **work in progress** and currently under development.  
> The goal is to evolve it into a robust platform for church administration and community engagement.

## 🧩 Structure Overview

The system is organized into independent services, each with its own domain and database:

```
ecclesia-erp/
├── auth-service/           # Authentication and identity
├── members-service/        # Member registration, data and lifecycle
├── finance-service/        # Donations, expenses, reports
├── agenda-service/         # Events, schedules and church calendar
├── notifications-service/  # Messaging, reminders and alerts
├── gateway-service/        # API gateway for routing and aggregation
├── frontend/               # Angular-based web client
├── docs/                   # Diagrams, decision records and API specs
├── infra/                  # Infrastructure for local development (DBs, RabbitMQ, etc)
└── docker-compose.yml      # Container orchestration for development
```



## ✅ Goals

- Modular codebase following domain boundaries
- Independent services with isolated databases
- Communication via synchronous REST and asynchronous messaging
- Observability, documentation and CI/CD ready
- Flexible enough to test different architectural styles per service

## 🚧 Current Status

- Project skeleton initialized
- Directory structure and service scaffolding created
- Docker Compose environment in preparation
- Services will be implemented incrementally

## 📌 Notes

- This project is intended for learning and architectural exploration as well as real-world application.
- Each microservice may use a different architecture style and approach, to demonstrate versatility and design decisions.

Stay tuned as development progresses.
