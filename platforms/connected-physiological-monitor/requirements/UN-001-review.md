# UN-001 Requirements Review

**User Need**

> **UN-001** – The patient needs physiological monitoring to support their care.

**Status:** In Progress

---

# Objective

Develop and review the functional System Requirements derived from UN-001.

This review establishes the functional baseline before introducing performance, interface, safety, cybersecurity, and quality requirements.

---

# Capability Areas

The following capability areas have been identified and reviewed.

| ID | Capability Area | Status |
|----|-----------------|--------|
| CA-001 | Monitoring Session Management | Frozen |
| CA-002 | Monitoring State Management | Frozen |
| CA-003 | Monitoring Configuration | Frozen |
| CA-004 | Physiological Data Acquisition | Frozen |
| CA-005 | Physiological Data Availability | Frozen |
| CA-006 | Physiological Data Processing | Frozen |

---

# Current Functional Requirements

# CA-001 — Monitoring Session Management

**Purpose**

Manage the lifecycle of a patient monitoring session from initiation through completion.

---

## Functional Requirements

### SR-001

**Requirement**

> The system shall allow an authorized clinical operator to initiate a new monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-002

**Requirement**

> The system shall uniquely associate each monitoring session with a single patient identifier.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-003

**Requirement**

> The system shall indicate the current lifecycle state of the monitoring session.

**Verification**

- Inspection, Test

**Traceability**

- UN-001

---

### SR-016

**Requirement**

> The system shall transition an active monitoring session to the completed state upon request from an authorized clinical operator.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-017

**Requirement**

> The system shall terminate physiological data acquisition upon completion of the active monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-018

**Requirement**

> The system shall support only one active monitoring session at a time.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-019

**Requirement**

> The system shall prevent modification of the associated patient identifier while a monitoring session is active.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-020

**Requirement**

> The system shall not associate physiological measurements acquired after completion of a monitoring session with the completed monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-021

**Requirement**

> The system shall assign a unique identifier to each monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-022

**Requirement**

> The system shall record the initiation of each monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-023

**Requirement**

> The system shall record the completion of each monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-024

**Requirement**

> The system shall prevent initiation of a monitoring session unless all session preconditions are satisfied.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-025

**Requirement**

> The system shall prevent a completed monitoring session from returning to the active state.

**Verification**

- Test

**Traceability**

- UN-001

---

## Review Status

**Status:** Baseline Approved

This capability area establishes the functional requirements governing the lifecycle of a monitoring session. Additional performance, safety, cybersecurity, interface, and quality requirements may refine these requirements but shall not alter their intended functional behavior without an approved engineering change.

---

# CA-002 — Monitoring State Management

**Purpose**

Define the operational states of the Connected Physiological Monitor and govern the allowable transitions between those states during normal and abnormal operation.

The requirements in this capability area are derived from the System Operational State Model.

---

## Functional Requirements

### SR-026

**Requirement**

> The system shall enter the Initializing state upon system startup.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-027

**Requirement**

> The system shall transition from the Initializing state to the Ready state only after successful completion of initialization.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-028

**Requirement**

> The system shall transition from the Initializing state to the Fault state upon detection of a Fault Condition during initialization.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-029

**Requirement**

> The system shall accept requests to initiate a monitoring session only while in the Ready state.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-030

**Requirement**

> The system shall transition from the Ready state to the Monitoring state upon successful initiation of a monitoring session.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-031

**Requirement**

> The system shall transition from the Ready state to the Fault state upon detection of a Fault Condition.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-032

**Requirement**

> The system shall remain in the Monitoring state until either the active monitoring session is completed or a Fault Condition is detected.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-033

**Requirement**

> The system shall transition from the Monitoring state to the Finalizing state upon completion of the active monitoring session.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-034

**Requirement**

> The system shall transition from the Monitoring state to the Fault state upon detection of a Fault Condition.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-035

**Requirement**

> The system shall remain in the Finalizing state until finalization activities have been completed or a Fault Condition is detected.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-036

**Requirement**

> The system shall transition from the Finalizing state to the Ready state upon successful completion of finalization activities.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-037

**Requirement**

> The system shall transition from the Finalizing state to the Fault state upon detection of a Fault Condition.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-038

**Requirement**

> The system shall transition to the Fault state upon detection of a Fault Condition.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-039

**Requirement**

> The system shall suspend normal operation while in the Fault state.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-040

**Requirement**

> The system shall transition from the Fault state to the Initializing state upon initiation of system recovery.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-041

**Requirement**

> The system shall not transition directly from the Fault state to any operational state other than the Initializing state.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-042

**Requirement**

> The system shall occupy exactly one operational state at any given time.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

## Review Status

**Status:** Baseline Approved

---

# CA-003 — Monitoring Configuration

**Purpose**

Establish and validate the monitoring configuration required before initiating a monitoring session.

The requirements in this capability area define how the Connected Physiological Monitor establishes, validates, and maintains the monitoring configuration throughout the monitoring session lifecycle.

---

## Functional Requirements

### SR-043

**Requirement**

> The system shall permit modification of the monitoring configuration only while in the Ready state.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-044

**Requirement**

> The system shall validate the monitoring configuration before permitting initiation of a monitoring session.

**Verification**

- Test

**Traceability**

- UN-001
- CA-001 Monitoring Session Management
- System Operational State Model

---

### SR-045

**Requirement**

> The system shall prevent modification of the monitoring configuration while a monitoring session is active.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-046

**Requirement**

> The system shall preserve the monitoring configuration following completion of a monitoring session until modified by an authorized clinical operator.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-047

**Requirement**

> The system shall use the validated monitoring configuration throughout the active monitoring session.

**Verification**

- Test

**Traceability**

- UN-001

---

## Review Status

**Status:** Baseline Approved

---

# CA-004 — Physiological Data Acquisition

**Purpose**

Acquire physiological measurements from configured physiological sensors during an active monitoring session.

The requirements in this capability area define how the Connected Physiological Monitor acquires physiological measurements from configured physiological sensors for use by downstream system functions.

---

## Functional Requirements

### SR-048

**Requirement**

> The system shall acquire physiological measurements only while in the Monitoring state.

**Verification**

- Test

**Traceability**

- UN-001
- System Operational State Model

---

### SR-049

**Requirement**

> The system shall acquire physiological measurements from configured physiological sensors.

**Verification**

- Test

**Traceability**

- UN-001
- CA-003 Monitoring Configuration

---

### SR-050

**Requirement**

> The system shall detect interruption of physiological measurement acquisition from a configured physiological sensor.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-051

**Requirement**

> The system shall detect restoration of physiological measurement acquisition from a configured physiological sensor.

**Verification**

- Test

**Traceability**

- UN-001

---

### SR-052

**Requirement**

> The system shall continue acquiring physiological measurements from available configured physiological sensors following interruption of physiological measurement acquisition from another configured physiological sensor.

**Verification**

- Test

**Traceability**

- UN-001

---

## Review Status

**Status:** Baseline Approved

---

## CA-005 — Physiological Data Availability

| Requirement | Status |
|------------|--------|
| SR-013 – Indicate measurement availability | Draft |
| SR-014 – Distinguish unavailable measurements | Draft |

### Review Questions

- Is availability evaluated independently for each physiological parameter?
- How is unavailable data represented?
- When does data transition from unavailable to available?
- Should historical availability be retained?

---

## CA-006 — Physiological Data Processing

| Requirement | Status |
|------------|--------|
| SR-007 – Process acquired measurements | Draft |
| SR-008 – Maintain chronological ordering | Draft |
| SR-009 – Provide processed measurements to downstream functions | Draft |

### Review Questions

- Is processing continuous while monitoring is active?
- What occurs when acquisition stops?
- Can downstream functions consume incomplete data?
- Are processed measurements buffered?
- What functions consume processed measurements?

---

# Outstanding Engineering Work

The following activities remain before UN-001 is considered complete.

- Complete functional requirements for each Capability Area.
- Resolve outstanding review questions.
- Perform peer review for ambiguity, completeness, and traceability.
- Establish the functional baseline for UN-001.
- Proceed to UN-002.

---

# Exit Criteria

UN-001 is complete when:

- Every Capability Area has a complete functional requirement set.
- Every requirement is objective and verifiable.
- Traceability to UN-001 has been established.
- Peer review comments have been resolved.
- The functional baseline has been approved.
