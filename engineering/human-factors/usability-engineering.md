# Usability Engineering

## Overview

Usability Engineering is the systematic application of engineering principles to ensure that a system supports its intended users in accomplishing their goals safely, effectively, efficiently, and consistently.

Rather than focusing solely on user interface design, Usability Engineering considers every aspect of the interaction between people and the system, including workflows, feedback, controls, information presentation, physical interactions, and recovery from errors.

Usability is an engineered system characteristic rather than a cosmetic feature.

---

## Purpose

The purpose of Usability Engineering is to design systems that enable successful task completion while minimizing unnecessary effort, confusion, and use-related risk.

Effective Usability Engineering enables engineering teams to:

- Support successful task completion.
- Reduce opportunities for use error.
- Improve user confidence.
- Reduce unnecessary cognitive workload.
- Improve operational efficiency.
- Increase overall system effectiveness.

---

## Usability Engineering Principles

Effective Usability Engineering should be:

### User Centered

Design decisions should support the needs, capabilities, and expectations of intended users.

### Task Oriented

Interfaces and workflows should support how work is actually performed rather than how engineers expect it to be performed.

### Consistent

System behavior should be predictable across similar situations.

### Error Tolerant

The system should help prevent use errors where practical and support recovery when errors occur.

### Feedback Driven

The system should provide clear, timely, and meaningful feedback that helps users understand its current state and the results of their actions.

### Traceable

Usability decisions should remain traceable to User Research, Task Analysis, Use Scenarios, System Requirements, and verification activities.

---

## Applying Usability Engineering

Applying Usability Engineering typically includes:

1. Review User Research findings.
2. Review Task Analysis and Use Scenarios.
3. Identify opportunities to simplify user interaction.
4. Design workflows that support intended tasks.
5. Evaluate information presentation and feedback.
6. Consider error prevention and recovery.
7. Refine the design throughout system development.

Usability Engineering is iterative and should continue as the system evolves.

---

## Relationship to Other Artifacts

Usability Engineering transforms an understanding of users and their work into engineering decisions that shape the system.

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

Usability Engineering provides the design rationale that Human Factors Verification later evaluates.

---

## Reference Example

### Connected Physiological Monitor

During configuration of a physiological monitor, the system might:

- Display clear pairing status rather than a generic loading indicator.
- Warn the clinician before monitoring begins if electrode quality is poor.
- Provide confirmation when patient monitoring has successfully started.
- Guide recovery if the wireless connection is interrupted.

These design decisions reduce uncertainty, support efficient workflows, and help prevent use-related errors without requiring extensive user training.
