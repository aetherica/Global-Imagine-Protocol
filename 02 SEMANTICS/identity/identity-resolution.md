# Identity Resolution

**Semantic ID:** `SEM-IDENTITY-RESOLUTION-001`
**Preferred Name:** Identity Resolution
**Semantic Class:** Identity Process Concept
**Domain:** Identity
**Status:** CANONICAL CANDIDATE — V3.1 SEED
**Version:** 0.1.0

## 5W1H Orientation

### What

Identity Resolution is the process of determining whether available evidence refers to an existing identity, a new identity, or an unresolved/ambiguous referent within a declared scope.

### Why

Different records or observations may contain aliases, incomplete attributes, duplicate records, transformed representations, or conflicting evidence.

### Who

Identity systems, archivists, investigators, registries, AI systems, search systems, and human assessors may perform identity resolution.

### Where

Databases, image collections, digital identity systems, archives, scientific datasets, and machine perception pipelines.

### When

Resolution is performed relative to a specific time, population, task, and evidence set.

### How

Resolution compares candidate evidence against identity criteria and produces a result such as resolved, unresolved, ambiguous, or rejected according to the applicable process.

## Semantic Definition

**Identity Resolution** is the scoped process of linking an observation, record, representation, or claim to an identity candidate or determining that available evidence is insufficient or conflicting.

## Scope / Boundary

This page defines the identity-domain responsibility, not a universal matching algorithm. Similarity metrics, biometric comparison algorithms, clustering, database retrieval, and authentication protocols belong to their respective computational, biometric, relation, activity, process, workflow, or implementation layers.

## Core Distinctions

**Resolution vs Verification:** verification tests a presented claim against a specified reference or identity context; resolution may search among multiple possible identities.

**Resolution vs Identification:** identification is a task/result term used in specific systems; the generic identity process should not assume a particular modality or algorithm.

**Resolved vs Certain:** a resolution result can be tentative or confidence-qualified.

**Unresolved vs Wrong:** insufficient evidence is different from contradictory evidence.

## Cross-Domain Significance

`Identity → Candidate Evidence → Comparison/Assessment → Result → Provenance`.

## Trust / Evidence

Resolution should record scope, candidate population, evidence sources, decision criteria, uncertainty, and provenance. NIST's current digital identity guidance treats identity resolution as a distinct step in identity proofing; that digital use is a specialization rather than the generic GIOP meaning.

## Visitor Universe

Novice: linking records to the same referent.

Expert: candidate generation, disambiguation, evidence conflict, temporal continuity, and uncertainty.

## Lifecycle

Candidate seed → validation → Gate-J → Active Canonical.

## Retrieval Anchors

`IDENTITY RESOLUTION`, `ENTITY RESOLUTION`, `RECORD LINKAGE`, `IDENTITY MATCHING`, `IDENTITY DISAMBIGUATION`
