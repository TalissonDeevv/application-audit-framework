# Security Tests

This directory contains validation scenarios used to verify the Security Auditor.

## Purpose

Each test project is intentionally designed to validate specific security modules.

## Validation Goals

- Detect known vulnerabilities
- Minimize false positives
- Produce evidence-based findings
- Follow the official Finding Schema
- Generate consistent security scores

## Planned Test Suites

- OWASP Juice Shop
- DVWA
- WebGoat
- Deliberately Vulnerable APIs
- Secure Reference Projects

## Success Criteria

A test is considered successful when:

- The expected vulnerabilities are detected.
- False positives remain minimal.
- Findings follow the AAF specification.
- Reports remain deterministic and reproducible.
