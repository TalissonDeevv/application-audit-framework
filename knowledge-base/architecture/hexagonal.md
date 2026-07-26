# Hexagonal Architecture Audit Profile

## Overview

Hexagonal Architecture (Ports and Adapters) isolates business logic from external dependencies.

---

## Detection

Typical indicators:

- Domain layer
- Ports
- Adapters
- Dependency inversion
- Application layer

---

## Architecture Focus

Inspect:

- Domain isolation
- Dependency direction
- Port implementation
- Adapter responsibilities
- Layer independence

---

## Security Focus

Inspect:

- Validation at boundaries
- Authentication
- Authorization
- Secret handling
- External integrations

---

## Performance Focus

Inspect:

- Adapter efficiency
- Database access
- External API calls
- Dependency overhead

---

## Common Findings

- Domain depending on infrastructure
- Business logic in adapters
- Missing abstractions
- Tight coupling
- Layer violations

---

## Recommended Practices

- Dependency Inversion
- Rich domain model
- Thin adapters
- Isolated business rules
- Clear boundaries

---

## References

- Alistair Cockburn
- Ports and Adapters Architecture
