Frontend Best Practices (React / Next.js)

1. Favor simplicity and readability over clever abstractions.
2. Organize by feature, not file type (/events, /users).
3. Co-locate components, styles, and tests together.
4. Keep components small, focused, and pure.
5. Separate logic from presentation using custom hooks.
6. Use composition instead of inheritance.
7. Name components and hooks by intent and clarity.
8. Lift state only when necessary; keep it local when possible.
9. Use React Query or SWR for data fetching and caching.
10. Derive values instead of duplicating state.
11. Keep CSS shallow; prefer tokens or theme variables.
12. Be consistent with one styling approach (Tailwind, CSS Modules, etc.).
13. Test user behavior, not implementation details.
14. Keep tests near the components they cover.
15. Lazy-load heavy components and pages where practical.
16. Use memoization only when profiling shows a need.
17. Structure Next.js routes with clear layouts and groups.
18. Use server components for data fetching when possible.
19. Keep client components lean and interactive only where needed.
20. Ship small, learn fast, and refactor continuously.