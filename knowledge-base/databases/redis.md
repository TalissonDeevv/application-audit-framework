# Redis Audit Profile

## Overview

Redis is commonly used for caching, sessions, queues and distributed locks.

---

## Detection

Typical indicators:

- redis://
- ioredis
- redis package
- StackExchange.Redis

---

## Security Focus

Inspect:

- Authentication
- Public exposure
- TLS
- Secret management
- Protected mode

---

## Performance Focus

Inspect:

- Key expiration
- Memory usage
- Eviction policies
- Large keys
- Slow commands

---

## Architecture Focus

Inspect:

- Cache strategy
- Session storage
- Queue implementation
- Replication

---

## Common Findings

- Public Redis instance
- No password configured
- Unlimited cache growth
- Missing expiration
- Large keys

---

## Recommended Practices

- Enable Authentication
- TLS
- Protected Mode
- Key Expiration
- Memory Monitoring

---

## References

- Redis Documentation
