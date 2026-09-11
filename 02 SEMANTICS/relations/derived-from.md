# Derived From

## Identity / Metadata

- **GIOP ID:** `SEM-RELATION-DERIVED-FROM-001`
- **Title:** Derived From
- **Artifact Type:** Canonical Relation Concept
- **Primary Responsibility:** Reusable provenance relation specifying that one artifact, representation, result, or semantic product has its provenance in another entity or artifact.
- **Semantic Family:** Provenance / Lineage Relation
- **Status:** CANONICAL
- **Version:** V3.1
- **Authority:** GIOP canonical semantic synthesis
- **Lifecycle:** ACTIVE
- **Provenance:** GIOP semantic research and cross-layer reconciliation
- **Related IDs:** `SEM-CLASS-REPRESENTATION-001`, `SEM-RELATION-REPRESENTS-001`

## 5W1H Orientation

### What

`derived-from` expresses provenance or lineage from a source entity, artifact, representation, result, or other eligible predecessor to a derived entity.

### Why

It records lineage without collapsing derivation into identity, representation, structural composition, or a particular transformation process.

### Who / What participates

The subject is the derived entity. The object is its source or predecessor.

### Where

It applies to artifacts, representations, data products, transformed outputs, analysis results, or other entities for which provenance is meaningful.

### When

Derivation may be time-ordered and may involve one or more intermediate activities or processes.

### How

An assertion identifies the derived entity and source and states the provenance relation. More detailed provenance may qualify the derivation with generating activity, agent, time, parameters, or other provenance information.

## Semantic Definition

**Derived From is a reusable provenance relation concept specifying that a first entity has lineage originating from, or is produced through transformation or derivational dependence upon, a second eligible source entity.**

The relation records provenance, not necessarily physical causation, structural part–whole constitution, or representational reference.

## Relation Family

`derived-from` belongs to the provenance / lineage relation family.

It is intentionally broad enough to represent derivational lineage while allowing more qualified provenance relations to describe the generating activity, responsible agent, or exact transformation.

## Subject / Domain

The subject/domain is an eligible derived entity, such as:

- an image derivative;
- a transformed representation;
- an analysis result;
- a processed dataset;
- a rendered artifact;
- a documentation artifact derived from another source.

## Object / Range

The object/range is an eligible source, predecessor, parent artifact, source representation, dataset, result, or other entity from which the subject derives.

## Directionality

`derived-from` is directed:

`DERIVED ENTITY → SOURCE / PREDECESSOR`

A conventional inverse is `had-derived-output` or an equivalent formulation, but GIOP does not require a separate canonical inverse page merely to reverse the direction.

## Logical Characteristics

`derived-from` is directed and not symmetric.

It is not automatically transitive as an unrestricted inference rule. Provenance chains may often be traversed transitively for lineage discovery, but the exact semantics of transitive closure depend on the provenance model and whether intermediate derivations are semantically preserved.

A machine must not assume that transitive provenance traversal is equivalent to direct derivation.

The relation does not imply functional uniqueness: one source may yield many derived artifacts, and one derived artifact may have multiple sources.

## Applicability

Use `derived-from` when there is sufficient evidence of derivational lineage between the subject and source.

Where the exact generating activity or provenance agent is known, those may be represented separately rather than encoded ambiguously in the relation name.

## Distinctions / Non-equivalence

### Derived From vs Represents

A representation may represent a target without being derived from it. Conversely, an artifact may be derived from a source without representing that source.

### Derived From vs Part Of

Derivational lineage does not imply structural constitution.

### Derived From vs Causes

Provenance derivation is not automatically a general causal relation. A process may physically or computationally cause an output, but `derived-from` records lineage rather than asserting a complete causal theory.

### Derived From vs Same As

A derived artifact may preserve some information from a source while remaining a distinct entity. Derivation does not imply identity.

### Derived From vs Uses

A process may use a source without producing an artifact derived from it in the relevant semantic sense. Provenance concerns lineage of the resulting entity.

## Qualification / Context

Provenance may be qualified by:

- generating activity or process;
- agent or responsible entity;
- time;
- transformation;
- version;
- parameters;
- source role;
- derivation method;
- confidence or evidence.

Qualified provenance should be preferred when the unqualified relation would obscure important lineage distinctions.

## Inference Boundary

`derived-from` supports provenance-chain reasoning only within the declared provenance model.

It does not automatically imply:

- identity;
- exact duplication;
- representation;
- causation in every physical sense;
- part-of;
- quality or fidelity;
- authorship or responsibility.

## Cross-Layer Relations

Typical concept-level patterns include:

`Processed Image represents Scene`

`Processed Image derived-from Original Image`

`Analysis Result derived-from Measurement Result`

`Rendered Representation derived-from Source Representation`

The same entity may participate in multiple independent provenance and representational relations.

## Typical GIOP Usage

Use `derived-from` for asset lineage, image processing chains, dataset lineage, transformation history, reproducibility, archival provenance, and machine-readable provenance graphs.

## Evidence / Provenance

The relation is strongly informed by W3C PROV-O and established provenance modeling, including derivation, generation, usage, and attribution distinctions. PROV-O is evidence and a design reference; GIOP's canonical semantics remain independently synthesized.

## Trust / Validation

A derivation assertion should be supported by processing records, source metadata, transformation logs, reproducible workflows, archival records, or other provenance evidence.

File similarity or naming conventions alone do not establish derivation.

## Lifecycle

- **Current state:** ACTIVE / CANONICAL
- **Change control:** semantic changes require explicit review and versioning.
- **Supersession:** none currently.
- **Preservation:** provenance decisions and historical definitions remain auditable.

## Machine / AI Interpretation

A machine should interpret `derived-from` as a directed provenance predicate from derived entity to source entity.

It must preserve the distinction between direct and inferred lineage and must not infer identity, representation, causation, authorship, or fidelity without additional evidence.

## Retrieval Anchors

`derived from`, `derived-from`, `derivation`, `lineage`, `provenance`, `source artifact`, `predecessor`, `generated from`, `transformed from`, `data lineage`

## What This Relation Does NOT Mean

It does not by itself mean:

- represents;
- part-of;
- same-as;
- causes;
- authored-by;
- uses;
- identical copy;
- lossless transformation;
- accurate transformation.

## Semantic Boundary

**Derived From is the GIOP provenance relation for derivational lineage between a derived entity and its source. It must remain distinct from representation, structural composition, identity, generic causation, and operational use.**
