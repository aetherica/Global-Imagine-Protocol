# Biometric Reference

## Identity / Metadata
- GIOP ID: SEM-BIOMETRIC-REFERENCE-001
- Semantic Layer: Domain Semantic Layer
- Domain: Biometrics
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Identity, Representation, Measurement, Provenance, Temporal

## 5W1H Orientation

### What
A Biometric Reference is a stored or designated representation of biometric information associated with a subject or identity reference for later biometric comparison, verification, identification, or related operations.

### Why
A reference provides a stable comparison target derived from biometric evidence while separating stored biometric information from the live sample captured during a later operation.

### Who
References may be created and managed by biometric systems, identity authorities, service providers, institutions, or other authorized operators. Governance depends on the application and sensitivity of the biometric data.

### Where
A reference may reside in a controlled biometric repository, identity system, device, credential, or other storage environment. Storage location and access policy are distinct from reference semantics.

### When
A reference is enrolled, updated, re-enrolled, suspended, revoked, archived, or deleted according to policy. Biological change and reference lifecycle must not be conflated.

### How
A reference is generated from one or more biometric samples through a defined acquisition and processing workflow, with metadata and provenance sufficient to interpret its origin and intended use.

## Semantic Definition
A Biometric Reference is a persistent or designated representation of biometric information intended to serve as a comparison reference in a biometric system.

## Scope / Boundary
Reference owns the biometric-domain role of a stored comparison representation. Generic Representation owns representation semantics. Template is a particular derived representation when the system defines it as such. Identity owns the subject referent. Provenance owns lineage. BIL may use a biometric reference as integrity evidence.

## Core Distinctions
- Reference ≠ live biometric sample.
- Reference ≠ identity.
- Reference ≠ identifier.
- Reference ≠ arbitrary image of a subject.
- Reference validity ≠ biometric truth.

## Cross-Domain Significance
Biometric references connect enrollment, identity management, representation, security, provenance, and later comparison. They can support identity resolution while remaining distinct from the decision produced by a biometric operation.

## Trust / Evidence
Trust depends on source, binding to the intended subject, acquisition conditions, processing history, integrity protection, lifecycle status, and applicable governance. Reference authenticity does not guarantee current biological correspondence.

## Visitor Universe
Novices need sample-versus-reference distinction. Experts need binding, quality, lifecycle, revocation, renewability, provenance, and privacy/security controls. Machines need reference IDs, subject bindings, modality metadata, provenance, and lifecycle state.

## Lifecycle
Creation → enrollment → active use → update/re-enrollment → suspension or revocation → archival/deletion. Exact lifecycle is governed by the application.

## Retrieval Anchors
biometric reference, biometric reference data, enrolled biometric reference, biometric enrollment reference
