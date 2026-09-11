# Characteristic of Division

> **A Characteristic of Division is the explicit criterion by which a defined conceptual scope is divided into distinguishable and comparable sibling concepts or arrays within a controlled facet organization.**

## Identity

- **ID:** `SEM-FACET-DIVISION-001`
- **Title:** Characteristic of Division
- **Artifact Type:** Semantic Definition
- **Primary Responsibility:** Facet organization structure
- **Semantic Class:** STRUCTURAL FACET CONCEPT
- **Status:** ACTIVE
- **Version:** V3.1
- **Authority:** GIOP Canonical Semantic Layer
- **Provenance:** GIOP semantic synthesis supported by established faceted classification and knowledge-organization terminology
- **Validation:** V3.1 semantic boundary and structural validation
- **Related IDs:** `SEM-FACET-GENERIC-001`

## What

A Characteristic of Division is the criterion used to determine how a defined conceptual scope is subdivided into distinguishable sibling concepts within a facet organization.

It answers the question:

> **According to what meaningful criterion are these concepts divided?**

The criterion provides the rationale for an Array. Without a coherent characteristic of division, a collection of related terms is not automatically a valid facet array.

## Why

Facet organization must be more than a list of terms that happen to be related. A characteristic of division makes the organizing logic explicit and testable.

For GIOP this prevents arbitrary taxonomies, search-driven grouping, vendor taxonomy leakage, and semantic duplication. It also gives machines and human reviewers a recoverable explanation for why concepts appear together as siblings.

## Structure

The structural pattern is:

```text
DEFINED CONCEPTUAL SCOPE
        ↓
CHARACTERISTIC OF DIVISION
        ↓
DISTINGUISHABLE SIBLING CONCEPTS
        ↓
ARRAY
        ↓
FACET MEMBERSHIP
```

A single Facet may use more than one division structure where justified. Each division must retain its own explicit criterion.

## How

To establish a Characteristic of Division:

1. define the conceptual scope;
2. identify the concepts that are candidates for comparison;
3. determine the common organizational dimension;
4. state the division criterion explicitly;
5. test whether every proposed sibling can be evaluated under that same criterion;
6. remove concepts that require a different semantic responsibility or division logic;
7. verify that the resulting organization does not duplicate another canonical semantic hierarchy;
8. record evidence and unresolved alternatives;
9. validate the resulting Array and memberships.

## Where

Characteristics of Division operate within knowledge-organization structures. They may organize canonical concepts for:

- conceptual browsing;
- faceted retrieval;
- controlled classification;
- documentation navigation;
- knowledge discovery;
- machine-assisted retrieval.

They do not replace the semantic relations or definitions that establish the meaning of the organized concepts.

## Who

The concept is relevant to knowledge architects, technical writers, standards specialists, information scientists, ontology and knowledge-engineering practitioners, imaging researchers, system integrators, AI/data-curation engineers, and machine consumers that need to interpret or validate structured organization.

General visitors and learners may encounter the resulting grouping without needing to know the formal term.

## Semantic Definition

A Characteristic of Division is the explicit criterion by which a defined conceptual scope is divided into distinguishable and comparable sibling concepts or arrays within a controlled facet organization.

The criterion is organizational. It does not automatically assert that the criterion is a Property of each member.

## Examples of Division Logic

The following are structural examples rather than currently approved GIOP domain-specific Facets:

```text
Scope: Camera
Criterion: capture modality
Possible sibling concepts: still imaging / motion imaging / hybrid imaging
```

```text
Scope: Imaging workflow
Criterion: processing stage
Possible sibling concepts: acquisition / processing / finishing
```

These examples illustrate how a criterion can organize concepts. They do not by themselves authorize those terms as canonical Facets or Arrays.

## Core Distinctions

### Characteristic of Division vs Property

A Property denotes an attributable characteristic. A Characteristic of Division specifies the criterion used to organize concepts. A property may sometimes supply a useful division basis, but the two responsibilities are not identical.

### Characteristic of Division vs Relation

A Relation specifies a typed connection between semantic elements. A division criterion organizes comparable concepts; it does not automatically assert a relation between them.

### Characteristic of Division vs Context

Context defines a situational frame. A division criterion defines how knowledge is organized within a classification structure.

### Characteristic of Division vs Visitor Category

A visitor category may affect which organization is useful for navigation, but it cannot serve as the semantic justification for a Facet merely because a particular audience prefers it.

## Validity Conditions

A division criterion should satisfy the following conditions:

1. **Explicitness** — the criterion can be stated clearly.
2. **Scope** — the conceptual universe being divided is identifiable.
3. **Comparability** — proposed siblings can be assessed under the same criterion.
4. **Consistency** — the criterion is applied consistently within the relevant scope.
5. **Discriminability** — the criterion distinguishes members meaningfully.
6. **Semantic preservation** — member identities remain owned by their canonical layers.
7. **Non-duplication** — the division does not silently recreate another semantic authority.
8. **Evidence** — the organization has defensible evidence or explicit GIOP synthesis.

## Invalid or Weak Cases

The following are weak evidence for a Characteristic of Division when used alone:

- keyword similarity;
- popularity in search;
- UI convenience;
- arbitrary alphabetical grouping;
- vendor-specific menus;
- topical association without a criterion;
- a list of examples from unrelated semantic layers;
- audience preference;
- a desired navigation result imposed before semantic analysis.

## Array Relationship

An Array is a resulting sibling set produced by applying the Characteristic of Division to an appropriate scope.

```text
Characteristic of Division
          ↓
     applies criterion
          ↓
       Array
          ↓
   sibling concepts
```

Array is currently treated as a structural construct in GIOP V3.1 rather than an independent first-wave semantic entry.

## Facet Relationship

The Characteristic of Division gives a Facet organization its explicit dividing logic. A Facet may have one or more organizational structures, but every claimed sibling array should have a recoverable rationale.

## Cross-Layer Authority

The criterion does not take ownership of the concepts it organizes.

For example, if a division organizes:

```text
Camera
Spectral Response
Measurement Context
```

their primary semantic authorities remain:

```text
Camera → classes/
Spectral Response → properties/
Measurement Context → contexts/
```

The Facet organization links or indexes those canonical identities rather than redefining them.

## Machine / AI Interpretation

A machine should interpret a Characteristic of Division as an organizational criterion.

It should be able to recover:

- the criterion ID;
- preferred name;
- scope;
- applicable Facet;
- resulting Array;
- member canonical IDs;
- qualification;
- evidence/provenance;
- validation state;
- lifecycle.

The machine must not infer that the criterion is a Property, Relation, Class, Context, or other primary semantic type unless separately asserted.

## Trust / Evidence / Validation

External knowledge-organization standards and mature classification systems provide evidence for the concept and its structural role. Their specific classifications must not be imported without GIOP analysis.

Where alternative division criteria are equally defensible for different purposes, the distinction should remain explicit rather than being collapsed into a single supposedly universal criterion.

## Lifecycle

Changes to a Characteristic of Division can affect arrays and memberships. Any material change therefore requires review of dependent organizational structures and retrieval indexes.

Changing the division criterion does not automatically change the primary semantic identity of any member.

## Relations / Retrieval Anchors

**Related concepts:** Facet; Array; Facet Membership; Hierarchy; Concept Group; Property; Relation; Context.

**Retrieval anchors:** `SEM-FACET-DIVISION-001`; `CHARACTERISTIC OF DIVISION`; `DIVISION CRITERION`; `CONCEPTUAL SCOPE`; `SIBLING CONCEPT`; `ARRAY`; `FACET MEMBERSHIP`; `ORGANIZATIONAL CRITERION`; `SEMANTIC PRESERVATION`.

## Semantic Boundary

Characteristic of Division means the criterion used to structure a conceptual division within facet organization.

It does not mean:

- an arbitrary property value;
- a primary semantic Class;
- a Relation between members;
- a Context;
- a visitor category;
- a search filter;
- a UI label;
- a vendor taxonomy merely because it is commercially used.

## Limitations

No single division criterion is universally correct for every knowledge domain or every retrieval purpose. GIOP must preserve scope and purpose and must not present a context-dependent organization as an absolute ontology.

## Change History

- V3.1 — Initial canonical Characteristic of Division semantic entry established after consolidated Facet research and GIOP architectural boundary analysis.
- V3.1 — Cross-layer validation removed the standalone Visitor Universe section in accordance with the canonical entry-depth rule.
