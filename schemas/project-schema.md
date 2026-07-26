# Project Schema

## Overview

The Project Schema defines the standardized structure used to describe a software project after the Discovery Auditor completes its analysis.

This schema serves as the primary input for all subsequent auditors.

---

# Schema

```yaml
project:
  name:
  description:
  type:
  maturity:
  repository:

languages:
  primary:
  secondary: []

frameworks:
  frontend:
  backend:
  mobile:
  desktop:

runtime:
  primary:
  version:

package_manager:

build_tools: []

database:
  primary:
  secondary: []

orm:
  name:
  version:

apis:
  rest: false
  graphql: false
  websocket: false
  grpc: false

authentication:
  provider:
  method:

deployment:
  provider:
  environment:
  region:

infrastructure:
  docker: false
  kubernetes: false
  reverse_proxy:
  cdn:

ci_cd:
  provider:
  pipelines: []

cloud:
  provider:
  services: []

storage:
  provider:
  type:

documentation:
  readme: false
  api_docs: false
  architecture_docs: false

configuration:
  environment_files: []
  secrets_detected: false

dependencies:
  production: 0
  development: 0

metadata:
  generated_by: Discovery Auditor
  framework_version:
  generated_at:
```

---

# Principles

- Every field should be populated using evidence.
- Unknown values should remain empty.
- Never invent information.
- Additional fields may be added without breaking compatibility.
