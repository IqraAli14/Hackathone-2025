# Speckit-Plus Constitution
<!-- Example: Spec Constitution, TaskFlow Constitution, etc. -->

## Core Principles

### I. Full-Stack Development
<!-- Example: I. Library-First -->
Speckit-Plus follows a full-stack approach with both frontend (Docusaurus-based documentation) and backend (FastAPI-powered chatbot) components that work cohesively to deliver the Physical AI & Humanoid Robotics textbook experience.
<!-- Example: Every feature starts as a standalone library; Libraries must be self-contained, independently testable, documented; Clear purpose required - no organizational-only libraries -->

### II. Modular Architecture
<!-- Example: II. CLI Interface -->
The system is built with modular components that can function independently – Frontend handles documentation presentation, while Backend manages AI interactions and book content processing.
<!-- Example: Every library exposes functionality via CLI; Text in/out protocol: stdin/args → stdout, errors → stderr; Support JSON + human-readable formats -->

### III. Test-First (NON-NEGOTIABLE)
<!-- Example: III. Test-First (NON-NEGOTIABLE) -->
All features must be tested before implementation; TDD is mandatory: Tests written → User approved → Tests fail → Then implement; Red-Green-Refactor cycle strictly enforced.
<!-- Example: TDD mandatory: Tests written → User approved → Tests fail → Then implement; Red-Green-Refactor cycle strictly enforced -->

### IV. Integration Testing
<!-- Example: IV. Integration Testing -->
Focus areas requiring integration tests: Frontend-backend communication, AI model interactions, Book content retrieval and processing, User input handling.
<!-- Example: Focus areas requiring integration tests: New library contract tests, Contract changes, Inter-service communication, Shared schemas -->

### V. AI Integration
<!-- Example: V, VI. Versioning & Breaking Changes, VII. Simplicity -->
The system integrates advanced AI capabilities for natural language processing and response generation, ensuring seamless interactions with the Physical AI & Humanoid Robotics textbook content.
<!-- Example: Text I/O ensures debuggability; Structured logging required; Or: MAJOR.MINOR.BUILD format; Or: Start simple, YAGNI principles -->

### VI. Education-First Design

All features and system components prioritize educational value and accessibility, ensuring the Physical AI & Humanoid Robotics content is delivered in a manner that enhances learning outcomes and user engagement.
<!-- Example: Text I/O ensures debuggability; Structured logging required; Or: MAJOR.MINOR.BUILD format; Or: Start simple, YAGNI principles -->

## Backend Technologies
<!-- Example: Additional Constraints, Security Requirements, Performance Standards, etc. -->

The backend utilizes FastAPI for robust API development, integrates with OpenAI models for AI responses, and incorporates CORS middleware for secure frontend communication.
<!-- Example: Technology stack requirements, compliance standards, deployment policies, etc. -->

## Frontend Technologies
<!-- Example: Development Workflow, Review Process, Quality Gates, etc. -->

The frontend leverages Docusaurus for documentation delivery, React for dynamic UI components, and modern JavaScript/TypeScript for responsive user interactions.
<!-- Example: Code review requirements, testing gates, deployment approval process, etc. -->

## Governance
<!-- Example: Constitution supersedes all other practices; Amendments require documentation, approval, migration plan -->

This constitution governs all development activities in Speckit-Plus. All contributions must align with these principles, undergo peer review, and maintain the high standards for AI integration and educational content delivery.
<!-- Example: All PRs/reviews must verify compliance; Complexity must be justified; Use [GUIDANCE_FILE] for runtime development guidance -->

**Version**: 1.0.0 | **Ratified**: 2025-01-01 | **Last Amended**: 2025-12-17
<!-- Example: Version: 2.1.1 | Ratified: 2025-06-13 | Last Amended: 2025-07-16 -->
