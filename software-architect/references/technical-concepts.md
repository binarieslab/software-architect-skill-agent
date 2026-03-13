# Technical Concepts and Cross-Cutting Concerns

## Core Definition
Technical concepts are horizontal rules or solutions that apply to multiple building blocks. They ensure conceptual integrity and prevent redundant implementations of system-wide issues.

## Key Areas of Responsibility (R1)
Architects must identify, design, and implement horizontal solutions for the following:

### 1. Persistence
- **Storage Strategies:** Selection of relational, document-oriented, graph, or key/value storage.
- **Decoupling:** Ensuring data models are independent of their physical representation in databases or transmission protocols.
- **Qualities:** Managing consistency, performance, and robustness during data access.

### 2. Security
A minimum set of security concerns must be addressed:
- **Authentication:** Verifying the identity of users or systems.
- **Authorization:** Granting rights based on identity.
- **Confidentiality:** Protecting data from unauthorized access during transfer or storage.
- **Integrity:** Ensuring data has not been manipulated.
- **Availability:** Countering system malfunctions or attacks.

### 3. Error Handling
- **Classification:** Categorizing errors by severity and type (functional vs. technical).
- **Reaction:** Defining standard system responses, such as retries, fail-fast, or graceful degradation.
- **Technology:** Standardizing mechanisms like status codes or exceptions.

### 4. Infrastructure and Operations
- **Communication:** Standardizing protocols (synchronous/asynchronous) and message formats.
- **Observability:** Implementing consistent logging and caching strategies.
- **Deployment:** Managing how artifacts are mapped to nodes consistently.