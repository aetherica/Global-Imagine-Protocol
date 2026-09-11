# GIOP V3.1 — Facet Analysis Specification

## Status

**CANONICAL — V3.1 FACET ORGANIZATION SPECIFICATION**

## Purpose

This specification defines how GIOP identifies, validates, and applies controlled facet organization over existing canonical knowledge. It governs analysis and structure; it does not create an alternative semantic ontology.

## Governing Principle

Facet analysis organizes canonical knowledge without changing the semantic identity of the organized concepts.

```text
EXISTING CANONICAL KNOWLEDGE
        ↓
FACET ANALYSIS
        ↓
ORGANIZING DIMENSION
        ↓
CHARACTERISTIC OF DIVISION
        ↓
ARRAY / SIBLING GROUP
        ↓
FACET MEMBERSHIP
```

## 1. Facet Analysis

Facet Analysis is the controlled analytical method for determining whether a set of concepts can be organized according to one or more coherent dimensions and, if so, identifying the characteristics of division and resulting structures.

It asks:

- What knowledge is being organized?
- Which concepts are actually comparable?
- What inherent category or organizing dimension is shared?
- What criterion distinguishes members?
- Does the proposed grouping create meaningful siblings?
- Does the organization duplicate an existing semantic hierarchy or definition?
- Can every member retain its own canonical identity?

Facet Analysis is methodology and therefore is not treated as a first-wave independent semantic entry in V3.1.

## 2. Facet

A Facet is the resulting reusable organizational construct representing a coherent category or dimension under which compatible canonical concepts may be organized.

A Facet may provide one organizational view of knowledge. It does not imply that the concepts organized beneath it share the same primary semantic type.

## 3. Characteristic of Division

A Characteristic of Division is the explicit criterion by which a broader conceptual scope is divided into distinguishable sibling concepts or arrays.

Examples of possible criteria include form, function, mode, purpose, location/context, process stage, or another criterion that is demonstrably appropriate to the concepts being divided. The criterion must be selected from the actual semantics of the corpus rather than imposed for convenience.

A characteristic of division is not automatically a Property. It describes the basis of a conceptual organization; it does not necessarily describe an attributable characteristic of a bearer.

## 4. Array

An Array is a structured set of sibling concepts resulting from the application of a common characteristic of division.

For GIOP V3.1, Array is treated as a structural construct inside the Facet organization model. It is not admitted as an independent first-wave semantic entry unless later validation establishes an independent reusable semantic responsibility and retrieval need.

## 5. Facet Membership

Facet Membership records that an existing canonical concept participates in a particular facet organization or array.

Membership is an organizational assertion. It does not imply any of the following unless separately asserted by the responsible semantic layer:

- `is-a` / subclassing;
- `part-of`;
- causal dependency;
- physical containment;
- measurement dependence;
- representation;
- observation;
- contextual inclusion;
- equivalence;
- identity;
- provenance.

## 6. Valid Division

A division is valid when:

1. the scope being divided is explicit;
2. the members are semantically compatible enough to be compared;
3. a coherent characteristic of division is identifiable;
4. the characteristic is applied consistently within the relevant scope;
5. the resulting siblings are distinguishable under that criterion;
6. existing canonical identities are preserved;
7. the organization does not silently create a new primary semantic definition;
8. evidence or GIOP synthesis supports the organization.

## 7. Invalid or Weak Division

The following are insufficient on their own:

- arbitrary topical proximity;
- keyword similarity;
- UI convenience;
- visitor preference;
- frequency of search;
- vendor taxonomy;
- a flat list of examples with no common criterion;
- a grouping that mixes unrelated semantic responsibilities without explanation;
- a grouping that duplicates an existing canonical hierarchy merely for discoverability.

## 8. Multiple Facets

A canonical concept may legitimately participate in multiple facets when each membership represents a distinct and defensible organizational dimension.

Multiple membership does not mean semantic ambiguity. It means the same canonical identity can be discovered through different controlled views.

## 9. Facet versus Hierarchy

A Facet is an organizational dimension. A hierarchy is a structured relation of broader/narrower concepts within an organizational or semantic system.

A Facet may contain or expose one or more hierarchical structures, but Facet and Hierarchy are not synonyms.

Hierarchy must not be reconstructed in `facets/` merely to duplicate the semantic hierarchy owned by another canonical layer.

## 10. Facet versus Concept Group

A Concept Group is a collection of concepts brought together for a stated grouping purpose. A Facet requires a stronger organizational rationale: a coherent category or division dimension under which compatible concepts can be systematically organized.

Therefore every Concept Group is not automatically a Facet.

## 11. Facet versus Tag

A tag may be an uncontrolled or lightweight discovery label. A Facet is controlled and semantically justified.

Search frequency or interface utility cannot by itself establish Facet status.

## 12. Facet versus Property

Property answers which characteristic can be attributed to an eligible bearer. Facet answers according to which organizational dimension compatible knowledge is arranged.

A property may be used as the basis of a facet organization in an appropriate classification system, but the property definition remains authoritative in `properties/`.

## 13. Facet versus Context

Context specifies the setting, circumstance, purpose, perspective, or situational frame in which something is understood or used. Facet organizes concepts for controlled navigation or classification.

A context may be a member of a facet; a facet does not become a context merely because it is used to navigate contextual knowledge.

## 14. Facet versus Visitor Universe

Visitor Universe describes who enters canonical knowledge, their entry depth, orientation, and navigation path. It is not a semantic classification of the knowledge itself.

Facet organization may improve navigation for different visitor classes, but visitor identity or audience demand must never be used as the semantic definition of a Facet.

The canonical model remains:

`CANONICAL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

## 15. Analysis Procedure

### Step 1 — Identify the candidate corpus

Specify the canonical concepts that are proposed for organization. Do not begin with a desired facet name and then collect convenient examples.

### Step 2 — Verify primary semantic identity

Resolve each candidate concept to its existing canonical owner. If no owner exists, the candidate must first pass the ordinary GIOP canonicalization process.

### Step 3 — Identify the common organizing dimension

Determine what makes the candidate concepts comparable for this particular organization.

### Step 4 — State the characteristic of division

Write the criterion in a form that can be independently inspected and applied.

### Step 5 — Test sibling coherence

Check whether the resulting members are distinguishable under the same criterion and whether any member is actually a different semantic kind requiring separate treatment.

### Step 6 — Check cross-layer duplication

Compare the proposed organization against Classes, Properties, Conditions, States, Relations, Quantities, Activities, Processes, Representations, Perceptions, Contexts, and future semantic layers.

### Step 7 — Record evidence and conflicts

Retain standards terminology, research evidence, alternative classifications, and unresolved conflicts in the appropriate registry before canonical promotion where required.

### Step 8 — Make the GIOP decision

Classify the result as canonical, candidate, deferred, routed elsewhere, unverified, conflicted, or historical/non-canonical.

### Step 9 — Author only the justified structure

Create only the canonical semantic and specification artifacts justified by the decision.

### Step 10 — Validate with retrieval and visitor-depth tests

Confirm that the organization is machine-retrievable and supports different visitor entry depths without creating different underlying truths.

## 16. Evidence Standard

Evidence that a faceted organization exists in a recognized terminology system is evidence for use and structure, not automatic evidence that GIOP should adopt the same structure.

GIOP synthesis must preserve meaningful differences between external systems. A verified external classification must not be silently imported as GIOP ontology.

## 17. Machine Interpretation

A machine-readable Facet organization should make explicit:

- facet ID;
- facet label;
- definition;
- organizing dimension;
- characteristic of division;
- applicable scope;
- member canonical IDs;
- array membership where applicable;
- related organizational structures;
- evidence/provenance;
- validation state;
- lifecycle state.

Machine retrieval must never infer primary semantic class from facet membership.

## 18. Visitor-Depth Interpretation

The same facet structure can be consumed at different depths:

```text
GENERAL
→ What is the Facet and why does it help?

LEARNING
→ How does the division work?

PRACTICE
→ How can the organization support discovery?

ENGINEERING / RESEARCH
→ What criterion, boundaries, evidence, and membership rules govern it?

MACHINE
→ What are the stable IDs, memberships, constraints, relations, provenance, and validation states?
```

These are consumption depths, not alternate definitions.

## 19. Change Control

Changing a Facet organization does not automatically change the primary meaning of its members. If the change reveals a new semantic identity, the new identity must be processed through the normal GIOP canonicalization workflow.

Existing memberships must be revalidated when a facet's scope or division criterion materially changes.

## 20. V3.1 Boundary Decision

The V3.1 first-wave Facet layer admits:

- `Facet` as the canonical organizational construct;
- `Characteristic of Division` as the canonical structural criterion.

It treats:

- `Array` as a structural construct;
- `Facet Membership` as an organizational assertion;
- `Facet Analysis` as methodology/specification.

It defers independent canonical entries for hierarchy, guide terms, node labels, facet indicators, facet schemes, concept groups, and domain-specific facets until distinct GIOP responsibility is established.
