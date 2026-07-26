# Cross-Site Request Forgery (CSRF) Module

## Overview

This module evaluates protections against unauthorized state-changing requests initiated from third-party websites.

---

## Objective

Identify missing or weak CSRF protections.

---

## Scope

### Included

- Forms
- APIs using cookies
- State-changing endpoints
- Session authentication

### Excluded

- JWT Authorization Header implementations
- CORS configuration

---

## Standards

- OWASP CSRF Prevention Cheat Sheet
- OWASP ASVS
- CWE-352

---

## What Must Be Analyzed

- CSRF Tokens
- SameSite cookies
- Origin validation
- Referer validation
- Double Submit Cookie
- Anti-CSRF middleware

---

## Detection Methodology

Inspect all state-changing endpoints.

Verify anti-CSRF protections.

Verify cookie attributes.

---

## Evidence Requirements

Every finding must include:

- Endpoint
- Missing protection
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Sensitive endpoint completely unprotected.

High

Weak token validation.

Medium

Incomplete protection.

Low

Defense-in-depth recommendation.

Informational

Implementation guidance.

---

## Common Findings

- Missing CSRF Token
- SameSite=None without justification
- Missing Origin validation
- Missing Referer validation

---

## Secure Practices

- Synchronizer Token Pattern
- SameSite cookies
- Origin validation
- Framework CSRF middleware

---

## False Positive Prevention

Do not report CSRF when the application exclusively uses Authorization headers without cookie authentication.

---

## Expected Output

Generate CSRF findings following the Finding Schema.
