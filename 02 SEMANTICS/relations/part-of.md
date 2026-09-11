# Part Of

## Identity / Metadata

- **GIOP ID:** `SEM-RELATION-PART-OF-001`
- **Title:** Part Of
- **Artifact Type:** Canonical Relation Concept
- **Primary Responsibility:** Reusable structural relation specifying that one participant is a constituent part of another.
- **Semantic Family:** Structural / Partitive Relation
- **Status:** CANONICAL
- **Version:** V3.1
- **Authority:** GIOP canonical semantic synthesis
- **Lifecycle:** ACTIVE
- **Provenance:** GIOP semantic research and cross-layer reconciliation
- **Related IDs:** `SEM-RELATION-PARTICIPATES-IN-001`, `SEM-CLASS-CAMERA-001`, `SEM-CLASS-LENS-001`, `SEM-CLASS-SENSOR-001`

## 5W1H Orientation

### What

`part-of` is a relation between a part and a whole, system, structure, or composite entity.

### Why

It represents structural constitution without confusing constitution with use, participation, observation, or provenance.

### Who / What participates

The subject is the part; the object is the whole or composite entity of which it is a part.

### Where

It applies wherever a GIOP entity or semantic element has a genuine part–whole structure.

### When

Its validity may be time-dependent where membership changes over a lifecycle. Temporal qualification is required when a static assertion would otherwise be misleading.

### How

A part–whole assertion is made by identifying the part and the whole and asserting the canonical `part-of` relation between them.

## Semantic Definition

**Part of is a reusable relation concept specifying that a first participant constitutes or belongs as a structural part of a second participant within a recognized part–whole organization.**

The relation concerns structural constitution or membership in a whole. It does not merely mean that the first participant is used by, interacts with, operates within, observes, represents, or is associated with the second participant.

## Relation Family

`part-of` belongs to the structural / partitive relation family.

It is intended for semantic structures in which the identity or organization of a whole includes a part as a constituent component or member under the applicable GIOP interpretation.

## Subject / Domain

The subject/domain is an eligible part, component, constituent, member, substructure, or other semantic element that can meaningfully stand in a part–whole relation.

Examples include:

- a sensor as part of an imaging system;
- an optical element as part of a lens assembly;
- a subsystem as part of a larger capture system;
- a documented structural component as part of a larger artifact.

Eligibility must be established by the semantics of the entities involved, not merely by physical proximity or frequent co-occurrence.

## Object / Range

The object/range is an eligible whole, composite entity, structure, assembly, system, or other semantic element that can have the subject as a structural part.

## Directionality

`part-of` is directed:

`PART → WHOLE`

The direction is semantically significant.

Its inverse is conventionally expressible as `has-part`:

`WHOLE → PART`

The inverse is not automatically a separate GIOP canonical relation page unless independently required by the semantic architecture.

## Logical Characteristics

`part-of` is generally treated as transitive where the represented part–whole relation satisfies the relevant structural semantics:

`A part-of B` and `B part-of C` may support `A part-of C`.

However, transitivity must not be applied blindly to every domain-specific notion of component membership. The asserted relation must genuinely use the canonical part–whole semantics.

The relation is normally irreflexive for ordinary proper part semantics: an entity is not a proper part of itself. If GIOP later adopts a broader non-proper-part interpretation, that distinction must be explicitly versioned rather than silently changing the current meaning.

`part-of` is not symmetric.

## Applicability

Use `part-of` when the intended assertion concerns structural constitution, compositional membership, or part–whole organization.

Do not use it merely because:

- one entity is used by another;
- one entity operates with another;
- one entity is connected to another;
- one entity participates in an event involving another;
- one entity is stored within another representation;
- one entity is physically near another.

## Distinctions / Non-equivalence

### Part Of vs Component Of

`component-of` may be useful as a more specialized system/component relation, but it must not be assumed identical to `part-of` without a defined boundary. A component may carry system-functional semantics that a general part–whole relation does not require.

### Part Of vs Participates In

A component can participate in a process without being part of the process. `part-of` expresses constitution; `participates-in` expresses involvement in an activity or process.

### Part Of vs Uses

A camera using a lens does not, by that fact alone, establish a structural part–whole relation. The use relation concerns operation or utilization; part–whole concerns constitution.

### Part Of vs Located In

Spatial containment or location does not automatically establish structural constitution.

### Part Of vs Derived From

Provenance is not constitution. An artifact can be derived from another artifact without being its structural part.

## Qualification / Context

Relevant qualifications may include:

- lifecycle interval;
- assembly configuration;
- version;
- system architecture;
- domain-specific structural convention.

Where a component is removable, replaceable, optional, or configuration-dependent, the assertion may require temporal or configuration qualification.

## Inference Boundary

Permitted structural inference may include inverse reasoning and, where applicable, transitive closure.

It is not valid to infer:

- functional use;
- participation;
- observation;
- representation;
- causation;
- provenance;
- spatial location;

solely from `part-of`.

## Cross-Layer Relations

`part-of` can connect classes and other semantic elements across the GIOP knowledge model.

Typical patterns include:

`Sensor part-of Camera/System`

`Lens Element part-of Lens Assembly`

`Subsystem part-of Capture System`

The existence of a class-level relation does not create an instance assertion without evidence.

## Typical GIOP Usage

Use the relation to represent stable or qualified structural composition in canonical knowledge graphs, semantic retrieval, architecture descriptions, and machine-readable system structure.

## Evidence / Provenance

The relation is supported by established part–whole modeling practice, formal ontology relation patterns, and terminology traditions distinguishing partitive relations from associative and participation relations. OBO Relation Ontology and ISO terminology traditions provide design evidence; they are not themselves GIOP authority.

## Trust / Validation

A `part-of` assertion should be supported by authoritative system documentation, engineering structure, explicit composition semantics, or other appropriate evidence.

Co-occurrence in text, shared packaging, or common usage is insufficient by itself.

## Lifecycle

- **Current state:** ACTIVE / CANONICAL
- **Change control:** semantic changes require explicit review and versioned change history.
- **Supersession:** none currently.
- **Preservation:** prior definitions and material decisions must remain auditable.

## Machine / AI Interpretation

A machine should encode the relation as a directed semantic predicate whose subject is the part and object is the whole.

Machine reasoning may use the declared inverse and approved transitivity rules. It must not generate functional, causal, spatial, or operational assertions from the relation unless separately supported.

## Retrieval Anchors

`part of`, `part-of`, `has part`, `has-part`, `part–whole`, `partitive relation`, `structural composition`, `component membership`, `constituent`, `whole`, `substructure`

## What This Relation Does NOT Mean

`part-of` does not by itself mean:

- uses;
- depends on;
- participates in;
- observes;
- represents;
- located in;
- contains in a purely spatial sense;
- derived from;
- caused by;
- equivalent to.

## Semantic Boundary

**Part Of is the GIOP relation for structural part–whole constitution. It must remain distinct from participation, operational use, spatial containment, provenance, and other associative relations.**
