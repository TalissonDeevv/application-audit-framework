# Logging Module

## Overview

Evaluates application and infrastructure logging practices.

Proper logging enables auditing, troubleshooting and incident investigation.

---

## Objective

Identify weaknesses in log generation, storage and management.

---

## What to Inspect

Inspect:

- Log structure
- Log levels
- Centralized logging
- Sensitive data exposure
- Log retention
- Correlation IDs
- Error logging
- Audit logging

---

## Common Findings

- Missing logs
- Plain text sensitive data
- Inconsistent log format
- Missing error context
- No centralized logging
- Missing audit logs

---

## Operational Impact

Possible impacts:

- Difficult incident analysis
- Compliance issues
- Security risks
- Slow debugging

---

## Severity

Critical:

Sensitive data exposed in logs.

High:

Important events are not logged.

Medium:

Logging quality should improve.

Low:

Formatting improvements.

---

## Expected Evidence

- Source code
- Logging configuration
- Log samples
- Infrastructure configuration

---

## Recommendations

Use structured logs.

Protect sensitive information.

Implement centralized logging.

Include correlation identifiers.

Define log retention policies.

---

## References

- OpenTelemetry Logging
- OWASP Logging Cheat Sheet
