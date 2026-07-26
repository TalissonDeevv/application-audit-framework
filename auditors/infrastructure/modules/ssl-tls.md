# SSL/TLS Module

## Overview

Evaluates encryption configuration protecting communication between clients and servers.

Strong SSL/TLS configuration is essential for confidentiality and integrity.

---

## Objective

Identify insecure or outdated SSL/TLS configurations.

---

## What to Inspect

Inspect:

- HTTPS configuration
- TLS version
- SSL certificates
- Certificate expiration
- HSTS
- Cipher suites
- Certificate authority
- Redirect configuration

---

## Common Findings

- Expired certificates
- Missing HTTPS redirect
- Weak TLS versions
- Missing HSTS
- Invalid certificates
- Self-signed certificates in production
- Weak cipher suites

---

## Operational Impact

Possible impacts:

- Sensitive data exposure
- Browser security warnings
- Compliance issues
- Reduced user trust

---

## Severity

Critical:

Insecure production encryption.

High:

Weak TLS configuration.

Medium:

Recommended improvements.

Low:

Configuration optimization.

---

## Expected Evidence

- Web server configuration
- Reverse proxy configuration
- Certificate information
- Security headers

---

## Recommendations

Use TLS 1.2 or newer.

Enable HSTS.

Automatically renew certificates.

Redirect HTTP to HTTPS.

Use trusted Certificate Authorities.

---

## References

- OWASP Transport Layer Protection
- Mozilla SSL Configuration Guidelines
