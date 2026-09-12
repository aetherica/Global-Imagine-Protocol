# Identity Resolution

## Identity / Metadata
- GIOP ID: SEM-IDENTITY-RESOLUTION-001
- Semantic Layer: Domain Semantic Layer
- Domain: Identity
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Identity, Relation, Representation, Evidence, Process, Activity, Temporal

## 5W1H Orientation

### What
Identity Resolution is the determination of whether records, references, observations, representations, or claims correspond to the same intended identity, or to distinct identities, within a declared scope.

### Why
Resolution is necessary when multiple records may describe the same referent, when identifiers differ across systems, or when an observed entity must be associated with an existing identity without assuming that lexical similarity proves correspondence.

### Who
Resolution may be performed by human adjudicators, authoritative registries, analysts, software systems, biometric systems, or hybrid workflows. Responsibility and assurance depend on the application.

### Where
It operates within a defined population, registry, dataset, scene, institutional domain, or cross-system mapping. Scope determines which identities and evidence are eligible for comparison.

### When
Resolution occurs during enrollment, record linkage, deduplication, observation association, investigation, migration, synchronization, or other identity-management events. Results may be revised when new evidence appears.

### How
Resolution combines identifiers, attributes, representations, relations, temporal context, biometric evidence where appropriate, provenance, and decision rules. The output is a correspondence decision or unresolved/indeterminate result, not merely a similarity score.

## Semantic Definition
Identity Resolution is the semantic determination of correspondence between identity references and candidate referents within a specified scope, based on available evidence and an explicit decision context.

## Scope / Boundary
Identity Resolution owns correspondence semantics. The computational method used to perform matching belongs to Computational Method/Implementation. Biometric Verification and Identification are operational biometric activities and processes. Authentication is a separate security decision. BIL may consume resolution results as evidence but does not own identity resolution.

## Core Distinctions
- Resolution ≠ Identification of every kind; terminology is context-dependent.
- Resolution ≠ Authentication.
- Resolution ≠ Similarity measurement.
- Resolution ≠ Identity itself.
- Unresolved ≠ false: insufficient evidence must remain distinguishable from contradiction.

## Cross-Domain Significance
Resolution connects identity, biometrics, records, observation, representation, temporal continuity, provenance, and decision semantics. It is a major bridge between raw evidence and identity-level assertions.

## Trust / Evidence
Resolution requires evidence appropriate to the risk and scope. Evidence conflict, missing evidence, model uncertainty, and provenance should remain visible rather than being collapsed into an unexplained binary result.

## Visitor Universe
Novices need the correspondence concept. Experts need candidate generation, evidence fusion, scope, thresholds, adjudication, uncertainty, and temporal identity continuity. Machines need candidate sets, evidence references, correspondence relations, decision state, and provenance.

## Lifecycle
A resolution decision can be proposed, evaluated, accepted, rejected, disputed, superseded, or revised. The lifecycle of the decision is distinct from the lifecycle of the identity.

## Retrieval Anchors
identity resolution, record linkage, identity correspondence, entity resolution, identity matching, identity reconciliation
