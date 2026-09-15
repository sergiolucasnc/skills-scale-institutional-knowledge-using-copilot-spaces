# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, data-informed decisions, and psychological safety. This documentation serves as a central hub for understanding how we run projects across the organization.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named accountabilities
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Overview

OctoAcme follows a structured lifecycle approach to project management that prioritizes customer value, iterative delivery, and clear ownership. The framework spans five key phases: **Initiation** (validating business need and stakeholder alignment through a lightweight One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and acceptance criteria), **Execution** (managing day-to-day delivery with daily standups and weekly syncs), **Release** (standardizing deployment with pre-release checklists and rollback plans), and **Close & Retrospective** (capturing learnings for continuous improvement). This lifecycle is supported by core roles—Project Managers coordinate delivery and risk, Product Managers define outcomes and measure success, Developers implement features collaboratively, and QA/Testing validates quality—ensuring clear accountability and decision-making at each stage.

Execution and tracking are managed through a structured team rhythm and artifact-driven approach. Teams conduct daily 15-minute standups focused on progress and blockers, hold weekly delivery syncs to review progress and flagged risks, and deliver demos at sprint/milestone endpoints. Work flows through a GitHub Projects board with columns spanning Backlog → Ready → In Progress → In Review → QA → Done, supported by small pull requests (≤400 lines), automated CI testing and linting, and a requirement for at least one approval before merging. Quality is ensured through unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed.

Risk and communication are woven throughout the process to maintain transparency and enable proactive mitigation. OctoAcme maintains a Risk Register tracking ID, Description, Impact, Likelihood, Owner, and Mitigation status, with risks reviewed at weekly syncs and updated continuously. Stakeholder communication follows a tiered escalation model (Team-level → PM → Product Lead → Sponsor) and is anchored in regular updates using a standard template covering progress, next steps, risks/blockers, and decisions needed.

## Process Documents

### Getting Started

- [Project Management Overview](./octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach, roles, and key artifacts

### Project Lifecycle

1. [Project Initiation](./octoacme-project-initiation.md) - Define business need, align stakeholders, create lightweight initial plan
2. [Project Planning](./octoacme-project-planning.md) - Break work into shippable increments, identify dependencies
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution, team rhythm, quality standards
4. [Release & Deployment](./octoacme-release-and-deployment.md) - Release types, pre-release requirements, deployment checklist
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

### Cross-cutting Concerns

- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk registers, escalation paths, stakeholder communication
- [Roles & Personas](./octoacme-roles-and-personas.md) - Detailed responsibilities and communication patterns for Project Managers, Product Managers, and Developers

## Quick Reference

### Key Roles

- **Project Manager**: Coordinates delivery, schedules, risks, communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria

### Communication Cadence

- **Weekly sync**: PM + Product Manager
- **Twice-weekly standups**: Delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations**: As needed

### Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

### Execution Checklist (Sample)

- Branching and PR conventions documented in repo
- CI configured for tests and lint
- Regular demos scheduled
- Risk register updated weekly
- Deployment window scheduled (if needed)
- Post-deploy verifications completed

## How to Use This Documentation

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project**: Follow the sequence from Initiation → Planning → Execution → Release → Retrospective
- **During execution**: Reference the [Execution & Tracking](./octoacme-execution-and-tracking.md) guide for daily team workflows
- **Managing risks**: Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and tracking
- **Preparing for release**: Review [Release & Deployment](./octoacme-release-and-deployment.md) for pre-release checklists and deployment procedures
- **Using in Copilot Spaces**: Add this folder to Copilot Spaces context to get AI-assisted guidance grounded in OctoAcme processes
