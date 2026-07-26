# Security Checklist

## Authentication

- [ ] Login implementation
- [ ] Password hashing
- [ ] Multi-factor authentication
- [ ] Password reset flow
- [ ] Account lockout
- [ ] Brute-force protection

---

## Authorization

- [ ] Role-Based Access Control (RBAC)
- [ ] Attribute-Based Access Control (ABAC)
- [ ] Permission validation
- [ ] Resource ownership validation

---

## Session Management

- [ ] Secure cookies
- [ ] HttpOnly
- [ ] Secure flag
- [ ] SameSite
- [ ] Session expiration
- [ ] Session invalidation

---

## JWT

- [ ] Secure algorithm
- [ ] Expiration
- [ ] Signature validation
- [ ] Secret protection

---

## Input Validation

- [ ] Server-side validation
- [ ] Input sanitization
- [ ] Output encoding
- [ ] File validation

---

## Injection

- [ ] SQL Injection
- [ ] NoSQL Injection
- [ ] Command Injection
- [ ] LDAP Injection

---

## Cross-Site Scripting

- [ ] Reflected XSS
- [ ] Stored XSS
- [ ] DOM XSS

---

## CSRF

- [ ] CSRF Tokens
- [ ] SameSite Cookies

---

## IDOR

- [ ] Resource ownership validation
- [ ] Access control verification

---

## SSRF

- [ ] URL validation
- [ ] Internal network protection

---

## CORS

- [ ] Origin validation
- [ ] Credential handling
- [ ] Allowed methods

---

## Security Headers

- [ ] CSP
- [ ] HSTS
- [ ] X-Frame-Options
- [ ] X-Content-Type-Options
- [ ] Referrer-Policy

---

## File Upload

- [ ] File type validation
- [ ] File size limits
- [ ] Malware scanning
- [ ] Storage isolation

---

## Rate Limiting

- [ ] Authentication endpoints
- [ ] Public APIs
- [ ] Abuse protection

---

## Logging

- [ ] Authentication events
- [ ] Authorization failures
- [ ] Security events
- [ ] Sensitive data exposure

---

## Dependencies

- [ ] Outdated packages
- [ ] Known vulnerabilities
- [ ] Dependency integrity

---

## Environment

- [ ] Secret management
- [ ] Debug mode disabled
- [ ] Environment variables protected
- [ ] Production configuration

---

## Final Validation

- [ ] All modules executed
- [ ] Findings documented
- [ ] Severity classified
- [ ] Recommendations generated
- [ ] Security score calculated
