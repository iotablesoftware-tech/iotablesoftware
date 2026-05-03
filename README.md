# IoTable Implementation Specification

This repository contains the canonical implementation specification for IoTable.

IoTable is a multi-tenant cafe and restaurant operations platform. The specification in this repository is the source of truth for downstream implementation repositories.

## Structure

```text
specs/      YAML specification documents
schemas/    JSON Schemas for specification validation
tools/      validation and maintenance tooling
```

## Validation

```bash
pnpm install
pnpm validate
```

## Authoring rules

Start with:

- `specs/00-meta/specification-constitution.yaml`
- `specs/00-meta/documentation-index.yaml`
- `specs/00-meta/llm-execution-policy.yaml`

The canonical branch for this repository is `main`.
