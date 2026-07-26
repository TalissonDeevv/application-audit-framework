# Authentication Module

## Overview

This module evaluates the authentication mechanisms responsible for verifying user identity.

The objective is to determine whether authentication is implemented securely according to industry best practices.

---

## Objective

Identify authentication weaknesses that could allow unauthorized access.

---

## Scope

### Included

- Login flow
- Registration
- Password storage
- Password reset
- MFA
- OAuth
- OpenID Connect
- Passkeys
- Brute-force protection
- Account lockout

### Excluded

- Authorization
- Session management
- JWT validation

---

## Standards

- OWASP ASVS
- OWASP Authentication Cheat Sheet
- NIST SP 800-63

---

## What Must Be Analyzed

- Password hashing algorithm
- Password policy
- MFA implementation
- Login throttling
- Failed login handling
- Password reset tokens
- OAuth configuration
- User enumeration
- Account lockout
- Authentication logging

---

## Detection Methodology

Verify every authentication endpoint.

Confirm whether passwords are securely hashed.

Verify password reset implementation.

Check brute-force protection.

Evaluate MFA support.

---

## Evidence Requirements

Every finding must include:

- Endpoint
- Code reference
- Configuration
- Impact
- Recommendation

---

## Common Findings

- Plain text passwords
- Weak password hashing
- Missing MFA
- Unlimited login attempts
- Predictable reset tokens
- User enumeration

---

## Secure Practices

- Argon2id or bcrypt
- MFA
- Strong password policy
- Account lockout
- Secure reset flow

---

## False Positive Prevention

Do not report missing MFA when authentication is intentionally delegated to a trusted identity provider.

---

## Expected Output

Generate Authentication findings following the Finding Schema.
