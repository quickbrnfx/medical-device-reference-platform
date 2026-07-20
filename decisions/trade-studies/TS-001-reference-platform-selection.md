# Trade Study 001 — Reference Platform Selection

**Document ID:** TS-001

**Status:** Approved

**Repository:** Medical Device Engineering Reference

---

# Objective

Evaluate representative medical device product concepts using objective engineering criteria to identify the reference platform that best demonstrates disciplined medical device engineering throughout the complete product lifecycle.

The selected platform should maximize educational value while remaining achievable as a complete engineering case study.

Rather than selecting the most technically sophisticated product, this trade study identifies the product that best supports the educational objectives, engineering methodology, and long-term vision of the Medical Device Engineering Reference repository.

---

# Executive Summary

Four representative connected medical device concepts were evaluated using a weighted engineering decision framework.

The evaluation intentionally emphasized engineering disciplines that are foundational to modern medical device development, including:

- Systems Engineering
- Requirements Engineering
- Product Cybersecurity
- Human Factors & Usability Engineering
- Verification Engineering
- Embedded Systems Engineering
- Engineering Decision Making

Each candidate demonstrated meaningful engineering value.

However, the Connected Physiological Monitor consistently provided the strongest balance between engineering breadth, project scope, educational value, and long-term extensibility.

Accordingly, the Connected Physiological Monitor is selected as the Version 1 reference platform.

---

# Definition

A Trade Study is a structured engineering activity used to compare multiple viable candidate solutions against objective evaluation criteria.

Rather than selecting a solution based on intuition or implementation preference, a trade study documents:

- evaluation criteria
- weighting rationale
- candidate assessments
- engineering observations
- trade-offs
- decision rationale

Trade studies improve engineering quality by making important decisions transparent, repeatable, and traceable.

---

# Engineering Question

> Which candidate medical device provides the strongest foundation for demonstrating disciplined medical device engineering throughout the complete engineering lifecycle?

---

# Scope

This trade study evaluates candidate reference platforms for Version 1 of the Medical Device Engineering Reference repository.

The evaluation considers engineering value rather than commercial viability or market competitiveness.

Specifically, this study evaluates each candidate's ability to demonstrate:

- Systems Engineering
- Requirements Engineering
- Architecture
- Embedded Systems Engineering
- Product Cybersecurity
- Human Factors Engineering
- Verification Engineering
- Engineering Decision Making
- Engineering Traceability

Implementation complexity alone is intentionally **not** considered a positive attribute.

---

# Evaluation Process

```text
Repository Vision
        │
        ▼
Engineering Objectives
        │
        ▼
Selection Criteria
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

| ID | Criterion | Why it Matters |
| -- | --------------------- | ---------------------------------------------------------- |
| C1 | Systems Engineering | Drives requirements, architecture, and traceability. |
| C2 | Product Cybersecurity | Creates meaningful security decisions. |
| C3 | Human Factors & Usability | Requires user interaction and workflow considerations. |
| C4 | Verification Engineering | Can be realistically verified. |
| C5 | Project Scope | Achievable by one engineer within a reasonable timeframe. |
| C6 | Embedded Systems Engineering | Requires enough firmware to support the engineering story. |
| C7 | Engineering Case Study | Clearly demonstrates engineering reasoning and trade-offs. |

---

# Evaluation Methodology

## Criterion Weights

| ID | Criterion | Weight |
|----|-----------|:------:|
| C1 | Systems Engineering | **5** |
| C2 | Product Cybersecurity | **5** |
| C3 | Human Factors & Usability | **5** |
| C4 | Verification Engineering | **5** |
| C5 | Project Scope | **5** |
| C6 | Embedded Systems Engineering | **4** |
| C7 | Engineering Case Study | **5** |

The weighting reflects the educational objectives of the repository rather than the inherent complexity of any individual product.

Disciplines that most strongly demonstrate the engineering lifecycle receive the highest weighting.

Embedded Systems Engineering receives a slightly lower weighting because implementation exists to support the engineering narrative rather than define it.

---

## Scoring Scale

| Score | Meaning |
|-------|---------|
| **5** | Excellent Fit |
| **4** | Strong Fit |
| **3** | Adequate Fit |
| **2** | Weak Fit |
| **1** | Poor Fit |

Weighted Score = Score × Weight

Higher scores indicate stronger alignment with the repository's engineering objectives rather than increased product complexity.

---

# Candidate Products

| ID | Candidate | Summary | Representative Example |
|----|-----------|---------|------------------------|
| P1 | Connected Physiological Monitor | Acquires physiological measurements and securely communicates them for monitoring and analysis. | Multi-parameter vital signs monitor |
| P2 | Connected Patient Monitor | Aggregates data from multiple sources to present patient status, alarms, and device information. | Bedside patient monitor |
| P3 | Connected Diagnostic Device | Performs diagnostic measurements and presents results to support clinical decision making. | Point-of-care diagnostic analyzer |
| P4 | Connected Wearable Health Monitor | Continuously collects physiological data in a wearable form factor for remote monitoring. | Wearable ECG or health monitoring patch |

---

# Evaluation Criteria

## C1 – Systems Engineering

### Engineering Question

> How well does this product naturally support systems engineering activities throughout its lifecycle?

---

### Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Naturally requires substantial requirements development, architecture, interface definition, trade studies, traceability, risk management, and verification planning. |
| **4** | Requires most systems engineering activities but with lower complexity. |
| **3** | Requires some systems engineering but has limited architectural depth. |
| **2** | Minimal systems engineering required. |
| **1** | Primarily implementation-focused with limited systems engineering value. |

---

### Engineering Observations

- The Connected Physiological Monitor provides the richest standalone systems engineering problem.
- The Connected Patient Monitor and Connected Wearable Health Monitor both require substantial systems engineering, although for different reasons.
- The Connected Diagnostic Device remains a strong candidate but generally presents a narrower systems context.
- All four candidates require meaningful systems engineering; none were eliminated by this criterion.

---

### Lessons Learned

- Systems engineering value is driven primarily by interactions between subsystems rather than the complexity of any individual component.
- Evaluating systems engineering independently of project scope helps reduce selection bias.
- A product does not need to be the most complex system to provide an excellent systems engineering case study.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **4** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **4** | ✅ |

---

# C2 – Product Cybersecurity

## Engineering Question

> How well does this product create opportunities to demonstrate secure-by-design engineering throughout the product lifecycle?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Naturally requires identity, authentication, authorization, secure communications, secure update mechanisms, threat modeling, trust boundaries, and cybersecurity verification as core engineering activities. |
| **4** | Requires several significant product cybersecurity activities but with fewer interacting trust boundaries or security mechanisms. |
| **3** | Requires basic cybersecurity considerations, but security is not a primary architectural driver. |
| **2** | Requires only limited cybersecurity decisions. |
| **1** | Product cybersecurity plays only a minor role in engineering activities. |

---

## Engineering Observations

- Cybersecurity is a first-order engineering concern for all connected medical device categories.
- Continuous connectivity generally increases the number of trust boundaries and cybersecurity considerations.
- The Connected Diagnostic Device presents a narrower cybersecurity problem than continuous monitoring products.

---

## Lessons Learned

- Product cybersecurity is driven more by system interactions than by sensing technology.
- Evaluating cybersecurity independently of project scope produced a more objective assessment.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **5** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **5** | ✅ |

---

# C3 – Human Factors & Usability

## Engineering Question

> How well does this product create opportunities to demonstrate human factors engineering and usability engineering throughout the product lifecycle?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Human factors are a primary engineering driver requiring user research, workflow analysis, use-related risk analysis, iterative usability evaluation, and design validation. |
| **4** | Human factors significantly influence product design and verification but are not the dominant engineering driver. |
| **3** | Human factors contribute to the design but are limited in scope or complexity. |
| **2** | Human interaction is relatively simple and requires minimal human factors analysis. |
| **1** | Human factors have little influence on engineering decisions. |

---

## Engineering Observations

- Continuous interaction with users significantly increases the importance of human factors engineering.
- Human factors challenges differ across product categories; complexity is driven by user context rather than the product itself.
- The Connected Physiological Monitor, Connected Patient Monitor, and Connected Wearable Health Monitor all require extensive human factors engineering, although for different reasons.
- The Connected Diagnostic Device remains a strong candidate but generally involves more focused workflows and fewer continuous user interactions.

---

## Lessons Learned

- Human factors engineering extends well beyond interface design and includes workflow analysis, use-related risk management, training, and environmental considerations.
- Products intended for frequent or continuous interaction naturally provide richer opportunities for usability engineering.
- Evaluating usability independently from implementation complexity produced more objective results.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **5** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **5** | ✅ |

---

# C4 – Verification Engineering

## Engineering Question

> How well does this product create opportunities to demonstrate verification engineering throughout the product lifecycle?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Naturally requires comprehensive verification planning, traceability, unit, integration, and system testing, objective evidence, and verification across multiple interacting subsystems. |
| **4** | Requires substantial verification across several engineering disciplines but with fewer interacting systems or verification challenges. |
| **3** | Requires meaningful verification but with limited system complexity or traceability needs. |
| **2** | Verification is relatively straightforward and limited in scope. |
| **1** | Minimal verification planning or objective evidence is required. |

---

## Engineering Observations

- The Connected Physiological Monitor, Connected Patient Monitor, and Connected Wearable Health Monitor all provide excellent opportunities to demonstrate verification engineering across the complete product lifecycle.
- The Connected Diagnostic Device remains a strong verification candidate but generally involves fewer continuously interacting subsystems and operational scenarios.
- Verification complexity is driven primarily by subsystem interactions rather than the number of individual components.
- All four candidates naturally support requirements traceability and objective verification evidence.

---

## Lessons Learned

- Effective verification engineering begins with well-defined requirements and traceability rather than test execution.
- Products with multiple interacting subsystems create richer opportunities for integration testing and system verification.
- Verification strategy should be developed throughout product development rather than treated as a final project phase.
- Verification engineering encompasses planning, execution, objective evidence, and traceability—not simply writing and executing tests.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **5** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **5** | ✅ |

# C5 – Project Scope

## Engineering Question

> How well does this product fit the intended scope of Version 1 while enabling a complete, high-quality engineering case study?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | The product can realistically satisfy the Version 1 Definition of Done while demonstrating the complete engineering lifecycle without significant scope reduction or unnecessary complexity. |
| **4** | The product is achievable within Version 1 but requires disciplined scope management and selective deferral of lower-priority features. |
| **3** | The product is achievable only through significant scope reduction, limiting the completeness of the engineering case study. |
| **2** | The product is unlikely to satisfy the Version 1 Definition of Done without major compromises or extended timelines. |
| **1** | The product is not a realistic fit for Version 1 and is likely to prevent completion of a coherent engineering case study. |

---

## Engineering Observations

- The Connected Physiological Monitor and Connected Wearable Health Monitor provide broad engineering coverage while remaining well aligned with the intended Version 1 scope.
- The Connected Diagnostic Device offers the cleanest execution path because of its well-defined workflows and system boundaries.
- The Connected Patient Monitor remains achievable but introduces substantially greater inherent complexity that must be actively managed.
- Clearly defining the system boundary emerged as one of the strongest indicators of a product's suitability for Version 1.

---

## Lessons Learned

- Project scope should be evaluated against the project's Definition of Done rather than the inherent complexity of the product.
- A more ambitious product does not necessarily produce a better engineering case study.
- Well-defined system boundaries reduce scope creep and improve the likelihood of completing a coherent engineering narrative.
- Version 1 should optimize for demonstrating the engineering lifecycle rather than maximizing feature count.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **4** | ✅ |
| **P3 – Connected Diagnostic Device** | **5** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **5** | ✅ |

---

# C6 – Embedded Systems Engineering

## Engineering Question

> How well does this product create opportunities to demonstrate embedded systems engineering while maintaining the project's focus on the overall engineering lifecycle?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Naturally supports meaningful embedded systems engineering across firmware architecture, hardware/software interfaces, communications, diagnostics, and lifecycle considerations without allowing implementation to dominate the project. |
| **4** | Provides substantial embedded development opportunities but with a narrower range of embedded engineering activities or greater reliance on external systems. |
| **3** | Supports moderate embedded development but limits opportunities to demonstrate broader embedded systems engineering concepts. |
| **2** | Embedded development is relatively limited or secondary to other engineering disciplines. |
| **1** | Embedded development plays only a minor role in the product. |

---

## Engineering Observations

- The Connected Physiological Monitor, Connected Patient Monitor, and Connected Wearable Health Monitor all provide excellent opportunities to demonstrate embedded systems engineering, each emphasizing different aspects of the discipline.
- The Connected Diagnostic Device remains a strong embedded platform but generally involves fewer real-time interactions and embedded subsystems.
- Embedded systems engineering extends beyond firmware implementation to include hardware/software interfaces, system architecture, diagnostics, lifecycle planning, and verification.
- Resource constraints and system interactions influence the nature of embedded systems engineering more than the physical size or complexity of the device.

---

## Lessons Learned

- Embedded systems engineering should be evaluated as an engineering discipline rather than by the volume of firmware or code complexity.
- The strongest reference products integrate embedded development with systems engineering, cybersecurity, verification, and human factors instead of treating firmware as an isolated activity.
- A well-defined embedded architecture provides greater educational value than highly optimized or feature-rich firmware.
- Implementation should continue to validate engineering decisions rather than become the primary focus of the project.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **5** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **5** | ✅ |

---

# C7 – Engineering Case Study

## Engineering Question

> How well does this product support demonstrating disciplined engineering from concept through verification in a way that aligns with the repository's vision, mission, and engineering principles?

---

## Score Definitions

| Score | Definition |
|-------|------------|
| **5** | Naturally supports a complete and well-balanced demonstration of the engineering lifecycle, enabling strong traceability between decisions, requirements, architecture, implementation, verification, and product cybersecurity without unnecessary complexity. |
| **4** | Supports most aspects of the engineering lifecycle but places greater emphasis on particular engineering disciplines or requires additional explanation to maintain a balanced engineering narrative. |
| **3** | Demonstrates several engineering disciplines well but provides limited opportunities to illustrate the complete engineering lifecycle. |
| **2** | Demonstrates isolated engineering concepts but does not naturally support a cohesive engineering case study. |
| **1** | Provides limited value for demonstrating the engineering process defined by the repository vision. |

---

## Engineering Observations

- The Connected Physiological Monitor provides the most balanced engineering narrative across the complete product lifecycle.
- The Connected Patient Monitor offers exceptional engineering depth but requires greater effort to maintain a focused engineering case study.
- The Connected Diagnostic Device provides a clean and approachable engineering story but demonstrates a narrower range of engineering interactions.
- The Connected Wearable Health Monitor offers a compelling modern engineering narrative but requires disciplined system boundary management to prevent ecosystem expansion from dominating the project.

---

## Lessons Learned

- A compelling engineering case study is defined by the quality and traceability of engineering decisions rather than the complexity of the product.
- The strongest educational artifacts balance breadth and depth across engineering disciplines instead of maximizing implementation complexity.
- A clear and defensible system boundary is essential for maintaining a coherent engineering narrative.
- Engineering documentation should explain why decisions were made, not simply record what was built.

---

## Evaluation Results

| Candidate | Score | Status |
|-----------|:----:|:------:|
| **P1 – Connected Physiological Monitor** | **5** | ✅ |
| **P2 – Connected Patient Monitor** | **4** | ✅ |
| **P3 – Connected Diagnostic Device** | **4** | ✅ |
| **P4 – Connected Wearable Health Monitor** | **4** | ✅ |

# Weighted Evaluation Summary

The weighted evaluation provides a quantitative comparison of the candidate reference platforms using the engineering criteria defined in this trade study.

| Criterion | Weight | P1 | P2 | P3 | P4 |
|-----------|:------:|:--:|:--:|:--:|:--:|
| Systems Engineering | 5 | 25 | 20 | 20 | 20 |
| Product Cybersecurity | 5 | 25 | 25 | 20 | 25 |
| Human Factors & Usability | 5 | 25 | 25 | 20 | 25 |
| Verification Engineering | 5 | 25 | 25 | 20 | 25 |
| Project Scope | 5 | 25 | 20 | 25 | 25 |
| Embedded Systems Engineering | 4 | 20 | 20 | 16 | 20 |
| Engineering Case Study | 5 | 25 | 20 | 20 | 20 |
| **Total** | | **170** | **155** | **141** | **160** |

> **Note:** Weighted scores support the engineering recommendation but are not intended to replace engineering judgment. They provide an objective framework for comparing alternatives while preserving the need for professional evaluation of trade-offs.

---

# Overall Findings

## Purpose

The purpose of this evaluation was not to identify the most technically complex product.

Instead, the objective was to identify the product that best supports the vision of the Medical Device Engineering Reference repository by demonstrating disciplined engineering across the complete product lifecycle.

The selected reference platform should enable a coherent engineering case study spanning systems engineering, requirements engineering, architecture, embedded systems engineering, product cybersecurity, human factors engineering, verification engineering, and engineering decision making.

---

## Engineering Breadth

All four candidate products demonstrated meaningful engineering value.

The Connected Physiological Monitor, Connected Patient Monitor, and Connected Wearable Health Monitor consistently provided broad opportunities to demonstrate systems engineering, product cybersecurity, human factors engineering, verification engineering, and embedded systems engineering.

The Connected Diagnostic Device also demonstrated strong engineering value, although within a narrower operational context.

No candidate was eliminated due to insufficient engineering depth.

---

## Project Alignment

The most significant differentiation between candidates emerged when evaluating alignment with the objectives of this repository rather than intrinsic product complexity.

Criteria such as **Project Scope** and **Engineering Case Study** emphasized the importance of producing a complete and coherent engineering narrative instead of maximizing implementation complexity.

This reinforces one of the repository's guiding principles:

> **Implementation exists to validate engineering decisions, not replace them.**

---

## System Boundaries

A recurring theme throughout the evaluation was the importance of defining a clear Version 1 system boundary.

Products with naturally constrained boundaries were easier to envision as complete engineering case studies.

Products that naturally expand into broader ecosystems remained excellent engineering candidates but require significantly greater scope management to prevent unnecessary complexity from overshadowing the educational objectives of the repository.

---

## Engineering Narrative

The evaluation demonstrated that the strongest reference platform is not necessarily the one with the greatest technical complexity.

Instead, the strongest platform provides a balanced opportunity to demonstrate engineering decisions across multiple disciplines while maintaining a coherent and traceable engineering story from concept through verification.

Engineering documentation should communicate not only what decisions were made, but why those decisions were made and how they influenced subsequent engineering activities.

---

## Trade-offs

Each candidate demonstrated distinct engineering strengths.

| Candidate | Primary Strength |
|-----------|------------------|
| Connected Physiological Monitor | Balanced representation of the complete engineering lifecycle |
| Connected Patient Monitor | Systems integration and complex clinical workflows |
| Connected Diagnostic Device | Well-defined scope and focused engineering problem |
| Connected Wearable Health Monitor | Modern connected embedded systems and mobile integration |

No objectively superior medical device emerged from the evaluation.

Rather, each candidate represented a different balance of engineering priorities.

The Connected Physiological Monitor most closely aligned with the educational objectives, engineering philosophy, and long-term vision of the repository.

---

## Summary

The evaluation demonstrated that successful reference platforms are defined less by technical complexity than by their ability to communicate disciplined engineering.

The Connected Physiological Monitor consistently provided the strongest balance between engineering breadth, project scope, educational value, and long-term extensibility.

These findings provide the engineering basis for the recommendation documented below.

---

# Recommendation

## Selected Reference Platform

**Connected Physiological Monitor**

---

## Recommendation

Based on the engineering evaluation documented in this trade study, the **Connected Physiological Monitor** is recommended as the Version 1 reference platform for the Medical Device Engineering Reference repository.

While each candidate demonstrated substantial engineering value, the Connected Physiological Monitor consistently provided the strongest balance between:

- Systems Engineering
- Requirements Engineering
- System Architecture
- Embedded Systems Engineering
- Product Cybersecurity
- Human Factors Engineering
- Verification Engineering
- Engineering Decision Making
- Requirements Traceability

without allowing any individual engineering discipline to dominate the project.

The selected platform naturally supports a complete engineering lifecycle while remaining appropriately scoped for Version 1.

---

## Alternatives Considered

### Connected Patient Monitor

Provides exceptional opportunities to demonstrate systems integration, alarm management, and complex clinical workflows.

However, these capabilities substantially increase project scope and make it more difficult to maintain a focused engineering narrative for Version 1.

---

### Connected Diagnostic Device

Provides a well-defined engineering problem with clear system boundaries and manageable implementation scope.

Although it represents an excellent engineering project, it demonstrates a narrower range of engineering interactions than the selected platform.

---

### Connected Wearable Health Monitor

Provides an outstanding opportunity to demonstrate modern embedded systems engineering, wireless communications, low-power design, and mobile ecosystem integration.

However, it requires significantly greater discipline in defining Version 1 system boundaries to prevent companion applications and cloud infrastructure from becoming the dominant engineering focus.

---

# Engineering Rationale

The objective of this repository is not to build the most feature-rich medical device.

Its purpose is to demonstrate disciplined engineering.

The Connected Physiological Monitor consistently provides the strongest balance between engineering breadth, project scope, educational value, and long-term maintainability.

Most importantly, it naturally demonstrates the engineering philosophy adopted throughout this repository:

> **Implementation exists to validate engineering decisions—not replace them.**

---

# Final Decision

**Decision ID:** DEC-001

**Decision:** Approved

The **Connected Physiological Monitor** is adopted as the Version 1 reference platform for the Medical Device Engineering Reference repository.

Future reference platforms should be evaluated using the same trade study methodology to ensure engineering consistency and objective decision making.

---

# Engineering Principles

- Engineering decisions should be objective, documented, and traceable.
- Trade studies should compare multiple viable alternatives before selecting a preferred solution.
- Product selection should be driven by engineering objectives rather than implementation preference.
- Engineering breadth is more valuable than implementation complexity when developing educational reference platforms.
- Clear system boundaries improve engineering quality, reduce scope creep, and strengthen verification.
- Implementation exists to validate engineering decisions—not replace them.

---

# Traceability

## Inputs

- Repository Vision
- Project Charter
- Engineering Methodology

## Outputs

- DEC-001 — Reference Platform Selection
- ADR-001 — Repository Architecture
- Connected Physiological Monitor Reference Platform
- Repository Roadmap

---

# Related Documents

- Repository Vision
- Project Charter
- Engineering Methodology
- DEC-001 — Reference Platform Selection
- ADR-001 — Repository Architecture
- Connected Physiological Monitor
