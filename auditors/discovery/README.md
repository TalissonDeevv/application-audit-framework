# Discovery Auditor

## Overview

The Discovery Auditor is the first stage of the AI Audit Framework (AAF).

Its responsibility is to understand the target project before any engineering analysis begins.

Unlike other auditors, the Discovery Auditor does not evaluate security, architecture, performance or code quality.

Instead, it builds a structured inventory describing the project.

Every subsequent auditor depends on the information collected during this stage.

---

# Purpose

The purpose of the Discovery Auditor is to identify the technologies, frameworks, project structure and execution environment.

This information becomes the foundation for every subsequent audit.

---

# Responsibilities

The Discovery Auditor is responsible for identifying:

- Project type
- Programming languages
- Frameworks
- Runtime
- Package managers
- Build tools
- Project structure
- Databases
- ORMs
- APIs
- Deployment platforms
- Environment configuration
- Containers
- CI/CD configuration
- Documentation

---

# Out of Scope

The Discovery Auditor must never:

- Detect vulnerabilities
- Review architecture
- Evaluate performance
- Suggest improvements
- Generate recommendations
- Produce security findings

---

# Inputs

The Discovery Auditor may consume:

- Source code
- Repository structure
- Configuration files
- Documentation
- Build files
- Environment configuration

---

# Outputs

The Discovery Auditor produces a structured inventory describing the project.

This inventory is consumed by every subsequent auditor.

---

# Dependencies

None.

This is the first auditor executed by AAF.

---

# Consumers

The Discovery output is consumed by:

- Architecture
- Code Quality
- Security
- Performance
- Infrastructure
- Report
