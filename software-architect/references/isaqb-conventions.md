# Architectural Conventions and Rules

## Documentation Rules
- **Rule 1: Target Audience.** Tailor documentation detail to the specific group (e.g., developers vs. management).
- **Rule 2: Avoid Repetition.** Minimize redundancy to improve maintainability.
- **Rule 3: Use Standardized Templates.** Follow proven structures like arc42 to ensure consistency.
- **Rule 4: Justify Decisions.** Always provide written justifications for significant architectural choices to support comprehensibility.

## Design Conventions
- **Explicit over Implicit.** Proactively turn implicit assumptions into explicit, documented requirements to avoid misunderstandings.
- **Conceptual Integrity.** Ensure uniformity of solutions for similar problems across the system.
- **Coupling and Cohesion.** Aim for high cohesion within building blocks and loose, but functionally sufficient, coupling between them.
- **Twin Peaks.** Iteratively align requirements engineering and architectural design.

## Standard Views
- **Context View:** Describe external interfaces and the environment.
- **Building-Block View:** Document static structure and hierarchy.
- **Runtime View:** Show dynamic interactions and behavior.
- **Deployment View:** Map software to physical infrastructure.