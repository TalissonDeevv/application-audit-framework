# Rate Limiting Module

## Overview

This module evaluates protections against abuse and denial-of-service attempts.

---

## Objective

Identify endpoints lacking request throttling.

---

## Scope

### Included

- Login
- APIs
- Password reset
- Registration
- Search endpoints

---

## Standards

- OWASP API Security Top 10

---

## What Must Be Analyzed

- Request limits
- Retry delays
- IP throttling
- User throttling
- Abuse detection

---

## Detection Methodology

Inspect sensitive endpoints.

Verify throttling.

---

## Common Findings

- Unlimited login attempts
- Unlimited password reset
- No API throttling
- Missing abuse protection

---

## Secure Practices

- Sliding window
- Token bucket
- Exponential backoff
- Account lockout

---

## Expected Output

Generate Rate Limit findings following the Finding Schema.
