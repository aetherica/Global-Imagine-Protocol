# Facet

> **Facet is a reusable canonical organizational construct that groups compatible canonical semantic concepts according to a coherent inherent category or declared organizing criterion, without replacing or redefining the primary semantic identity of those concepts.**

## Identity

- **ID:** `SEM-FACET-GENERIC-001`
- **Title:** Facet
- **Artifact Type:** Semantic Definition
- **Primary Responsibility:** Knowledge-organization semantics
- **Semantic Class:** FACET
- **Status:** ACTIVE
- **Version:** V3.1
- **Authority:** GIOP Canonical Semantic Layer
- **Provenance:** GIOP semantic synthesis supported by established faceted classification and knowledge-organization terminology
- **Validation:** V3.1 semantic boundary and architecture validation
- **Related IDs:** `SEM-FACET-DIVISION-001`

## What

A Facet is a controlled organizational construct used to arrange compatible canonical concepts according to a coherent category or organizing dimension.

The concepts organized by a Facet retain their own canonical semantic identities. A Camera remains a Class, Spectral Response remains a Property, and Measurement Context remains a Context even when any of them participates in an appropriate Facet organization.

A Facet therefore operates over canonical knowledge rather than replacing the semantic layers that own that knowledge.

## Why

Complex knowledge domains often require more than one useful route through the same body of concepts. A single hierarchy may privilege one perspective while obscuring another. Faceted organization permits controlled alternative views without duplicating the underlying semantic definitions.

For GIOP this is especially important because the repository must support general visitors, specialists, researchers, engineers, standards users, and machine consumers without creating separate knowledge bases for them.

## Structure

The core Facet organization model is:

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

A Facet may support one or more arrays and may expose or organize hierarchical structures. The exact structure depends on the classification problem and must not be inferred solely from the Facet name.

### Organizing Dimension

The organizing dimension is the coherent category or aspect under which concepts are arranged.

### Characteristic of Division

The characteristic of division is the explicit criterion used to distinguish members within the relevant scope. It is authoritative for determining whether an array is a coherent sibling set.

### Array

An Array is the resulting structured group of sibling concepts sharing the same characteristic of division. In V3.1 it is treated as a structural construct rather than an independent first-wave semantic entry.

### Membership

Membership is an organizational assertion that an existing canonical concept participates in a Facet or Array. Membership does not transfer semantic ownership.

## How

A Facet organization should be created through controlled semantic analysis rather than by collecting terms that appear related.

The author should:

1. identify the canonical concepts being organized;
2. verify their primary semantic identities;
3. identify a coherent organizing dimension;
4. state the characteristic of division;
5. test whether the resulting concepts are comparable siblings;
6. check existing semantic layers for duplication or boundary conflict;
7. retain evidence and competing classifications;
8. make an explicit GIOP canonical decision;
9. establish controlled membership;
10. validate the resulting organization for human and machine retrieval.

The complete analytical procedure is defined in `FACET-ANALYSIS-SPECIFICATION.md`.

## Where

Facet organization may support:

- conceptual navigation;
- knowledge discovery;
- controlled classification;
- retrieval;
- cross-domain browsing;
- alternative views over the same canonical corpus;
- machine-assisted semantic retrieval.

It may be projected into indexes, APIs, search interfaces, documentation systems, or other downstream representations. Those projections are not authoritative over the canonical semantic meaning.

## Who

Facet semantics can be useful to anyone navigating a structured knowledge base. General visitors may use a facet as a simple discovery route. Learners may use it to understand how concepts are organized. Practitioners may use it to locate related knowledge. Engineers, scientists, metrology professionals, standards specialists, technical writers, and knowledge architects may inspect its division logic and membership. AI and data systems may use stable IDs and organizational assertions for retrieval.

These uses do not create visitor-specific Facet definitions.

## Semantic Definition

A Facet is a reusable canonical organizational construct that groups compatible canonical semantic concepts according to a coherent inherent category or declared organizing criterion, without replacing or redefining the primary semantic identity of those concepts.

The phrase “compatible canonical semantic concepts” means concepts that can legitimately be compared or organized under the selected dimension. Compatibility is local to the organization; it does not imply that all members have the same primary semantic type.

## Core Distinctions

### Facet vs Class

A Class identifies what kind of entity something is. A Facet organizes already identified concepts for controlled navigation or classification.

### Facet vs Property

A Property denotes an attributable characteristic. A Facet denotes an organizing dimension. A Property may provide a basis for an organization, but the Property remains authoritative in the Property layer.

### Facet vs Condition

A Condition describes a relevant circumstance or condition. A Facet organizes concepts; it does not describe the physical or observational condition in which something occurs.

### Facet vs State / Status

State or Status concerns the mode or status of an entity or process. Facet organization does not assert such a mode.

### Facet vs Relation

A Relation specifies a typed connection between semantic elements. Facet Membership is an organizational assertion and does not automatically become a physical, causal, partitive, observational, representational, or other relation.

### Facet vs Quantity

A Quantity denotes a measurable concept. A Facet can organize quantities but does not become a quantity because its members are measurable.

### Facet vs Context

Context specifies the setting, circumstance, purpose, perspective, or situational frame in which something is understood or used. Facet specifies how compatible knowledge is organized for classification and navigation.

### Facet vs Tag

A tag may be a lightweight discovery label. A Facet requires controlled semantic justification and a coherent organizational criterion.

### Facet vs Visitor Universe

Visitor Universe determines who enters and navigates canonical knowledge and how deeply they need to enter it. Facet is part of the organization of the knowledge itself.

## Boundary Conditions

A grouping should not be called a Facet merely because:

- its members are topically related;
- its labels are frequently searched together;
- it is convenient for a user interface;
- a vendor uses the grouping;
- a list can be assembled around a keyword;
- the grouping helps one visitor type;
- the grouping duplicates an existing semantic hierarchy;
- the grouping contains examples without a defensible division criterion.

A valid Facet must have a recoverable organizing rationale.

## Multiple Facets

The same canonical concept may participate in multiple Facets when the memberships express genuinely different organizational dimensions.

This does not imply multiple semantic identities. It provides multiple controlled views over one canonical identity.

Multiple membership should not be used to conceal unresolved semantic ambiguity. If two candidate identities are actually different concepts, the ordinary GIOP canonicalization process must resolve them before facet membership is treated as established.

## Cross-Layer Authority

Facet entries must preserve the authority of other semantic layers.

```text
Camera
→ `classes/camera.md`

Spectral Response
→ `properties/spectral-response.md`

Measurement Context
→ `contexts/measurement-context.md`

Viewing Context
→ `contexts/viewing-context.md`
```

The Facet layer may organize these identities but must not reproduce their canonical definitions as competing authority.

## Technical Organization Model

A Facet can be understood as an organizational view over a canonical concept graph:

```text
Canonical Identity Graph
        │
        ├── Class identity
        ├── Property identity
        ├── Context identity
        ├── Relation identity
        └── Other semantic identities
                 │
                 ▼
          Facet Organization
                 │
       ┌─────────┼─────────┐
       ▼         ▼         ▼
    Array A   Array B   Array C
       │         │         │
       └────── memberships ────┘
```

The organization is a view over canonical knowledge. It is not a replacement graph of semantic ownership.

## Trust / Evidence / Validation

The existence of a Facet in an external terminology or classification system is evidence that such an organization is recognized or useful in that system. It is not, by itself, authority for adopting the same organization as GIOP canonical structure.

Canonical admission requires GIOP semantic synthesis, boundary analysis, evidence assessment, and validation.

Conflicting external classifications must be retained and analyzed rather than silently averaged.

## Machine / AI Interpretation

A machine consuming this entry should interpret `Facet` as an organizational construct, not as a primary semantic type replacing Class, Property, Context, or another layer.

Stable retrieval anchors include:

- `SEM-FACET-GENERIC-001`;
- Facet;
- organizational construct;
- organizing dimension;
- characteristic of division;
- Array;
- Facet Membership;
- primary semantic authority;
- canonical concept;
- Visitor Universe;
- entry depth.

A machine must not infer `is-a`, `part-of`, causality, observation, representation, or measurement semantics from Facet membership alone.

## Visitor Universe and Entry Depth

The canonical entry is intentionally organized as progressive depth rather than audience-specific copies.

```text
GENERAL RECOGNITION
→ What is a Facet?

LEARNING
→ Why does it exist? How is it different from a Class, Property, Context, or Tag?

PRACTICAL USE
→ How can Facets support controlled navigation and discovery?

SPECIALIST DEPTH
→ How are division criteria, arrays, memberships, evidence, and boundaries validated?

MACHINE DEPTH
→ How are stable identities, memberships, qualifications, provenance, and validation interpreted?
```

The Visitor Universe determines the appropriate entry path and stopping depth. It does not alter this definition.

## Lifecycle

This entry follows the GIOP lifecycle controls. Changes to the definition or semantic boundary require review of affected facet structures and memberships.

A changed organizational view must not silently change the primary meaning of member concepts.

## Relations / Retrieval Anchors

**Related concepts:** Characteristic of Division; Array; Facet Membership; Hierarchy; Concept Group; Context; Property; Class.

**Retrieval anchors:** `FACET`; `SEM-FACET-GENERIC-001`; `ORGANIZATIONAL CONSTRUCT`; `ORGANIZING DIMENSION`; `CHARACTERISTIC OF DIVISION`; `ARRAY`; `FACET MEMBERSHIP`; `PRIMARY SEMANTIC AUTHORITY`; `CANONICAL CONCEPT`; `VISITOR UNIVERSE`; `ENTRY DEPTH`.

## Semantic Boundary

Facet means a controlled organizational construct over canonical knowledge.

It does not mean:

- a primary entity type;
- an attributable characteristic;
- a physical or observational condition;
- an entity state;
- a typed semantic relation;
- a measurable quantity;
- an action or transformation;
- an information representation;
- a perceptual experience;
- a situational context;
- a visitor category;
- an uncontrolled tag;
- a user-interface filter;
- a duplicate definition of a concept owned elsewhere.

## Limitations

Not every useful grouping is a Facet. The appropriateness of a Facet depends on the scope, semantic compatibility of members, explicit division criterion, evidence, and intended knowledge-organization function.

V3.1 intentionally defers domain-specific Facets until their semantic ownership and cross-layer boundaries are validated.

## Change History

- V3.1 — Initial canonical Facet semantic entry established after consolidated research and GIOP Foundation boundary analysis.
