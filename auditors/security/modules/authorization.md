# Authorization Module

## Overview

This module evaluates whether authenticated users can access only the resources and actions they are authorized to use.

---

## Objective

Detect authorization flaws and privilege escalation risks.

---

## Scope

### Included

- RBAC
- ABAC
- ACL
- Resource ownership
- Administrative endpoints
- Protected routes

### Excluded

- Authentication
- Session management

---

## Standards

- OWASP ASVS
- CWE-285
- OWASP Authorization Cheat Sheet

---

## What Must Be Analyzed

- Role validation
- Permission checks
- Ownership validation
- Protected APIs
- Admin-only resources
- Access control middleware
- Resource filtering

---

## Detection Methodology

Inspect every protected endpoint.

Verify authorization occurs on the server.

Ensure permissions are validated before business logic executes.

---

## Evidence Requirements

Every finding must include:

- Protected endpoint
- Missing validation
- Impact
- Recommendation

---

## Common Findings

- Missing authorization
- Horizontal privilege escalation
- Vertical privilege escalation
- Public administrative routes
- Insecure object ownership

---

## Secure Practices

- Server-side authorization
- Principle of Least Privilege
- RBAC
- Fine-grained permissions
- Ownership validation

---

## False Positive Prevention

Do not assume authorization is missing simply because middleware is not visible in one file.

Search for centralized authorization mechanisms.

---

## Expected Output

Generate Authorization findings following the Finding Schema.
