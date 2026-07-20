# Use Scenarios

## Overview

Use Scenarios describe representative interactions between users and a system as they work toward specific goals within realistic operational contexts.

Rather than documenting isolated tasks, Use Scenarios illustrate how tasks, decisions, system behavior, and environmental conditions combine during actual system use.

Use Scenarios provide engineering teams with a shared understanding of intended system operation and help evaluate whether the system supports users under realistic conditions.

---

## Purpose

The purpose of Use Scenarios is to connect user tasks with real-world operational contexts.

Effective Use Scenarios enable engineering teams to:

- Understand complete user workflows.
- Evaluate interactions between users and the system.
- Identify operational challenges.
- Reveal opportunities for improved usability.
- Support requirements, architecture, and interface design.
- Inform verification planning.

---

## Use Scenario Principles

Effective Use Scenarios should be:

### Representative

Scenarios should reflect realistic situations that intended users are likely to encounter.

### Context Rich

Scenarios should include relevant environmental conditions, operational constraints, and system states.

### Goal Focused

Each scenario should describe how a user attempts to accomplish a meaningful objective.

### Comprehensive

A complete set of scenarios should consider normal operation, abnormal situations, recovery activities, and maintenance where appropriate.

### Traceable

Scenarios should remain traceable to User Research, Task Analysis, User Needs, and verification activities.

---

## Developing Use Scenarios

Developing Use Scenarios typically includes:

1. Select the intended user group.
2. Define the user's objective.
3. Describe the operational environment.
4. Describe the sequence of interactions between the user and the system.
5. Identify decision points and potential errors.
6. Describe the expected system responses.
7. Capture engineering insights that influence system design.

Use Scenarios should evolve alongside system requirements and architecture as the product matures.

---

## Relationship to Other Artifacts

Use Scenarios apply the results of User Research and Task Analysis to realistic operational situations.

```text
User Research
       │
       ▼
Task Analysis
       │
       ▼
Use Scenarios
       │
       ▼
Usability Engineering
       │
       ▼
Human Factors Verification
```

Use Scenarios provide an engineering bridge between understanding user work and designing a system that effectively supports that work.

---

## Reference Example

### Connected Physiological Monitor

**Scenario:** A nurse admits a patient to a telemetry unit.

The nurse:

1. Retrieves a prepared monitor.
2. Verifies the patient's identity.
3. Applies electrodes.
4. Powers on the device.
5. Confirms successful pairing with the central monitoring station.
6. Verifies acceptable signal quality.
7. Begins continuous monitoring.

During the scenario, engineering questions include:

- What information does the nurse need at each step?
- What happens if pairing fails?
- How does the system indicate poor electrode contact?
- Can recovery be completed without restarting the entire workflow?

These questions influence requirements, architecture, interface behavior, alarm design, and verification activities.
