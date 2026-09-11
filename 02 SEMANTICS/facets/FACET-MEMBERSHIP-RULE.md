# GIOP V3.1 — Facet Membership Rule

## Status

**CANONICAL — V3.1 FACET ORGANIZATION RULE**

## Purpose

This rule defines how existing canonical GIOP concepts may participate in Facet organization without transferring semantic authority to the `facets/` directory.

## Governing Rule

> **Facet membership organizes an existing canonical identity; it does not redefine that identity.**

The canonical source of a concept remains its primary semantic layer.

```text
CANONICAL CONCEPT
      ↓
PRIMARY SEMANTIC AUTHORITY
      │
      └──────→ FACET MEMBERSHIP
                       ↓
                    FACET / ARRAY
```

## 1. Membership Is an Organizational Assertion

A membership assertion states that a canonical concept participates in a specified Facet organization or Array for a defined organizational purpose.

It does not by itself assert:

- class membership;
- subclassing;
- part-whole structure;
- physical containment;
- causal dependence;
- observation;
- representation;
- measurement dependence;
- contextual containment;
- identity or equivalence;
- provenance.

Those meanings remain the responsibility of their respective semantic layers.

## 2. Eligibility

A membership target should have a stable canonical identity or an explicitly governed candidate identity. Unresolved research terms must not be presented as established canonical members merely because they fit a desired grouping.

## 3. Membership Evidence

Every material canonical membership should be supportable by one or more of:

- recognized terminology/classification evidence;
- coherent GIOP semantic synthesis;
- explicit characteristic-of-division analysis;
- validated domain organization;
- established cross-layer relationships.

A visitor's preference or search behavior is not sufficient evidence for canonical membership.

## 4. Multiple Membership

A concept may belong to multiple Facets when the memberships represent genuinely different organizational dimensions.

For example, a canonical imaging concept may be discoverable through a technical facet and through an application-oriented facet. This does not create multiple semantic identities.

Multiple memberships should be avoided when they are merely synonyms for the same organization.

## 5. Array Membership

Where an Array is used, membership means that the concept is one of the sibling members produced by the Array's common characteristic of division.

The membership must therefore be consistent with:

```text
BROADER SCOPE
      ↓
CHARACTERISTIC OF DIVISION
      ↓
SIBLING ARRAY
      ↓
MEMBER
```

## 6. Primary Semantic Ownership

If a Facet name resembles an existing semantic concept, the existing concept remains authoritative.

Examples:

```text
Camera
→ primary authority: classes/camera.md
→ may participate in a Facet

Spectral Response
→ primary authority: properties/spectral-response.md
→ may participate in a Facet

Measurement Context
→ primary authority: contexts/measurement-context.md
→ may participate in a Facet
```

A Facet page must not reproduce the full primary definition merely for convenience.

## 7. Membership Does Not Imply Is-A

The statement:

`X is a member of Facet Y`

does not mean:

`X is a Y`.

The first is organizational membership; the second is a semantic classification assertion and must be justified independently.

## 8. Membership Does Not Imply Part-Of

A concept appearing in a Facet does not become a physical, functional, informational, or logical component of that Facet.

Facet organization is not part-whole modeling.

## 9. Membership Does Not Imply Context

A Context can be organized by a Facet, but appearing in a Facet does not place the member inside a contextual situation.

## 10. Membership Does Not Imply Visitor Identity

Visitor Universe mapping is an access and consumption concern. Membership must never encode:

- photographer;
- student;
- engineer;
- scientist;
- AI consumer;
- or another visitor class

as the semantic basis of a Facet.

Visitor relevance may influence navigation and entry depth outside the canonical semantic membership assertion.

## 11. Membership Qualification

Where necessary, a membership may be qualified by:

- scope;
- characteristic of division;
- array;
- source classification;
- temporal validity;
- domain applicability;
- confidence or validation state;
- implementation or deployment context.

Qualification must not be hidden if it materially changes interpretation.

## 12. Canonical Membership Lifecycle

```text
CANDIDATE ORGANIZATION
        ↓
IDENTIFY EXISTING CONCEPTS
        ↓
VERIFY DIVISION CRITERION
        ↓
CHECK CROSS-LAYER BOUNDARIES
        ↓
ASSESS EVIDENCE / CONFLICT
        ↓
CANONICAL MEMBERSHIP DECISION
        ↓
VALIDATE
        ↓
PUBLISH / UPDATE
```

## 13. Removal or Change

Removing a membership does not delete the member concept. It changes only the organizational view.

Changing a characteristic of division requires review of affected arrays and memberships. If the change reveals a new primary semantic concept, that concept must pass the ordinary GIOP canonicalization process.

## 14. Machine Interpretation

Machines should be able to distinguish:

```text
member identity
primary semantic type
facet identity
array identity
division criterion
membership status
qualification
provenance
validation
lifecycle
```

A machine must not replace primary semantic type with Facet membership.

## 15. Visitor-Depth Interpretation

Facet membership may be used differently at different entry depths:

- general visitors use it indirectly for browsing;
- learners use it to understand conceptual organization;
- practitioners use it to locate related knowledge;
- specialists inspect division criteria and qualification;
- AI/data systems use stable membership and canonical IDs for retrieval.

The membership assertion itself remains one canonical organizational fact.

## 16. V3.1 Boundary

V3.1 treats Facet Membership as an organizational assertion governed by this rule. It is not currently declared a standalone canonical Relation concept. Future relation analysis may revisit this decision if independent semantic responsibility is established.
