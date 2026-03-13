# Guidelines for Creating Architectural Views

Architectural views reduce complexity by focusing on essential elements aligned with specific stakeholder concerns.

## 1. Context View
- **Purpose:** Describes the system as a "black box" within its environment.
- **Content:** Identifies all external actors (users and adjacent systems) and their interfaces.
- **Sub-views:**
    - **Business Context:** Domain-specific neighbors and information exchange.
    - **Technical Context:** Technological relationships, protocols (e.g., HTTP, SMB), and device types.
- **Notation:** UML component diagrams or context diagrams.

## 2. Building-Block View
- **Purpose:** Shows the static structure of the system and source code organization.
- **Content:** A hierarchical decomposition into components, packages, or classes. 
- **Levels:**
    - **Black-box:** Hides internal details; shows only provided/required interfaces.
    - **White-box:** Reveals internal decomposition into sub-blocks and their relationships.
- **Notation:** UML component, package, or top-level class diagrams.

## 3. Runtime View
- **Purpose:** Illustrates the dynamic interaction between building block instances.
- **Content:** Documents key scenarios, including data flow and control flow during execution.
- **Notation:** Sequence diagrams, activity diagrams, flowcharts, or numbered lists.

## 4. Deployment View
- **Purpose:** Describes the technical infrastructure and physical environment.
- **Content:** Maps software artifacts (e.g., .jar, .war) to hardware nodes (servers, devices) and communication channels (networks).
- **Notation:** UML deployment diagrams using nodes and associations.

## Drawing Instructions for Agent
- **Preferred Tool:** Use **PlantUML** for generating diagrams.
- **Strategy:** Start with the Context View to define boundaries, then use Stepwise Refinement to decompose the Building-Block View.