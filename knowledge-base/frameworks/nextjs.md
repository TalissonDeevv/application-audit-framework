# Next.js Audit Profile

## Overview

Next.js extends React with server-side rendering, routing and API capabilities.

---

## Detection

- next.config.js
- app/
- pages/
- middleware.ts
- next.config.ts

---

## Security Focus

Inspect:

- Server Actions
- API Routes
- Middleware
- Cookies
- Authentication
- Environment Variables
- Edge Runtime
- SSR Secrets
- CSP

---

## Architecture

Evaluate:

- App Router
- Route Groups
- Layouts
- Server Components
- Client Components

---

## Performance

Inspect:

- Image Optimization
- Metadata API
- Dynamic Imports
- Caching
- Streaming
- Static Generation
- ISR

---

## Common Findings

- Secrets exposed
- Missing CSP
- Large client bundles
- Wrong Server Component usage
- Excessive hydration

---

## Recommended Practices

- Server Components
- Edge Middleware
- Route Handlers
- next/image
- next/font
