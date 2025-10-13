Backend Best Practices (Python / FastAPI)

1. Design for simplicity, clarity, and change.
2. Organize by feature (users/, orders/) with clear module boundaries.
3. Keep route handlers thin; put logic in services.
4. Use Pydantic for validation and type safety.
5. Separate request/response schemas from domain models.
6. Manage DB access through repository classes.
7. Handle transactions explicitly; use Alembic for migrations.
8. Version APIs (/api/v1) and return consistent errors.
9. Validate all inputs and sanitize all outputs.
10. Use dependency injection for DB, config, and user context.
11. Apply auth (JWT/OAuth2) and rate limiting where needed.
12. Write small, isolated tests; favor behavior over implementation.
13. Log in structured JSON with request IDs.
14. Collect metrics and traces for key endpoints.
15. Profile before optimizing; cache behind clear interfaces.
16. Retry external calls with backoff; batch expensive loops.
17. Follow 12-factor app principles for config and deploys.
18. Keep secrets out of code; use environment or secret manager.
19. Maintain OpenAPI docs with examples and changelogs.
20. Favor boring, predictable solutions that are easy to read and delete.