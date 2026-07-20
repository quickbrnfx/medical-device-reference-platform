# Engineering Framework

**Status:** Draft

---

# Objective

The Engineering Framework defines the core engineering disciplines that comprise the Medical Device Engineering Reference repository.

Each discipline answers a unique engineering question, consumes information produced by other disciplines, and produces engineering artifacts that support subsequent engineering activities.

Together, these disciplines form a traceable engineering framework that transforms stakeholder needs into verified engineering evidence.

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
| Quality | How do we evaluate and improve the engineering process and resulting product? |

---

# Information Flow

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
       ╱│╲
      ╱ │ ╲
     ▼  ▼  ▼
 Risk HF Cybersecurity
     ╲  │  ╱
      ╲ │ ╱
       ▼
Verification
       │
       ▼
Objective Evidence
       │
       ▼
Quality
```

Engineering is iterative.

Information produced by downstream disciplines may require refinement of upstream engineering artifacts through formal engineering change.

---

# Discipline Summary

## Product

**Engineering Question**

> What problem are we solving?

**Primary Inputs**

- Project Charter
- Stakeholders
- Intended Use

**Primary Outputs**

- Operational Context
- User Needs
- Product Definition

---

## Requirements

**Engineering Question**

> What shall the system do?

**Primary Inputs**

- User Needs
- Operational Context
- Engineering Decisions

**Primary Outputs**

- System Requirements
- Traceability

---

## Architecture

**Engineering Question**

> How should the system be organized?

**Primary Inputs**

- System Requirements

**Primary Outputs**

- Functional Decomposition
- System Architecture
- Interfaces
- State Models

---

## Risk

**Engineering Question**

> What could prevent the system from achieving its intended purpose safely and effectively?

**Primary Inputs**

- Requirements
- Architecture
- Operational Context

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

**Primary Outputs**

- Verification Evidence
- Verification Reports
- Objective Evidence

---

## Quality

**Engineering Question**

> How do we evaluate and improve the engineering process and resulting product?

**Primary Inputs**

- All Engineering Disciplines

**Primary Outputs**

- Quality Assessments
- Process Improvement
- Engineering Confidence

---

# Engineering Principles

Each engineering discipline exists to answer a unique engineering question.

Disciplines exchange engineering information through traceable artifacts rather than informal knowledge.

No discipline operates independently; engineering decisions made within one discipline frequently influence others.

The framework is iterative and supports continual refinement through objective engineering evidence.

---

# Related Documents

- README.md
- ENGINEERING_LIFECYCLE.md
- PROJECT_CHARTER.md
