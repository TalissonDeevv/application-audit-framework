# Infrastructure Auditor Examples

## Overview

This directory contains practical examples demonstrating how the Infrastructure Auditor evaluates deployment environments, cloud resources, networking and operational infrastructure.

Examples are used to validate the auditor's ability to detect infrastructure weaknesses and recommend operational improvements.

---

## Purpose

Examples demonstrate:

- Infrastructure findings
- Evidence collection
- Risk analysis
- Severity classification
- Practical recommendations

---

## Example Structure

Each example should follow this structure:

```
example-name/

├── source/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── deployment.yaml
│   ├── terraform/
│   └── infrastructure files

├── context.md

├── expected-findings.md

└── report.md
```

---

## Example Categories

### Container Infrastructure

Examples involving:

- Docker
- Docker Compose
- Container security
- Container optimization

---

### Kubernetes

Examples involving:

- Deployments
- Services
- Ingress
- ConfigMaps
- Secrets
- Resource limits

---

### Cloud Infrastructure

Examples involving:

- AWS
- Azure
- Google Cloud
- Cloudflare

---

### CI/CD

Examples involving:

- GitHub Actions
- GitLab CI
- Jenkins
- Azure DevOps

---

### Networking

Examples involving:

- DNS
- SSL/TLS
- Firewalls
- Reverse Proxies
- Load Balancers

---

### Operations

Examples involving:

- Monitoring
- Logging
- Backup
- Disaster Recovery
- High Availability

---

## Finding Validation

Each example should define:

- Finding title
- Description
- Evidence
- Operational impact
- Severity
- Recommendation

---

## Guidelines

Examples should:

- Represent real production environments.
- Demonstrate common infrastructure mistakes.
- Be reproducible.
- Use realistic configurations.

---

## Future Examples

Planned examples:

- Docker image running as root
- Missing Kubernetes resource limits
- Public S3 bucket
- Flexible SSL in Cloudflare
- Missing CI pipeline validation
- Infrastructure without monitoring
- Missing backup strategy
- Single Point of Failure
- Missing Auto Scaling
- Poor DNS configuration
