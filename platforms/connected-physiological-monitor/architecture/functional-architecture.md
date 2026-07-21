# Functional Architecture

## Purpose

The Functional Architecture describes the major system functions required to satisfy the user needs of the Connected Physiological Monitor.

Unlike the System Requirements Specification, which defines required system behaviors, the Functional Architecture describes **how those behaviors are organized into cooperating system functions**. These functions are logical responsibilities and do not imply a particular software, hardware, or physical implementation.

The Functional Architecture provides the bridge between User Needs, System Requirements, and subsequent architectural design activities.

---

# Functional Decomposition

```
Connected Physiological Monitor
│
├── Manage Monitoring Session
│
├── Manage Operational State
│
├── Manage Monitoring Configuration
│
├── Acquire Physiological Measurements
│
├── Determine Measurement Availability
│
├── Process Physiological Measurements
│
└── Provide Physiological Information
```

---

# Functional Descriptions

## F-001 — Manage Monitoring Session

Responsible for establishing, maintaining, and completing patient monitoring sessions.

Associated Capability Areas

- CA-001

---

## F-002 — Manage Operational State

Responsible for controlling the operational behavior of the Connected Physiological Monitor and governing transitions between operational states.

Associated Capability Areas

- CA-002

---

## F-003 — Manage Monitoring Configuration

Responsible for establishing, validating, and maintaining the monitoring configuration required before monitoring begins.

Associated Capability Areas

- CA-003

---

## F-004 — Acquire Physiological Measurements

Responsible for acquiring physiological measurements from configured physiological sensors during active monitoring.

Associated Capability Areas

- CA-004

---

## F-005 — Determine Measurement Availability

Responsible for determining whether acquired physiological measurements are available for downstream system functions.

Associated Capability Areas

- CA-005

---

## F-006 — Process Physiological Measurements

Responsible for transforming acquired physiological measurements into processed physiological measurements suitable for downstream system functions.

Associated Capability Areas

- CA-006

## F-007 — Provide Physiological Information

Responsible for producing physiological information from processed physiological measurements and their associated physiological measurement availability for downstream system functions.

Associated Capability Areas

- CA-007

---

# Functional Relationships

The major system functions cooperate to fulfill physiological monitoring.

```
Manage Monitoring Session
            │
            ▼
Manage Operational State
            │
            ▼
Manage Monitoring Configuration
            │
            ▼
Acquire Physiological Measurements
       ├────────────────────┐
       ▼                    ▼
Determine             Process
Measurement           Physiological
Availability          Measurements
       └────────────┬────────────┘
                    ▼
     Provide Physiological Information
```

The relationships shown represent functional dependencies rather than execution order. Individual functions may operate concurrently during normal system operation. A function may provide engineering information to multiple downstream functions, and downstream functions may depend upon engineering information produced by multiple upstream functions.

---

# Traceability

| Function | Capability Area |
|----------|-----------------|
| F-001 | CA-001 |
| F-002 | CA-002 |
| F-003 | CA-003 |
| F-004 | CA-004 |
| F-005 | CA-005 |
| F-006 | CA-006 |
| F-007 | CA-007 |


---

# Review Status

**Status:** Updated Following UN-001 Engineering Review
