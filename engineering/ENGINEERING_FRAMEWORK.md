# Engineering Framework

**Status:** Approved

**Version:** 1.2

---

# Objective

The Engineering Framework defines the core engineering disciplines that comprise the Medical Device Engineering Reference repository.

Each discipline answers a unique engineering question, consumes information produced by other disciplines, and produces engineering artifacts that support subsequent engineering activities.

Together, these disciplines establish a traceable engineering framework that transforms stakeholder needs into verified engineering evidence.

---

# Relationship to the Engineering Lifecycle

The Engineering Lifecycle describes **when** engineering activities occur.

The Engineering Framework describes **what** engineering disciplines participate in those activities and how engineering information flows between them.

These documents are complementary.

- **Engineering Lifecycle** → Engineering process
- **Engineering Framework** → Engineering structure

---

# Engineering Disciplines

| Discipline | Engineering Question |
|------------|----------------------|
| Product | What problem are we solving? |
| Requirements | What shall the system do? |
| Architecture | How should the system be organized? |
| Risk | What could prevent the system from achieving its intended purpose safely and effectively? |
| Cybersecurity | How do we protect the system and its data? |
| Human Factors | How can users safely and effectively interact with the system? |
| Verification | Did we build the system correctly? |
| Quality | How do we ensure the engineering process consistently produces products that satisfy their intended requirements? |

---

# Primary Engineering Flow

The primary engineering flow represents the progression of engineering information throughout product development.

```text
Project Charter
        │
        ▼
Product
        │
        ▼
Requirements
        │
        ▼
Architecture
        │
        ▼
Implementation
        │
        ▼
Verification
        │
        ▼
Objective Evidence
```

Engineering is iterative.

Information produced by downstream activities may require refinement of upstream engineering artifacts through formal engineering change.

---

# Cross-Cutting Engineering Disciplines

Several engineering disciplines continuously influence the primary engineering flow rather than occurring at a single point within it.

```text
                 Quality
                    │
                    │
Requirements ───────────────┐
Architecture ───────────────┼────► Verification
Risk ───────────────────────┤
Cybersecurity ──────────────┤
Human Factors ──────────────┘
```

These disciplines contribute engineering requirements, architectural constraints, risk controls, usability considerations, and verification objectives throughout system development.

---

# Discipline Summary

## Product

**Engineering Question**

> What problem are we solving?

**Primary Inputs**

- Project Charter
- Stakeholder Identification
- Intended Use

**Primary Outputs**

- Product Definition
- Operational Context
- Operational Scenarios
- User Needs

---

## Requirements

**Engineering Question**

> What shall the system do?

**Primary Inputs**

- Product Definition
- Engineering Decisions

**Primary Outputs**

- User Needs
- Capability Areas
- System Requirements
- Requirements Traceability

---

## Architecture

**Engineering Question**

> How should the system be organized?

**Primary Inputs**

- System Requirements

**Primary Outputs**

- Functional Architecture
- Logical Architecture
- System Interface Architecture
- System Models

---

## Risk

**Engineering Question**

> What could prevent the system from achieving its intended purpose safely and effectively?

**Primary Inputs**

- Product Definition
- Requirements
- Architecture

**Primary Outputs**

- Hazard Analysis
- Risk Controls
- Derived Requirements

---

## Cybersecurity

**Engineering Question**

> How do we protect the system and its data?

**Primary Inputs**

- Architecture
- Risk
- Requirements

**Primary Outputs**

- Security Objectives
- Security Requirements
- Security Verification

---

## Human Factors

**Engineering Question**

> How can users safely and effectively interact with the system?

**Primary Inputs**

- Product Definition
- Requirements
- Operational Context

**Primary Outputs**

- Task Analysis
- Use Scenarios
- Usability Requirements

---

## Verification

**Engineering Question**

> Did we build the system correctly?

**Primary Inputs**

- Requirements
- Architecture
- Risk Controls
- Security Requirements
- Human Factors Requirements

**Primary Outputs**

- Verification Evidence
- Verification Reports
- Objective Evidence

---

## Quality

**Engineering Question**

> How do we ensure the engineering process consistently produces products that satisfy their intended requirements?

**Primary Inputs**

- Engineering Artifacts
- Engineering Decisions
- Verification Evidence
- Engineering Reviews

**Primary Outputs**

- Engineering Reviews
- Quality Assessments
- Process Improvements
- Engineering Confidence

Quality is a cross-cutting engineering discipline that evaluates both engineering process and engineering outputs throughout the product lifecycle.

---

# Engineering Principles

Every engineering discipline exists to answer a unique engineering question.

Engineering disciplines exchange information through traceable engineering artifacts.

Engineering decisions should precede implementation whenever practical.

Verification produces objective evidence demonstrating that approved engineering requirements have been satisfied.

Quality provides confidence that engineering activities are consistently performed and that the resulting engineering outputs support safe, effective, and maintainable products.

The Engineering Framework is iterative. Information generated by downstream disciplines may require refinement of upstream engineering artifacts through formal engineering change.

---

# Related Documents

- README.md
- ENGINEERING_LIFECYCLE.md
- PROJECT_CHARTER.md
