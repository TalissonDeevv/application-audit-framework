# Microservices Architecture Audit Profile

## Overview

Microservices split the application into independently deployable services communicating through APIs or messaging.

---

## Detection

Typical indicators:

- Multiple services
- Independent deployments
- API Gateway
- Service discovery
- Multiple databases

---

## Architecture Focus

Inspect:

- Service boundaries
- Communication
- Fault isolation
- Data ownership
- API contracts

---

## Security Focus

Inspect:

- Service authentication
- Authorization
- Internal APIs
- Secret distribution
- Service-to-service encryption

---

## Performance Focus

Inspect:

- Network latency
- Retry strategies
- Circuit breakers
- Load balancing
- Scalability

---

## Common Findings

- Tight coupling
- Shared databases
- Chatty communication
- Missing observability
- No resilience strategy

---

## Recommended Practices

- Independent services
- API Gateway
- Service Mesh
- Distributed tracing
- Circuit Breaker

---

## References

- Martin Fowler
- Microservices.io
