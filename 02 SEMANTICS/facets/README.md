# GIOP Canonical Facets

## Status

**CANONICAL — V3.1 SEMANTIC ORGANIZATION LAYER**

The `facets/` directory defines the authoritative GIOP semantics for controlled multidimensional organization of existing canonical knowledge. It does not create a second ontology and does not replace the primary semantic authority of classes, properties, conditions, states, relations, quantities, activities, processes, representations, perceptions, or contexts.

## Governing Question

> **According to what coherent organizing dimension or division criterion may compatible canonical concepts be grouped and navigated without changing their primary semantic identity?**

## Canonical Facet Definition

**Facet is a reusable canonical organizational construct that groups compatible canonical semantic concepts according to a coherent inherent category or declared organizing criterion, without replacing or redefining the primary semantic identity of those concepts.**

A Facet is therefore an organizing construct over canonical knowledge. It is not an arbitrary tag, a duplicate concept definition, a visitor category, a UI filter, or a substitute for an existing semantic layer.

## Architectural Position

GIOP separates semantic identity from knowledge organization and from visitor consumption:

`CANONICAL SEMANTIC KNOWLEDGE → FACET ORGANIZATION → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

Facet organization may support discovery and retrieval, but it does not determine whether a concept is a Class, Property, Condition, State, Relation, Quantity, Activity, Process, Representation, Perception, or Context.

## Core Structural Model

```text
FACET
  ↓
CHARACTERISTIC OF DIVISION
  ↓
ARRAY / STRUCTURED SIBLING GROUP
  ↓
FACET MEMBERSHIP
  ↓
EXISTING CANONICAL CONCEPTS
```

The structure is organizational rather than a replacement for primary semantic identity.

## Core Vocabulary

### Facet

The canonical organizing construct. It represents a coherent organizational dimension or category under which compatible concepts may be arranged.

### Characteristic of Division

The explicit criterion by which a conceptual domain or broader grouping is divided into distinguishable sibling concepts or arrays. It provides the semantic basis for the grouping rather than merely naming the result.

### Array

A structured set of sibling concepts produced by applying a common characteristic of division. In V3.1 it is treated primarily as a structural construct and is defined in the Facet Analysis Specification rather than admitted as an independent first-wave semantic entry.

### Facet Membership

An organizational assertion that an existing canonical concept participates in a specified Facet or array. Membership does not transfer semantic ownership to `facets/`.

### Facet Analysis

The analytical method used to identify coherent organizing dimensions, characteristics of division, compatible concept groups, and resulting facet structures. It is treated as methodology/specification, not as a first-wave canonical semantic entry.

## Boundary Model

```text
FACET          → knowledge-organizing construct
CLASS          → kind of entity
PROPERTY       → attributable characteristic
CONDITION      → contextual circumstance / condition
STATE          → mode or status
RELATION       → typed connection
QUANTITY       → measurable concept
ACTIVITY       → action
PROCESS        → transformation / progression
REPRESENTATION → information-bearing form
PERCEPTION     → perceptual experience / interpretation
CONTEXT        → situational frame
VISITOR UNIVERSE → access, navigation, and consumption framework
```

A canonical concept remains owned by its primary semantic layer even when it participates in one or more facet organizations.

## Non-Equivalences

`Facet ≠ Class`

`Facet ≠ Property`

`Facet ≠ Context`

`Facet ≠ Relation`

`Facet ≠ Category in every generic sense`

`Facet ≠ Tag`

`Facet ≠ UI filter`

`Facet ≠ Visitor Universe`

`Facet ≠ Entry Depth`

`Facet ≠ duplicate ontology`

## Existing-Concept Rule

A facet must organize existing canonical identities wherever possible. A term must not be promoted into a Facet merely because it is useful for browsing or because a list can be made around it.

Before creating a new facet organization, check whether the proposed organizing concept is already owned by another semantic layer. If it is, the Facet must reference that canonical identity rather than redefine it.

## Characteristic-of-Division Rule

A proposed division should expose a coherent criterion. Sibling concepts must be comparable under that criterion and must not merely be a heterogeneous list of convenient examples.

A useful division should make it possible to answer:

1. What broader conceptual scope is being divided?
2. What characteristic determines the division?
3. Why are the resulting members comparable?
4. What distinguishes one member from its siblings?
5. Which existing canonical identity owns each member?
6. What evidence supports the organization?

## Array Rule

An array is valid only when its members are siblings under a common division criterion. It must not be used to manufacture false equivalence between concepts that belong to different semantic responsibilities.

An array may be part of a larger hierarchy or facet scheme, but hierarchy and scheme semantics must not be silently redefined here.

## Facet Membership Rule

Facet membership is organizational. It may be many-to-many where the knowledge organization legitimately requires multiple views, provided that each membership has an explicit organizing rationale.

Membership does not imply:

- subclassing;
- equivalence;
- part-of relation;
- causal relation;
- measurement relation;
- provenance;
- contextual containment;
- visitor identity.

Where one of those meanings is intended, the responsible semantic layer must own it.

## Visitor Universe and Entry Depth

Visitor Universe is not encoded as a semantic payload in Facet entries.

The same Facet knowledge supports different entry depths:

- general visitors can understand the What/Why and a simple organization example;
- learners can follow definitions and distinctions;
- practitioners can use structural organization and navigation implications;
- engineers, scientists, metrology and standards professionals can inspect division criteria, boundaries, evidence, and cross-layer ownership;
- AI, data-curation, API, and system consumers can use stable IDs, membership structures, relations, provenance, and validation anchors.

These are consumption paths through the same canonical knowledge, not separate Facet definitions.

## Machine Interpretation

Facet records must remain locally intelligible for machine retrieval. Stable IDs, preferred names, definitions, primary responsibility, membership semantics, relations, provenance, validation, status, and lifecycle must remain explicit.

A machine must not infer semantic ownership from folder placement alone.

## Evidence and Trust

Facet admission is evidence-dependent. External terminology may establish that a faceted organization is used in a recognized knowledge-organization system, but external verification does not automatically make the resulting GIOP structure canonical.

The GIOP decision must distinguish recovered terminology, evidence, synthesis, and canonical organizational decision.

## Lifecycle

Facet structures are subject to normal GIOP lifecycle and change controls. Changes that alter established semantic organization must remain traceable and must not silently redefine the primary meaning of existing concepts.

## Current V3.1 Seed

The first-wave Facet semantic nucleus consists of:

1. `facet`
2. `characteristic-of-division`

The following remain structural or methodological rather than first-wave independent semantic entries:

- Array;
- Facet Membership;
- Facet Analysis;
- Hierarchy;
- Guide Term;
- Node Label;
- Facet Indicator;
- Facet Scheme;
- Concept Group;
- Concept Scheme.

Domain-specific facet candidates such as spatial, temporal, modality, measurement, domain, application, and capture facets are deferred until their semantic ownership and cross-layer boundaries are validated.

## Canonical Authoring Requirements

A substantive Facet entry should expose, as applicable:

1. stable identity and metadata;
2. 5W1H orientation;
3. explicit semantic definition;
4. scope and organizing responsibility;
5. structural semantics;
6. distinction from neighboring semantic layers;
7. characteristic-of-division implications;
8. membership and array implications;
9. evidence and provenance;
10. validation and trust;
11. lifecycle;
12. machine/AI interpretation;
13. retrieval anchors;
14. cross-layer relations;
15. explicit non-meaning / boundary statements.

## Completion Rule

The V3.1 Facet pass is complete for its current seed scope when the Facet semantic contract is canonical, the characteristic-of-division boundary is canonicalized, the structural and methodological rules are explicit, the index is internally consistent, deferred candidates remain explicitly retained, and canonical entries do not duplicate authority held by other semantic layers.
