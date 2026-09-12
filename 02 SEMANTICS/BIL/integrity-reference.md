# BIL Integrity Reference

**Semantic ID:** `SEM-BIL-INTEGRITY-REFERENCE-001`  
**Preferred Name:** Integrity Reference  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Reference** is the explicitly declared reference basis against which a bounded Biological Integrity Lock claim is interpreted and evaluated. It establishes comparison scope; it does not itself establish truth, fidelity, identity, or correctness.

## 5W1H Orientation

### What

An Integrity Reference is the declared evidence-bearing basis used to determine what aspect of a biological or biologically relevant configuration is being preserved, compared, or evaluated.

### Why

The same source can support different integrity questions. A portrait may support facial identity but not full-body gait. A wildlife frame may support individual marking comparison but provide insufficient evidence for hidden anatomy. The reference therefore requires explicit scope.

### Who

The concept is relevant to imaging scientists, photographers, cinematographers, VFX and digital-human practitioners, wildlife specialists, validation engineers, researchers, ML systems, and machine-readable integrity systems.

### Where

It may be associated with still images, video, multi-view captures, 3D/4D representations, scientific/medical observations, VFX plates, synthetic references, and other declared integrity contexts.

### When

A reference may apply to a single observation, frame sequence, version interval, transformation stage, or lifecycle period. Temporal scope must remain explicit where change is relevant.

### How

The reference identifies the subject/configuration scope, evidence basis, representation or model used, applicable profile, and the integrity claims for which it is sufficient.

## Semantic Definition

**Integrity Reference** is a BIL control concept denoting the declared comparison basis for one or more bounded Integrity Claims.

## Core Distinctions

### Reference vs Source Representation
A source image, video, mesh, or other representation is an information-bearing form. An Integrity Reference is a declared use and scope of evidence from one or more such forms for integrity evaluation.

### Reference vs Identity
A reference may support an identity-related claim but is not itself an identity.

### Reference vs Biometric Template/Model
A biometric template or model is a domain-specific representation. BIL may use it as evidence or reference material without redefining biometric semantics.

### Reference vs Truth
A reference is a comparison basis, not a guarantee that the source is correct or complete.

### Reference vs Result
The evaluated result is an outcome; the reference defines the comparison basis.

## Scope and Boundary

An Integrity Reference may cover identity, structure, state, appearance, interaction, spatial configuration, temporal continuity, species/biological characteristics, or contextual relationships. Scope MUST be claim-specific where necessary.

Reference sufficiency is not assumed. A valid reference may be insufficient for a particular claim.

## Cross-Domain Significance

`Reference → Integrity Claim → Evidence → Integrity Validation → Integrity Decision`

The reference may be supplied through `Representation`, qualified by `Temporal`, supported by `Relation`, `Quantity`, `State`, `Condition`, `Activity`, or `Result`, and traced through provenance controls.

## Trust and Evidence

A promoted or validated reference must preserve provenance, representation identity, scope, version, evidence status, and unresolved limitations. External reference authority and GIOP canonical authority remain distinct.

## Visitor Universe

All visitor depths use the same Integrity Reference semantics. Depth 0 explains the idea; deeper levels expose scope, sufficiency, representation, provenance, evidence and machine identifiers. No visitor receives an alternate definition.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived` according to Foundation controls.

## Retrieval Anchors

`INTEGRITY REFERENCE`, `REFERENCE BASIS`, `REFERENCE SCOPE`, `REFERENCE SUFFICIENCY`, `REFERENCE CONFIGURATION`, `INTEGRITY CLAIM`, `REFERENCE PROVENANCE`, `BIL`
