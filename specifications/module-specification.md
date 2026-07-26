# Module Specification

## Purpose

This document defines the standard structure that every AAF audit module must follow.

The goal is to ensure consistency, maintainability and interoperability across all modules.

---

# Module Identity

Every module must have:

- Name
- Version
- Category
- Description

---

# Objective

Each module must define a single and well-defined objective.

A module should never perform responsibilities that belong to another module.

---

# Inputs

Every module must clearly define:

- Required inputs
- Optional inputs
- Expected format
- Validation requirements

---

# Outputs

Every module must return structured outputs.

Outputs should be predictable and reusable by subsequent modules.

---

# Responsibilities

Every module must explicitly document:

- What it analyzes
- What it does not analyze
- Which engineering domain it belongs to

---

# Analysis Process

Every module should follow these steps:

1. Understand the available information.
2. Validate the provided context.
3. Execute the analysis.
4. Collect evidence.
5. Produce findings.
6. Generate recommendations.

---

# Completion Criteria

A module is considered complete when:

- All analysis steps have been executed.
- Findings have been documented.
- Evidence has been collected.
- Recommendations have been generated.

---

# Dependencies

Modules may consume outputs produced by previous modules.

Modules must never depend on future modules.

---

# Limitations

Modules must clearly communicate when:

- Information is missing.
- Context is incomplete.
- Additional verification is required.

---

# Future Compatibility

Every module should be designed to evolve independently without breaking existing modules.
