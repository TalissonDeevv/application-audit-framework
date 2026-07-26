# CORS Module

## Overview

This module evaluates the Cross-Origin Resource Sharing (CORS) configuration to ensure that cross-origin requests are securely controlled.

---

## Objective

Detect insecure CORS configurations that could expose sensitive resources.

---

## Scope

### Included

- Allowed Origins
- Allowed Methods
- Allowed Headers
- Credentials
- Preflight Requests

### Excluded

- CSRF protection
- Authentication

---

## Standards

- Fetch Standard
- MDN CORS Documentation
- OWASP ASVS

---

## What Must Be Analyzed

- Access-Control-Allow-Origin
- Wildcard origins
- Credential handling
- Origin validation
- Allowed methods
- Allowed headers
- Dynamic origin reflection

---

## Detection Methodology

Inspect server responses.

Validate origin restrictions.

Verify credential policies.

---

## Evidence Requirements

Every finding must include:

- Endpoint
- Response headers
- Configuration
- Recommendation

---

## Severity Guidelines

Critical

Credentialed requests allowed from arbitrary origins.

High

Wildcard origin exposing sensitive endpoints.

Medium

Overly permissive methods.

Low

Minor hardening opportunities.

Informational

Best-practice recommendation.

---

## Common Findings

- Access-Control-Allow-Origin: *
- Access-Control-Allow-Credentials: true
- Dynamic origin reflection
- Overly permissive methods

---

## Secure Practices

- Explicit allowlists
- Restrict credentials
- Validate origins
- Least privilege

---

## False Positive Prevention

Do not report wildcard origins on public static assets without sensitive data.

---

## Expected Output

Generate CORS findings following the Finding Schema.
