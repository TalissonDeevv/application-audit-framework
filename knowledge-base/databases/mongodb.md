# MongoDB Audit Profile

## Overview

MongoDB is a document-oriented NoSQL database.

---

## Detection

Typical indicators:

- mongodb://
- mongoose
- mongodb package

---

## Security Focus

Inspect:

- Authentication
- Authorization
- Injection risks
- Public exposure
- Secret management
- TLS configuration

---

## Performance Focus

Inspect:

- Missing indexes
- Large collections
- Aggregation pipelines
- Query efficiency

---

## Architecture Focus

Inspect:

- Document modeling
- Embedding
- Referencing
- Collection design

---

## Common Findings

- Public MongoDB instance
- Missing authentication
- Missing indexes
- Large documents
- Collection scans

---

## Recommended Practices

- Authentication enabled
- TLS
- Proper indexing
- Principle of Least Privilege
- Secure backups

---

## References

- MongoDB Documentation
