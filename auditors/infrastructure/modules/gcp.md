# Google Cloud Platform (GCP) Module

## Overview

Evaluates infrastructure hosted on Google Cloud Platform.

Focuses on security, scalability and cloud operational practices.

---

## Objective

Verify that GCP resources follow recommended engineering standards.

---

## What to Inspect

Inspect:

- Compute Engine
- Cloud Run
- Cloud Functions
- GKE
- Cloud Storage
- Cloud SQL
- IAM
- Secret Manager
- Load Balancer
- Cloud Monitoring
- VPC configuration

---

## Common Findings

- Excessive IAM permissions
- Public storage buckets
- Missing monitoring
- Poor resource organization
- Hardcoded credentials
- Weak network configuration

---

## Operational Impact

Possible impacts:

- Service interruptions
- Security exposure
- Increased operational costs
- Reduced scalability

---

## Severity

Critical:

High-risk production configuration.

High:

Operational weaknesses.

Medium:

Recommended improvements.

Low:

Minor optimization.

---

## Expected Evidence

- Terraform
- Deployment Manager
- Infrastructure code
- Cloud configuration

---

## Recommendations

Enable monitoring.

Protect secrets.

Implement IAM best practices.

Automate infrastructure.

Review networking.

---

## References

- Google Cloud Architecture Framework
