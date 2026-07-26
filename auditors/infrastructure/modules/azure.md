# Microsoft Azure Module

## Overview

Evaluates applications deployed on Microsoft Azure.

Analyzes cloud resource configuration, operational maturity and security.

---

## Objective

Identify Azure configuration issues affecting reliability and operational quality.

---

## What to Inspect

Inspect:

- Azure Virtual Machines
- App Services
- Azure Functions
- AKS
- Azure Storage
- Azure SQL
- Azure Monitor
- Key Vault
- Virtual Networks
- Azure DNS
- RBAC configuration

---

## Common Findings

- Excessive RBAC permissions
- Missing monitoring
- Poor network segmentation
- Unprotected secrets
- Missing backups
- Weak security policies

---

## Operational Impact

Possible impacts:

- Increased attack surface
- Reduced availability
- Operational complexity
- Cost inefficiency

---

## Severity

Critical:

High-risk Azure configuration.

High:

Security or operational risks.

Medium:

Recommended improvements.

Low:

Optimization opportunities.

---

## Expected Evidence

- ARM Templates
- Bicep
- Terraform
- Azure configuration
- Deployment pipelines

---

## Recommendations

Implement least privilege.

Use Key Vault.

Enable Azure Monitor.

Automate deployments.

Review network security.

---

## References

- Microsoft Azure Well-Architected Framework
