# Security Objectives

## Overview

Security Objectives define the intended cybersecurity outcomes that a system should achieve throughout its operational lifecycle.

Rather than prescribing specific security controls or technologies, Security Objectives establish the engineering goals that guide requirements development, architectural decisions, implementation, and verification.

They provide a common understanding of what the system must protect and why that protection is important.

---

## Purpose

The purpose of defining Security Objectives is to establish clear cybersecurity expectations before engineering solutions are developed.

Well-defined Security Objectives enable engineering teams to:

- Identify assets requiring protection.
- Guide cybersecurity requirements.
- Support architectural decision-making.
- Prioritize engineering effort.
- Evaluate security tradeoffs.
- Define meaningful security verification activities.

---

## Security Objective Principles

Effective Security Objectives should be:

### Stakeholder Driven

Security objectives should reflect stakeholder expectations, operational needs, and the intended use of the system.

### Risk Informed

The importance of each objective should be proportional to the potential impact of its compromise.

### Technology Independent

Objectives should define desired outcomes rather than prescribe implementation mechanisms.

### Traceable

Each objective should remain traceable to stakeholder needs, system requirements, and cybersecurity decisions.

### Verifiable

Objectives should ultimately be supported by measurable engineering evidence.

---

## Common Security Objectives

Although priorities vary by system, common Security Objectives include:

| Security Objective | Description |
|--------------------|-------------|
| Confidentiality | Protect sensitive information from unauthorized disclosure. |
| Integrity | Prevent unauthorized or unintended modification of data, software, or system behavior. |
| Availability | Ensure required system functions remain accessible when needed. |
| Authenticity | Establish confidence in the identity of users, devices, software, or data sources. |
| Accountability | Enable actions and events to be attributed to responsible entities. |
| Resilience | Maintain or recover intended operation despite failures or attacks. |

Projects may define additional objectives depending on operational context and stakeholder expectations.

---

## Relationship to Other Artifacts

Security Objectives establish the cybersecurity goals that guide subsequent engineering activities.

```text
Stakeholder Needs
         │
         ▼
Security Objectives
         │
         ▼
Security Requirements
         │
         ▼
Threat Modeling
         │
         ▼
Secure Architecture
         │
         ▼
Security Verification
```

Security Objectives provide the foundation for engineering cybersecurity throughout system development.
