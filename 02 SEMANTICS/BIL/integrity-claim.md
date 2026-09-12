# BIL Integrity Claim

**Semantic ID:** `SEM-BIL-INTEGRITY-CLAIM-001`  
**Preferred Name:** Integrity Claim  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Claim** is a bounded assertion that a specified integrity-relevant correspondence or preservation condition holds for a declared reference, target, context, and transformation scope.

## 5W1H Orientation

### What
A scoped assertion about preservation or consistency of identity, structure, state, interaction, appearance, configuration, temporal continuity, or another declared integrity dimension.

### Why
A raw statement such as “the subject is preserved” is too broad. The claim must identify exactly what is being evaluated and under which context.

### Who
Relevant to imaging practitioners, scientists, VFX teams, validation engineers, researchers, auditors, and machine systems.

### Where
Still, video, multi-view, 3D/4D, generated-media, scientific, medical, wildlife, sports, dance and VFX contexts.

### When
Claims may apply at a frame, sequence, transformation stage, version interval, or lifecycle interval.

### How
`Reference → Claim Target → Integrity Claim → Evidence → Evaluation → Decision`.

## Semantic Definition

**Integrity Claim** is a BIL control concept denoting a bounded assertion about the consistency, preservation, or permitted correspondence of an integrity-relevant target relative to a declared reference and context.

## Core Distinctions

Claim ≠ Property; Claim ≠ State; Claim ≠ Evidence; Claim ≠ Validation; Claim ≠ Result; Claim ≠ Decision; Claim ≠ generic truth statement.

A claim does not become true because it is written. Its support is determined through evidence and evaluation.

## Scope and Boundary

Every claim should expose, where applicable: reference, target, integrity dimension, profile/context, temporal scope, transformation intent, permitted variation, evidence state, provenance and validation state.

## Cross-Domain Significance

Claims may target canonical concepts owned by other GIOP layers. BIL does not redefine those concepts; it evaluates an integrity proposition about them.

## Trust and Evidence

Claims must distinguish source statement, GIOP synthesis, evidence, validation status, confidence, unresolved questions, and historical status.

## Visitor Universe

D0 explains the claim idea; D1 introduces claim structure; D2 exposes applied scope; D3 exposes evidence and validation; D4 exposes stable IDs and machine relations. Meaning remains invariant.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`INTEGRITY CLAIM`, `CLAIM TARGET`, `CLAIM SCOPE`, `CLAIM EVIDENCE`, `CLAIM VALIDATION`, `BIL`
