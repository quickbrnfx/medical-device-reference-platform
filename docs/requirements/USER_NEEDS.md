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

| ID         | User Need                                                                                                           |  Priority  | Reasoning                                                                          |
| ---------- | ------------------------------------------------------------------------------------------------------------------- | :--------: | ---------------------------------------------------------------------------------- |
| **UN-001** | The patient needs physiological monitoring to support their care.                                                   |  **High**  | The primary purpose of the system.                                                 |
| **UN-002** | The patient needs their physiological information to remain protected throughout monitoring.                        |  **High**  | Security and privacy are fundamental stakeholder expectations for medical devices. |
| **UN-003** | The patient needs clinically significant changes in their physiological condition to be identified.                 |  **High**  | A core objective of physiological monitoring.                                      |
| **UN-004** | The patient needs monitoring to be performed without compromising their safety.                                     |  **High**  | Safety is foundational to the intended use.                                        |
| **UN-005** | The clinical operator needs to establish physiological monitoring for a patient.                                    |  **High**  | Monitoring cannot occur without successful setup.                                  |
| **UN-006** | The clinical operator needs to monitor a patient's physiological condition.                                         |  **High**  | A primary operational goal.                                                        |
| **UN-007** | The clinical operator needs to respond to abnormal conditions affecting patient monitoring.                         |  **High**  | Necessary to maintain safe and effective monitoring.                               |
| **UN-008** | The clinical operator needs to conclude a patient monitoring session.                                               | **Medium** | Important, but occurs after monitoring has been completed.                         |
| **UN-009** | The healthcare provider needs physiological information to assess the patient's condition.                          |  **High**  | Central to clinical decision-making.                                               |
| **UN-010** | The healthcare provider needs to recognize clinically significant changes in the patient's physiological condition. |  **High**  | One of the primary reasons for monitoring.                                         |
| **UN-011** | The healthcare provider needs completed monitoring information to support continuity of care.                       | **Medium** | Important for ongoing care, but not required to perform active monitoring.         |



---

# Priority Definitions

User need priorities indicate the relative importance of satisfying each stakeholder goal to achieve the intended use of the reference platform.

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
