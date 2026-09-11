# GIOP Canonical Properties

## Status

**CANONICAL**

The `properties/` directory is the authoritative published GIOP layer for reusable semantic characteristic concepts.

## Purpose

The governing question is:

> **What characteristic may be attributed to an eligible entity or concept?**

A Property is not a class, quantity, value, state, condition, relation, activity, process, measurement result, or implementation claim.

## Canonical Property Definition

**Property is a reusable canonical semantic concept denoting a characteristic that may be attributed to an eligible entity or concept independently of any particular measured value, state, condition, representation, process, or relation.**

## Canonical Boundary

`ENTITY TYPE → CLASS`

`CHARACTERISTIC → PROPERTY`

`MEASURABLE CONCEPT → QUANTITY`

`VALUE / MEASUREMENT RESULT → VALUE / RESULT`

`STATE / STATUS → STATE / STATUS`

`CONTEXTUAL CIRCUMSTANCE → CONDITION`

`RELATIONSHIP → RELATION`

`ACTION → ACTIVITY`

`TRANSFORMATION / DEVELOPMENT → PROCESS`

## Current Canonical Vocabulary

The current canonical Property set is:

1. `optical-distortion`
2. `chromatic-aberration`
3. `spectral-response`
4. `sensitivity`
5. `linearity`
6. `transparency`
7. `chromaticity`
8. `dynamic-range-characteristic`

See `PROPERTY-INDEX.md` for the canonical index and identifiers.

## Quantification Boundary

A Property may have quantitative realizations, but the Property document does not become a value, measurement result, formula, threshold, or performance claim merely because the characteristic is measurable.

Examples:

- spectral response → wavelength-dependent response values;
- chromaticity → chromaticity coordinates;
- linearity → linearity error or other measurement-derived quantities;
- sensitivity → sensitivity coefficient or threshold;
- optical distortion → measured distortion parameters;
- dynamic-range characteristic → dynamic-range ratio, logarithmic expression, or other defined performance measure.

Quantitative realizations belong in the appropriate quantity/value/result semantics.

## Bearer and Applicability

Each Property page MUST identify the kinds of entities or concepts to which the characteristic may meaningfully apply. Applicability does not imply that every instance of an eligible class possesses the Property or that a particular value is present.

## Evidence and Trust

External standards, scientific literature, technical documentation, and domain practice provide evidence. GIOP canonical Property pages are independent semantic syntheses and MUST NOT simply reproduce source definitions.

A verified external term does not automatically become a canonical GIOP Property. Semantic abstraction and layer placement must also be established.

## Knowledge Retention

Important technical terms that are not canonical Property entries are not discarded. They are retained in `../registry/` with epistemic status, semantic classification, evidence, and destination decisions.

Thus:

`VERIFIED ≠ CANONICAL`

`NOT A PROPERTY ≠ NOT KNOWLEDGE`

`DEFERRED ≠ DELETED`

## Authoring Requirements

Each canonical Property page should provide, as applicable:

1. Identity and stable canonical ID;
2. 5W1H orientation;
3. semantic definition;
4. bearer and applicability;
5. distinctions from adjacent concepts;
6. quantification/value boundary;
7. conditions and context;
8. relations;
9. evidence/provenance;
10. machine interpretation;
11. lifecycle state;
12. semantic boundary.

Numerical instance values and vendor-specific performance claims MUST NOT be embedded as if they were Property definitions.

## Cross-Layer Validation

The Property layer is validated against the established GIOP semantic boundary:

- Classes define entity types, not characteristics.
- Quantities define measurable concepts, not general characteristic abstractions.
- Values and results carry realizations and outcomes, not Property identity.
- Conditions describe contextual circumstances.
- States and statuses describe modes or status conditions.
- Activities and processes describe actions and transformations.
- Relations describe connections between entities or concepts.

This prevents common category errors such as treating focal length as a Property when used as a quantity, treating resolution as a generic Property when its current GIOP treatment is measurement-oriented and deferred, or treating transmittance as synonymous with transparency.

## Completion Rule

The Property folder is considered complete for the current V3.1 semantic pass when:

- this specification is canonical;
- the canonical Property index exists;
- every admitted seed Property has a canonical page;
- deferred/non-Property candidates remain retained in the registry;
- no current canonical Property candidate lacks either a published page or an explicit documented reason for deferral.

The current V3.1 Property pass satisfies this rule.
