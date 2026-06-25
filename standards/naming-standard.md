# Naming Standard

# Naming Standard

**Identifier:** STD-0003
**Title:** Naming Standard
**Status:** Draft
**Version:** 1.0.0
**Category:** Standard
**Depends On:**

* FOUNDATION
* FND-0003 Principles
* STD-0001 Specification Standard
* STD-0002 Documentation Standard

**Review Status:** Draft

---

# 1. Purpose

This standard defines the naming conventions used throughout the Thinking Standard.

Its objectives are to ensure:

* consistency,
* discoverability,
* interoperability,
* long-term maintainability,
* machine readability.

---

# 2. Scope

This standard applies to:

* document identifiers,
* filenames,
* directories,
* Knowledge Types,
* relationship names,
* metadata fields,
* future specification families.

Implementation-specific naming is outside the scope of this standard.

---

# 3. General Principles

Names should be:

* descriptive,
* concise,
* stable,
* unambiguous,
* implementation independent.

Names should describe meaning rather than implementation.

---

# 4. Document Identifiers

Every normative document SHALL possess a unique identifier.

The following prefixes are reserved.

| Prefix | Category                     |
| ------ | ---------------------------- |
| FND    | Foundation                   |
| ADR    | Architecture Decision Record |
| SPEC   | Specification                |
| STD    | Standard                     |
| REF    | Reference                    |

Examples:

```text
FND-0001
ADR-0002
SPEC-0004
STD-0002
REF-0001
```

Identifiers are permanent.

Identifiers SHALL NOT be reused.

---

# 5. Filenames

Filenames should:

* use lowercase,
* separate words with hyphens,
* use the `.md` extension,
* describe document content.

Examples:

```text
knowledge-object.md
relationship-taxonomy.md
identity-model.md
metadata-schema.md
```

Avoid:

* spaces,
* version numbers,
* dates,
* implementation names.

---

# 6. Directory Names

Repository directories represent architectural categories.

Current categories include:

```text
foundation/
architecture/
specification/
standards/
reference/
```

Directory names should remain singular in purpose.

---

# 7. Knowledge Types

Knowledge Type names should:

* use singular nouns,
* begin with capital letters when used as formal type names,
* remain stable over time.

Examples:

* Concept
* Definition
* Requirement
* Decision
* Principle
* Specification
* Standard
* Evidence

---

# 8. Relationship Types

Relationship names should express semantic meaning.

Preferred forms include:

* depends-on
* references
* contains
* derives-from
* supports
* contradicts
* supersedes
* implements

Relationship names should describe intent rather than implementation.

---

# 9. Metadata Fields

Metadata field names should:

* be singular,
* use Title Case in documentation,
* remain implementation neutral.

Examples:

* Identifier
* Title
* Version
* Status
* Category
* Author
* Created
* Updated

Implementations may map these to language-specific conventions.

---

# 10. Reserved Names

The following document categories are reserved:

* Foundation
* Architecture
* Specification
* Standard
* Reference

Reserved identifiers defined by this standard shall not be repurposed.

---

# 11. Future Naming

Future specification families should follow the established identifier convention.

Examples:

```text
SPEC-0100 Query Language
SPEC-0200 Reasoning
SPEC-0300 Validation
SPEC-0400 Exchange
```

This numbering is illustrative rather than mandatory.

---

# 12. Stability

Names should evolve rarely.

Changing a name should not alter the underlying identity of the corresponding Knowledge Object.

Identifiers remain authoritative.

---

# 13. Conformance

Conforming repositories and derivative standards should follow the naming conventions established by this standard.

Minor implementation-specific adaptations are permitted provided semantic consistency is preserved.

---

# 14. Summary

Consistent naming improves readability, discoverability, interoperability, and long-term maintainability.

The Naming Standard establishes stable conventions that allow both humans and machines to navigate the Thinking Standard consistently.

