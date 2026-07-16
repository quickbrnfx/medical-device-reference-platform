# Project Documentation

This directory contains the project management and engineering planning artifacts for the Medical Device Reference Platform.

These documents define the project's direction, record engineering decisions, track progress, and establish the engineering process used throughout development.

Unlike implementation artifacts, the documents in this directory describe *how* the project is planned and managed.

---

# Purpose

The purpose of this directory is to provide a single location for project-level documentation.

These artifacts establish:

- Project objectives
- Engineering milestones
- Current project status
- Architectural decisions
- Planning information
- Future work

Together, they form the management layer that supports the engineering case study.

---

# Directory Contents

| Document | Purpose |
|----------|---------|
| PROJECT_CHARTER.md | Defines the project's vision, mission, guiding principles, roadmap, and Definition of Done. |
| ROADMAP.md | High-level milestone plan for the project. |
| CURRENT_STATE.md | Snapshot of the current project status and immediate priorities. |
| BACKLOG.md | Prioritized engineering and repository work that has not yet been started. |
| DECISION_LOG.md | Chronological index of significant engineering decisions and associated ADRs. |
| REPOSITORY_INFRASTRUCTURE.md | Defines the repository infrastructure work required to support future engineering activities. |

Additional project documents may be added as the repository evolves.

---

# Relationship to Other Documentation

Project documentation answers questions such as:

- Why does this project exist?
- What are we working on now?
- What work remains?
- What engineering decisions have been made?

Other directories answer different questions:

| Directory | Purpose |
|-----------|---------|
| `docs/adr/` | Long-term architectural decisions. |
| `docs/requirements/` | System and stakeholder requirements. |
| `docs/architecture/` | System architecture and design. |
| `docs/verification/` | Verification strategy and evidence. |
| `docs/product/` | Product definition and engineering evaluations. |

---

# Guiding Principles

Project documentation should:

- Be concise.
- Be traceable.
- Reflect the current state of the project.
- Capture engineering rationale rather than implementation details.
- Remain consistent with the Project Charter.

---

# Navigation

For readers new to the project, the recommended reading order is:

1. PROJECT_CHARTER.md
2. REFERENCE_PRODUCT_SELECTION.md
3. ADR-001 — Reference Product Selection
4. CURRENT_STATE.md
5. ROADMAP.md

This sequence provides the context needed to understand the project's objectives before reviewing implementation artifacts.
