# Observes

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-OBSERVES-001`
- **Preferred Term:** `observes`
- **Artifact Type:** Canonical Relation Concept
- **Semantic Family:** Observation
- **Primary Responsibility:** Directed observation of an eligible target by an eligible observer.
- **Status:** ACTIVE — SCOPED CANONICAL
- **Version:** 1.0.0
- **Authority:** GIOP canonical semantic synthesis

## 5W1H Orientation
**What:** An observer-to-target observation relation.
**Why:** To distinguish observation from measurement, representation, participation, structure, and causation.
**Who:** Subject is an eligible observer or observing system/model.
**What is observed:** Object is an eligible target such as scene, object, phenomenon, signal, state, or representation.
**Where/When:** May be spatially and temporally qualified.
**How:** Establish the observer-target connection under the applicable observation context.

## Semantic Definition
**Observes specifies that an eligible observer observes an eligible target under a context in which observation is semantically meaningful.**

It does not require a calibrated quantitative result or conscious perception.

## Relation Contract
- **Domain:** Eligible observer, observing entity/system, or formal observer model.
- **Range:** Eligible observed target.
- **Direction:** `OBSERVER → OBSERVED TARGET`.
- **Inverse:** `is-observed-by` (inverse/retrieval term; not independently canonicalized here).
- **Characteristics:** Not symmetric and not generally transitive. Reflexivity is not fixed globally.

## Qualification / Context
Time/interval, spatial viewpoint, spectral range, modality, observation conditions, instrument configuration, perceptual/computational model, confidence, and provenance may qualify an assertion.

## Core Distinctions
`observes` ≠ `measures`, `represents`, `participates-in`, `part-of`, or `causes`. A Camera or Sensor does not automatically create an observation assertion merely by existing.

## Inference Boundary
Observation alone does not establish measurement, accuracy, representation, conscious perception, completeness, physical location, existence proof, or causation.

## Cross-Layer Significance
Connects Observer and other observing systems to Scene/Object/phenomenon/signal/state targets. It can coexist with participation in an observation activity, but the relations have different responsibilities.

## Trust / Validation
Support assertions with observation records, system descriptions, experimental protocols, acquisition context, or equivalent evidence. Co-occurrence is insufficient.

## Machine / AI Interpretation
Encode a directed predicate from observer to target; preserve context and uncertainty. Do not infer measurement, perception, representation, or accuracy.

## Lifecycle
ACTIVE — semantic changes require explicit review, versioning, and preservation.

## Retrieval Anchors
`observes`, `observe`, `observation`, `observed by`, `observer`, `observed target`, `observation relation`, `imaging observation`

## Semantic Boundary
**Observes is the GIOP relation for observation between an eligible observer and target and must remain distinct from measurement, perception, representation, participation, structure, and causation.**
