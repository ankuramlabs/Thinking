# SPEC-0000: Vocabulary

# SPEC-0000: Vocabulary

**Identifier:** SPEC-0000
**Title:** Canonical Vocabulary
**Status:** Draft
**Version:** 1.0.0
**Category:** Core Specification
**Depends On:** FND-0001, ADR-0001, ADR-0002
**Review Status:** Draft

---

# 1. Purpose

This specification defines the canonical vocabulary of the Thinking Standard.

The purpose of this document is to ensure that every architectural decision, specification, standard, implementation, and conforming system uses a common and unambiguous terminology.

No subsequent specification shall redefine terms established by this document.

---

# 2. Scope

This specification applies to:

* Foundation documents
* Architecture Decision Records (ADR)
* Specifications (SPEC)
* Standards (STD)
* Reference material
* Conforming implementations

---

# 3. Normative Language

The key words **SHALL**, **MUST**, **SHOULD**, **SHOULD NOT**, **MAY**, and **MUST NOT** are to be interpreted as normative requirements.

---

# 4. Canonical Terms

## Meaning

The conceptual significance intended to be preserved independent of any particular representation.

---

## Semantics

The formal interpretation of meaning that enables consistent understanding, communication, and reasoning.

---

## Knowledge

Structured semantics organized for reasoning, communication, and decision-making.

---

## Knowledge Object

The fundamental semantic unit managed by the Thinking Standard.

Every Knowledge Object SHALL possess a stable identity independent of its representation.

---

## Knowledge Type

The primary classification assigned to a Knowledge Object.

Each Knowledge Object SHALL have exactly one primary Knowledge Type.

Additional classifications MAY be introduced through metadata or relationships.

---

## Representation

A concrete encoding of a Knowledge Object.

Representations include, but are not limited to:

* Markdown
* JSON
* YAML
* XML
* RDF
* SQL
* Graph structures

Representations SHALL NOT define semantics.

---

## Identity

A stable identifier assigned to a Knowledge Object.

Identity SHALL remain independent of representation, storage, and implementation.

---

## Relationship

A typed semantic connection between two or more Knowledge Objects.

Relationships SHALL be explicit.

---

## Metadata

Descriptive information associated with a Knowledge Object.

Metadata describes a Knowledge Object without altering its semantic meaning.

---

## Provenance

Information describing the origin, ownership, derivation, revision history, and evolution of a Knowledge Object.

---

## Evidence

Information supporting, explaining, validating, or challenging a Knowledge Object.

---

## Confidence

An assessment of the reliability or certainty associated with a Knowledge Object.

Confidence represents belief in correctness rather than correctness itself.

---

## Lifecycle

The current maturity state of a Knowledge Object throughout its existence.

Lifecycle states are defined separately by the Lifecycle specification.

---

## Standard

A normative document defining required behaviour or structure.

---

## Specification

A normative technical definition describing a component of the Thinking Standard.

---

## Architecture Decision Record (ADR)

A document recording a significant architectural decision together with its rationale and consequences.

---

## Implementation

Any software, system, repository, service, or platform that claims conformance with the Thinking Standard.

Implementations SHALL conform to the specifications.

Specifications SHALL NOT depend upon implementations.

---

# 5. Reserved Terms

The following terms are reserved by the Thinking Standard:

* Meaning
* Semantics
* Knowledge
* Knowledge Object
* Knowledge Type
* Representation
* Identity
* Relationship
* Metadata
* Provenance
* Evidence
* Confidence
* Lifecycle
* Specification
* Standard
* Architecture Decision Record
* Implementation

These terms SHALL be interpreted according to this specification.

---

# 6. Vocabulary Governance

New canonical terms MAY be added through future revisions.

Existing canonical definitions SHALL NOT be redefined without constitutional review.

---

# 7. Conformance

Every normative artifact within the Thinking Standard SHALL use the vocabulary defined by this specification.

Where ambiguity exists, this specification takes precedence over informal usage.

---

# 8. Summary

The Thinking Standard depends upon a controlled vocabulary to ensure semantic consistency across architecture, specifications, standards, and implementations.

This vocabulary establishes the common language upon which the remainder of the standard is built.

