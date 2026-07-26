# Score Module

## Overview

Calculates the overall quality score of the audited project.

The score summarizes the project's engineering maturity while considering severity, confidence and finding distribution.

---

## Objective

Generate an overall score representing project quality.

---

## Responsibilities

The module must:

- Calculate the project score.
- Explain how the score was produced.
- Classify engineering maturity.
- Maintain consistency between audit executions.

---

## Scoring Principles

The score starts at:

100 points

Points are deducted according to finding severity.

Suggested weights:

Critical: -15

High: -8

Medium: -4

Low: -1

Informational: 0

Confidence may be used to adjust deductions when appropriate.

---

## Engineering Maturity

95–100

Excellent

Production-ready with minimal improvements.

---

85–94

Very Good

Minor improvements recommended.

---

70–84

Good

Production capable with moderate improvements.

---

50–69

Needs Improvement

Important engineering work remains.

---

Below 50

High Risk

Significant improvements required before production.

---

## Validation

The score must:

- Be reproducible.
- Explain deductions.
- Reflect actual findings.
- Never exceed 100.
- Never be negative.

---

## Output Example

Overall Score

82 / 100

Engineering Maturity:

Good

Major factors reducing the score:

- Authentication weaknesses
- Missing monitoring
- Infrastructure configuration issues
