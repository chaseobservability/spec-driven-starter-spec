# AGENTS.md

This repository is agent-first. Keep this file short and use it as a map.

## Mission
- Own contract-first specification artifacts.
- Keep contracts deterministic and machine-verifiable.

## Start Here
- Repo overview: `README.md`
- Engineering guardrails: `docs/ENGINEERING_GUIDELINES.md`
- Harness map: `docs/index.md`
- Architecture map: `docs/architecture/index.md`
- Product/spec map: `docs/product-specs/index.md`
- Execution plans: `docs/exec-plans/`
- References: `docs/references/index.md`

## Source of Truth
- API contract: `interfaces/api.openapi.yaml`
- Schemas: `schemas/*.json`
- Acceptance flows: `flows/*.yaml`
- Governance: `ROADMAP.md`, `RELEASE_CHECKLIST.md`, `CHANGELOG.md`

## Invariants
- Contracts parse cleanly.
- Flows remain deterministic.
- Breaking changes require versioning + changelog updates.

## Workflow
1. Define or change contract artifacts.
2. Update docs and execution plan when needed.
3. Run local checks.
4. Open small PRs with explicit scope.

## CI Expectations
- OpenAPI parse passes.
- JSON schema parse passes.
- Flow parse passes.
- Governance + harness docs exist.
