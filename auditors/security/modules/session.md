# Session Management Module

## Overview

This module evaluates how authenticated sessions are created, maintained and terminated.

---

## Objective

Identify weaknesses that could allow session hijacking or session abuse.

---

## Scope

### Included

- Cookies
- Session lifecycle
- Session expiration
- Session rotation
- Session invalidation
- Cookie attributes

### Excluded

- Authentication logic
- Authorization rules

---

## Standards

- OWASP Session Management Cheat Sheet
- OWASP ASVS

---

## What Must Be Analyzed

- Secure cookies
- HttpOnly
- SameSite
- Secure flag
- Session timeout
- Logout
- Session rotation
- Session fixation protection
- Session invalidation

---

## Detection Methodology

Inspect cookie configuration.

Verify session expiration.

Verify logout invalidates active sessions.

Check session identifiers.

---

## Evidence Requirements

Every finding must include:

- Cookie configuration
- Session implementation
- Evidence
- Recommendation

---

## Common Findings

- Missing HttpOnly
- Missing Secure flag
- Missing SameSite
- Long session lifetime
- Session fixation
- Session not invalidated after logout

---

## Secure Practices

- Secure cookies
- HttpOnly
- SameSite=Lax or Strict
- Session rotation
- Short expiration
- Proper logout

---

## False Positive Prevention

Ignore cookies that are intentionally public and do not contain authentication information.

---

## Expected Output

Generate Session Management findings following the Finding Schema.
