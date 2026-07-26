# SQL Injection Module

## Overview

This module evaluates database interactions to identify SQL Injection risks.

---

## Objective

Detect unsafe query construction that may allow attackers to manipulate database queries.

---

## Scope

### Included

- Raw SQL
- Dynamic SQL
- Query builders
- ORM
- Stored procedures
- Database APIs

### Excluded

- Database performance
- Database architecture

---

## Standards

- OWASP Top 10
- CWE-89
- OWASP SQL Injection Prevention Cheat Sheet

---

## What Must Be Analyzed

- String concatenation
- Prepared statements
- Parameterized queries
- ORM safety
- Raw queries
- Stored procedures
- Dynamic filters
- Search endpoints

---

## Detection Methodology

Inspect every database query.

Verify whether user-controlled data reaches SQL statements.

Confirm parameterization.

Evaluate ORM usage.

---

## Evidence Requirements

Every finding must include

- Query
- User input source
- Code reference
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Confirmed SQL Injection.

High

Unsafe dynamic SQL.

Medium

Potential injection vector requiring additional validation.

Low

Minor implementation weakness.

Informational

Secure implementation recommendation.

---

## Common Findings

- String concatenation
- Unparameterized query
- Dynamic ORDER BY
- Dynamic WHERE clause
- Unsafe raw SQL
- Unsanitized filters

---

## Secure Practices

- Prepared statements
- Parameterized queries
- Safe ORM usage
- Input validation
- Principle of least privilege

---

## False Positive Prevention

Do not report ORM-generated queries as vulnerable unless user input bypasses parameterization or raw SQL is used.

---

## Expected Output

Generate SQL Injection findings following the Finding Schema.
