# Secrets Management Module

## Overview

Evaluates how sensitive information is stored, accessed and protected.

Proper secrets management reduces the risk of credential leakage and unauthorized access.

---

## Objective

Identify insecure handling of credentials and confidential information.

---

## What to Inspect

Inspect:

- API keys
- Tokens
- Passwords
- Database credentials
- Cloud credentials
- Secret storage
- Environment variables
- Secret rotation
- Access permissions

---

## Common Findings

- Hardcoded secrets
- Secrets committed to Git
- Plain text credentials
- Shared secrets
- Missing secret rotation
- Excessive access permissions
- Unencrypted secret storage

---

## Operational Impact

Possible impacts:

- Credential leakage
- Unauthorized access
- Infrastructure compromise
- Regulatory violations
- Production incidents

---

## Severity

Critical:

Sensitive credentials exposed.

High:

Weak secret management.

Medium:

Operational improvements.

Low:

Optimization opportunities.

---

## Expected Evidence

- Source code
- Environment files
- CI/CD configuration
- Secret manager configuration
- Infrastructure as Code

---

## Recommendations

Never hardcode secrets.

Use dedicated Secret Managers.

Rotate credentials periodically.

Restrict access using least privilege.

Encrypt sensitive information.

Audit secret access regularly.

---

## References

- OWASP Secrets Management Cheat Sheet
- NIST Secret Management Guidelines
