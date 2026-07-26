# MySQL Audit Profile

## Overview

MySQL is one of the most widely used relational databases for web applications.

---

## Detection

Typical indicators:

- mysql://
- mysql2
- mysqlclient
- MySQL Connector/J

---

## Security Focus

Inspect:

- SQL Injection
- User privileges
- SSL configuration
- Secret management
- Authentication plugins

---

## Performance Focus

Inspect:

- Slow queries
- Missing indexes
- Query cache usage
- Connection pooling
- Table locks

---

## Architecture Focus

Inspect:

- Schema normalization
- Foreign keys
- Transactions
- Storage engine

---

## Common Findings

- Missing indexes
- Full table scans
- Excessive privileges
- Weak passwords
- Public database access

---

## Recommended Practices

- Prepared Statements
- Least Privilege
- InnoDB
- SSL Connections
- Regular Backups

---

## References

- MySQL Documentation
