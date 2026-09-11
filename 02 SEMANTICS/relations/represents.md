# Represents

## Identity / Metadata

- **GIOP ID:** `SEM-RELATION-REPRESENTS-001`
- **Title:** Represents
- **Artifact Type:** Canonical Relation Concept
- **Primary Responsibility:** Reusable relation connecting a representation to the entity, phenomenon, state, event, or information it represents.
- **Semantic Family:** Representation Relation
- **Status:** CANONICAL
- **Version:** V3.1
- **Authority:** GIOP canonical semantic synthesis
- **Lifecycle:** ACTIVE
- **Provenance:** GIOP semantic research and cross-layer reconciliation
- **Related IDs:** `SEM-CLASS-REPRESENTATION-001`, `SEM-RELATION-OBSERVES-001`, `SEM-RELATION-DERIVED-FROM-001`

## 5W1H Orientation

### What

`represents` connects a representation to a target or referent that the representation semantically stands for, depicts, encodes, models, describes, or otherwise represents under a defined representational convention.

### Why

It distinguishes representational correspondence from physical observation, structural composition, provenance, and mere association.

### Who / What participates

The subject is a Representation or other eligible representational entity. The object is the represented target or referent.

### Where

It applies to images, encoded data, diagrams, metadata-bearing representations, models, records, and other information-bearing representations where representational semantics are established.

### When

Representation may be time-specific or version-specific. A representation may represent a target at a particular state, observation time, or semantic scope.

### How

An assertion identifies the representation and its referent and states the canonical representational relation, optionally with qualification.

## Semantic Definition

**Represents is a reusable relation concept specifying that an eligible representation stands for, depicts, encodes, models, describes, or otherwise represents an eligible target or referent under an established representational semantics.**

The relation concerns semantic representational correspondence. It does not assert that the representation is a complete, accurate, original, lossless, or physically identical copy of its target.

## Relation Family

`represents` belongs to the representation relation family.

It can connect representations to physical entities, scenes, objects, phenomena, states, events, concepts, or other referents depending on the representational system.

## Subject / Domain

The subject/domain is an eligible Representation or representational artifact.

Examples include:

- an image representation representing a scene;
- a diagram representing a system;
- encoded data representing measured observations;
- a model representing a physical or conceptual target.

An arbitrary file is not automatically a representation of a particular target merely because it contains related information.

## Object / Range

The object/range is an eligible represented target or referent.

The referent may be physical, conceptual, informational, event-based, or state-specific, depending on the representation's semantics.

## Directionality

`represents` is directed:

`REPRESENTATION → REFERENT`

The inverse may be expressed as `is-represented-by` when useful, but the inverse need not be a separate canonical concept.

## Logical Characteristics

`represents` is not generally symmetric.

It is not generally transitive. If representation A represents B and B represents C, A does not automatically represent C.

Multiple representations may represent the same target, and one representation may represent multiple targets or aspects of a target when its semantics permit.

The relation does not imply uniqueness, bijection, or identity.

## Applicability

Use `represents` when a representational convention establishes a semantic connection between the representation and its referent.

The representational convention may be explicit or sufficiently supported by domain context, but it must not be inferred from superficial similarity alone.

## Distinctions / Non-equivalence

### Represents vs Observes

An observer observes a target. A representation represents a target. A representation may be produced from observation, but representation is not itself observation.

### Represents vs Derived From

A representation may be derived from another artifact while also representing a target. Provenance and representational semantics are independent relations.

### Represents vs Part Of

A representation representing a scene is not thereby a structural part of the scene.

### Represents vs Corresponds To

`corresponds-to` may be a broader or differently qualified relation. `represents` specifically carries representational semantics and must not be used as a generic synonym for any correspondence.

### Represents vs Is Identical To

A representation is not necessarily identical to its referent. Encoding, abstraction, sampling, transformation, and loss may intervene.

## Qualification / Context

Relevant qualification may include:

- representational convention;
- scope or aspect represented;
- temporal state of the referent;
- spatial extent;
- modality;
- encoding or model;
- provenance;
- fidelity or completeness information.

The relation itself should not be overloaded with fidelity claims.

## Inference Boundary

From `represents` alone, a machine must not infer:

- physical identity;
- completeness;
- accuracy;
- losslessness;
- originality;
- direct observation;
- direct derivation;
- causal dependence.

Those properties require separate semantic concepts or evidence.

## Cross-Layer Relations

Typical GIOP concept-level patterns include:

`Representation represents Scene`

`Image Representation represents Object`

`Encoded Measurement Record represents Measurement Result`

A representation can simultaneously stand in relations such as `derived-from`, `represents`, and `part-of` where each assertion is independently justified.

## Typical GIOP Usage

Use `represents` in semantic image models, information representations, encoded records, diagrams, computational models, documentation, and knowledge graphs.

## Evidence / Provenance

The relation is supported by representational semantics across information modeling, imaging, documentation, and formal knowledge representation. RDF/OWL and related formal systems provide implementation and reasoning patterns, but GIOP defines its own canonical semantic boundary.

## Trust / Validation

A representation assertion should be supported by explicit metadata, documentation, encoding conventions, acquisition context, model specification, or other evidence establishing the intended referent.

Visual or lexical similarity alone does not prove representation.

## Lifecycle

- **Current state:** ACTIVE / CANONICAL
- **Change control:** semantic changes require explicit review and versioning.
- **Supersession:** none currently.
- **Preservation:** historical semantic decisions remain auditable.

## Machine / AI Interpretation

A machine should interpret `represents` as a directed semantic predicate from a representation to its referent.

It must preserve uncertainty and qualification and must not infer accuracy, fidelity, identity, observation, or provenance from the relation alone.

## Retrieval Anchors

`represents`, `representation of`, `represented by`, `referent`, `depicts`, `encodes`, `models`, `describes`, `representational relation`, `semantic representation`

## What This Relation Does NOT Mean

It does not by itself mean:

- observes;
- derived-from;
- identical-to;
- accurate representation;
- complete representation;
- lossless representation;
- original artifact;
- physically co-located;
- part-of.

## Semantic Boundary

**Represents is the GIOP relation for semantic representation between a representation and its referent. It must remain distinct from observation, provenance, identity, structural composition, and generic correspondence.**
