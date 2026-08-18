# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management knowledge base. This directory contains the complete framework for how we run projects, from initial concept through delivery and continuous improvement.

## Overview of OctoAcme Project Management

OctoAcme follows a structured five-phase project lifecycle designed to ensure customer value delivery and organizational alignment. Projects begin with **Initiation**, where stakeholders validate business needs and create a lightweight Project One-pager defining success metrics, timeline, and team composition. Once approved, projects move into **Planning**, where the team breaks work into shippable increments, creates a prioritized backlog with acceptance criteria, and identifies dependencies. The **Execution** phase leverages daily standups, GitHub Projects boards, and pull request workflows to maintain momentum, while **Release & Deployment** includes pre-release verification and rollback procedures. Finally, **Retrospectives** capture learnings and convert them into actionable improvements.

### Core Roles & Communication

OctoAcme defines three core delivery roles: **Product Managers** who define what should be built by establishing problem statements and measuring outcomes; **Project Managers** who coordinate delivery by creating plans and managing risks; and **Developers** who implement features while writing tests and identifying technical risks. The organization maintains a consistent communication cadence including daily standups (15 minutes focused on progress and blockers), weekly delivery syncs between PM and PdM, monthly stakeholder updates, and structured escalation paths that move from team-level triage through Product Lead to sponsor-level escalation.

### Execution & Quality Standards

During execution, teams use GitHub Projects with standardized columns and maintain small pull requests (≤400 lines when possible) linked to issues with clear acceptance criteria. Quality is ensured through unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI pipelines before release. Risk management is embedded throughout the lifecycle via a centralized Risk Register that tracks impact, likelihood, mitigation plans, and status—reviewed weekly in syncs. Blockers are escalated through a three-level system, and release gates require passing CI, security scans, documented rollback plans, and staged deployment to staging before production.

---

## Quick Links by Lifecycle Phase

### 📋 Initiation
When you have a new idea or feature proposal ready to validate:
- [Project Initiation Guide](./octoacme-project-initiation.md) — Define business need, identify stakeholders, create a lightweight plan

### 📐 Planning
Once initiated, turn the concept into an actionable plan:
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, estimate, define DoD

### 🚀 Execution & Tracking
Day-to-day activities to move the work forward:
- [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) — Daily standups, PR workflow, quality standards, and blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify risks, maintain a risk register, escalate blockers

### 📦 Release & Deployment
Getting your work to production safely:
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-release checklist, deployment process, rollback procedures

### 🔄 Retrospective & Continuous Improvement
After each release or milestone:
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, improve processes

## Core Concepts

**OctoAcme Project Management Overview** — Start here for a high-level introduction to our approach, roles, and key artifacts.
- [Project Management Overview](./octoacme-project-management-overview.md)

**OctoAcme Personas** — Understand typical roles and responsibilities:
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Key Principles
- **Customer-First**: Prioritize customer value and usability
- **Iterative Delivery**: Deliver small, testable increments
- **Clear Ownership**: Each project has a named PM and Product Lead
- **Data-Informed**: Measure impact and iterate based on evidence
- **Psychological Safety**: Encourage feedback and learning

## Getting Started

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for an introduction.
2. **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md).
3. **Need to understand a specific phase?** Use the links above to navigate by lifecycle stage.
4. **Looking for a template or checklist?** Each guide includes practical checklists and templates you can use immediately.
