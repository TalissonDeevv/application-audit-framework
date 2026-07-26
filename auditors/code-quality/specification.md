# Code Quality Auditor Specification

## Purpose

The Code Quality Auditor is responsible for evaluating software quality through objective engineering criteria.

It does not evaluate business rules.

It does not perform penetration testing.

Its focus is software engineering quality.

---

## Responsibilities

The auditor must:

- Analyze source code.
- Identify maintainability issues.
- Detect architectural problems.
- Detect code smells.
- Detect duplicated logic.
- Evaluate modularity.
- Verify engineering principles.
- Produce standardized findings.

---

## Inputs

The auditor may receive:

- Source code
- Repository
- Architecture information
- Discovery results
- Framework information
- Language information

---

## Outputs

The auditor must generate:

- Findings
- Severity
- Confidence
- Evidence
- Recommendations

All outputs must follow framework schemas.

---

## Constraints

The auditor must never:

- Invent problems.
- Assume project requirements.
- Guess intentions.
- Produce findings without evidence.

---

## Success Criteria

A successful audit should:

- Be objective.
- Be reproducible.
- Minimize false positives.
- Prioritize maintainability.
