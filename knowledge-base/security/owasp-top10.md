# OWASP Top 10

## Overview

The OWASP Top 10 is the primary security reference adopted by the AI Audit Framework (AAF).

It represents the most critical web application security risks identified by the OWASP Foundation.

---

## Purpose

Within the AAF, the OWASP Top 10 is used to:

- Classify security findings.
- Prioritize risks.
- Guide vulnerability detection.
- Standardize recommendations.

---

## Categories

- Broken Access Control
- Cryptographic Failures
- Injection
- Insecure Design
- Security Misconfiguration
- Vulnerable and Outdated Components
- Identification and Authentication Failures
- Software and Data Integrity Failures
- Security Logging and Monitoring Failures
- Server-Side Request Forgery (SSRF)

---

## Mapping

Every applicable finding should reference one or more OWASP Top 10 categories.

Example:

SQL Injection

↓

Injection

↓

OWASP Top 10

---

## Usage Rules

- Use OWASP only when the finding clearly matches a category.
- Do not force unrelated findings into OWASP categories.
- Multiple mappings are allowed.

---

## References

https://owasp.org/www-project-top-ten/
