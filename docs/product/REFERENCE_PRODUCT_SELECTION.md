# Reference Product Selection


| Section                | Status         |
| ---------------------- | -------------- |
| Objective              | ✅              |
| Selection Criteria     | ✅              |
| Evaluation Methodology | ✅              |
| Candidate Products     | ✅              |
| Evaluation Results     | 🟡 In Progress |
| Recommendation         | ⬜              |
| Final Decision         | ⬜              |


## Objective

The objective of this document is to evaluate candidate reference products using consistent engineering criteria and document the rationale for selecting the product that best demonstrates the engineering process defined in the Project Charter.

## Selection Criteria

| ID | Criterion             | Why it Matters                                             |
| -- | --------------------- | ---------------------------------------------------------- |
| C1 | Systems Engineering   | Drives requirements, architecture, and traceability.       |
| C2 | Product Cybersecurity | Creates meaningful security decisions.                     |
| C3 | Human Factors         | Requires user interaction and workflow considerations.     |
| C4 | Verification          | Can be realistically verified.                             |
| C5 | Project Scope         | Achievable by one engineer within a reasonable timeframe. |
| C6 | Embedded Development  | Requires enough firmware to support the engineering story.  |
| C7 | Engineering Demonstration | Clearly demonstrates engineering reasoning and tradeoffs.  |

# Evaluation Methodology

## Criterion Weights

| ID | Criterion | Weight |
|----|-----------|:------:|
| C1 | Systems Engineering | 5 |
| C2 | Product Cybersecurity | 5 |
| C3 | Human Factors | 5 |
| C4 | Verification | 5 |
| C5 | Project Scope | 5 |
| C6 | Embedded Development | 4 |
| C7 | Engineering Demonstration | 5 |

---

## Scoring Scale

| Score | Meaning |
|-------|---------|
| 1 | Poor Fit |
| 2 | Weak Fit |
| 3 | Adequate Fit |
| 4 | Strong Fit |
| 5 | Excellent Fit |

Weighted Score = Score × Weight

---

## Scoring Rubrics

### C1 – Systems Engineering

**Question**

> How well does this product naturally support systems engineering activities throughout its lifecycle?

| Score | Definition |
|-------|------------|
| 5 | Naturally requires substantial requirements development, architecture, interface definition, trade studies, traceability, risk management, and verification planning. |
| 4 | Requires most systems engineering activities but with lower complexity. |
| 3 | Requires some systems engineering but has limited architectural depth. |
| 2 | Minimal systems engineering required. |
| 1 | Mostly implementation-focused with little systems engineering value. |

Observations
- The Connected Physiological Monitor provides the richest standalone systems engineering problem.
- The Patient Monitor and Wearable Health Monitor both require substantial systems engineering, but for different reasons.
- The Connected Diagnostic Device remains a strong candidate but generally has a narrower systems context.
- All four candidates require meaningful systems engineering; none were eliminated by this criterion.

Lessons Learned
- Systems engineering value is driven by the interactions between subsystems rather than the complexity of any individual component.
- It is important to evaluate systems engineering independently of project scope to avoid biasing the results.
- A product does not need to be the most complex system to provide a valuable systems engineering case study.

### C2 – Product Cybersecurity

**Question**

> How well does this product create opportunities to demonstrate secure-by-design engineering throughout the product lifecycle?

| Score | Definition                                                                                                                                                                                                |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | Naturally requires identity, authentication, authorization, secure communications, secure update mechanisms, threat modeling, trust boundaries, and security verification as core engineering activities. |
| **4** | Requires several significant product cybersecurity activities but with fewer interacting trust boundaries or security mechanisms.                                                                         |
| **3** | Requires basic product security considerations but security is not a primary architectural driver.                                                                                                        |
| **2** | Requires only limited product security decisions.                                                                                                                                                         |
| **1** | Product cybersecurity plays a minimal role in the engineering process.                                                                                                                                    |

Observations

- Cybersecurity is a first-order engineering concern for all connected medical device categories.
- Continuous connectivity generally increases the number of trust boundaries and security considerations.
- Diagnostic devices present a narrower cybersecurity problem than continuous monitoring products.

Lessons Learned
- Product cybersecurity is driven more by system interactions than by the sensing technology itself.
- Separating cybersecurity from project scope helped produce more objective scores.

### C3 – Human Factors & Usability

**Question**

> How well does this product create opportunities to demonstrate human factors engineering and usability engineering throughout the product lifecycle?

Score Definitions
| Score | Definition                                                                                                                                                                    |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | Human factors are a primary engineering driver, requiring user research, workflow analysis, use-related risk analysis, iterative usability evaluation, and design validation. |
| **4** | Human factors significantly influence product design and verification but are not the dominant engineering driver.                                                            |
| **3** | Human factors contribute to the design but are limited in scope or complexity.                                                                                                |
| **2** | Human interaction is relatively simple and requires minimal human factors analysis.                                                                                           |
| **1** | Human factors have little influence on engineering decisions.                                                                                                                 |

Observations
- Continuous interaction with users significantly increases the importance of human factors engineering.
- Human factors challenges differ across product categories; complexity is driven by the user context rather than the product alone.
- The Connected Physiological Monitor, Patient Monitor, and Wearable Health Monitor all require extensive human factors and usability engineering, but for different reasons.
- The Connected Diagnostic Device remains a strong candidate but generally involves more focused workflows and fewer continuous user interactions.

Lessons Learned
- Human factors engineering extends far beyond interface design and includes workflow analysis, use-related risk management, training, and environmental considerations.
- Products intended for frequent or continuous interaction naturally create richer opportunities for usability engineering.
- Evaluating usability independently from implementation complexity helped produce more objective scores.

### C4 – Verification

**Question**

> How well does this product create opportunities to demonstrate verification engineering throughout the product lifecycle?

Score Definitions
| Score | Definition                                                                                                                                                                                                  |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | Naturally requires comprehensive verification planning, traceability, unit/integration/system testing, verification against requirements, and objective evidence across multiple subsystems and interfaces. |
| **4** | Requires substantial verification activities across several engineering disciplines but with fewer interacting systems or verification challenges.                                                          |
| **3** | Requires meaningful verification but with limited system complexity or traceability needs.                                                                                                                  |
| **2** | Verification is relatively straightforward and limited in scope.                                                                                                                                            |
| **1** | Minimal verification planning or evidence is required.                                                                                                                                                      |

Observations
The Connected Physiological Monitor, Patient Monitor, and Wearable Health Monitor all provide excellent opportunities to demonstrate verification engineering across the full product lifecycle.
The Connected Diagnostic Device remains a strong verification candidate but generally involves fewer continuously interacting subsystems and operational scenarios.
Verification complexity is driven by the interactions between subsystems and interfaces rather than the number of individual components.
All four candidates naturally support requirements traceability and objective verification evidence.

Lessons Learned
Effective verification engineering begins with well-defined requirements and traceability rather than test execution alone.
Products with multiple interacting subsystems create richer opportunities to demonstrate verification planning, integration testing, and system-level validation.
Verification strategy should be considered throughout product development rather than treated as a final project phase.
Verification engineering encompasses planning, execution, objective evidence, and traceability—not simply writing and running tests.

### C5 – Project Scope

**Question**

> How well does this product fit the intended scope of Version 1 while enabling a complete, high-quality engineering case study?

| Score | Definition                                                                                                                                                                                   |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | The product can realistically satisfy the Version 1 Definition of Done while demonstrating the complete engineering lifecycle without significant scope reduction or unnecessary complexity. |
| **4** | The product is achievable within Version 1 but requires disciplined scope management and selective deferral of lower-priority features.                                                      |
| **3** | The product is achievable only through significant scope reduction, limiting the completeness of the engineering case study.                                                                 |
| **2** | The product is unlikely to satisfy the Version 1 Definition of Done without major compromises or extended timelines.                                                                         |
| **1** | The product is not a realistic fit for Version 1 and is likely to prevent completion of a coherent engineering case study.                                                                   |

Observations
The Connected Physiological Monitor and Connected Wearable Health Monitor provide broad engineering coverage while remaining well aligned with the intended Version 1 scope.
The Connected Diagnostic Device offers the cleanest execution path because of its well-defined workflows and system boundaries.
The Connected Patient Monitor remains achievable but introduces substantially more inherent complexity that must be actively managed.
Clearly defining the system boundary has emerged as one of the strongest indicators of a product's suitability for Version 1.

Lessons Learned
Project scope should be evaluated against the project's Definition of Done, not the inherent complexity of the product.
A more ambitious product does not necessarily produce a better engineering case study.
Well-defined system boundaries reduce scope creep and improve the likelihood of completing a coherent engineering narrative.
Version 1 should optimize for demonstrating the engineering lifecycle rather than maximizing feature count.

### C6 – Embedded Development

**Question**

> How well does this product create opportunities to demonstrate embedded systems engineering while maintaining the project's focus on the overall engineering lifecycle?

| Score | Definition                                                                                                                                                                                                                                |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | Naturally supports meaningful embedded systems engineering across firmware architecture, hardware/software interfaces, communications, diagnostics, and lifecycle considerations without allowing implementation to dominate the project. |
| **4** | Provides substantial embedded development opportunities but with a narrower range of embedded engineering activities or greater reliance on external systems.                                                                             |
| **3** | Supports moderate embedded development but limits opportunities to demonstrate broader embedded systems engineering concepts.                                                                                                             |
| **2** | Embedded development is relatively limited or secondary to other engineering disciplines.                                                                                                                                                 |
| **1** | Embedded development plays only a minor role in the product.                                                                                                                                                                              |
Observations
The Connected Physiological Monitor, Patient Monitor, and Wearable Health Monitor all provide excellent opportunities to demonstrate embedded systems engineering, each emphasizing different aspects of the discipline.
The Connected Diagnostic Device remains a strong embedded platform but generally involves fewer real-time interactions and embedded subsystems.
Embedded systems engineering extends beyond firmware implementation to include hardware/software interfaces, system architecture, diagnostics, lifecycle planning, and verification.
Resource constraints and system interactions influence the nature of embedded engineering more than the physical size or complexity of the device.

Lessons Learned
Embedded systems engineering should be evaluated as an engineering discipline rather than by the volume of firmware or code complexity.
The strongest reference products integrate embedded development with systems engineering, cybersecurity, verification, and human factors rather than treating firmware as an isolated activity.
A well-defined embedded architecture provides greater educational and engineering value than highly optimized or feature-rich firmware.
Implementation should continue to validate engineering decisions rather than become the primary focus of the project.

---

## Candidate Products

| ID | Candidate | Summary | Representative Example |
|----|-----------|---------|------------------------|
| P1 | Connected Physiological Monitor | Acquires physiological measurements and securely communicates them for monitoring and analysis. | Multi-parameter vital signs monitor |
| P2 | Connected Patient Monitor | Aggregates data from multiple sources to present patient status, alarms, and device information. | Bedside patient monitor |
| P3 | Connected Diagnostic Device | Performs diagnostic measurements and presents results to support clinical decision making. | Point-of-care diagnostic analyzer |
| P4 | Connected Wearable Health Monitor | Continuously collects physiological data in a wearable form factor for remote monitoring. | Wearable ECG or health monitoring patch |


---

# Evaluation Results

### C1 – Systems Engineering

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **4** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor | **4** |  ✅    |

### C2 – Product Cybersecurity

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **5** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor | **5** | ✅    |

### C3 – Human Factors & Usability

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **5** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor | **5** |  ✅     |

### C4 – Verification

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **5** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor | **5** | ✅      |

### C5 – Project Scope

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **4** | ✅      |
| P3 – Connected Diagnostic Device       | **5** | ✅      |
| P4 – Connected Wearable Health Monitor | **5** | ✅      |

### C6 – Embedded Development

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **5** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor | **5** | ✅      |



---

# Recommendation

*(Pending.)*

---

# Final Decision

*(Pending.)*
