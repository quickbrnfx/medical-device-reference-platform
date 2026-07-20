# User Needs

**Status:** Draft

---

# Objective

Capture the needs of stakeholders in a solution-independent manner.

User needs describe the outcomes stakeholders require from the system without prescribing how those needs will be implemented.

---

## User Need Derivation


User needs were derived by evaluating the goals of each primary stakeholder across representative operational scenarios.

Operational scenarios provided context for understanding stakeholder interactions with the reference platform, while stakeholder personas identified the underlying goals that remain consistent regardless of implementation.

Each user need represents a stakeholder goal that the reference platform must enable through one or more system requirements.

The following persona–scenario relationships were identified:

| User Need | Primary Persona                | Operational Scenarios     |
| --------- | ------------------------------ | ------------------------- |
| UN-001    | STKP-001 – Patient             | OPS-001, OPS-002, OPS-003 |
| UN-002    | STKP-001 – Patient             | OPS-002, OPS-005          |
| UN-003    | STKP-001 – Patient             | OPS-003, OPS-004          |
| UN-004    | STKP-001 – Patient             | OPS-001, OPS-002, OPS-004 |
| UN-005    | STKP-002 – Clinical Operator   | OPS-001                   |
| UN-006    | STKP-002 – Clinical Operator   | OPS-002                   |
| UN-007    | STKP-002 – Clinical Operator   | OPS-004                   |
| UN-008    | STKP-002 – Clinical Operator   | OPS-005                   |
| UN-009    | STKP-003 – Healthcare Provider | OPS-002, OPS-003          |
| UN-010    | STKP-003 – Healthcare Provider | OPS-003, OPS-004          |
| UN-011    | STKP-003 – Healthcare Provider | OPS-005                   |


---

## User Needs Summary

| ID         | Persona                        | User Need                                                                                                           |
| ---------- | ------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| **UN-001** | STKP-001 – Patient             | The patient needs physiological monitoring to support their care.                                                   |
| **UN-002** | STKP-001 – Patient             | The patient needs their physiological information to remain protected throughout monitoring.                        |
| **UN-003** | STKP-001 – Patient             | The patient needs clinically significant changes in their physiological condition to be recognized.                 |
| **UN-004** | STKP-001 – Patient             | The patient needs monitoring to be performed without compromising their safety.                                     |
| **UN-005** | STKP-002 – Clinical Operator   | The clinical operator needs to establish physiological monitoring for a patient.                                    |
| **UN-006** | STKP-002 – Clinical Operator   | The clinical operator needs to monitor a patient's physiological condition.                                         |
| **UN-007** | STKP-002 – Clinical Operator   | The clinical operator needs to respond to abnormal conditions affecting patient monitoring.                         |
| **UN-008** | STKP-002 – Clinical Operator   | The clinical operator needs to conclude a patient monitoring session.                                               |
| **UN-009** | STKP-003 – Healthcare Provider | The healthcare provider needs physiological information to assess the patient's condition.                          |
| **UN-010** | STKP-003 – Healthcare Provider | The healthcare provider needs to recognize clinically significant changes in the patient's physiological condition. |
| **UN-011** | STKP-003 – Healthcare Provider | The healthcare provider needs completed monitoring information to support continuity of care.                       |


---

# Priority Definitions

| Priority | Description |
|----------|-------------|
| High | Essential to achieving the intended use or ensuring safety. |
| Medium | Important to system effectiveness or workflow efficiency. |
| Low | Desirable but not essential for the initial reference platform. |

---

## Observations

- User needs describe stakeholder goals rather than operational tasks.
- Multiple operational scenarios often contribute to a single stakeholder goal.
- User needs remain solution-independent and do not prescribe system behavior or implementation.
- Each user need is expected to decompose into one or more system requirements during requirements development.
---

## Lessons Learned

- Separating stakeholder goals from operational tasks produces more stable and reusable user needs.
- Deferring implementation details to system requirements improves traceability and verification.
- Deriving user needs from both stakeholder personas and operational scenarios provides a stronger engineering rationale than considering either artifact independently.
