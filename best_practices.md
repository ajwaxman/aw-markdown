Engineering Best Practices
Core Principles

1. Favor clarity over cleverness — code should explain itself.
2. Solve the problem you have now (YAGNI).
3. Optimize for reading, not writing — clarity beats brevity.
4. Code should be easy to delete, refactor, and evolve.
5. Keep functions, modules, and components small and focused.
6. Use clear, descriptive names that communicate intent.
7. Abstract only after proven repetition; duplication is often fine.
8. Consistency matters more than perfection.
9. Document the why, not the what.
10. Ship small, review often, and iterate quickly.

Frontend (React / Next.js)

1. Organize by feature, not file type; co-locate related files.
2. Keep components pure — no side effects in render.
3. Use custom hooks for shared logic, not shared state.
4. Lift state only when needed; derive values when possible.
5. Prefer composition over inheritance.
6. Use React Query or SWR for async data and caching.
7. Keep styling consistent — one approach, shallow selectors, use tokens.
8. Test user behavior, not implementation details.
9. Lazy-load and memoize only when measured performance needs it.
10. In Next.js, use server components for data, client components for interactivity.

Backend (Python / FastAPI)

1. Structure by feature (users/, orders/), not by layer.
2. Keep route handlers thin; move logic to services.
3. Use Pydantic for type-safe validation and serialization.
4. Manage DB access through repositories; handle transactions explicitly.
5. Version APIs (/api/v1) and return structured errors.
6. Validate all inputs and sanitize all outputs.
7. Enforce auth and permissions in the service layer.
8. Log in structured JSON with correlation IDs.
9. Profile before optimizing; cache and retry responsibly.
10. Follow 12-factor app principles for config, deploy, and scaling.