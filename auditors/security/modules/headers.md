# Security Headers Module

## Overview

This module evaluates HTTP security headers.

---

## Objective

Identify missing or insecure HTTP security headers.

---

## Scope

### Included

- CSP
- HSTS
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy

---

## Standards

- OWASP Secure Headers Project
- Mozilla Observatory

---

## What Must Be Analyzed

- CSP
- HSTS
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy

---

## Detection Methodology

Inspect HTTP responses.

Verify security header values.

---

## Common Findings

- Missing CSP
- Missing HSTS
- Missing X-Frame-Options
- Weak CSP
- Unsafe directives

---

## Secure Practices

- Strict CSP
- HSTS enabled
- DENY or SAMEORIGIN
- nosniff

---

## Expected Output

Generate Security Header findings following the Finding Schema.
