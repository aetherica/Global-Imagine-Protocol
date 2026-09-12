# BIL Permitted Variation

**Semantic ID:** `SEM-BIL-PERMITTED-VARIATION-001`  
**Preferred Name:** Permitted Variation  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Permitted Variation** specifies a declared class, range, or mode of change that remains compatible with an Integrity Claim under a defined reference, context and transformation intent.

## 5W1H Orientation

### What
A context-qualified description of changes that are allowed without automatically becoming an integrity failure.

### Why
Lighting, pose, expression, viewpoint, clothing, motion, rendering and other transformations can legitimately change observed content while preserving the intended integrity dimension.

### Who
Relevant to photographers, filmmakers, VFX artists, scientists, validation engineers, ML systems and profile designers.

### Where
Human, wildlife, sports, dance, fashion, VFX, synthetic-creature, still, video and 3D/4D profiles.

### When
Only for the context and transformation scope in which the variation is declared.

### How
`Reference + Profile + Transformation Intent → Permitted Variation Policy`.

## Semantic Definition

**Permitted Variation** is the BIL control concept for change explicitly allowed by the applicable integrity policy without invalidating the scoped claim.

## Core Distinctions

Permitted Variation ≠ Deviation; ≠ Drift; ≠ Invariant; ≠ arbitrary change; ≠ error; ≠ transformation itself.

A transformation may produce both permitted and impermissible changes.

## Scope and Boundary

Typical variations include pose, expression, illumination, viewpoint, clothing state, declared stylization, animation and specified VFX transformation. Each requires profile and claim scope.

## Cross-Domain Significance

Permitted variation interprets changes originating in State, Condition, Relation, Process, Representation, Activity and Temporal layers. It does not replace those semantics.

## Trust and Evidence

The policy itself requires provenance/versioning; its application requires evidence sufficient to distinguish permitted variation from unintended change.

## Visitor Universe

Different profiles expose different permitted-variation examples while preserving one concept. Machine views retain the policy ID and applicability scope.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`PERMITTED VARIATION`, `ALLOWED CHANGE`, `DECLARED TRANSFORMATION`, `VARIATION POLICY`, `BIL`
