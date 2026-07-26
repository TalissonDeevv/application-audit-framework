# Square Cloud Audit Profile

## Overview

Square Cloud is a cloud platform focused on hosting bots, APIs, web applications and other services with simplified deployment and management.

The AI Audit Framework (AAF) uses this profile to evaluate applications deployed on Square Cloud.

---

## Detection

Typical indicators:

- squarecloud.app domains
- squarecloud.config
- Square Cloud deployment configuration

---

## Security Focus

Inspect:

- Environment Variables
- Secret management
- Public endpoints
- Authentication
- Authorization
- File permissions

---

## Infrastructure Focus

Inspect:

- Deployment configuration
- Runtime configuration
- Resource allocation
- Application isolation
- Logging

---

## Performance Focus

Inspect:

- Startup time
- Memory usage
- CPU utilization
- Application responsiveness
- Resource limits

---

## Common Findings

- Secrets committed to repository
- Missing environment variables
- Weak authentication
- Public administrative endpoints
- Insufficient logging

---

## Recommended Practices

- Store secrets using environment variables
- Validate all external inputs
- Enable structured logging
- Monitor resource usage
- Follow least privilege principles

---

## References

- Square Cloud Documentation
