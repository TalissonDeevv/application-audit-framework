# PostgreSQL Audit Profile

## Overview

PostgreSQL is a relational database widely used in enterprise systems, SaaS platforms and cloud-native applications.

The AI Audit Framework (AAF) uses this profile to identify PostgreSQL-specific security, performance and configuration issues.

---

## Detection

Typical indicators:

- PostgreSQL connection strings
- postgres://
- postgresql://
- pg package
- psycopg
- PostgreSQL JDBC Driver
- Npgsql

---

## Security Focus

Inspect:

- SQL Injection
- Database permissions
- Role management
- SSL/TLS configuration
- Secret exposure
- Connection security
- Public database exposure

---

## Performance Focus

Inspect:

- Missing indexes
- Sequential scans
- Slow queries
- Large joins
- Connection pooling
- Vacuum configuration

---

## Architecture Focus

Evaluate:

- Schema organization
- Migration strategy
- Transaction usage
- Foreign keys
- Constraints

---

## Common Findings

- Missing indexes
- Unsafe raw SQL
- Excessive privileges
- Database exposed to the Internet
- Weak credentials
- Missing backups

---

## Recommended Practices

- Least Privilege
- Prepared Statements
- Connection Pooling
- SSL Enabled
- Automated Backups
- Proper Indexing

---

## References

- PostgreSQL Documentation
