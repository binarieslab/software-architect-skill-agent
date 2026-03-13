# Architecture Analysis and Assessment

## Primary Objectives
- **Risk Identification:** Uncovering technical risks or weaknesses early in the lifecycle.
- **Requirement Verification:** Determining if the design actually fulfills the stated functional and quality goals.
- **Conformance Check:** Ensuring the source code and implementation align with architectural decisions.

## Evaluation Methods (R1)
- **Scenario-Based Analysis:** Using stakeholder-driven user stories to derive requirements and define measurement methods.
- **ATAM (Architecture Trade-off Analysis Method):** A systematic qualitative method focusing on three categories: **Risks**, **Sensitivity Points**, and **Trade-offs** (Compromises).
- **Quantitative Measurement:** Tracking runtime behaviour (e.g., latency, memory usage) and architecture metrics.
- **Conformance Evaluation:** Assessing design-to-code alignment through code reviews or tool-supported static analysis.

## Critical Metrics to Monitor (R1)
- **Coupling & Cohesion:** Degrees of inbound (afferent) and outbound (efferent) dependencies.
- **Complexity:** Measuring linearly independent paths via Cyclomatic Complexity.
- **Code Health:** Lines of code (LOC), error clusters in building blocks, and change rates.

## Evaluation Artifacts
- Quality trees and scenarios.
- Architecture models and diagrams.
- Source code, metrology logs, and test results.