# Cross-Site Scripting (XSS) Module

## Overview

This module evaluates whether the application is vulnerable to Cross-Site Scripting (XSS), allowing attackers to inject and execute malicious JavaScript in users' browsers.

---

## Objective

Detect reflected, stored and DOM-based XSS vulnerabilities.

---

## Scope

### Included

- HTML rendering
- User-generated content
- Templates
- DOM manipulation
- Rich text editors
- Markdown rendering

### Excluded

- SQL Injection
- CSRF
- Server-side code execution

---

## Standards

- OWASP Top 10
- OWASP XSS Prevention Cheat Sheet
- CWE-79

---

## What Must Be Analyzed

- Output encoding
- HTML escaping
- DOM manipulation
- innerHTML usage
- dangerouslySetInnerHTML
- Template rendering
- Rich text rendering
- Content Security Policy

---

## Detection Methodology

Inspect all user-controlled output.

Identify whether untrusted input reaches the DOM.

Verify output encoding.

Verify CSP implementation.

---

## Evidence Requirements

Every finding must include:

- Injection point
- Sink
- Code reference
- Impact
- Recommendation

---

## Severity Guidelines

Critical

Confirmed executable XSS.

High

User-controlled HTML rendering.

Medium

Weak output encoding.

Low

Missing defense-in-depth controls.

Informational

Best-practice recommendation.

---

## Common Findings

- innerHTML
- dangerouslySetInnerHTML
- Missing escaping
- Missing CSP
- HTML injection
- DOM-based XSS

---

## Secure Practices

- Automatic escaping
- Context-aware encoding
- DOMPurify
- Content Security Policy
- Trusted Types (when supported)

---

## False Positive Prevention

Do not report escaped output as vulnerable.

Verify framework protections before generating findings.

---

## Expected Output

Generate XSS findings following the Finding Schema.
