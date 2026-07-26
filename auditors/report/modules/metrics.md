# Metrics Module

## Overview

Generates quantitative metrics describing the overall quality of the audited project.

Metrics provide an objective view of the project's current state and allow comparisons between audit executions.

---

## Objective

Produce measurable indicators that summarize the audit results.

---

## Responsibilities

The module must:

- Aggregate audit statistics.
- Calculate distributions.
- Generate project indicators.
- Support executive reporting.

---

## Metrics

The report should include:

### Findings

- Total Findings
- Critical Findings
- High Findings
- Medium Findings
- Low Findings
- Informational Findings

---

### Categories

Findings per category:

- Discovery
- Architecture
- Security
- Code Quality
- Performance
- Infrastructure

---

### Severity Distribution

Calculate:

- Percentage by severity
- Highest severity
- Average severity

---

### Confidence Distribution

Calculate:

- Very High
- High
- Medium
- Low

---

### Coverage

When available:

- Files analyzed
- Directories analyzed
- Languages detected
- Frameworks detected
- Infrastructure components detected

---

## Validation

Metrics must:

- Be reproducible.
- Be based only on audit findings.
- Never include fabricated values.

---

## Output Example

Project Metrics

Total Findings: 48

Critical: 2

High: 7

Medium: 18

Low: 15

Informational: 6

Average Confidence:

91%

Overall Coverage:

94%
