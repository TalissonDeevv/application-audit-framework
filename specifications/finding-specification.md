# Finding Specification

## Overview

A Finding is a standardized record generated during an audit whenever the framework identifies an observation, issue, risk or recommendation.

Every finding must follow this specification to ensure consistency across all audit modules.

---

# Purpose

The purpose of a Finding is to:

- Describe an issue or observation.
- Provide supporting evidence.
- Explain the potential impact.
- Suggest a recommendation.
- Standardize reporting.

---

# Finding Types

Every finding must be classified as one of the following:

## Security

Security vulnerabilities and security risks.

Examples:

- SQL Injection
- XSS
- Broken Authentication
- IDOR

---

## Architecture

Architectural weaknesses or design issues.

Examples:

- High coupling
- Circular dependencies
- Incorrect layering

---

## Code Quality

Maintainability and engineering quality issues.

Examples:

- Code duplication
- Long methods
- SOLID violations

---

## Performance

Performance bottlenecks.

Examples:

- N+1 Queries
- Memory leaks
- Expensive rendering

---

## Infrastructure

Infrastructure and deployment observations.

Examples:

- Missing backups
- Missing monitoring
- Weak secret management

---

## Production Readiness

Issues affecting production deployment.

Examples:

- Missing environment variables
- Missing health checks
- Missing logging

---

# Required Fields

Every finding must contain the following information.

---

## ID

Unique identifier.

Example:

```
AAF-SEC-001
```

---

## Title

Short and descriptive title.

Example:

```
JWT Secret Hardcoded
```

---

## Category

One of:

- Security
- Architecture
- Code Quality
- Performance
- Infrastructure
- Production Readiness

---

## Severity

Possible values:

- Critical
- High
- Medium
- Low
- Informational

---

## Confidence

Represents the confidence level of the finding.

Possible values:

- Confirmed
- High Confidence
- Medium Confidence
- Low Confidence
- Requires Verification

---

## Description

Explain the finding in a clear and objective manner.

---

## Evidence

Describe the evidence supporting the finding.

Evidence may include:

- Source code
- Configuration
- Logs
- Documentation
- API responses

---

## Impact

Describe the possible consequences if the issue is not addressed.

---

## Root Cause

Explain why the issue exists.

---

## Recommendation

Describe the recommended solution.

Recommendations should prioritize secure and maintainable implementations.

---

## References

When applicable, reference engineering standards.

Examples:

- OWASP Top 10
- OWASP ASVS
- CWE
- CVSS
- NIST

---

## Affected Components

List affected components.

Examples:

- Authentication
- API
- Database
- Frontend
- Backend

---

## Affected Files

List files involved in the finding whenever possible.

---

## Reproduction Steps

Describe how the issue can be reproduced.

If reproduction is not possible, explain why.

---

## Validation Status

Possible values:

- Pending
- Validated
- Requires Manual Review

---

# Finding Lifecycle

Every finding follows the same lifecycle.

```
Detected

↓

Validated

↓

Classified

↓

Documented

↓

Recommended

↓

Included in Final Report
```

---

# Writing Principles

Every finding should be:

- Objective
- Reproducible
- Evidence-based
- Actionable
- Easy to understand

The framework should avoid speculation.

Whenever sufficient evidence is unavailable, the finding should explicitly indicate that additional verification is required.

---

# Relationships

A finding may reference:

- Related findings
- Similar findings
- Previous findings
- Engineering standards

This helps create a more complete audit report while avoiding duplicated information.
