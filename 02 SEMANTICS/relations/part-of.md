# Part Of

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-PART-OF-001`
- **Preferred Term:** `part-of`
- **Artifact Type:** Canonical Relation Concept
- **Semantic Family:** Structural / Partitive
- **Primary Responsibility:** Structural constitution between a part and a whole.
- **Status:** ACTIVE — SCOPED CANONICAL
- **Version:** 1.0.0
- **Authority:** GIOP canonical semantic synthesis

## 5W1H Orientation
**What:** A directed part–whole relation.
**Why:** To express structural constitution without conflating it with use, participation, location, observation, or provenance.
**Who/What:** Subject is the part; object is the whole/composite.
**Where:** Any genuine structural composition or membership context.
**When:** May require lifecycle/configuration qualification when membership changes.
**How:** Identify both endpoints and assert the relation with the applicable structural evidence.

## Semantic Definition
**Part Of specifies that the subject constitutes or belongs as a structural part of the object within a recognized part–whole organization.**

## Relation Contract
- **Domain:** Eligible part/component/constituent/member/substructure.
- **Range:** Eligible whole/composite/system/assembly/structure.
- **Direction:** `PART → WHOLE`.
- **Inverse:** `has-part` (retrieval/inverse term; not independently canonicalized here).
- **Characteristics:** Not symmetric. Proper-part interpretation is normally irreflexive. Transitive closure is permitted only where the asserted semantics genuinely support it.

## Qualification / Context
Relevant qualification may include lifecycle interval, assembly configuration, version, system architecture, and domain-specific structural convention.

## Core Distinctions
`part-of` is not `participates-in`, `uses`, `located-in`, `derived-from`, `observes`, or `represents`. Physical proximity, co-occurrence, operational use, or provenance do not establish part–whole constitution by themselves.

## Inference Boundary
Permitted inference is limited to the declared inverse and semantically justified transitive closure. No functional, causal, observational, spatial, operational, or provenance assertion follows from `part-of` alone.

## Cross-Layer Significance
Supports structural graphs such as `Sensor part-of Camera/System` and `Lens Element part-of Lens Assembly`. A class-level pattern does not create an instance assertion without evidence.

## Trust / Validation
Assertions require authoritative structural documentation, engineering architecture, explicit composition semantics, or equivalent evidence. Textual co-occurrence is insufficient.

## Machine / AI Interpretation
Encode a directed predicate from part to whole. Preserve qualification and distinguish asserted from inferred closure.

## Lifecycle
ACTIVE — semantic changes require explicit review, versioning, and preservation of prior decisions.

## Retrieval Anchors
`part of`, `part-of`, `has part`, `has-part`, `part–whole`, `partitive`, `structural composition`, `constituent`, `substructure`

## Semantic Boundary
**Part Of is the GIOP relation for structural part–whole constitution and must remain distinct from participation, use, spatial containment, provenance, observation, and representation.**
