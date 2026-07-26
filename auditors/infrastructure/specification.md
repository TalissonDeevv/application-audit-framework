# Infrastructure Auditor Specification

## Purpose

The Infrastructure Auditor evaluates infrastructure maturity and identifies operational risks that may affect software reliability, security and scalability.

---

## Responsibilities

The auditor must:

- Analyze infrastructure configurations.
- Identify operational weaknesses.
- Evaluate deployment practices.
- Review reliability patterns.
- Detect scalability limitations.
- Generate infrastructure findings.

---

## Inputs

The auditor may receive:

- Docker files
- Container configurations
- Kubernetes manifests
- CI/CD workflows
- Cloud configurations
- Server configurations
- Environment variables
- Network configurations
- Monitoring configurations

---

## Outputs

The auditor generates:

- Infrastructure findings
- Evidence references
- Severity classification
- Confidence score
- Recommendations

---

## Analysis Principles

The auditor must:

### Evidence-Based Analysis

Every finding must be supported by available evidence.

---

### Risk Prioritization

Findings should be prioritized according to:

- Business impact
- Availability impact
- Security impact
- Operational impact

---

### Practical Recommendations

Recommendations must be:

- Actionable
- Realistic
- Compatible with the current environment

---

## Limitations

The auditor must not:

- Invent cloud resources.
- Assume production traffic.
- Claim outages without evidence.
- Suggest unnecessary complexity.

---

## Success Criteria

A successful audit should:

- Identify infrastructure weaknesses.
- Improve operational reliability.
- Reduce deployment risks.
- Increase system maturity.
