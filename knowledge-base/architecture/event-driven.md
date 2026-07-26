# Event-Driven Architecture Audit Profile

## Overview

Event-driven systems communicate through events instead of direct synchronous calls.

---

## Detection

Typical indicators:

- Message brokers
- Kafka
- RabbitMQ
- SQS
- Pub/Sub
- Event Bus

---

## Architecture Focus

Inspect:

- Event contracts
- Producer/Consumer separation
- Idempotency
- Event versioning
- Dead Letter Queues

---

## Security Focus

Inspect:

- Event validation
- Authentication
- Authorization
- Encryption
- Message integrity

---

## Performance Focus

Inspect:

- Queue latency
- Consumer throughput
- Retry mechanisms
- Backpressure

---

## Common Findings

- Missing DLQ
- Duplicate event processing
- Weak event validation
- Tight coupling
- Infinite retry loops

---

## Recommended Practices

- Idempotent consumers
- Event versioning
- Dead Letter Queue
- Observability
- Structured logging

---

## References

- Enterprise Integration Patterns
