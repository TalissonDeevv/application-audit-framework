# Amazon Web Services (AWS) Module

## Overview

Evaluates infrastructure deployed on Amazon Web Services (AWS).

The objective is to identify configuration, security, scalability and operational issues based on AWS best practices.

---

## Objective

Verify whether AWS resources are configured securely, efficiently and according to cloud engineering standards.

---

## What to Inspect

Inspect:

- IAM configuration
- EC2 instances
- ECS/EKS
- Lambda functions
- S3 buckets
- RDS databases
- VPC configuration
- Security Groups
- Route 53
- CloudFront
- CloudWatch
- Secrets Manager
- Auto Scaling

---

## Common Findings

- Excessive IAM permissions
- Public S3 buckets
- Missing encryption
- Poor VPC segmentation
- Missing backups
- Disabled monitoring
- Hardcoded credentials
- Missing Auto Scaling

---

## Operational Impact

Possible impacts:

- Security breaches
- Increased costs
- Reduced availability
- Poor scalability

---

## Severity

Critical:

Public resources or excessive permissions.

High:

Infrastructure misconfiguration.

Medium:

Operational improvements.

Low:

Optimization opportunities.

---

## Expected Evidence

- Terraform
- CloudFormation
- CDK
- AWS Console exports
- Deployment configuration

---

## Recommendations

Apply least privilege.

Enable monitoring.

Encrypt sensitive resources.

Implement infrastructure as code.

Enable backups and scaling.

---

## References

- AWS Well-Architected Framework
- AWS Security Best Practices
