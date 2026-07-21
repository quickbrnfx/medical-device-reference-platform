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

## CA-001 — Monitoring Session Management

| Requirement | Status |
|------------|--------|
| SR-001 – Initiate monitoring session | Draft |
| SR-002 – Associate monitoring session with patient | Draft |
| SR-003 – Indicate active monitoring session | Draft |

### Review Questions

- How is a monitoring session completed?
- Can a monitoring session be cancelled?
- Can multiple monitoring sessions exist simultaneously?
- Can a completed monitoring session be resumed?
- What constitutes the lifecycle of a monitoring session?

---

## CA-002 — Monitoring State Management

| Requirement | Status |
|------------|--------|
| SR-010 – Transition to Ready state | Draft |
| SR-011 – Transition to Monitoring state | Draft |
| SR-012 – Indicate current operational state | Draft |

### Review Questions

- What operational states are required?
- What events trigger state transitions?
- Which transitions are prohibited?
- Are fault states required?
- Are shutdown and initialization represented as operational states?

---

## CA-003 — Monitoring Configuration

| Requirement | Status |
|------------|--------|
| SR-015 – Configure monitoring prior to session initiation | Draft |

### Review Questions

- Can monitoring configuration be modified?
- When is configuration permitted?
- How is configuration validated?
- Can monitoring begin with an invalid configuration?
- What configuration information is mandatory?

---

## CA-004 — Physiological Data Acquisition

| Requirement | Status |
|------------|--------|
| SR-004 – Acquire physiological measurements | Draft |
| SR-005 – Detect sensor communication loss | Draft |
| SR-006 – Identify unavailable measurements | Draft |

### Review Questions

- Is acquisition continuous?
- Is partial acquisition permitted?
- What occurs following sensor reconnection?
- Can acquisition continue if only a subset of sensors is available?
- What conditions suspend acquisition?

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
