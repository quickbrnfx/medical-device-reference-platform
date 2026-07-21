# Operational State Model

**Status:** Baseline

---

# Objective

Define the operational states of the Connected Physiological Monitor and the allowable transitions between those states during normal and abnormal operation.

This model establishes the operational behavior of the system and serves as the basis for deriving System Requirements, Functional Architecture, Risk Analysis, and Verification activities.

---

# Engineering Question

> What operational states can the Connected Physiological Monitor occupy, and how does it transition between them during normal and abnormal operation?

---

# State Model

```text
                 +----------------+
                 | Initializing   |
                 +----------------+
                        |
                Initialization Successful
                        |
                        ▼
                 +----------------+
                 |     Ready      |
                 +----------------+
                        |
               Monitoring Session Started
                        |
                        ▼
                 +----------------+
                 |   Monitoring   |
                 +----------------+
                        |
              Monitoring Session Completed
                        |
                        ▼
                 +----------------+
                 |   Finalizing   |
                 +----------------+
                        |
             Finalization Successful
                        |
                        ▼
                 +----------------+
                 |     Ready      |
                 +----------------+

Fault Transitions
-----------------

Initializing ─────────────► Fault
Ready ────────────────────► Fault
Monitoring ───────────────► Fault
Finalizing ───────────────► Fault

Recovery

Fault
  │
  ▼
Initializing
```

---

# Operational States

## Initializing

The system performs the initialization activities required to establish a known operational baseline.

Representative activities include:

- Initialize hardware resources
- Initialize software components
- Perform system self-tests
- Establish communication with connected peripherals
- Verify readiness for operation

Successful completion of initialization transitions the system to the **Ready** state.

---

## Ready

The system is capable of beginning a monitoring session but is not actively monitoring a patient.

Characteristics include:

- No active monitoring session
- No physiological data acquisition
- Ready to accept operator commands
- Capable of transitioning to the Monitoring state

---

## Monitoring

The system is actively performing physiological monitoring for an active monitoring session.

Representative activities include:

- Physiological data acquisition
- Physiological data processing
- Presentation of physiological information
- Monitoring of system health
- Monitoring of connected sensors

---

## Finalizing

The system performs the activities required to safely conclude a monitoring session before returning to the Ready state.

Representative activities include:

- Terminate physiological data acquisition
- Complete the monitoring session
- Finalize session records
- Release monitoring resources

Successful completion transitions the system to the **Ready** state.

---

## Fault

The system has detected a condition that prevents continued normal operation.

Characteristics include:

- Normal monitoring is suspended
- Fault condition is indicated
- Recovery requires system re-initialization

The system shall not return directly from the Fault state to the Ready or Monitoring states.

---

# Valid State Transitions

| From | To | Description |
|------|----|-------------|
| Initializing | Ready | Initialization completed successfully |
| Ready | Monitoring | Monitoring session initiated |
| Monitoring | Finalizing | Monitoring session completed |
| Finalizing | Ready | Finalization completed successfully |
| Initializing | Fault | Fault detected during initialization |
| Ready | Fault | Fault detected while ready |
| Monitoring | Fault | Fault detected during monitoring |
| Finalizing | Fault | Fault detected during finalization |
| Fault | Initializing | Recovery initiated |

---

# Invalid State Transitions

The following transitions are not permitted by the operational state model.

- Ready → Finalizing
- Initializing → Monitoring
- Initializing → Finalizing
- Monitoring → Ready
- Finalizing → Monitoring
- Fault → Ready
- Fault → Monitoring
- Fault → Finalizing

---

# Engineering Implications

The Operational State Model establishes the allowable system behavior throughout the operational lifecycle.

This model provides the foundation for:

- System Requirements
- Functional Architecture
- Risk Analysis
- Alarm Management
- Cybersecurity Engineering
- Verification Planning

---

# Traceability

## Inputs

- Operational Context
- User Needs

## Outputs

- System Requirements
- Functional Architecture
- Risk Analysis
- Verification Strategy
