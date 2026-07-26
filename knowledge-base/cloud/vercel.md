# Vercel Audit Profile

## Overview

Vercel is a deployment platform optimized for frontend frameworks and serverless applications.

---

## Detection

Typical indicators:

- vercel.json
- Vercel CLI
- Next.js deployment
- Vercel Environment Variables

---

## Security Focus

Inspect:

- Environment Variables
- API Routes
- Server Actions
- Edge Functions
- Preview Deployments
- Secret exposure

---

## Infrastructure Focus

Inspect:

- Deployment configuration
- Domains
- Edge Network
- Function configuration

---

## Performance Focus

Inspect:

- ISR
- Static Generation
- Edge Functions
- Image Optimization
- Caching

---

## Common Findings

- Public environment variables
- Incorrect caching
- Secrets exposed to client
- Misconfigured Server Actions
- Large serverless functions

---

## Recommended Practices

- Keep secrets server-side
- Use ISR when applicable
- Optimize images
- Configure caching correctly
- Monitor deployments

---

## References

- Vercel Documentation
