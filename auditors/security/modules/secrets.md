# Secrets Management Module

## Overview

This module evaluates how secrets are stored, managed and protected.

---

## Objective

Identify exposed credentials and insecure secret management practices.

---

## Scope

### Included

- API Keys
- Tokens
- Passwords
- Environment variables
- Certificates
- Private keys
- Cloud credentials

### Excluded

- Database permissions
- Authentication flow

---

## Standards

- OWASP Secrets Management Cheat Sheet
- NIST SSDF

---

## What Must Be Analyzed

- Hardcoded credentials
- .env files
- Secret rotation
- Secret managers
- Git history
- Public repositories
- Build pipelines
- CI/CD secrets

---

## Detection Methodology

Inspect source code.

Inspect configuration files.

Inspect deployment configuration.

Inspect repository history when available.

---

## Evidence Requirements

Every finding must include

- Secret location
- Secret type
- Exposure evidence
- Recommendation

---

## Severity Guidelines

Critical

Production credentials publicly exposed.

High

Hardcoded secrets.

Medium

Weak secret management.

Low

Operational recommendation.

Informational

Good practice observation.

---

## Common Findings

- Hardcoded passwords
- API Keys committed
- .env committed
- Cloud credentials exposed
- Missing rotation

---

## Secure Practices

- Secret Manager
- Vault
- Environment variables
- Automatic rotation
- Principle of least exposure

---

## False Positive Prevention

Ignore placeholder values used exclusively for documentation or testing.

---

## Expected Output

Generate Secrets Management findings following the Finding Schema.
