# Cloudflare Audit Profile

## Overview

Cloudflare provides CDN, DNS, WAF, Zero Trust and security services.

---

## Detection

Typical indicators:

- Cloudflare DNS
- cloudflare package
- Wrangler
- Workers
- Pages

---

## Security Focus

Inspect:

- DNS configuration
- WAF
- SSL/TLS
- Security Headers
- DDoS Protection
- Access Rules
- Zero Trust configuration

---

## Infrastructure Focus

Inspect:

- CDN
- Cache Rules
- Workers
- Pages
- Load Balancing

---

## Performance Focus

Inspect:

- Cache Hit Ratio
- Compression
- Image Optimization
- Edge Caching
- CDN configuration

---

## Common Findings

- Disabled WAF
- Weak TLS configuration
- Missing cache rules
- DNS misconfiguration
- Missing security headers

---

## Recommended Practices

- Enable WAF
- Full (Strict) SSL
- Edge Cache
- Automatic HTTPS Rewrites
- Bot Protection

---

## References

- Cloudflare Documentation
