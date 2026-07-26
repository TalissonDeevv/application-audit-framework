<div align="center">

# AI Audit Framework (AAF)

### A standardized framework for AI-powered software audits

Analyze • Validate • Prioritize • Improve • Ship with confidence

![Version](https://img.shields.io/badge/version-v1.0-blue)
![Status](https://img.shields.io/badge/status-foundation-success)
![License](https://img.shields.io/badge/license-MIT-green)
![AI](https://img.shields.io/badge/AI-Multi--Model-purple)

</div>

---

## Table of Contents

- Overview
- Why AAF?
- Features
- Core Principles
- Audit Categories
- Architecture
- Workflow
- Directory Structure
- Getting Started
- How to Use
- AI Compatibility
- Prompt Pipeline
- Knowledge Base
- Auditors
- Roadmap
- FAQ
- Glossary
- Community
- Contributing
- License

---

# Overview

The **AI Audit Framework (AAF)** is an open methodology that standardizes software audits performed with Artificial Intelligence.

Instead of relying on one large prompt, AAF divides the audit into specialized auditors, each responsible for a single engineering domain. The results are consolidated into a consistent, evidence-based report.

## Why AAF?

Traditional AI reviews often suffer from:

- Generic responses
- Hallucinated vulnerabilities
- Missing architectural context
- Inconsistent severity
- Poor prioritization
- Lack of reproducibility

AAF addresses these problems through modular analysis, schemas, scoring and standardized reporting.

# Features

- Modular auditing
- Multi-agent prompt strategy
- Standardized findings
- Evidence-first methodology
- Severity & confidence models
- Executive and technical reports
- Knowledge Base
- Extensible architecture
- AI-model agnostic

# Core Principles

- Evidence over assumptions
- Never invent vulnerabilities
- Preserve traceability
- Prioritize production impact
- Explain every finding
- Produce actionable recommendations
- Keep terminology consistent

# Audit Categories

- Discovery
- Architecture
- Security
- Code Quality
- Performance
- Infrastructure
- Reporting

# Architecture

```text
Project
   │
Discovery
   │
Architecture
   │
Security
   │
Code Quality
   │
Performance
   │
Infrastructure
   │
Report
```

# Workflow

```text
Project
   │
   ▼
Discovery Auditor
   │
Architecture Auditor
   │
Security Auditor
   │
Code Quality Auditor
   │
Performance Auditor
   │
Infrastructure Auditor
   │
Severity + Confidence
   │
Report Auditor
   │
Executive Report
```

# Project Structure

```text
core/
auditors/
knowledge-base/
prompts/
schemas/
docs/
```

# Getting Started

```bash
git clone https://github.com/<your-org>/ai-audit-framework.git
cd ai-audit-framework
```

Read:

1. docs/
2. core/
3. knowledge-base/
4. auditors/

# How to Use

Current version focuses on methodology.

Future CLI:

```bash
aaf audit .
```

# AI Compatibility

| Model | Status | Recommendation |
|-------|--------|----------------|
| GPT-5.5 | ✅ Tested | ⭐⭐⭐⭐⭐ |
| Claude 4 | ✅ Tested | ⭐⭐⭐⭐⭐ |
| Gemini 2.5 Pro | ✅ Tested | ⭐⭐⭐⭐☆ |
| Grok | 🧪 Experimental | ⭐⭐⭐☆☆ |
| DeepSeek | 🧪 Experimental | ⭐⭐⭐☆☆ |
| Qwen | 🧪 Experimental | ⭐⭐⭐☆☆ |

# Prompt Pipeline

```text
System
 ↓
Planner
 ↓
Discovery
 ↓
Architecture
 ↓
Security
 ↓
Code Quality
 ↓
Performance
 ↓
Infrastructure
 ↓
Reviewer
 ↓
Critic
 ↓
Reporter
```

# Knowledge Base

- Security standards
- Languages
- Frameworks
- Databases
- Cloud
- Architecture patterns

# Auditors

| Auditor | Purpose |
|----------|---------|
| Discovery | Understand the project |
| Architecture | Evaluate design |
| Security | Identify security risks |
| Code Quality | Assess maintainability |
| Performance | Detect bottlenecks |
| Infrastructure | Review deployment and operations |
| Report | Consolidate results |

# Roadmap

- ✅ V1 Documentation & Methodology
- 🟨 V2 Engine
- ⬜ V3 AI Agents
- ⬜ V4 CLI
- ⬜ V5 Dashboard
- ⬜ V6 VS Code Extension
- ⬜ V7 GitHub Action
- ⬜ V8 Enterprise

# FAQ

**Is AAF an AI model?**

No. It is a framework and methodology.

**Does it replace security scanners?**

No. It complements them with structured AI reasoning.

**Can I use my preferred LLM?**

Yes. The framework is model-agnostic.

# Glossary

- Audit
- Auditor
- Finding
- Evidence
- Severity
- Confidence
- Recommendation
- Report
- Schema
- Knowledge Base

# Community

🌐 Website

https://www.talissonsouza.com.br

💬 Discord

https://discord.talissonsouza.com.br

# Contributing

Contributions are welcome after the first stable release of the framework.

# License

MIT License.

---

<div align="center">

Built for developers and engineering teams who care about software quality.

</div>
