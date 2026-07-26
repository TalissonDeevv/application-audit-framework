# DNS Module

## Overview

Evaluates Domain Name System (DNS) configuration and operational practices.

Correct DNS configuration improves reliability, security and availability.

---

## Objective

Identify DNS configuration issues affecting application accessibility.

---

## What to Inspect

Inspect:

- DNS records
- TTL configuration
- Nameservers
- Subdomains
- DNSSEC
- CNAME usage
- MX records
- TXT records
- SPF
- DKIM
- DMARC

---

## Common Findings

- Missing DNSSEC
- Incorrect DNS records
- Excessive TTL
- Missing SPF
- Missing DKIM
- Missing DMARC
- Duplicate records
- Invalid subdomains

---

## Operational Impact

Possible impacts:

- Service interruption
- Email delivery problems
- Increased downtime
- DNS spoofing risks

---

## Severity

Critical:

DNS configuration causes production failures.

High:

Security weaknesses.

Medium:

Reliability improvements.

Low:

Configuration optimization.

---

## Expected Evidence

- DNS zone
- Domain configuration
- Cloud provider configuration
- Registrar settings

---

## Recommendations

Review DNS records.

Enable DNSSEC.

Configure SPF, DKIM and DMARC.

Remove obsolete records.

Document DNS architecture.

---

## References

- DNS Best Practices
- ICANN Guidelines
