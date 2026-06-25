# Thinking Roadmap

> **Status:** Draft
> **Purpose:** Define the ordered development phases for the Thinking Knowledge Operating System.

## Roadmap Principle

Thinking MUST evolve from constitutional foundations toward implementation only through documented specifications, architecture, and knowledge assets.

Each phase MUST depend on the phases before it. Work SHOULD proceed in the order defined here unless an architectural decision explicitly changes the sequence.

## Phase 0 - Constitution

Phase 0 MUST establish the repository's governing foundation.

Required artifacts:

- `FOUNDATION.md`
- `AGENTS.md`

## Phase 1 - Core Specifications

Phase 1 MUST define the core conceptual specifications that govern knowledge representation.

Required specifications:

- Knowledge Language
- Knowledge Model
- Identity
- Relationships
- Lifecycle
- Metadata

## Phase 2 - Architecture

Phase 2 MUST define the architectural structures that organize and constrain the repository.

Required architecture assets:

- Architecture Decision Records
- Repository Blueprint
- Standards

## Phase 3 - Knowledge

Phase 3 MUST develop durable knowledge assets after the foundation, specifications, and architecture are in place.

Required knowledge areas:

- Research
- Frameworks
- Patterns
- Reference material

## Phase 4 - Implementations

Phase 4 MUST introduce implementations only after the required foundation, specifications, architecture, and knowledge assets justify them.

Potential implementation surfaces:

- CLI
- Desktop
- Web
- AI
- APIs

## Dependency Rule

Implementation work MUST NOT begin before the relevant specifications and architectural decisions exist. Missing architecture MUST stop implementation work until the gap is resolved.
