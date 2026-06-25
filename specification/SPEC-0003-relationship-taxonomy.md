# SPEC-0003: Relationship Taxonomy

# SPEC-0003: Relationship Taxonomy

**Identifier:** SPEC-0003
**Title:** Relationship Taxonomy
**Status:** Draft
**Version:** 1.0.0
**Category:** Core Specification
**Depends On:** SPEC-0001, SPEC-0002
**Review Status:** Draft

---

# 1. Purpose

This specification defines the semantic relationships between Knowledge Objects.

Relationships provide the structure through which individual Knowledge Objects form coherent knowledge networks.

---

# 2. Scope

This specification defines:

* relationship concepts,
* relationship rules,
* relationship constraints,
* relationship categories.

It does not define graph databases, storage models, or query languages.

---

# 3. Definition

A Relationship is a typed semantic association between two or more Knowledge Objects.

Relationships are semantic constructs.

They are not implementation details.

---

# 4. Relationship Properties

Every Relationship SHALL define:

* Relationship Type
* Source Knowledge Object
* Target Knowledge Object

Relationships MAY additionally define:

* Direction
* Strength
* Confidence
* Validity Period
* Provenance

---

# 5. Cardinality

The Thinking Standard supports:

* One-to-One
* One-to-Many
* Many-to-One
* Many-to-Many

Cardinality is an implementation concern unless constrained by a specific specification.

---

# 6. Relationship Categories

The following categories are defined.

## Structural

Examples:

* contains
* composed-of
* part-of

---

## Semantic

Examples:

* defines
* describes
* explains
* represents

---

## Dependency

Examples:

* depends-on
* requires
* blocks

---

## Reference

Examples:

* references
* cites
* links-to

---

## Temporal

Examples:

* precedes
* follows
* supersedes

---

## Derivation

Examples:

* derived-from
* generated-from
* inferred-from

---

## Validation

Examples:

* supports
* contradicts
* validates
* invalidates

---

# 7. Relationship Rules

Every Relationship SHALL:

* connect valid Knowledge Objects,
* possess exactly one Relationship Type,
* preserve semantic consistency.

Relationships SHALL NOT redefine the meaning of connected Knowledge Objects.

---

# 8. Directionality

Relationships MAY be:

* directed,
* bidirectional,
* symmetric.

The relationship definition determines directionality.

---

# 9. Relationship Identity

Relationships MAY possess their own stable identity.

Implementations that assign identity shall preserve it independently of storage.

---

# 10. Relationship Evolution

Relationship definitions may evolve.

Relationship identity, where assigned, should remain stable.

Historical relationships should remain traceable.

---

# 11. Conformance

Conforming implementations shall preserve relationship semantics independently of representation or storage.

---

# 12. Summary

Relationships transform isolated Knowledge Objects into interconnected semantic knowledge.

They constitute the structural foundation upon which reasoning, navigation, traceability, and knowledge evolution are built.
