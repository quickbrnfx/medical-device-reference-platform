# Requirement Lifecycle

**Status:** Approved

---

# Objective

Define the engineering lifecycle through which System Requirements progress from initial development to verified engineering baseline.

This lifecycle establishes when a requirement becomes an approved engineering artifact and defines the major engineering activities that occur throughout its development.

---

# Overview

System Requirements are developed through a structured engineering process that progressively transforms stakeholder objectives into verified system behavior.

A requirement is not considered part of the engineering baseline until it has successfully completed the Requirements Review.

---

# Requirement Lifecycle

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
Implementation
        ↓
Verification
        ↓
Released Engineering Baseline
```

---

# Lifecycle Stages

| Stage | Description | Output |
|--------|-------------|--------|
| Stakeholder Persona | Defines the stakeholder interacting with the system. | Stakeholder Persona |
| User Need | Defines the stakeholder outcome that the system must satisfy. | Approved User Need |
| Capability Review | Identifies the engineering responsibilities required to satisfy the User Need. | Approved Capability Area(s) |
| Requirements Review | Decomposes each approved Capability Area into the minimum set of observable, verifiable system behaviors. | Approved System Requirement(s) |
| Architecture Allocation | Allocates approved requirements to architectural elements without modifying requirement intent. | System Architecture |
| Implementation | Implements the allocated engineering responsibilities. | Implemented System |
| Verification | Demonstrates objective evidence that each approved requirement has been satisfied. | Verification Evidence |
| Released Engineering Baseline | Establishes the verified engineering baseline for the product. | Released Product Baseline |

---

# Requirement States

Each System Requirement progresses through the following engineering states.

| State | Description |
|-------|-------------|
| Draft | Requirement is under development and has not entered formal review. |
| Proposed | Requirement has been submitted for Requirements Review. |
| Approved | Requirement has successfully completed Requirements Review and is part of the engineering baseline. |
| Allocated | Requirement has been assigned to one or more architectural elements. |
| Implemented | Required system behavior has been implemented. |
| Verified | Objective evidence demonstrates that the requirement has been satisfied. |
| Released | Requirement forms part of the released engineering baseline. |
| Retired | Requirement is no longer active but remains preserved for engineering traceability. |

---

# Engineering Principles

- Requirements become engineering baseline artifacts only after successful completion of the Requirements Review.
- Architecture allocates requirements but does not redefine their intent.
- Implementation satisfies requirements but does not establish them.
- Verification produces objective evidence demonstrating requirement satisfaction.
- Every approved requirement remains traceable throughout its lifecycle.

---

# Definition of Done

A System Requirement is considered complete when:

- It traces to one or more approved User Needs.
- It traces to one or more approved Capability Areas.
- It satisfies the established Requirement Quality Characteristics.
- It has successfully completed the Requirements Review.
- It has been incorporated into the approved System Requirements Specification.
- Objective verification evidence demonstrates compliance.

---

# Traceability

## Inputs

- Stakeholder Personas
- User Needs
- Capability Reviews

## Outputs

- System Requirements Specification
- System Architecture
- Verification Planning
- Verification Procedures
- Verification Evidence

---

# Observations

- Requirements evolve through a controlled engineering process rather than being written directly from stakeholder needs.
- Requirement approval precedes architecture, implementation, and verification.
- Stable requirements reduce downstream engineering changes.
- Complete lifecycle traceability supports maintainability, regulatory compliance, and objective verification.
