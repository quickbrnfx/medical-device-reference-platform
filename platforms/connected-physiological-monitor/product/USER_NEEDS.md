# User Needs

**Status:** Approved

---

# Objective

# Objective

Capture stakeholder needs in a solution-independent manner to establish the product outcomes that the reference platform must enable.

User Needs express stakeholder objectives rather than implementation decisions. They provide the foundation from which engineering disciplines derive System Requirements, Human Factors Engineering activities, System Architecture, Cybersecurity Engineering, Verification Planning, and Validation Planning.

The purpose of this document is to establish a stable product definition that remains independent of implementation throughout system development.

---

# Definition

User Needs describe **what stakeholders need to accomplish** in order to achieve the intended use of the system.

They represent stakeholder goals rather than implementation decisions.

Well-written User Needs should be:

- Stakeholder focused
- Solution independent
- Clear and unambiguous
- Necessary
- Traceable
- Stable throughout product development

User Needs define **what** the system must enable—not **how** it will achieve those outcomes.

---

# User Need Derivation

User Needs were derived by evaluating the goals of each primary stakeholder across representative operational scenarios.

Operational Scenarios provide context for understanding stakeholder interactions with the reference platform, while Stakeholder Personas identify the underlying goals that remain consistent regardless of implementation.

Each User Need represents a stakeholder objective that the reference platform must enable through one or more engineering responsibilities. These responsibilities are established during Capability Review and ultimately realized through one or more System Requirements.

The following persona–scenario relationships were identified.

| User Need | Primary Persona | Operational Scenarios |
|-----------|-----------------|-----------------------|
| UN-001 | STKP-001 – Patient | OPS-001, OPS-002, OPS-003 |
| UN-002 | STKP-001 – Patient | OPS-002, OPS-005 |
| UN-003 | STKP-001 – Patient | OPS-003, OPS-004 |
| UN-004 | STKP-001 – Patient | OPS-001, OPS-002, OPS-004 |
| UN-005 | STKP-002 – Clinical Operator | OPS-001 |
| UN-006 | STKP-002 – Clinical Operator | OPS-002 |
| UN-007 | STKP-002 – Clinical Operator | OPS-004 |
| UN-008 | STKP-002 – Clinical Operator | OPS-005 |
| UN-009 | STKP-003 – Healthcare Provider | OPS-002, OPS-003 |
| UN-010 | STKP-003 – Healthcare Provider | OPS-003, OPS-004 |
| UN-011 | STKP-003 – Healthcare Provider | OPS-005 |

This derivation establishes the engineering rationale linking stakeholder goals to representative operational scenarios before requirements development begins.

---

# User Needs Summary

| ID | User Need | Priority | Reasoning |
|----|-----------|:--------:|-----------|
| **UN-001** | The patient needs physiological monitoring to support their care. | **High** | The primary purpose of the system. |
| **UN-002** | The patient needs only authorized entities to obtain their physiological information throughout monitoring. | **High** | Security and privacy are fundamental stakeholder expectations for medical devices. |
| **UN-003** | The patient needs clinically significant changes in their physiological condition to be identified. | **High** | A core objective of physiological monitoring. |
| **UN-004** | The patient needs monitoring to be performed without compromising their safety. | **High** | Safety is foundational to the intended use. |
| **UN-005** | The clinical operator needs to establish physiological monitoring for a patient. | **High** | Monitoring cannot occur without successful setup. |
| **UN-006** | The clinical operator needs to monitor a patient's physiological condition. | **High** | A primary operational goal. |
| **UN-007** | The clinical operator needs to respond to abnormal conditions affecting patient monitoring. | **High** | Necessary to maintain safe and effective monitoring. |
| **UN-008** | The clinical operator needs to conclude a patient monitoring session. | **Medium** | Important, but occurs after monitoring has been completed. |
| **UN-009** | The healthcare provider needs physiological information to assess the patient's condition. | **High** | Central to clinical decision-making. |
| **UN-010** | The healthcare provider needs to recognize clinically significant changes in the patient's physiological condition. | **High** | One of the primary reasons for monitoring. |
| **UN-011** | The healthcare provider needs completed monitoring information to support continuity of care. | **Medium** | Important for ongoing care, but not required during active monitoring. |

---

# User Need Priorities

User Need priorities indicate the relative importance of satisfying each stakeholder goal in achieving the intended use of the reference platform.

| Priority | Description |
|----------|-------------|
| **High** | Essential to achieving the intended use or ensuring patient safety. |
| **Medium** | Important to system effectiveness, usability, or clinical workflow efficiency. |
| **Low** | Desirable but not essential for Version 1 of the reference platform. |

Priorities support engineering tradeoff discussions and implementation planning but do not replace risk management activities.

---

# Engineering Implications

Each User Need establishes one or more engineering objectives that are realized through downstream engineering outputs.

| Engineering Output        | Relationship                                                                         |
| ------------------------- | ------------------------------------------------------------------------------------ |
| Capability Areas          | Define the enduring engineering responsibilities required to satisfy each User Need. |
| System Requirements       | Define the observable system behaviors that realize approved Capability Areas.       |
| System Architecture       | Allocates engineering responsibilities across system elements.                       |
| Human Factors Engineering | Ensures user interactions support stakeholder goals.                                 |
| Cybersecurity Engineering | Identifies additional security requirements within approved Capability Areas.        |
| Risk Management           | Identifies additional safety requirements within approved Capability Areas.          |
| Verification Planning     | Confirms System Requirements have been satisfied.                                    |
| Validation Planning       | Demonstrates User Needs have been achieved in representative use environments.       |


User Needs serve as the primary bridge between Product Definition and Requirements Engineering.

---

# Observations

- User Needs describe stakeholder goals rather than operational tasks.
- Multiple Operational Scenarios often contribute to a single stakeholder goal.
- User Needs remain solution-independent and do not prescribe system behavior or implementation.
- A single User Need typically decomposes into one or more Capability Areas, which are subsequently realized through one or more System Requirements.
- User Needs should remain stable unless stakeholder objectives or intended use change.

---

# Engineering Principles

- Stakeholder goals should remain independent of implementation decisions.
- Operational tasks should not be confused with stakeholder needs.
- User Needs provide a stable foundation for Requirements Engineering.
- Every Capability Area shall trace to one or more User Needs.
- Every System Requirement shall trace to one or more approved Capability Areas.
- Traceability from System Requirements to User Needs shall be maintained through Capability Areas.
- User Needs should remain solution-independent so they can be satisfied by multiple system architectures and implementations.

---

# Traceability

## Inputs

- Stakeholder Analysis
- Stakeholder Personas
- Operational Context
- Representative Operational Scenarios

## Outputs

- Capability Areas
- System Requirements
- System Architecture
- Human Factors Engineering
- Cybersecurity Engineering
- Risk Management
- Verification Planning
- Validation Planning

User Needs form the primary transition from Product Definition into Requirements Engineering by translating stakeholder objectives into engineering intent.
