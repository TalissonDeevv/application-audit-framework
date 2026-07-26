# Finding Schema

## Overview

The Finding Schema defines the standard structure used to represent every issue, observation or recommendation produced by the AI Audit Framework.

All auditors must generate findings using this format.

---

# Schema

```yaml
id:

module:

category:

title:

description:

severity:

confidence:

status:

impact:

likelihood:

risk_score:

affected_components: []

affected_files: []

evidence:
  source:
  description:

recommendation:

references: []

tags: []

metadata:
  generated_by:
  generated_at:
```

---

# Severity

Possible values:

- Critical
- High
- Medium
- Low
- Informational

---

# Confidence

Possible values:

- Confirmed
- High
- Medium
- Low
- Requires Verification

---

# Status

Possible values:

- Open
- Confirmed
- False Positive
- Resolved
- Needs Review

---

# Principles

Every finding must:

- include evidence
- explain impact
- include recommendations
- use standardized severity
