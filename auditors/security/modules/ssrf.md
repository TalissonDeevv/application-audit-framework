# SSRF Module

## Overview

This module evaluates whether the application can be abused to perform unauthorized requests to internal or external resources.

---

## Objective

Detect Server-Side Request Forgery vulnerabilities.

---

## Scope

### Included

- URL fetching
- Webhooks
- Proxy endpoints
- File import
- Image import
- PDF generation

### Excluded

- Client-side requests
- Browser fetch operations

---

## Standards

- OWASP SSRF Prevention Cheat Sheet
- CWE-918

---

## What Must Be Analyzed

- URL validation
- Internal IP access
- Metadata services
- DNS rebinding
- Redirect handling
- Allowlists

---

## Detection Methodology

Inspect every feature accepting external URLs.

Verify destination validation.

Check internal network restrictions.

---

## Evidence Requirements

Every finding must include:

- Endpoint
- Request destination
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Access to internal infrastructure.

High

Unrestricted URL fetching.

Medium

Weak validation.

Low

Hardening recommendation.

Informational

Operational recommendation.

---

## Common Findings

- Internal network access
- AWS Metadata access
- GCP Metadata access
- Open proxy behavior
- Missing allowlist

---

## Secure Practices

- Allowlists
- Private IP blocking
- Metadata endpoint blocking
- Redirect validation

---

## False Positive Prevention

Do not report URL fetching as SSRF unless user-controlled destinations exist.

---

## Expected Output

Generate SSRF findings following the Finding Schema.
