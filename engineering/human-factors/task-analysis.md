# Task Analysis

## Overview

Task Analysis is the systematic process of understanding the activities users perform to accomplish their goals while interacting with a system.

Rather than focusing on system features, Task Analysis examines the work users must perform, the sequence of actions required, the information they need, and the conditions under which those activities occur.

Understanding user tasks helps engineering teams design systems that support real-world operation rather than idealized workflows.

---

## Purpose

The purpose of Task Analysis is to ensure that engineering decisions support effective task performance.

Effective Task Analysis enables engineering teams to:

- Understand user workflows.
- Identify task dependencies.
- Reveal opportunities to simplify operation.
- Identify potential sources of use error.
- Inform requirements and interface design.
- Support verification of intended use.

---

## Task Analysis Principles

Effective Task Analysis should be:

### Goal Oriented

Task Analysis begins with what users are trying to accomplish rather than how the current system performs the work.

### Context Aware

Tasks should be understood within their operational environment, including time pressures, distractions, and available resources.

### User Centered

Different user groups may perform different tasks using the same system. Their responsibilities should be analyzed independently.

### Complete

Task Analysis should include routine, infrequent, abnormal, and recovery activities where applicable.

### Traceable

Task Analysis should remain traceable to User Needs, System Requirements, interface design, and verification activities.

---

## Performing Task Analysis

Task Analysis typically includes the following activities:

1. Define the user group.
2. Identify the user's goals.
3. List the tasks required to achieve those goals.
4. Document the sequence and dependencies of each task.
5. Identify information, tools, and system interactions required.
6. Evaluate potential challenges and sources of error.
7. Document engineering insights that influence system design.

Task Analysis should be refined as workflows evolve throughout development.

---

## Relationship to Other Artifacts

Task Analysis translates User Research into a structured understanding of how work is performed.

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

---

## Reference Example

### Connected Physiological Monitor

A clinician configuring a physiological monitor may perform the following high-level tasks:

1. Verify patient identity.
2. Apply sensing electrodes.
3. Power on the device.
4. Pair the monitor with a gateway.
5. Confirm signal quality.
6. Begin patient monitoring.

Task Analysis asks engineering questions such as:

- Which steps are most error-prone?
- Which information is needed at each step?
- Can any steps be simplified or automated?
- What happens if a task is performed incorrectly or out of sequence?

The answers influence system requirements, interface design, alarms, workflow, and verification planning.
