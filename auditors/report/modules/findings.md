# Findings Module

## Overview

Responsible for organizing and presenting every finding generated during the audit.

This is the core section of the final report.

---

## Objective

Present findings in a structured and standardized format.

---

## Finding Structure

Each finding must contain:

- Identifier
- Title
- Category
- Severity
- Confidence
- Description
- Evidence
- Impact
- Recommendation
- References

---

## Organization

Findings should be grouped by:

- Discovery
- Architecture
- Security
- Code Quality
- Performance
- Infrastructure

---

## Ordering

Findings should be ordered by:

1. Critical
2. High
3. Medium
4. Low
5. Informational

---

## Validation

Every finding must:

- Be evidence-based.
- Have a valid severity.
- Have a confidence score.
- Include actionable recommendations.

---

## Constraints

Never:

- Duplicate findings.
- Invent evidence.
- Change finding severity.
- Remove valid findings.

---

## Output Example

Finding ID: SEC-001

Category: Security

Severity: High

Confidence: High

Title:

Hardcoded API Key

Description:

An API key was found directly inside the source code.

Impact:

Credential exposure.

Recommendation:

Move the credential to a secure Secret Manager.
