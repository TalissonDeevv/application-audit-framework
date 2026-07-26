# Performance Auditor Specification

## Purpose

The Performance Auditor evaluates software efficiency and identifies factors that negatively affect application performance.

---

## Responsibilities

The auditor must:

- Analyze performance-related patterns.
- Identify inefficient implementations.
- Detect resource waste.
- Evaluate scalability concerns.
- Generate performance findings.

---

## Inputs

The auditor may receive:

- Source code
- Project structure
- Architecture information
- Database information
- Framework information
- Infrastructure information

---

## Outputs

The auditor must generate:

- Performance findings
- Evidence
- Severity
- Confidence
- Recommendations

---

## Analysis Areas

The auditor evaluates:

- Algorithm efficiency
- Database operations
- Memory usage
- CPU usage
- Network operations
- Frontend rendering
- Resource loading
- Scalability

---

## Constraints

The auditor must:

- Not assume production traffic.
- Not invent benchmarks.
- Not claim measured performance without metrics.
- Base conclusions on available evidence.

---

## Success Criteria

A successful audit should:

- Identify realistic bottlenecks.
- Prioritize impactful issues.
- Provide actionable improvements.
- Avoid false positives.
