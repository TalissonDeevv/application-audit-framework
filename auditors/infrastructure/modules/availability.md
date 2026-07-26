# Availability Module

## Overview

Evaluates whether the infrastructure is designed to keep services continuously available and resilient to failures.

High availability minimizes downtime and improves system reliability.

---

## Objective

Identify infrastructure weaknesses that reduce service availability.

---

## What to Inspect

Inspect:

- Redundancy
- Failover mechanisms
- High Availability architecture
- Health checks
- Load balancing
- Service replication
- Infrastructure redundancy
- Database replication
- Monitoring
- Recovery mechanisms

---

## Common Findings

- Single Point of Failure (SPOF)
- Missing failover strategy
- No redundancy
- Missing health checks
- Single database instance
- No replication
- Manual recovery procedures
- Weak infrastructure resilience

---

## Operational Impact

Possible impacts:

- Production downtime
- Service interruption
- Customer impact
- Financial losses
- SLA violations
- Reputation damage

---

## Severity

Critical:

Infrastructure contains critical Single Points of Failure.

High:

Availability is significantly limited.

Medium:

Reliability improvements are recommended.

Low:

Optimization opportunities.

Informational:

Availability architecture follows good engineering practices.

---

## Expected Evidence

Examples:

- Infrastructure diagrams
- Deployment architecture
- Health check configuration
- Monitoring systems
- Cloud configuration
- Kubernetes manifests
- Load balancer configuration

---

## Recommendations

Eliminate Single Points of Failure.

Implement redundancy for critical services.

Use automatic failover.

Continuously monitor infrastructure health.

Deploy across multiple availability zones when appropriate.

Regularly test recovery procedures.

---

## References

- Google SRE
- AWS Well-Architected Framework
- Azure Reliability Guidance
- NIST SP 800-34
