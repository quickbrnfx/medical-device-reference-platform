# System Requirements

## Objective

Define the system capabilities, behaviors, constraints, and qualities required for the Connected Physiological Monitor reference platform to satisfy stakeholder user needs.

System requirements describe **what** the reference platform must do and provide the primary engineering input for system architecture, implementation, and verification.

---

## Requirement Development

System requirements are derived from stakeholder user needs and decompose each stakeholder goal into one or more verifiable engineering requirements.

```
Stakeholder Persona
        ↓
User Need
        ↓
System Requirement(s)
        ↓
Verification Case(s)
```

Every system requirement shall trace to at least one user need.

---

## Requirement Characteristics

A high-quality system requirement should be:

| Characteristic | Description |
|---------------|-------------|
| Necessary | Exists to satisfy one or more user needs. |
| Clear | Can be interpreted in only one reasonable way. |
| Atomic | Expresses a single requirement. |
| Solution Independent | States what the system must accomplish rather than how it is implemented unless implementation itself is required. |
| Verifiable | Can be objectively confirmed through inspection, analysis, demonstration, or test. |
| Traceable | Can be linked to originating user needs and downstream verification activities. |

---

## Requirement Writing Rules

System requirements shall follow these conventions.

### Rule 1

Every requirement begins with:

> **The system shall...**

---

### Rule 2

Each requirement expresses a single obligation.

---

### Rule 3

Requirements describe required system behavior rather than implementation.

---

### Rule 4

Requirements avoid subjective language.

Avoid terms such as:

- quickly
- efficiently
- easily
- intuitively
- appropriately
- reliably
- user-friendly

unless objectively defined.

---

### Rule 5

Any quantitative requirement shall be objectively measurable.

---

## Requirement Decomposition

Before developing individual requirements, each user need is decomposed into engineering capability areas.

| User Need | Requirement Capability Areas |
|-----------|------------------------------|
| **UN-001** Patient monitoring | Monitoring Session Management, Physiological Data Acquisition, Physiological Data Processing |
| **UN-002** Information protection | Identity & Access Management, Data Protection, Secure Communications, Audit Logging |
| **UN-003** Identify clinically significant changes | Clinical Event Detection, Clinical Notification |
| **UN-004** Patient safety | Fault Management, Safety Controls |
| **UN-005** Establish monitoring | Session Establishment, Patient Association, Monitoring Configuration |
| **UN-006** Monitor patient condition | Physiological Data Presentation, Monitoring Status Indication |
| **UN-007** Respond to abnormal conditions | Alarm Management, Fault Recovery |
| **UN-008** Conclude monitoring | Session Completion, Data Preservation |
| **UN-009** Assess patient condition | Clinical Data Review, Historical Data Access |
| **UN-010** Recognize clinically significant changes | Trend Analysis, Event History |
| **UN-011** Support continuity of care | Record Management, Data Export |

Capability areas guide requirements development but are not themselves requirements.

---

## System Requirements Summary

| ID | Category | User Need | System Requirement | Verification |
|----|----------|-----------|--------------------|--------------|
| SR-001 | — | UN-001 | *To be developed* | — |

---

## Verification Methods

| Method | Description |
|--------|-------------|
| Inspection | Verification through examination of documentation or system artifacts. |
| Analysis | Verification through calculation, modeling, or engineering analysis. |
| Demonstration | Verification by demonstrating required behavior under representative conditions. |
| Test | Verification through objective test procedures and acceptance criteria. |

---

## Observations

- System requirements translate stakeholder goals into verifiable engineering statements.
- One user need typically results in multiple system requirements.
- Requirement decomposition improves organization and traceability before detailed specification begins.

---

## Lessons Learned

- Requirements should specify system obligations rather than implementation.
- Clear decomposition before specification produces more complete and maintainable requirements.
- Objective, traceable requirements simplify verification and future design decisions.
