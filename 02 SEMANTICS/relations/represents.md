# Represents

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-REPRESENTS-001`
- **Preferred Term:** `represents`
- **Artifact Type:** Canonical Relation Concept
- **Semantic Family:** Representation
- **Primary Responsibility:** Semantic representational correspondence between a representation and its referent.
- **Status:** ACTIVE — SCOPED CANONICAL
- **Version:** 1.0.0
- **Authority:** GIOP canonical semantic synthesis

## 5W1H Orientation
**What:** A representation-to-referent relation.
**Why:** To express depiction, encoding, modeling, description, or other representational standing-for semantics.
**Who/What:** Subject is the representation; object is its referent.
**Where:** Images, encoded data, diagrams, records, models, and other information-bearing representations.
**When:** May be state-, time-, version-, or scope-specific.
**How:** Establish the representational convention and identify the referent.

## Semantic Definition
**Represents specifies that an eligible representation stands for, depicts, encodes, models, describes, or otherwise represents an eligible target or referent under established representational semantics.**

It does not imply completeness, accuracy, identity, originality, or losslessness.

## Relation Contract
- **Domain:** Eligible Representation or representational artifact.
- **Range:** Eligible referent/target, physical or conceptual.
- **Direction:** `REPRESENTATION → REFERENT`.
- **Inverse:** `is-represented-by` (inverse/retrieval term; not independently canonicalized here).
- **Characteristics:** Not generally symmetric or transitive. No uniqueness or identity is implied.

## Qualification / Context
Representational convention, represented scope/aspect, temporal state, spatial extent, modality, encoding/model, provenance, and fidelity/completeness information may qualify an assertion.

## Core Distinctions
`represents` ≠ `observes`, `derived-from`, `part-of`, `identical-to`, or generic correspondence. A representation may be observed or derived while retaining a separate representational relation.

## Inference Boundary
Do not infer physical identity, completeness, accuracy, losslessness, originality, observation, derivation, or causation from `represents` alone.

## Cross-Layer Significance
Connects the Representation layer to scenes, objects, phenomena, states, events, concepts, and other referents. Example: `Image Representation represents Scene`.

## Trust / Validation
Use explicit metadata, representational conventions, encoding/model specifications, acquisition context, or equivalent evidence. Superficial visual/lexical similarity is insufficient.

## Machine / AI Interpretation
Encode a directed predicate from representation to referent while preserving scope and qualification. Fidelity must be represented separately.

## Lifecycle
ACTIVE — semantic changes require explicit review, versioning, and preservation.

## Retrieval Anchors
`represents`, `representation of`, `represented by`, `referent`, `depicts`, `encodes`, `models`, `describes`, `representational relation`

## Semantic Boundary
**Represents is the GIOP relation for semantic representation between a representation and its referent and must remain distinct from observation, provenance, identity, structural composition, and generic correspondence.**
