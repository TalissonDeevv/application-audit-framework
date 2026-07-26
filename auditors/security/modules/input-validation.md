# Input Validation Module

## Overview

This module evaluates whether user-controlled input is properly validated and sanitized.

---

## Objective

Prevent malformed or malicious input from reaching sensitive components.

---

## Scope

### Included

- Forms
- APIs
- Query parameters
- Path parameters
- Headers
- Cookies
- File uploads

### Excluded

- Authentication
- Authorization

---

## Standards

- OWASP Input Validation Cheat Sheet
- OWASP ASVS

---

## What Must Be Analyzed

- Server-side validation
- Client-side validation
- Input sanitization
- Output encoding
- Type validation
- Length validation
- Allowed values
- Regex validation

---

## Detection Methodology

Inspect every user input.

Verify validation occurs on the server.

Check sanitization.

Check encoding.

---

## Evidence Requirements

Every finding must include

- Input source
- Validation status
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Validation completely absent on sensitive input.

High

User input reaches dangerous functions.

Medium

Weak validation.

Low

Minor validation improvements.

Informational

Recommendations.

---

## Common Findings

- Missing validation
- Trusting client-side validation
- Weak regex
- Missing encoding
- Missing sanitization

---

## Secure Practices

- Validate on server
- Whitelist validation
- Strong typing
- Encode output
- Reject unexpected values

---

## False Positive Prevention

Do not assume validation is missing because it is centralized.

Search for reusable validation middleware.

---

## Expected Output

Generate Input Validation findings following the Finding Schema.
