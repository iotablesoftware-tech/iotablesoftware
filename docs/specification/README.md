# IoTable Implementation Specification

IoTable is a multi-tenant cafe and restaurant operations platform.

This directory contains the implementation specification for IoTable.

## Purpose

This specification is the canonical source for machine-readable implementation requirements used by coding agents and developers.

The specification precedes code. Code generated for IoTable must follow the documents in this directory.

## Format

- Source documents are written in YAML.
- Every YAML specification document must have a matching JSON Schema.
- Specification documents describe the intended final form of the system.
- The repository avoids migration-style, changelog-style, or patch-style specification language.

## Structure

```text
specs/      YAML source specifications
schemas/    JSON Schemas matching each YAML spec
tools/      Validation tooling
```

## Required meta documents

Specification work must start by reading:

- `specs/00-meta/specification-constitution.yaml`
- `specs/00-meta/documentation-index.yaml`

## Validation

From this directory:

```bash
pnpm install
pnpm validate
```
