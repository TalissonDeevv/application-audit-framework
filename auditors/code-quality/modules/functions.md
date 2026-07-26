# Functions Module

## Overview

Evaluates function design, organization and responsibility.

Functions should be small, focused and easy to understand.

---

## Objective

Identify functions that violate software engineering best practices.

---

## What to Inspect

Inspect:

- Function size
- Single Responsibility
- Parameter count
- Return consistency
- Side effects
- Complexity

---

## Common Findings

- Long functions
- Too many parameters
- Multiple responsibilities
- Hidden side effects
- Deep nesting
- Duplicate logic

---

## Severity

High for functions that significantly reduce maintainability.

Medium for organizational issues.

Low for optimization opportunities.

---

## Expected Evidence

- Large methods
- Complex logic
- Repeated code
- Mixed responsibilities

---

## Recommendations

Split large functions.

Reduce parameters.

Extract reusable logic.

Keep one responsibility per function.

---

## References

- Clean Code
- SOLID
