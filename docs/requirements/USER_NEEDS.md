# User Needs

**Status:** Draft

---

# Objective

Capture the needs of stakeholders in a solution-independent manner.

User needs describe the outcomes stakeholders require from the system without prescribing how those needs will be implemented.

---

## User Need Derivation

User needs were derived by evaluating the interactions between the primary stakeholder personas and the representative operational scenarios defined in the Operational Context.

The following persona–scenario relationships were identified:

| Persona | OPS-001 | OPS-002 | OPS-003 | OPS-004 | OPS-005 |
|----------|:-------:|:-------:|:-------:|:-------:|:-------:|
| Patient | ✓ | ✓ | | ✓ | |
| Clinical Operator | ✓ | | | ✓ | ✓ |
| Healthcare Provider | | ✓ | ✓ | ✓ | ✓ |

---

## User Needs Summary

| ID         | Persona                          | Operational Scenario                                | User Need                                                                                                   | Rationale                                                                    | Priority |
| ---------- | -------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | :------: |
| **UN-007** | **STKP-002 – Clinical Operator** | **OPS-001 – Patient Setup & Device Initialization** | The clinical operator needs to safely and correctly configure the monitoring system for a new patient.               | Supports efficient workflow and reduces the potential for setup errors.      |   High   |
| **UN-008** | **STKP-002 – Clinical Operator** | **OPS-001 – Patient Setup & Device Initialization** | The clinical operator needs to associate the correct patient with the monitoring session.                   | Supports accurate patient identification and data association.               |   High   |
| **UN-009** | **STKP-002 – Clinical Operator** | **OPS-001 – Patient Setup & Device Initialization** | The clinical operator needs to determine that the monitoring system is ready for patient use.               | Supports safe initiation of physiological monitoring.                        |   High   |
| **UN-010** | **STKP-002 – Clinical Operator** | **OPS-001 – Patient Setup & Device Initialization** | The clinical operator needs to identify setup problems before monitoring begins.                            | Reduces the likelihood of monitoring interruptions and configuration errors. |   High   |
| **UN-011** | **STKP-002 – Clinical Operator** | **OPS-004 – Abnormal Condition Response**           | The clinical operator needs to recognize system faults during monitoring.                                   | Supports timely response to abnormal operating conditions.                   |   High   |
| **UN-012** | **STKP-002 – Clinical Operator** | **OPS-004 – Abnormal Condition Response**           | The clinical operator needs to understand appropriate corrective actions when faults occur.                 | Supports safe and effective resolution of abnormal operating conditions.     |   High   |
| **UN-013** | **STKP-002 – Clinical Operator** | **OPS-004 – Abnormal Condition Response**           | The clinical operator needs to safely continue or discontinue monitoring following a system fault.          | Supports patient safety during abnormal operating conditions.                |   High   |
| **UN-014** | **STKP-002 – Clinical Operator** | **OPS-005 – Data Review & Session Completion**      | The clinical operator needs to complete a patient monitoring session in a safe and controlled manner. | Supports consistent completion of patient monitoring activities.             |  Medium  |
| **UN-015** | **STKP-002 – Clinical Operator** | **OPS-005 – Data Review & Session Completion**      | The clinical operator needs monitoring data to be been preserved before ending the session.   | Supports data availability for future clinical review.                       |   High   |
| **UN-016** | **STKP-002 – Clinical Operator** | **OPS-005 – Data Review & Session Completion**      | The clinical operator needs to prepare the monitoring system for subsequent patient use.        | Supports efficient transition between monitoring sessions.                   |  Medium  |
| **UN-017** | **STKP-003 – Healthcare Provider** | **OPS-002 – Continuous Physiological Monitoring**    | The healthcare provider needs access to current physiological information.                                       | Supports informed clinical assessment and decision-making.              |   High   |
| **UN-018** | **STKP-003 – Healthcare Provider** | **OPS-002 – Continuous Physiological Monitoring**    | The healthcare provider needs physiological information that accurately represents the patient's physiological condition.                    | Supports confident interpretation of patient condition.                 |   High   |
| **UN-019** | **STKP-003 – Healthcare Provider** | **OPS-003 – Clinical Assessment & Decision Support** | The healthcare provider needs to assess the patient's condition using current and historical physiological information. | Supports informed clinical decision-making over the course of care.     |   High   |
| **UN-020** | **STKP-003 – Healthcare Provider** | **OPS-003 – Clinical Assessment & Decision Support** | The healthcare provider needs to identify clinically significant changes in the patient's physiological condition.                  | Supports recognition of changes that may require clinical intervention. |   High   |
| **UN-021** | **STKP-003 – Healthcare Provider** | **OPS-004 – Abnormal Condition Response**            | The healthcare provider needs to be informed of clinically significant changes in the patient's physiological condition.    | Supports timely awareness of conditions requiring clinical response.    |   High   |
| **UN-022** | **STKP-003 – Healthcare Provider** | **OPS-004 – Abnormal Condition Response**            | The healthcare provider needs to distinguish patient conditions from monitoring system issues.                          | Supports appropriate clinical decisions during abnormal conditions.     |   High   |
| **UN-023** | **STKP-003 – Healthcare Provider** | **OPS-005 – Data Review & Session Completion**       | The healthcare provider needs access to completed monitoring records for future clinical review.                        | Supports continuity of care and retrospective clinical assessment.      |  Medium  |


---

# Priority Definitions

| Priority | Description |
|----------|-------------|
| High | Essential to achieving the intended use or ensuring safety. |
| Medium | Important to system effectiveness or workflow efficiency. |
| Low | Desirable but not essential for the initial reference platform. |

---

# Observations

-

---

# Lessons Learned

-
