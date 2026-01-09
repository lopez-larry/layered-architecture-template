# Layered Architecture Template

This repository provides a minimal example of a layered architecture.

The goal is to show how to separate concerns into clear layers while keeping the project small enough to understand in one sitting. It is intended as a starting point for learning, experimentation, and architectural documentation, not as a production-ready framework.

## Purpose

Layered architecture organizes code into vertical slices with clear responsibilities:

- Presentation: user interfaces, API endpoints, adapters
- Application: use cases, orchestration, application services
- Domain: core business rules and models
- Infrastructure: technical details such as databases, messaging, external services

## Folder Structure

src/
  presentation/   - UI, controllers, HTTP handlers, API adapters
  application/    - use cases, application services, workflows
  domain/         - domain models, domain services, business rules
  infrastructure/ - persistence, messaging, external integrations

tests/            - unit and integration tests

docs/
  architecture.md - high-level views and diagrams
  decisions.md    - architecture decision records (ADRs)
