# System Requirements

**Status:** Approved

---

# Objective

Define the system capabilities, behaviors, constraints, and qualities required for the Connected Physiological Monitor reference platform to satisfy stakeholder User Needs.

System Requirements describe **what** the reference platform must do and provide the primary engineering input for System Architecture, implementation, integration, Human Factors Engineering, Cybersecurity Engineering, Risk Management, and Verification activities.

---

# Definition

A System Requirement specifies an observable system behavior, constraint, or quality attribute that the system must satisfy.

System Requirements translate approved engineering responsibilities into objective engineering statements that can be allocated, implemented, and verified.

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

# Requirement Development

System Requirements are derived through a structured engineering decomposition process that transforms stakeholder objectives into verifiable engineering behaviors.

Each User Need is first decomposed into one or more engineering Capability Areas. Capability Areas define the engineering responsibilities required to satisfy the User Need and establish the basis for detailed requirements development.

Approved Capability Areas are then decomposed into the minimum set of observable System Requirements necessary to fulfill each engineering responsibility.

```text
Stakeholder Persona
        ↓
User Need
        ↓
Capability Review
        ↓
Approved Capability Area
        ↓
Requirements Review
        ↓
Approved System Requirement
        ↓
Architecture Allocation
        ↓
Verification Case
```

Every System Requirement shall trace to:

- at least one approved User Need
- at least one approved Capability Area

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
| Traceable | Can be linked to originating User Needs, approved Capability Areas, and downstream Verification activities. |

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

Before developing individual System Requirements, each User Need is decomposed into one or more approved engineering Capability Areas. Capability Areas define the engineering responsibilities that collectively satisfy the User Need and provide the basis for requirements development.

Capability Areas are engineering responsibilities, not engineering requirements.

| User Need | Approved Capability Areas |
|-----------|---------------------------|
| **UN-001** Patient monitoring | CA-001 – CA-007 |
| **UN-002** Information protection | **CA-008 – Manage Access to Physiological Information** |
| **UN-003** Identify clinically significant changes | **CA-009 – Identify Clinically Significant Physiological Changes** |
| **UN-004** Patient safety | TBD |
| **UN-005** Establish monitoring | TBD |
| **UN-006** Monitor patient condition | TBD |
| **UN-007** Respond to abnormal conditions | TBD |
| **UN-008** Conclude monitoring | TBD |
| **UN-009** Assess patient condition | TBD |
| **UN-010** Recognize clinically significant changes | TBD |
| **UN-011** Support continuity of care | TBD |

Capability Areas organize engineering responsibilities prior to detailed requirements development.

Capability Areas organize requirements development but are not themselves engineering requirements.

---

# System Requirements Summary

Approved System Requirements are organized by User Need and associated Capability Areas.

| User Need | Capability Areas | Requirement IDs |
|-----------|------------------|-----------------|
| **UN-001** | CA-001 – CA-007 | SR-001 – SR-068 |
| **UN-002** | CA-008 | SR-069 – SR-071 |
| **UN-003** | CA-009 | SR-072 – SR-073 |
| **UN-004** | TBD | TBD |
| **UN-005** | TBD | TBD |
| **UN-006** | TBD | TBD |
| **UN-007** | TBD | TBD |
| **UN-008** | TBD | TBD |
| **UN-009** | TBD | TBD |
| **UN-010** | TBD | TBD |
| **UN-011** | TBD | TBD |

This document establishes the engineering baseline for approved System Requirements while preserving traceability to approved User Needs and Capability Areas.

---

---

# Requirement Allocation

Approved System Requirements are allocated to architectural elements during System Architecture development.

This specification intentionally does not allocate requirements to hardware, software, interfaces, or other implementation elements.

Requirement allocation is documented within the System Architecture discipline.

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

System Requirements establish the approved behavioral baseline for the system.

All downstream engineering disciplines consume this baseline when developing architecture, risk analyses, cybersecurity controls, human factors artifacts, and verification activities.

---

# Observations

- System Requirements translate stakeholder goals into objective engineering statements.
- One User Need typically results in multiple System Requirements.
- Requirement decomposition improves organization and traceability before detailed specification.
- Requirements should describe externally observable system behavior rather than implementation.
- Stable System Requirements reduce downstream architecture and verification changes.
- - User Needs are first decomposed into engineering Capability Areas.
- Approved Capability Areas are subsequently decomposed into one or more System Requirements.

---

# Engineering Principles

- Every System Requirement shall trace to one or more approved Capability Areas.
- Every approved Capability Area shall trace to one or more User Needs.
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
- Approved Capability Areas

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
