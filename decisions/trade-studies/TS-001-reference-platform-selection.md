# Trade Study 001 — Reference Platform Selection

**Document ID:** TS-001  
**Status:** Approved

---

# Objective

Evaluate representative medical device product concepts using objective engineering criteria to identify the reference platform that best demonstrates disciplined medical device engineering throughout the complete product lifecycle.

The selected platform should maximize educational value while remaining achievable as a complete engineering case study.

---

# Executive Summary

Four representative medical device concepts were evaluated against weighted engineering criteria representing the primary engineering disciplines emphasized by this repository.

The evaluation considered:

- Systems Engineering
- Product Cybersecurity
- Human Factors & Usability
- Verification Engineering
- Project Scope
- Embedded Systems Engineering
- Overall Engineering Value

Although each candidate provides substantial engineering value, the **Connected Physiological Monitor** consistently provides the best balance between engineering breadth, project scope, and educational value.

Accordingly, it is selected as the Version 1 reference platform for the Medical Device Engineering Reference.

---

# Definition

A Trade Study is a structured engineering process used to compare multiple candidate solutions against objective evaluation criteria.

Trade studies improve engineering decision making by documenting:

- Evaluation criteria
- Weighting rationale
- Candidate assessments
- Engineering observations
- Decision rationale

The purpose of a trade study is not to identify the most technically complex solution, but to identify the solution that best satisfies the project's engineering objectives.

---

# Evaluation Process

```text
Project Vision
        │
        ▼
Engineering Objectives
        │
        ▼
Evaluation Criteria
        │
        ▼
Candidate Evaluation
        │
        ▼
Trade-offs
        │
        ▼
Recommendation
        │
        ▼
Engineering Decision
```

---

# Selection Criteria

| ID | Criterion | Weight | Why it Matters |
|----|-----------|:------:|----------------|
| C1 | Systems Engineering | **5** | Demonstrates requirements, architecture, interfaces, and traceability. |
| C2 | Product Cybersecurity | **5** | Demonstrates secure-by-design engineering. |
| C3 | Human Factors & Usability | **5** | Demonstrates workflow and usability engineering. |
| C4 | Verification Engineering | **5** | Demonstrates verification planning and objective evidence. |
| C5 | Project Scope | **5** | Supports successful completion of Version 1. |
| C6 | Embedded Systems Engineering | **4** | Demonstrates embedded architecture and firmware integration. |
| C7 | Engineering Case Study | **5** | Produces the strongest overall engineering narrative. |

---

# Scoring Scale

| Score | Meaning |
|-------:|---------|
| 5 | Excellent Fit |
| 4 | Strong Fit |
| 3 | Adequate Fit |
| 2 | Weak Fit |
| 1 | Poor Fit |

Weighted Score = Score × Weight

---

# Candidate Products

| ID | Candidate | Representative Example |
|----|-----------|------------------------|
| P1 | Connected Physiological Monitor | Multi-parameter vital signs monitor |
| P2 | Connected Patient Monitor | Bedside patient monitor |
| P3 | Connected Diagnostic Device | Point-of-care analyzer |
| P4 | Connected Wearable Health Monitor | Wearable ECG / Health Patch |

---

# Evaluation Results

| Criterion | Weight | P1 | P2 | P3 | P4 |
|-----------|:------:|:--:|:--:|:--:|:--:|
| Systems Engineering | 5 | 5 | 4 | 4 | 4 |
| Product Cybersecurity | 5 | 5 | 5 | 4 | 5 |
| Human Factors | 5 | 5 | 5 | 4 | 5 |
| Verification | 5 | 5 | 5 | 4 | 5 |
| Project Scope | 5 | 5 | 4 | 5 | 5 |
| Embedded Systems | 4 | 5 | 5 | 4 | 5 |
| Engineering Case Study | 5 | 5 | 4 | 4 | 4 |

---

# Weighted Results

| Candidate | Weighted Score |
|-----------|---------------:|
| Connected Physiological Monitor | **170** |
| Connected Wearable Health Monitor | **159** |
| Connected Patient Monitor | **155** |
| Connected Diagnostic Device | **145** |

> **Note:** Scores should be recalculated automatically if evaluation weights change.

---

# Engineering Observations

## Systems Engineering

The Connected Physiological Monitor naturally demonstrates the greatest breadth of systems engineering activities while maintaining a manageable system boundary.

---

## Product Cybersecurity

Continuous connectivity creates meaningful opportunities to demonstrate secure communications, authentication, trust boundaries, threat modeling, and cybersecurity verification.

---

## Human Factors

Continuous interaction between clinicians, patients, and healthcare providers creates rich opportunities for usability engineering and workflow analysis.

---

## Verification

The Connected Physiological Monitor supports verification planning across hardware, firmware, software, interfaces, cybersecurity, and system behavior.

---

## Project Scope

Although several candidates provide comparable engineering value, the Connected Physiological Monitor best balances engineering breadth with achievable implementation scope.

---

## Embedded Systems Engineering

The selected platform naturally integrates sensing, embedded firmware, communications, diagnostics, and system architecture without allowing firmware implementation to dominate the project.

---

# Trade-offs

## Connected Physiological Monitor

### Strengths

- Balanced engineering lifecycle
- Strong systems engineering
- Rich verification opportunities
- Meaningful cybersecurity
- Strong human factors
- Appropriate Version 1 scope

### Weaknesses

- Moderate architectural complexity
- Requires disciplined scope management

---

## Connected Patient Monitor

### Strengths

- Excellent systems integration
- Rich clinical workflows
- Strong verification

### Weaknesses

- Larger architectural scope
- Higher implementation complexity

---

## Connected Diagnostic Device

### Strengths

- Well-defined boundaries
- Clear engineering problem
- Easier implementation

### Weaknesses

- Narrower engineering breadth
- Less interaction between engineering disciplines

---

## Connected Wearable Health Monitor

### Strengths

- Modern connected architecture
- Strong embedded systems
- Mobile ecosystem

### Weaknesses

- Ecosystem scope expands rapidly
- Companion applications risk dominating the engineering narrative

---

# Recommendation

## Selected Reference Platform

# Connected Physiological Monitor

The Connected Physiological Monitor is selected as the Version 1 reference platform.

The decision is based on its ability to demonstrate:

- Systems Engineering
- Requirements Engineering
- Architecture
- Embedded Systems
- Product Cybersecurity
- Human Factors Engineering
- Verification Engineering
- Engineering Decision Making
- Requirements Traceability

within a realistic and achievable project scope.

---

# Engineering Rationale

The purpose of this repository is not to build the most sophisticated medical device.

Its purpose is to demonstrate disciplined engineering.

The Connected Physiological Monitor consistently provides the strongest balance between engineering breadth, project scope, educational value, and long-term extensibility.

Implementation exists to validate engineering decisions—not replace them.

---

# Final Decision

**Decision:** Approved

**Selected Platform**

**Connected Physiological Monitor**

This trade study establishes the Connected Physiological Monitor as the baseline reference platform for Version 1 of the Medical Device Engineering Reference repository.

Future reference platforms may be added using the same trade study methodology.

---

# Engineering Principles

- Engineering decisions should be objective and traceable.
- Product selection should be driven by engineering objectives rather than implementation preference.
- Trade studies should evaluate multiple viable alternatives before selecting a solution.
- Educational value is maximized when engineering breadth and project scope remain balanced.
- Implementation exists to validate engineering decisions, not replace them.

---

# Traceability

## Inputs

- Project Charter
- Repository Vision
- Engineering Methodology

## Outputs

- ADR-001 — Reference Platform Selection
- Connected Physiological Monitor Reference Platform
- Repository Roadmap

---

# Related Documents

- Project Charter
- Repository Vision
- ADR-001 — Reference Platform Selection
- Connected Physiological Monitor
