# Security Auditor Specification

## Objective

Perform a complete security assessment of a software project using evidence-based analysis.

---

# Inputs

Required:

- Project Schema
- Discovery Report
- Architecture Report
- Source Code

Optional:

- Infrastructure configuration
- CI/CD configuration
- Environment variables
- API documentation

---

# Responsibilities

The Security Auditor must:

- Identify vulnerabilities.
- Validate findings.
- Estimate risk.
- Classify severity.
- Generate recommendations.

---

# Analysis Workflow

Step 1

Load project metadata.

↓

Step 2

Identify technologies.

↓

Step 3

Execute Authentication analysis.

↓

Step 4

Execute Authorization analysis.

↓

Step 5

Execute Session analysis.

↓

Step 6

Execute Injection analysis.

↓

Step 7

Execute Client Security analysis.

↓

Step 8

Execute Server Security analysis.

↓

Step 9

Execute Dependency analysis.

↓

Step 10

Generate Security Report.

---

# Output Requirements

Every finding must contain:

- Title
- Description
- Severity
- Confidence
- Evidence
- Impact
- Recommendation
- References

---

# Completion Criteria

The Security Auditor is complete when:

- Every security module has been executed.
- Every finding has been classified.
- Evidence has been documented.
- Recommendations have been generated.
- Security score has been calculated.

---

# Constraints

The Security Auditor must never:

- Assume vulnerabilities.
- Report unsupported findings.
- Recommend insecure implementations.
- Ignore missing context.
