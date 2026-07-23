# Methodology Findings

This document records observations made while developing the Medical Device Reference Platform engineering methodology.

Methodology findings capture lessons learned during engineering activities. They are not approved process changes. Findings remain open until sufficient evidence exists to either incorporate the observation into the engineering methodology or reject it.

---

# MF-001 — Capability Candidate Evaluation

**Status:** Open

## Background

During Capability Review for User Need UN-002, multiple candidate Capability Areas were evaluated before establishing the proposed capability model.

The review determined that documenting only the final Capability Areas obscured the engineering reasoning that led to acceptance or rejection of candidate capabilities.

## Observation

Capability Reviews currently record the approved Capability Areas but do not explicitly document Capability Areas that were evaluated and rejected.

As a result, future reviewers cannot easily determine:

- Which alternatives were considered
- Why candidate capabilities were rejected
- How the final capability baseline was established

## Recommendation

Future Capability Review templates should include a **Capability Evaluation** section documenting all candidate Capability Areas considered during decomposition.

Each candidate should include:

- Candidate Capability Area
- Decision (Accepted, Rejected, Deferred)
- Engineering rationale supporting the decision

## Potential Benefits

- Improves engineering traceability.
- Documents decomposition rationale.
- Prevents repeated evaluation of previously rejected capabilities.
- Improves review transparency.
- Better supports future methodology development.

## Decision

No methodology change at this time.

This finding will remain open until additional Capability Reviews provide sufficient evidence to determine whether the Capability Review template should be updated.
