# IDOR Module

## Overview

This module evaluates Insecure Direct Object References (IDOR), ensuring users cannot access resources belonging to other users.

---

## Objective

Detect broken object-level authorization.

---

## Scope

### Included

- User resources
- Files
- Orders
- Profiles
- Documents
- APIs

### Excluded

- Authentication
- Session Management

---

## Standards

- OWASP Top 10
- OWASP API Security Top 10
- CWE-639

---

## What Must Be Analyzed

- Resource ownership
- Object identifiers
- Sequential IDs
- UUID validation
- Access control
- Multi-tenant isolation

---

## Detection Methodology

Inspect every endpoint exposing object identifiers.

Verify ownership validation.

Verify authorization checks occur server-side.

---

## Evidence Requirements

Every finding must include:

- Endpoint
- Object identifier
- Missing authorization
- Recommendation

---

## Severity Guidelines

Critical

Confirmed unauthorized resource access.

High

Missing ownership validation.

Medium

Weak authorization logic.

Low

Hardening recommendation.

Informational

Architecture recommendation.

---

## Common Findings

- Sequential IDs
- Missing ownership validation
- Horizontal privilege escalation
- Resource enumeration

---

## Secure Practices

- Ownership verification
- UUIDs when appropriate
- Server-side authorization
- Tenant isolation

---

## False Positive Prevention

Do not assume sequential IDs are vulnerable without confirming missing authorization.

---

## Expected Output

Generate IDOR findings following the Finding Schema.
