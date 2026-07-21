# Logical Architecture

## Purpose

The Logical Architecture allocates the functions of the Connected Physiological Monitor into logical subsystems.

Logical subsystems represent collections of related responsibilities that cooperate to satisfy the system requirements. They are implementation-independent and do not imply software modules, hardware components, processors, or deployment decisions.

The Logical Architecture provides the bridge between the Functional Architecture and later physical and software architectures.

---

# Logical Subsystems

```
Connected Physiological Monitor
│
├── Monitoring Session
├── Operational State
├── Monitoring Configuration
├── Physiological Measurement Acquisition
├── Physiological Measurement Availability
├── Physiological Measurement Processing
└── Physiological Information
```

---

# Logical Subsystem Descriptions

## LS-001 — Monitoring Session

Responsible for establishing, maintaining, and completing monitoring sessions.

Associated Functions

- F-001 Manage Monitoring Session

Associated Capability Areas

- CA-001

---

## LS-002 — Operational State

Responsible for governing operational behavior and state transitions of the Connected Physiological Monitor.

Associated Functions

- F-002 Manage Operational State

Associated Capability Areas

- CA-002

---

## LS-003 — Monitoring Configuration

Responsible for establishing, validating, and maintaining the monitoring configuration required before monitoring begins.

Associated Functions

- F-003 Manage Monitoring Configuration

Associated Capability Areas

- CA-003

---

## LS-004 — Physiological Measurement Acquisition

Responsible for acquiring physiological measurements from configured physiological sensors.

Associated Functions

- F-004 Acquire Physiological Measurements

Associated Capability Areas

- CA-004

---

## LS-005 — Physiological Measurement Availability

Responsible for determining and communicating the availability of physiological measurements.

Associated Functions

- F-005 Determine Measurement Availability

Associated Capability Areas

- CA-005

---

## LS-006 — Physiological Measurement Processing

Responsible for transforming acquired physiological measurements into processed physiological measurements for downstream system functions.

Associated Functions

- F-006 Process Physiological Measurements

Associated Capability Areas

- CA-006

## LS-007 — Physiological Information

Responsible for producing physiological information from processed physiological measurements and their associated physiological measurement availability for downstream system functions.

Associated Functions

- F-007 Provide Physiological Information

Associated Capability Areas

- CA-007

---

# Logical Relationships

The logical subsystems cooperate to implement physiological monitoring.

```
                        Monitoring Session
                                 │
                                 ▼
                        Operational State
                                 │
                                 ▼
                 Monitoring Configuration
                                 │
                                 ▼
              Physiological Measurement Acquisition
                        ├──────────────────────┐
                        ▼                      ▼
      Physiological Measurement      Physiological Measurement
             Availability                 Processing
                        └──────────┬───────────┘
                                   ▼
                    Physiological Information
```

The relationships shown represent logical dependencies between subsystems. They do not imply software calls, execution order, or implementation mechanisms.

---

# Traceability

| Logical Subsystem | Functional Architecture | Capability Area |
|-------------------|-------------------------|-----------------|
| LS-001 | F-001 | CA-001 |
| LS-002 | F-002 | CA-002 |
| LS-003 | F-003 | CA-003 |
| LS-004 | F-004 | CA-004 |
| LS-005 | F-005 | CA-005 |
| LS-006 | F-006 | CA-006 |
| LS-007 | F-007 | CA-007 |
---

# Review Status

**Status:** Baseline Approved
