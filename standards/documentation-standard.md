# Documentation Standard

# Documentation Standard

**Identifier:** STD-0002
**Title:** Documentation Standard
**Status:** Draft
**Version:** 1.0.0
**Category:** Standard
**Depends On:**

* FOUNDATION
* FND-0003 Principles
* FND-0004 Governance
* STD-0001 Specification Standard

**Review Status:** Draft

---

# 1. Purpose

This standard defines the documentation conventions used throughout the Thinking Standard repository.

Its purpose is to ensure that every document remains:

* consistent,
* readable,
* maintainable,
* reviewable,
* implementation independent.

---

# 2. Scope

This standard applies to every Markdown document within the repository.

Including:

* README
* Foundation
* ADR
* Specification
* Standard
* Reference
* Guides
* Future documentation

---

# 3. Documentation Principles

Documentation shall be:

* accurate,
* concise,
* technically precise,
* implementation independent,
* internally consistent.

Documentation should explain concepts rather than repeat them.

---

# 4. Single Responsibility

Each document shall have one primary purpose.

Documents should reference related documents rather than duplicate content.

---

# 5. Layering

Documentation shall follow the architectural hierarchy.

```text
Foundation
        ↓
Architecture
        ↓
Specification
        ↓
Standards
        ↓
Reference
```

Lower layers shall not redefine concepts established in higher layers.

---

# 6. Cross References

Documents SHOULD reference related artifacts where appropriate.

Cross references improve traceability and reduce duplication.

---

# 7. Terminology

Canonical terminology SHALL be taken from:

SPEC-0000 Vocabulary.

New terminology shall not be introduced casually.

---

# 8. Writing Style

Documentation should prefer:

* precise language,
* active voice,
* short paragraphs,
* consistent terminology,
* unambiguous statements.

Avoid:

* marketing language,
* unnecessary adjectives,
* speculative statements,
* implementation assumptions.

---

# 9. Diagrams

Diagrams should:

* clarify architecture,
* remain implementation independent,
* use consistent terminology,
* complement rather than replace specifications.

ASCII diagrams are preferred for portability.

---

# 10. Examples

Examples should illustrate concepts.

Examples are informative.

Examples shall not introduce normative requirements.

---

# 11. Markdown Conventions

Documentation should use:

* ATX headings (`#`, `##`, `###`)
* fenced code blocks
* tables where appropriate
* ordered lists for procedures
* unordered lists for collections

Markdown extensions should be avoided unless widely supported.

---

# 12. Versioning

Normative documents should include:

* Identifier
* Title
* Status
* Version
* Category
* Dependencies
* Review Status

Reference documents may simplify metadata where appropriate.

---

# 13. Repository Organization

Documentation should reside in the directory corresponding to its architectural category.

Examples:

```text
foundation/
architecture/
specification/
standards/
reference/
```

Repository organization should reflect conceptual organization.

---

# 14. Review

Every significant documentation change should be reviewed for:

* technical correctness,
* consistency,
* editorial quality,
* architectural alignment.

Review comments should be resolved before publication.

---

# 15. Long-Term Maintenance

Documentation should be written for longevity.

Documents should remain understandable despite changes in:

* programming languages,
* software implementations,
* tooling,
* storage technologies.

---

# 16. Conformance

A document conforms to this standard when it follows the documentation conventions defined herein.

---

# 17. Summary

The Documentation Standard establishes a consistent editorial framework for the Thinking Standard repository.

Its objective is to ensure that every document contributes to a coherent, maintainable, and implementation-independent body of knowledge.

