# DRY Principle Module

## Overview

Evaluates compliance with the Don't Repeat Yourself (DRY) principle.

---

## Objective

Identify duplicated logic that increases maintenance cost.

---

## What to Inspect

Inspect:

- Repeated business rules
- Duplicate validation
- Repeated utilities
- Similar algorithms
- Repeated API logic
- Duplicate SQL

---

## Common Findings

- Copy-paste code
- Duplicate validation
- Repeated calculations
- Repeated configuration
- Similar services

---

## Severity

High when duplication affects maintainability.

Medium for repeated implementation.

Low for minor duplication.

---

## Expected Evidence

- Similar code blocks
- Duplicate functions
- Repeated classes
- Repeated business rules

---

## Recommendations

Extract reusable components.

Create shared services.

Create utility functions.

Centralize business logic.

---

## References

- DRY Principle
- Refactoring
