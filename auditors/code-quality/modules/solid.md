# SOLID Principles Module

## Overview

Evaluates compliance with the SOLID principles of object-oriented design.

---

## Objective

Identify violations that reduce maintainability, extensibility and testability.

---

## What to Inspect

Inspect:

- Single Responsibility Principle (SRP)
- Open/Closed Principle (OCP)
- Liskov Substitution Principle (LSP)
- Interface Segregation Principle (ISP)
- Dependency Inversion Principle (DIP)

---

## Common Findings

- Classes with multiple responsibilities
- Excessive inheritance
- Large interfaces
- Concrete dependencies
- Violated abstractions

---

## Severity

High for major SOLID violations.

Medium for architectural improvements.

Low for isolated design issues.

---

## Expected Evidence

- Class hierarchy
- Interfaces
- Dependency graph
- Business logic organization

---

## Recommendations

Separate responsibilities.

Depend on abstractions.

Split large interfaces.

Reduce inheritance complexity.

Improve object-oriented design.

---

## References

- SOLID Principles
- Robert C. Martin
