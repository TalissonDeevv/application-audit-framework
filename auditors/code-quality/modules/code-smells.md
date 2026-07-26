# Code Smells Module

## Overview

Identifies patterns in code that indicate possible design or maintainability problems.

Code smells are not always bugs, but they often represent areas requiring improvement.

---

## Objective

Detect warning signs that may lead to future problems.

---

## What to Inspect

Inspect:

- Large classes
- Long methods
- Duplicate logic
- Excessive parameters
- Feature envy
- Data clumps
- Primitive obsession
- Shotgun surgery
- Divergent changes

---

## Common Findings

- God Classes
- God Functions
- Long Methods
- Duplicate Code
- Excessive Conditionals
- Poor Object Design
- Hidden Dependencies

---

## Severity

High when smells significantly impact maintainability.

Medium when refactoring is recommended.

Low for minor design improvements.

---

## Expected Evidence

- Source code structure
- Class relationships
- Method size
- Dependency patterns

---

## Recommendations

Refactor gradually.

Improve responsibilities.

Reduce complexity.

Apply appropriate design patterns.

Avoid unnecessary abstractions.

---

## References

- Refactoring
- Martin Fowler
- Clean Code
