# JavaScript Audit Profile

## Overview

JavaScript is one of the most common languages used for web development.

The AI Audit Framework (AAF) uses this profile to identify JavaScript-specific risks, patterns and best practices.

---

## Typical Environments

- Browser
- Node.js
- Serverless
- Electron

---

## Common Frameworks

- React
- Next.js
- Vue
- Angular
- Express
- NestJS

---

## Security Focus

The auditor should verify:

- XSS
- Prototype Pollution
- Unsafe eval()
- Unsafe Function()
- Command Injection
- Path Traversal
- Insecure Deserialization
- Weak JWT handling
- Unsafe CORS
- Secret exposure

---

## Code Quality Focus

Analyze:

- Complexity
- Large functions
- Callback nesting
- Async error handling
- Promise handling
- Dead code
- Duplicate code
- Naming consistency

---

## Performance Focus

Inspect:

- Blocking operations
- Large loops
- Memory leaks
- Event loop blocking
- Unnecessary rendering
- Bundle size

---

## Dependency Focus

Verify:

- npm packages
- package-lock.json
- pnpm-lock.yaml
- yarn.lock

Look for:

- Vulnerable packages
- Deprecated libraries
- Unused dependencies

---

## Recommended Practices

- ESLint
- Prettier
- TypeScript when appropriate
- Parameter validation
- Secure dependency management

---

## References

- ECMAScript
- OWASP
- Node.js Documentation
