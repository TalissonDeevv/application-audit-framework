# SQL Server Audit Profile

## Overview

Microsoft SQL Server is an enterprise relational database used in business-critical applications.

---

## Detection

Typical indicators:

- mssql://
- Microsoft.Data.SqlClient
- System.Data.SqlClient

---

## Security Focus

Inspect:

- SQL Injection
- Authentication
- Database roles
- Encryption
- Secret management
- Public exposure

---

## Performance Focus

Inspect:

- Missing indexes
- Execution plans
- Connection pooling
- Blocking queries
- Deadlocks

---

## Architecture Focus

Inspect:

- Stored procedures
- Transactions
- Schema organization
- Constraints

---

## Common Findings

- SQL Injection risks
- Excessive privileges
- Missing indexes
- Weak authentication
- Public exposure

---

## Recommended Practices

- Parameterized Queries
- Least Privilege
- TLS Encryption
- Automated Backups
- Index Optimization

---

## References

- Microsoft SQL Server Documentation
