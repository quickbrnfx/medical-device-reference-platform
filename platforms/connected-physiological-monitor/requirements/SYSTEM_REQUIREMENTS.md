# System Requirements

**Status:** Approved

---

# Objective

Define the system capabilities, behaviors, constraints, and qualities required for the Connected Physiological Monitor reference platform to satisfy stakeholder User Needs.

System Requirements describe **what** the reference platform must do and provide the primary engineering input for System Architecture, implementation, integration, Human Factors Engineering, Cybersecurity Engineering, Risk Management, and Verification activities.

---

# Definition

A System Requirement specifies a capability, behavior, constraint, or quality attribute that the system must satisfy.

System Requirements translate stakeholder objectives into objective engineering statements that can be allocated, implemented, and verified.

Every System Requirement shall:

- Be necessary
- Be clear and unambiguous
- Be atomic
- Be feasible
- Be solution independent where practical
- Be objectively verifiable
- Trace to one or more User Needs

---

# Requirement Development

System Requirements are derived from stakeholder User Needs and decompose each stakeholder goal into one or more verifiable engineering requirements.

```text
Stakeholder Persona
        ↓
User Need
        ↓
System Requirement(s)
        ↓
Verification Case(s)
```

Every System Requirement shall trace to at least one User Need.

---

# Requirement Characteristics

A high-quality System Requirement should exhibit the following characteristics.

| Characteristic | Description |
|---------------|-------------|
| Necessary | Exists to satisfy one or more User Needs. |
| Clear | Can be interpreted in only one reasonable way. |
| Atomic | Expresses a single engineering obligation. |
| Solution Independent | States what the system must accomplish rather than how it is implemented, unless implementation itself is required. |
| Verifiable | Can be objectively confirmed through Inspection, Analysis, Demonstration, or Test. |
| Traceable | Can be linked to originating User Needs and downstream Verification activities. |

---

# Requirement Writing Rules

System Requirements shall follow the conventions below.

## Rule 1

Every requirement begins with:

> **The system shall...**

---

## Rule 2

Each requirement expresses a single engineering obligation.

---

## Rule 3

Requirements describe required system behavior rather than implementation.

---

## Rule 4

Requirements avoid subjective language.

Avoid terms such as:

- quickly
- efficiently
- easily
- intuitively
- appropriately
- reliably
- user-friendly

unless objectively defined elsewhere.

---

## Rule 5

Quantitative requirements shall be objectively measurable.

---

# Requirement Decomposition

Before developing individual requirements, each User Need is decomposed into representative engineering capability areas.

| User Need | Requirement Capability Areas |
|-----------|------------------------------|
| **UN-001** Patient monitoring | Manage Monitoring Session, Manage Monitoring State, Manage Monitoring Configuration, Acquire Physiological Measurements, Provide Physiological Measurement Availability, Process Physiological Measurements, Provide Physiological Information |
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

Capability Areas organize requirements development but are not themselves engineering requirements.

---

# System Requirements Summary

Detailed System Requirements will be developed within each capability area.

| ID | Category | User Need | System Requirement | Verification |
|----|----------|-----------|--------------------|--------------|
| SR-001 | — | UN-001 | *To be developed* | — |

This document establishes the engineering framework for developing complete, traceable System Requirements while preserving traceability to originating User Needs.

---

# Verification Methods

Each System Requirement shall identify one or more Verification Methods.

| Method | Description |
|--------|-------------|
| Inspection | Verification through examination of documentation, design artifacts, or system configuration. |
| Analysis | Verification through calculation, modeling, simulation, or engineering analysis. |
| Demonstration | Verification by demonstrating required behavior under representative operating conditions. |
| Test | Verification through objective test procedures with defined acceptance criteria. |

Selection of Verification Methods should be based on the nature of the requirement rather than convenience.

---

# Engineering Implications

Approved System Requirements establish the engineering baseline for subsequent development activities.

| Engineering Artifact | Relationship |
|----------------------|--------------|
| System Architecture | Allocates responsibilities for satisfying each requirement. |
| Interface Specifications | Define interactions required to satisfy system behavior. |
| State Models | Describe dynamic system behavior. |
| Risk Analysis | Identifies hazards and associated risk controls. |
| Human Factors Engineering | Ensures requirements support safe and effective user interaction. |
| Cybersecurity Engineering | Derives security architecture and security controls. |
| Verification Planning | Defines objective evidence demonstrating each requirement has been satisfied. |

System Requirements represent the primary engineering contract between Product Definition and System Design.

---

# Observations

- System Requirements translate stakeholder goals into objective engineering statements.
- One User Need typically results in multiple System Requirements.
- Requirement decomposition improves organization and traceability before detailed specification.
- Requirements should describe externally observable system behavior rather than implementation.
- Stable System Requirements reduce downstream architecture and verification changes.

---

# Engineering Principles

- Every System Requirement should satisfy one or more User Needs.
- Requirements should specify system obligations rather than implementation whenever practical.
- Requirements should be written so they can be objectively verified.
- Clear decomposition before specification produces more complete and maintainable requirements.
- Every requirement should participate in end-to-end engineering traceability.

---

# Traceability

## Inputs

- Stakeholder Analysis
- Operational Context
- Stakeholder Personas
- User Needs

## Outputs

- System Architecture
- Interface Specifications
- State Models
- Risk Analysis
- Human Factors Engineering
- Cybersecurity Engineering
- Verification Planning
- Verification Procedures

System Requirements form the primary engineering baseline from which the system architecture, implementation, and verification strategy are derived.
