# Code Duplication Module

## Overview

Detects duplicated logic across the project.

---

## Objective

Reduce maintenance cost by identifying repeated code.

---

## What to Inspect

Inspect:

- Duplicate functions
- Duplicate classes
- Repeated validation
- Repeated business logic
- Repeated SQL
- Repeated utilities

---

## Common Findings

- Copy-paste code
- Repeated algorithms
- Duplicate validations
- Duplicate services

---

## Severity

High when duplication causes maintenance risks.

Medium when reuse is possible.

Low for isolated cases.

---

## Expected Evidence

- Similar code blocks
- Identical implementations
- Repeated patterns

---

## Recommendations

Extract reusable components.

Create shared utilities.

Apply DRY.

---

## References

- Refactoring
- DRY Principle
