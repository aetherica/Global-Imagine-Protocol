# Derived From

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-DERIVED-FROM-001`
- **Preferred Term:** `derived-from`
- **Artifact Type:** Canonical Relation Concept
- **Semantic Family:** Provenance / Lineage
- **Primary Responsibility:** Derivational provenance between a derived entity and a source/predecessor.
- **Status:** ACTIVE — SCOPED CANONICAL
- **Version:** 1.0.0
- **Authority:** GIOP canonical semantic synthesis

## 5W1H Orientation
**What:** A directed provenance/lineage relation.
**Why:** To record derivation without collapsing it into identity, representation, structure, or generic causality.
**Who/What:** Subject is the derived entity; object is the source/predecessor.
**Where:** Artifacts, representations, data products, analysis results, rendered outputs, and documentation artifacts.
**When:** May involve ordered intermediate activities/processes.
**How:** Identify derived entity and source; qualify with generating activity or other provenance when known.

## Semantic Definition
**Derived From specifies that the subject has provenance or lineage originating from, or resulting through derivation or transformation from, the object.**

The relation records lineage; it is not a complete causal theory.

## Relation Contract
- **Domain:** Eligible derived entity/artifact/result/representation.
- **Range:** Eligible source/predecessor entity/artifact.
- **Direction:** `DERIVED ENTITY → SOURCE`.
- **Inverse:** Reverse provenance expression may be used for traversal; no separate canonical inverse page is required.
- **Characteristics:** Directed, not symmetric, and not globally transitive as an inference rule. Direct and inferred lineage must remain distinguishable. No functional uniqueness is implied.

## Qualification / Context
Generating activity/process, agent, time, transformation, version, parameters, source role, method, confidence, and evidence may qualify derivation.

## Core Distinctions
`derived-from` ≠ `represents`, `part-of`, `same-as`, `causes`, `uses`, or `authored-by`. Provenance is a claim about lineage, not merely use or similarity.

## Inference Boundary
Lineage traversal may be used within an approved provenance model, but inferred ancestry must not be represented as direct derivation. Do not infer identity, representation, causation, authorship, fidelity, or quality.

## Cross-Layer Significance
Supports chains such as `Processed Image derived-from Original Image` and `Analysis Result derived-from Measurement Result`. It can coexist with `represents` and `has-result` without replacing them.

## Trust / Validation
Support with processing records, source metadata, transformation logs, reproducible workflows, archival records, or equivalent provenance evidence. File similarity or naming conventions alone is insufficient.

## Machine / AI Interpretation
Encode a directed provenance predicate from derived entity to source and retain direct/inferred status plus qualification.

## Lifecycle
ACTIVE — semantic changes require explicit review, versioning, and preservation.

## Retrieval Anchors
`derived from`, `derived-from`, `derivation`, `lineage`, `provenance`, `source artifact`, `predecessor`, `generated from`, `transformed from`, `data lineage`

## Semantic Boundary
**Derived From is the GIOP provenance relation for derivational lineage and must remain distinct from representation, structural composition, identity, generic causation, and operational use.**
