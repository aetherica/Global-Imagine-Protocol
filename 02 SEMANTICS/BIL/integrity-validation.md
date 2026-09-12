# BIL Integrity Validation

**Semantic ID:** `SEM-BIL-INTEGRITY-VALIDATION-001`  
**Preferred Name:** Integrity Validation  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Validation** is the scoped evaluation activity/specification used to test an Integrity Claim against its reference, evidence, constraints, uncertainty and applicable policy.

## 5W1H Orientation

### What
A claim-specific validation specification and interpretation framework.

### Why
A numerical metric alone cannot establish biological integrity. The claim, evidence, method, uncertainty and policy must all be explicit.

### Who
Imaging scientists, validation engineers, VFX supervisors, ML engineers, researchers and expert reviewers.

### Where
Geometry, identity, interaction, appearance, temporal, physical, optical, cross-view and cross-representation validation.

### When
Applied after sufficient evidence is established and before a decision is recorded, or iteratively when evidence is updated.

### How
`Claim + Reference + Evidence + Constraint + Validation Method + Uncertainty → Evaluation Status`.

## Semantic Definition

**Integrity Validation** is the BIL control concept governing how a declared Integrity Claim is tested and interpreted against applicable evidence and constraints.

## Core Distinctions

Validation ≠ metric; ≠ evidence; ≠ measurement; ≠ decision; ≠ workflow; ≠ truth guarantee.

The actual validation occurrence remains an Activity; reusable procedure remains Workflow-owned; algorithms and software remain method/implementation-owned.

## Scope and Boundary

Validation may use landmark error, morphometry, colour difference, geometric correspondence, temporal consistency, contact consistency, physical checks, expert review or multimodal evidence. The selected method is profile-dependent.

## Cross-Domain Significance

BIL integrates methods from Quantity, Activity, Workflow, Computational Method, Representation, Temporal, Relation and Result layers without absorbing their definitions.

## Trust and Evidence

Every validation record should expose method identity, input evidence, version, assumptions, uncertainty, validation status and provenance.

## Visitor Universe

D0 explains purpose; D1 explains validation structure; D2 gives practical profile paths; D3 exposes methods and metrics; D4 exposes machine-readable validation records and test vectors.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`INTEGRITY VALIDATION`, `CLAIM VALIDATION`, `VALIDATION METHOD`, `VALIDATION EVIDENCE`, `VALIDATION UNCERTAINTY`, `BIL`
