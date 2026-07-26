# Serverless Architecture Audit Profile

## Overview

Serverless applications execute code on demand without requiring direct server management.

---

## Detection

Typical indicators:

- AWS Lambda
- Cloud Functions
- Azure Functions
- Vercel Functions
- Cloudflare Workers

---

## Architecture Focus

Inspect:

- Function isolation
- Event triggers
- Dependency management
- Stateless execution

---

## Security Focus

Inspect:

- Secret management
- IAM permissions
- Function authorization
- Input validation
- Public endpoints

---

## Performance Focus

Inspect:

- Cold starts
- Execution time
- Memory allocation
- Function size

---

## Common Findings

- Large functions
- Excessive permissions
- Secrets in source code
- Missing validation
- Long execution time

---

## Recommended Practices

- Small functions
- Least privilege
- Environment variables
- Monitoring
- Automatic scaling

---

## References

- AWS Lambda Documentation
- Azure Functions Documentation
