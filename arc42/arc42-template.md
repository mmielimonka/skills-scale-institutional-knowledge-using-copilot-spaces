# arc42 Template — [Project Name]

> **How to use this template:**  
> Copy this file into your project repository. Fill in each section as you progress through the project lifecycle. Sections can be marked *N/A* or *TBD* when not yet applicable. Delete this notice when the document is in active use.

---

## 1. Introduction and Goals

### 1.1 Requirements Overview
*Summarize the most important functional requirements and quality goals. Reference the product backlog, one-pager, or requirements document as appropriate.*

### 1.2 Quality Goals
*List the top 3–5 quality attributes (e.g., performance, security, maintainability) and their priority for this system.*

| Priority | Quality Goal | Motivation |
|---|---|---|
| 1 | | |
| 2 | | |

### 1.3 Stakeholders
*Who has an interest in the architecture of this system?*

| Role / Name | Expectation |
|---|---|
| | |

---

## 2. Architecture Constraints

*List technical, organizational, or regulatory constraints that restrict architectural choices.*

| Constraint | Background / Rationale |
|---|---|
| | |

---

## 3. System Scope and Context

### 3.1 Business Context
*Describe the system's environment: which external actors (users, systems, organizations) interact with the system, and what data flows in/out.*

*(Diagram or table recommended)*

### 3.2 Technical Context
*Map the business context to the technical channels and interfaces used (e.g., REST APIs, message queues, databases).*

---

## 4. Solution Strategy

*Summarize the key architectural decisions and strategies that address the most important goals and constraints.*

- **Technology decisions:** (e.g., programming language, frameworks, platforms)
- **Top-level decomposition:** (e.g., microservices, monolith, layered architecture)
- **Approaches to achieve quality goals:** (e.g., caching for performance, RBAC for security)

---

## 5. Building Block View

### 5.1 Level 1 — Whitebox Overall System
*Describe the main components (black boxes) of the system and their responsibilities.*

| Component | Responsibility |
|---|---|
| | |

### 5.2 Level 2 — Whitebox [Component Name]
*Zoom into the most important or complex component from Level 1.*

*(Add more levels as needed)*

---

## 6. Runtime View

*Describe the most important runtime scenarios: how the building blocks interact to deliver key use cases.*

### Scenario 1: [Name]
*Describe the sequence of interactions (text or sequence diagram).*

### Scenario 2: [Name]

---

## 7. Deployment View

### 7.1 Infrastructure Level 1
*Describe how the system is deployed: environments (dev, staging, production), compute, networking.*

*(Diagram or table recommended)*

### 7.2 Infrastructure Level 2 — [Environment Name]
*Add detail for each environment as needed.*

---

## 8. Cross-Cutting Concepts

*Describe solution approaches that apply to multiple parts of the system.*

| Concept | Description |
|---|---|
| **Security / Authentication** | |
| **Logging & Monitoring** | |
| **Error Handling** | |
| **Configuration Management** | |
| **Testing Strategy** | |
| **Internationalization** | |

*(Add or remove rows as relevant)*

---

## 9. Architecture Decisions

*Record significant architectural decisions (ADRs) here or link to a separate ADR log.*

| ID | Decision | Status | Rationale |
|---|---|---|---|
| ADR-001 | | Accepted / Proposed / Deprecated | |

---

## 10. Quality Requirements

### 10.1 Quality Tree
*Refine the quality goals from Section 1.2 into measurable scenarios.*

### 10.2 Quality Scenarios
*Describe specific, testable quality scenarios.*

| ID | Quality Goal | Scenario | Priority |
|---|---|---|---|
| QS-001 | | | High / Medium / Low |

---

## 11. Risks and Technical Debt

*List known risks and areas of technical debt that may affect future work.*

| ID | Description | Impact | Status |
|---|---|---|---|
| R-001 | | High / Medium / Low | Open / Mitigated |

---

## 12. Glossary

*Define domain-specific and technical terms used in this document.*

| Term | Definition |
|---|---|
| | |

---

*Template based on [arc42](https://arc42.org) — licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).*
