# SPEC-0005: Metadata Schema

# SPEC-0005: Metadata Schema

**Identifier:** SPEC-0005
**Title:** Metadata Schema
**Status:** Draft
**Version:** 1.0.0
**Category:** Core Specification
**Depends On:** SPEC-0000 (Vocabulary), SPEC-0001 (Knowledge Language), SPEC-0002 (Knowledge Object), SPEC-0004 (Identity Model)
**Review Status:** Draft

---

# 1. Purpose

This specification defines the metadata required to describe Knowledge Objects within the Thinking Standard.

Metadata provides descriptive, administrative, and governance information while remaining separate from the semantic content of a Knowledge Object.

---

# 2. Scope

This specification defines:

* mandatory metadata,
* optional metadata,
* metadata constraints,
* metadata evolution,
* metadata interoperability.

It does not define serialization formats, storage mechanisms, or database schemas.

---

# 3. Definition

Metadata is structured descriptive information associated with a Knowledge Object.

Metadata describes a Knowledge Object but SHALL NOT define or alter its semantic meaning.

---

# 4. Design Principles

Metadata SHALL be:

* implementation independent,
* representation independent,
* extensible,
* machine interpretable,
* human understandable.

---

# 5. Mandatory Metadata

Every Knowledge Object SHALL define the following metadata.

| Field      | Description                             |
| ---------- | --------------------------------------- |
| Identifier | Stable identity of the Knowledge Object |
| Type       | Primary Knowledge Type                  |
| Title      | Human-readable title                    |
| Status     | Current lifecycle status                |
| Version    | Revision identifier                     |
| Created    | Creation timestamp                      |
| Updated    | Most recent modification timestamp      |

---

# 6. Recommended Metadata

Implementations SHOULD support:

* Summary
* Description
* Author
* Contributors
* Tags
* Keywords
* Language
* License
* Namespace
* Classification

---

# 7. Extended Metadata

Implementations MAY define additional metadata including:

* External identifiers
* Domain-specific attributes
* Security classifications
* Access control information
* Localization data
* Digital signatures
* Custom extensions

Extensions SHALL NOT contradict this specification.

---

# 8. Metadata Constraints

Metadata SHALL satisfy the following constraints.

* Metadata SHALL describe the Knowledge Object.
* Metadata SHALL NOT redefine semantic meaning.
* Metadata SHALL remain independent of storage technology.
* Metadata SHALL support forward compatibility.
* Unknown metadata fields SHOULD be safely ignored by conforming implementations unless explicitly required.

---

# 9. Metadata Evolution

Metadata may evolve independently of semantic content.

Adding descriptive metadata SHALL NOT create a new Knowledge Object.

Changes to metadata SHALL preserve the Knowledge Object identity.

---

# 10. Metadata and Identity

Identity is metadata but possesses special architectural significance.

Identity SHALL remain stable across:

* revisions,
* migrations,
* serialization changes,
* implementation changes.

Identity rules are defined by SPEC-0004.

---

# 11. Metadata and Relationships

Relationships are not metadata.

Relationships are independent semantic constructs defined by SPEC-0003.

Metadata may describe relationships but SHALL NOT replace them.

---

# 12. Interoperability

Conforming implementations SHOULD preserve all recognized metadata during import, export, synchronization, and transformation.

Metadata loss SHOULD be minimized.

---

# 13. Conformance

A conforming implementation SHALL:

* preserve mandatory metadata,
* maintain metadata consistency,
* separate metadata from semantic content,
* preserve identity during metadata updates.

---

# 14. Future Extensions

Future specifications may introduce standardized metadata profiles for particular domains or implementations.

Such profiles SHALL remain compatible with this specification.

---

# 15. Summary

Metadata provides the descriptive framework surrounding a Knowledge Object.

It supports discovery, governance, traceability, interoperability, and lifecycle management while remaining distinct from the semantic content of the Knowledge Object itself.

