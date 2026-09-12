# Biometric Template

## Identity / Metadata
- GIOP ID: SEM-BIOMETRIC-TEMPLATE-001
- Semantic Layer: Domain Semantic Layer
- Domain: Biometrics
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Representation, Computation, Identity, Provenance, Temporal

## 5W1H Orientation

### What
A Biometric Template is a processed representation of biometric information structured for comparison or decision-making by a biometric system. It generally contains derived features rather than a direct unprocessed sample.

### Why
Templates make biometric comparison computationally tractable and can reduce dependence on retaining raw samples. Their representation and security properties depend on the biometric modality and algorithm.

### Who
Templates are produced and consumed by biometric algorithms and systems operated by authorized entities. Different systems may generate incompatible templates from the same underlying biometric characteristic.

### Where
Templates may be stored in biometric repositories, devices, credentials, or protected application systems. Storage and protection mechanisms are implementation concerns, while the template's semantic role remains a biometric representation.

### When
A template is generated during enrollment or update and may be replaced, revoked, archived, or deleted. Template age and algorithm version can affect its operational usefulness.

### How
A sample is acquired and processed by a feature-extraction or encoding method to produce a template. Later samples are transformed using compatible processing and compared according to a defined biometric method.

## Semantic Definition
A Biometric Template is a derived biometric representation intended for computational comparison within a specified biometric system or algorithmic ecosystem.

## Scope / Boundary
Template owns the derived biometric representation concept. Generic Representation owns representation semantics. Computational Method owns feature extraction and comparison algorithms. Identity owns referent semantics. A template is not inherently an identifier or identity proof.

## Core Distinctions
- Template ≠ sample.
- Template ≠ characteristic.
- Template ≠ identity.
- Template ≠ identifier.
- Template compatibility is method- and representation-dependent.

## Cross-Domain Significance
Templates bridge biometric sensing, representation, computation, identity, security, and evaluation. Their outputs may contribute evidence to verification or identification workflows but do not independently determine semantic truth.

## Trust / Evidence
Trust depends on acquisition provenance, algorithm/version, template integrity, subject binding, quality, lifecycle, and protection. A high similarity score is not equivalent to a proven identity.

## Visitor Universe
Novices need the sample/feature/template distinction. Experts need interoperability, algorithm dependence, template protection, versioning, quality, comparison scores, thresholds, and uncertainty. Machines need typed template metadata, modality, algorithm, subject/reference binding, and provenance.

## Lifecycle
Generation → validation → enrollment/storage → comparison → version migration or replacement → revocation/retirement → deletion or archival according to policy.

## Retrieval Anchors
biometric template, biometric feature template, biometric feature representation, comparison template
