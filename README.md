# Spec-Driven Starter Spec

A **contract-first spec** starter template designed to be paired with:

- https://github.com/chaseobservability/spec-driven-starter-implementation

Inspired by Sean Grove’s talk (Spec-Driven Development): https://youtu.be/8rABwKRsec4

Harness engineering reference: https://openai.com/index/harness-engineering/

## What belongs here
- API contract (OpenAPI)
- Data contracts (JSON Schemas)
- Deterministic rules and invariants
- Executable workflow specs (flow fixtures)
- Acceptance criteria
- Release and governance docs

## Where to start
- API contract: `interfaces/api.openapi.yaml`
- Schemas: `schemas/`
- Flows: `flows/`
- Engineering guidelines: `docs/ENGINEERING_GUIDELINES.md`
- Roadmap: `ROADMAP.md`

## Versioning
- Tag releases as `vX.Y.Z`.
- Breaking contract changes require a version bump and updated acceptance artifacts.

See `RELEASE_CHECKLIST.md`.


## Philosophy
See `SPEC_DRIVEN_DEVELOPMENT_PHILOSOPHY.md`.

## Docs
- Agent map: `AGENTS.md`
- Harness index: `docs/index.md`
- Starter pack contract: `SDD_STARTER_PACK_CONTRACT.md`
- Philosophy: `SPEC_DRIVEN_DEVELOPMENT_PHILOSOPHY.md`
- Engineering guidelines: `docs/ENGINEERING_GUIDELINES.md`
- ADR template: `docs/decisions/ADR_TEMPLATE.md`
- Spec → Implementation upgrade guide: `SPEC_TO_IMPLEMENTATION_UPGRADE_GUIDE.md`
- Roadmap: `ROADMAP.md`
- Contributing: `CONTRIBUTING.md`
- Release checklist: `RELEASE_CHECKLIST.md`
