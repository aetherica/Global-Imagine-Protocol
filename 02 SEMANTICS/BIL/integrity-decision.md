# BIL Integrity Decision

**Semantic ID:** `SEM-BIL-INTEGRITY-DECISION-001`  
**Preferred Name:** Integrity Decision  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Decision** is the qualified interpretation assigned to an Integrity Evaluation under a declared scope, policy, evidence state and uncertainty profile.

## 5W1H Orientation

### What
A decision records the interpreted outcome of an Integrity Evaluation.

### Why
Integrity cannot always be represented as binary pass/fail. A claim may be supported, uncertain, insufficiently evidenced, contradicted, or consistent only within a declared transformation policy.

### Who
Relevant to practitioners, validation engineers, auditors, expert reviewers, researchers and machine systems.

### Where
All BIL profiles where a claim reaches an evaluative outcome.

### When
After or alongside Integrity Validation; decision state may be revised when material evidence or policy changes.

### How
The decision references the claim, evaluation, policy version, evidence state, uncertainty and provenance.

## Semantic Definition

**Integrity Decision** is the BIL control concept denoting the qualified interpretation of an Integrity Evaluation within a declared scope and policy.

## Candidate Outcome Vocabulary

`CONSISTENT`  
`CONSISTENT_WITH_PERMITTED_VARIATION`  
`DECLARED_TRANSFORMATION`  
`INSUFFICIENT_EVIDENCE`  
`UNCERTAIN`  
`INCONSISTENT`  
`CONFLICTING_EVIDENCE`  
`POTENTIAL_INTEGRITY_THREAT`  
`REQUIRES_ADJUDICATION`

These are candidate control states, not yet universal normative vocabulary.

## Core Distinctions

Decision ≠ truth; ≠ evidence; ≠ validation; ≠ Result; ≠ confidence; ≠ automatic binary pass/fail.

## Cross-Domain Significance

A decision may become a Result artifact where appropriate, while its integrity meaning remains BIL-owned. Provenance and lifecycle remain separately controlled.

## Trust and Evidence

Every decision must identify decision basis, policy/version, evidence status, uncertainty, authority/reviewer where applicable, provenance and change history.

## Visitor Universe

D0 presents the outcome meaning; D1 explains the outcome vocabulary; D2 exposes profile interpretation; D3 exposes evidence/uncertainty; D4 exposes machine decision records.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`INTEGRITY DECISION`, `EVALUATION OUTCOME`, `CONSISTENT`, `INSUFFICIENT EVIDENCE`, `INCONSISTENT`, `BIL`
