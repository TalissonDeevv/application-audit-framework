# Architecture Quality Module

## Overview

Evaluates whether the project architecture is organized, modular and maintainable.

---

## Objective

Identify architectural problems that reduce maintainability or scalability.

---

## What to Inspect

Inspect:

- Layer separation
- Responsibility boundaries
- Coupling
- Cohesion
- Dependency direction
- Module organization

---

## Common Findings

- Tight coupling
- Circular dependencies
- Layer violations
- Business logic mixed with infrastructure
- Poor modularization

---

## Severity

High when architecture prevents maintainability.

Medium when improvements are recommended.

Low for minor inconsistencies.

---

## Expected Evidence

- Folder structure
- Imports
- Dependencies
- Module organization

---

## Recommendations

Improve separation of concerns.

Reduce coupling.

Increase cohesion.

Respect architectural boundaries.

---

## References

- Clean Architecture
- Hexagonal Architecture
