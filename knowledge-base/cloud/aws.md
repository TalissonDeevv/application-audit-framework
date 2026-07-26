# AWS Audit Profile

## Overview

Amazon Web Services (AWS) is one of the world's leading cloud platforms.

The AI Audit Framework (AAF) uses this profile to evaluate security, architecture, reliability and operational best practices for applications deployed on AWS.

---

## Detection

Typical indicators:

- aws-sdk
- @aws-sdk/*
- CloudFormation
- CDK
- Terraform AWS Provider
- AWS CLI configuration
- Lambda
- EC2
- ECS
- EKS
- S3
- RDS

---

## Security Focus

Inspect:

- IAM permissions
- Secret management
- Security Groups
- S3 bucket exposure
- Public resources
- Encryption
- Key management
- Network configuration

---

## Infrastructure Focus

Inspect:

- VPC configuration
- Load Balancers
- Auto Scaling
- Availability Zones
- Backup strategy
- Disaster Recovery

---

## Performance Focus

Inspect:

- Resource utilization
- Lambda cold starts
- Database performance
- Caching
- CDN usage

---

## Common Findings

- Overly permissive IAM roles
- Public S3 buckets
- Secrets stored in code
- Missing encryption
- Public databases
- Missing backups

---

## Recommended Practices

- Least Privilege IAM
- AWS Secrets Manager
- KMS Encryption
- CloudWatch Monitoring
- Multi-AZ Deployment
- Automatic Backups

---

## References

- AWS Documentation
- AWS Well-Architected Framework
