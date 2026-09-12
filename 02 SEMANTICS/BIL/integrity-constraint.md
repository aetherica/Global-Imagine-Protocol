# BIL Integrity Constraint

**Semantic ID:** `SEM-BIL-INTEGRITY-CONSTRAINT-001`  
**Preferred Name:** Integrity Constraint  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Constraint** is a scoped rule defining an invariant, permitted variation, correspondence requirement, or acceptance condition applicable to an Integrity Claim.

## 5W1H Orientation

### What
A rule describing what must remain consistent, what variation is allowed, or what relationship/condition must hold for a claim.

### Why
Observed differences become meaningful only when evaluated against explicit scope and permitted variation. A constraint provides that interpretation boundary.

### Who
Applicable to imaging scientists, validation engineers, VFX teams, researchers, workflow designers and machine evaluators.

### Where
Identity, structure, configuration, interaction, temporal, representation, contextual and transformation-sensitive integrity assessments.

### When
A constraint is valid only for its declared profile, reference, transformation and temporal scope.

### How
A constraint identifies subject/target scope, condition, expected behaviour, applicability and, where quantitative, the governing measurement or validation specification.

## Semantic Definition

**Integrity Constraint** is a BIL control concept denoting a bounded rule used to interpret an Integrity Claim and distinguish permitted change from integrity-relevant nonconformance.

## Core Distinctions

Constraint ≠ Property; Constraint ≠ Quantity; Constraint ≠ Validation Result; Constraint ≠ Physical Law; Constraint ≠ Decision.

A constraint may refer to an existing Property, State, Relation or Quantity without becoming that semantic layer.

## Scope and Boundary

Constraint families may include identity, structural, relational/configurational, temporal, representation, contextual and transformation constraints. Scope and applicability are mandatory.

A constraint does not itself assert that an observed deviation is a failure.

## Cross-Domain Significance

`Integrity Claim → applicable Constraint(s) → Evidence / Validation → Decision`.

Formal equations and numerical limits belong to the relevant scientific, quantity, validation or profile artifact and must not silently become universal BIL constants.

## Trust and Evidence

Constraint provenance, authority tier, validation state, version and applicability must remain visible. Conflicting policies must not be silently averaged.

## Visitor Universe

D0 explains intent; D1 explains constraint types and boundaries; D2 gives profile/application examples; D3 gives formal parameters; D4 exposes machine-checkable scope and IDs.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`INTEGRITY CONSTRAINT`, `INVARIANT`, `PERMITTED VARIATION`, `ACCEPTANCE CONDITION`, `CONSTRAINT SCOPE`, `BIL`
