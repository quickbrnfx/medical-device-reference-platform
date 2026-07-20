# Engineering Lifecycle

**Status:** Approved

---

# Objective

Describe how engineering information evolves throughout the development of a medical device.

Rather than presenting engineering artifacts as isolated documents, this lifecycle illustrates how each engineering activity produces information that enables subsequent engineering decisions.

The Engineering Lifecycle serves as the conceptual roadmap for the Medical Device Engineering Reference repository.

---

# Definition

Engineering is an iterative process of reducing uncertainty.

Each engineering activity answers a specific question about the system while producing objective information that enables subsequent engineering decisions.

The purpose of the Engineering Lifecycle is to demonstrate how disciplined engineering transforms an initial product concept into a verified system through traceable decisions and objective evidence.

---

# Engineering Philosophy

Engineering documentation should explain:

- Why work is performed
- What engineering question is being answered
- What information is produced
- How that information supports future engineering activities

Artifacts should not exist because a standard requires them.

They should exist because they reduce uncertainty and improve engineering decisions.

---

# Engineering Lifecycle

```text
Project Vision
        │
        ▼
Product Definition
        │
        ▼
Decision Analysis
        │
        ▼
Requirements Engineering
        │
        ▼
System Architecture
        │
        ▼
Risk Engineering
        │
        ▼
Product Cybersecurity
        │
        ▼
Human Factors Engineering
        │
        ▼
Verification Engineering
        │
        ▼
Implementation
        │
        ▼
Objective Evidence
```

---

# Lifecycle Activities

## 1. Product Definition

### Engineering Question

> What problem are we solving, for whom, and under what conditions?

### Purpose

Product Definition establishes a shared understanding of the intended product before engineering solutions are proposed.

### Primary Activities

- Stakeholder Analysis
- Stakeholder Personas
- Operational Context
- Operational Scenarios
- User Needs

### Outputs

- Product Definition
- Initial Engineering Scope
- System Boundary

---

## 2. Decision Analysis

### Engineering Question

> Which engineering approach best satisfies the project objectives?

### Purpose

Decision Analysis evaluates viable alternatives using objective engineering criteria.

Rather than selecting solutions based on intuition, engineering decisions are supported through documented trade-offs and evaluation rationale.

### Primary Activities

- Trade Studies
- Alternative Analysis
- Technology Evaluation
- Engineering Recommendations

### Outputs

- Engineering Decisions
- Decision Rationale
- Repository Direction

---

## 3. Requirements Engineering

### Engineering Question

> What shall the system do?

### Purpose

Requirements Engineering transforms stakeholder needs into measurable, verifiable engineering requirements.

### Primary Activities

- Requirement Development
- Requirement Decomposition
- Traceability
- Verification Planning

### Outputs

- System Requirements
- Verification Methods
- Requirement Traceability

---

## 4. System Architecture

### Engineering Question

> How should the system be organized?

### Purpose

Architecture organizes system behavior into logical and physical structures capable of satisfying system requirements.

### Primary Activities

- Functional Decomposition
- Interfaces
- Architecture Decisions
- System Models

### Outputs

- Architecture
- Interfaces
- Design Decisions

---

## 5. Risk Engineering

### Engineering Question

> What could prevent the system from achieving its intended purpose?

### Purpose

Risk Engineering identifies hazards, evaluates risk, and guides engineering decisions that reduce unacceptable risk throughout the product lifecycle.

### Primary Activities

- Hazard Analysis
- Risk Assessment
- Risk Controls
- Residual Risk Evaluation

### Outputs

- Risk Management File
- Risk Control Requirements

---

## 6. Product Cybersecurity

### Engineering Question

> How do we protect the system and its data throughout its lifecycle?

### Purpose

Product Cybersecurity applies secure-by-design engineering principles throughout product development.

### Primary Activities

- Asset Identification
- Threat Modeling
- Security Architecture
- Security Verification

### Outputs

- Security Requirements
- Threat Models
- Security Verification

---

## 7. Human Factors Engineering

### Engineering Question

> How can users safely and effectively interact with the system?

### Purpose

Human Factors Engineering evaluates workflows, user interactions, and use-related risks to improve safety and usability.

### Primary Activities

- Workflow Analysis
- Task Analysis
- Usability Engineering
- Human Factors Verification

### Outputs

- Usability Requirements
- Workflow Improvements
- Human Factors Evidence

---

## 8. Verification Engineering

### Engineering Question

> How do we demonstrate that engineering requirements have been satisfied?

### Purpose

Verification Engineering plans, executes, and documents objective evidence demonstrating compliance with engineering requirements.

### Primary Activities

- Verification Strategy
- Test Planning
- Test Design
- Verification Execution
- Reporting

### Outputs

- Verification Evidence
- Traceability
- Engineering Confidence

---

## 9. Implementation

### Engineering Question

> How are engineering decisions realized?

### Purpose

Implementation converts engineering decisions into working hardware, firmware, software, and documentation.

Implementation exists to realize engineering intent rather than define it.

### Primary Activities

- Hardware Development
- Firmware Development
- Software Development
- Integration

### Outputs

- Working System
- Source Code
- Design Documentation

---

## 10. Objective Evidence

### Engineering Question

> What evidence demonstrates that the engineering process produced the intended result?

### Purpose

Engineering concludes not with implementation but with objective evidence.

Objective evidence demonstrates that engineering decisions were correctly implemented and verified.

### Outputs

- Verification Results
- Design History
- Engineering Documentation
- Release Artifacts

---

# Key Engineering Principles

Engineering progresses by reducing uncertainty.

Each engineering artifact should answer a specific question.

Engineering decisions should be objective and traceable.

Implementation validates engineering decisions—it does not replace them.

Verification demonstrates engineering quality through objective evidence.

Engineering is iterative. Information produced by later activities frequently informs refinement of earlier engineering decisions.

---

# Relationship to the Repository

The repository is organized to reflect this lifecycle.

```text
engineering/
        │
        ├── product/
        ├── requirements/
        ├── architecture/
        ├── quality/
        ├── cybersecurity/
        ├── human-factors/
        ├── verification/
        └── templates/

decisions/
        ├── decision-analysis/
        ├── adr/
        └── decision-log/

platforms/
        └── connected-physiological-monitor/
```

Each engineering artifact demonstrates one stage of the lifecycle while maintaining traceability to the activities before and after it.

---

# Engineering Principles

- Every artifact should answer a specific engineering question.
- Engineering documentation should reduce uncertainty.
- Decisions should precede implementation.
- Requirements should be verifiable.
- Architecture should satisfy requirements.
- Verification should produce objective evidence.
- Traceability should connect engineering decisions throughout the lifecycle.

---

# Related Documents

- Project Charter
- Repository Vision
- Product Definition
- Decision Analysis
- Requirements Engineering
- Architecture
- Verification Engineering
