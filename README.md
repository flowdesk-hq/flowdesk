<div align="center">

# FlowDesk

**AI-Powered Front Desk & Revenue Operations**

FlowDesk is a multi-tenant SaaS platform for service businesses that brings communications, scheduling, customer management, automation, and revenue operations into one operational workspace.

[Overview](docs/overview.md) • [Features](docs/features.md) • [Architecture](docs/architecture.md) • [Roadmap](ROADMAP.md)

</div>

## Product Overview

FlowDesk is designed for service-oriented businesses that need to coordinate customer communications, appointment operations, and revenue workflows without relying on disconnected tools.

The platform vision is to give teams one place to manage day-to-day front desk operations while improving consistency, responsiveness, and business visibility.

## The Problem

Service businesses often operate across fragmented channels and systems:

- Customer conversations are split across SMS, email, and call records.
- Scheduling is managed in separate tools with inconsistent availability rules.
- Customer context is scattered across notes, inboxes, and spreadsheets.
- Administrative follow-up is manual, time-consuming, and easy to miss.
- Revenue opportunities can be lost when operational data is incomplete.

## The Solution

FlowDesk is being developed as a unified operations layer that centralizes front desk and revenue workflows. Instead of juggling multiple disconnected systems, teams can coordinate communication, booking, customer records, and follow-up automation from one account-scoped workspace.

## Core Capabilities

### Unified Inbox
A centralized conversation layer for SMS, email, templates, attachments, and call records, with account-aware context for each customer interaction.

### Smart Booking
Scheduling workflows for appointments, staff assignment, availability rules, service areas, reminders, and calendar-connected operations.

### Customer CRM
Structured customer profiles that connect contact data, addresses, notes, tags, and historical interactions.

### Workflow Automation
Operational automations for follow-ups, reminders, and AI-assisted communication workflows intended to reduce manual repetitive work.

### Revenue Intelligence
Business analytics and opportunity tracking intended to highlight demand trends, conversion patterns, and revenue-impacting operational gaps.

### Command Center
A unified dashboard experience intended to provide a clear operational snapshot across communications, bookings, and pipeline health.

> FlowDesk is actively under development. This repository documents the product direction and architecture scope; it does not imply all capabilities are fully implemented or production-ready.

## Product Preview

Authentic screenshots and product demonstrations will be added as development progresses. See [assets/README.md](assets/README.md) for planned visual assets and formatting guidance.

## Technology Stack

| Layer | Technology | Role |
| --- | --- | --- |
| Frontend | Next.js App Router, React, TypeScript | Web application UI and account-scoped operational workflows |
| Authentication | Clerk | Identity, session management, and tenant-aware access control |
| Database | Neon PostgreSQL | Multi-tenant relational data storage for platform entities |
| Communications | Twilio | Messaging and communication channel integrations |
| Object Storage | Cloudflare R2 | File and attachment storage for operational artifacts |

## Architecture

FlowDesk follows a multi-tenant SaaS architecture with account-scoped authorization boundaries across the application layer, data model, and integrated services.

See [docs/architecture.md](docs/architecture.md) for a high-level architecture view and conceptual system diagram.

## Development Status

FlowDesk is under active development. Public progress and planning are tracked in:

- [ROADMAP.md](ROADMAP.md)
- [CHANGELOG.md](CHANGELOG.md)

## Repository Information

This repository is the public product showcase and technical documentation hub for FlowDesk.

Production application source code, infrastructure configuration, and operational systems are maintained in a separate private repository.

---

FlowDesk — AI-powered operations for modern service businesses.
