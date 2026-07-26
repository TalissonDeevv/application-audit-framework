# React Audit Profile

## Overview

React is a JavaScript library for building user interfaces.

The AI Audit Framework (AAF) uses this profile to analyze React applications according to security, maintainability, performance and architecture best practices.

---

## Detection

Typical indicators:

- package.json
- react
- react-dom
- jsx
- tsx
- vite
- create-react-app

---

## Security Focus

Inspect:

- XSS
- dangerouslySetInnerHTML
- Client-side authentication
- JWT storage
- Secret exposure
- API endpoint exposure
- Environment variables
- CORS assumptions

---

## Architecture Focus

Evaluate:

- Folder structure
- Component organization
- State management
- Separation of concerns
- Reusable components

---

## Code Quality

Inspect:

- Component complexity
- Hook usage
- Custom hooks
- Dead components
- Duplicate logic
- Naming consistency

---

## Performance

Inspect:

- Memoization
- React.memo
- useMemo
- useCallback
- Lazy Loading
- Code Splitting
- Virtualization
- Large re-renders

---

## Common Findings

- Huge components
- Prop drilling
- Excessive re-rendering
- Secrets inside frontend
- JWT in localStorage
- Missing lazy loading

---

## Recommended Practices

- Functional Components
- Custom Hooks
- Feature-based architecture
- React Query
- TanStack Router
- Lazy imports
