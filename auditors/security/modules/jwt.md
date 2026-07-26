# JWT Module

## Overview

This module evaluates the implementation of JSON Web Tokens (JWT) used for authentication and authorization.

The goal is to ensure tokens are securely generated, validated, stored and revoked.

---

## Objective

Identify weaknesses in JWT implementation that could lead to authentication bypass, privilege escalation or token compromise.

---

## Scope

### Included

- JWT generation
- Signature validation
- Supported algorithms
- Token expiration
- Refresh tokens
- Claims validation
- Secret management
- Token revocation

### Excluded

- OAuth implementation
- Session cookies
- Authorization rules

---

## Standards

- RFC 7519
- OWASP JWT Cheat Sheet
- OWASP ASVS

---

## What Must Be Analyzed

- Signing algorithm
- Secret strength
- Public/private key usage
- Token expiration
- Refresh token flow
- Token storage
- Claim validation
- Audience validation
- Issuer validation
- Replay protection

---

## Detection Methodology

Inspect every JWT creation and validation process.

Verify that signatures are always validated.

Check expiration handling.

Verify refresh token implementation.

Inspect secret management.

---

## Evidence Requirements

Every finding must include:

- Token implementation
- Configuration
- Code reference
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Unsigned tokens.

High

Weak secret or missing validation.

Medium

Long expiration.

Low

Minor implementation weakness.

Informational

Best-practice recommendations.

---

## Common Findings

- Weak signing secret
- Missing expiration
- No issuer validation
- No audience validation
- Long-lived tokens
- Refresh token reuse
- Token stored in localStorage without mitigation

---

## Secure Practices

- RS256 or ES256 when appropriate
- Strong secrets
- Short expiration
- Refresh token rotation
- Revocation mechanism
- Validate iss, aud and exp claims

---

## False Positive Prevention

Do not report localStorage usage as automatically vulnerable.

Evaluate surrounding protections and application context.

---

## Expected Output

Generate JWT findings following the Finding Schema.
