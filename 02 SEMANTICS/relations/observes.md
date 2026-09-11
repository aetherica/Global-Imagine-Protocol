# Observes

## Identity / Metadata

- **GIOP ID:** `SEM-RELATION-OBSERVES-001`
- **Title:** Observes
- **Artifact Type:** Canonical Relation Concept
- **Primary Responsibility:** Reusable relation connecting an eligible observer to a target that is observed.
- **Semantic Family:** Observation Relation
- **Status:** CANONICAL
- **Version:** V3.1
- **Authority:** GIOP canonical semantic synthesis
- **Lifecycle:** ACTIVE
- **Provenance:** GIOP semantic research and cross-layer reconciliation
- **Related IDs:** `SEM-CLASS-OBSERVER-001`, `SEM-CLASS-SCENE-001`, `SEM-CLASS-OBJECT-001`, `SEM-RELATION-PARTICIPATES-IN-001`, `SEM-RELATION-REPRESENTS-001`

## 5W1H Orientation

### What

`observes` specifies that an eligible observer is directed toward or obtains information about an eligible target through an observation relation.

### Why

It distinguishes observation from representation, physical part–whole structure, participation in a process, and mere association.

### Who

The subject is an observer or other eligible observing entity or formal observer model.

### What is observed

The object is an eligible target such as an object, scene, phenomenon, state, signal, representation, or other entity that can meaningfully be observed under the relevant semantics.

### Where / When

Observation may be spatially and temporally qualified. The relation does not imply unrestricted access or continuous observation.

### How

An assertion identifies the observer and observed target and states that the observer observes the target under the applicable observation context.

## Semantic Definition

**Observes is a reusable relation concept specifying that an eligible observer observes an eligible target under a context in which observation is semantically meaningful.**

Observation is intentionally broader than a particular measurement procedure and does not require that the observation produce a calibrated quantitative result.

## Relation Family

`observes` belongs to the observation relation family.

It may connect human observers, instruments, cameras, sensors, computational observer models, or other explicitly eligible observing entities, depending on the target and context.

## Subject / Domain

The subject/domain is an eligible observer.

An observer may be:

- a human or other biological observer;
- an instrument or measuring system acting observationally;
- a camera or sensor system when the canonical semantics support treating its sensing activity as observation;
- a computational or formal observer model.

Being a Camera or Sensor does not automatically establish an observation assertion.

## Object / Range

The object/range is an eligible observed target, including an object, scene, phenomenon, signal, state, or other information-bearing target for which observation is defined.

The target need not be a human-perceived object.

## Directionality

`observes` is directed:

`OBSERVER → OBSERVED TARGET`

The inverse may be described as `is-observed-by`, but no separate canonical page is required merely to express the inverse.

## Logical Characteristics

`observes` is not symmetric.

It is not generally transitive. If A observes B and B observes C, A does not thereby observe C.

It is not automatically reflexive or irreflexive in every formal observation model; the applicable model must define any special self-observation case explicitly.

Observation does not imply measurement, representation, causation, ownership, or continuous attention.

## Applicability

Use `observes` when the semantic fact concerns an observer's observation of a target.

For measurement-specific semantics, a measurement relation such as `measures` may later provide a narrower concept. `observes` must not be silently used as a substitute for a measurement assertion.

## Distinctions / Non-equivalence

### Observes vs Measures

Observation does not necessarily involve a measurement procedure, quantity, calibrated system, or measurement result. Measurement is a narrower activity/process-oriented concept.

### Observes vs Represents

An observer observes a target; a representation represents a target or information about it. A representation may be observed, but the two relations describe different semantic directions and roles.

### Observes vs Participates In

An observer can participate in an observation activity, but participation does not itself establish what the observer observes.

### Observes vs Part Of

Observation does not imply structural constitution.

### Observes vs Causes / Affects

Observation alone does not establish causal influence. An observation process can affect a target in some physical systems, but that is a separate claim.

## Qualification / Context

Observation may be qualified by:

- time or interval;
- spatial viewpoint or region;
- spectral range;
- modality;
- observation conditions;
- instrument configuration;
- perceptual or computational model;
- confidence or provenance.

A context-sensitive observation assertion must retain enough qualification to avoid overgeneralization.

## Inference Boundary

An `observes` assertion does not permit automatic inference that:

- the target is physically present in a particular location;
- the target is accurately measured;
- a representation is generated;
- the observer perceives the target consciously;
- the observation is complete;
- the observation is correct or unbiased.

Those claims require independent evidence or relations.

## Cross-Layer Relations

`observes` may connect an Observer class to a Scene, Object, Phenomenon, Signal, or other eligible target.

Typical concept-level patterns include:

`Observer observes Scene`

`Camera observes Scene`

`Sensor observes Optical Signal`

These patterns do not assert any particular real-world instance.

## Typical GIOP Usage

Use `observes` for semantic retrieval, observation-chain descriptions, imaging-system relationships, scientific observation contexts, and machine-readable knowledge graphs.

## Evidence / Provenance

The relation is supported by observation modeling across scientific and imaging domains and by formal ontology patterns distinguishing observers, observed entities, and measurement activities. GIOP semantics remain an independent synthesis.

## Trust / Validation

An observation assertion should be supported by an observation record, system description, experimental protocol, image acquisition context, or other evidence demonstrating the observer-target connection.

Presence of both entities in the same document is insufficient.

## Lifecycle

- **Current state:** ACTIVE / CANONICAL
- **Change control:** semantic changes require explicit review and versioning.
- **Supersession:** none currently.
- **Preservation:** prior semantic decisions remain auditable.

## Machine / AI Interpretation

A machine should treat `observes` as a directed relation from an observer to an observed target.

It must not infer measurement, accuracy, perception, causation, or representation merely from the predicate.

## Retrieval Anchors

`observes`, `observe`, `observation`, `observed by`, `observer`, `observed target`, `observation relation`, `imaging observation`, `scientific observation`

## What This Relation Does NOT Mean

It does not by itself mean:

- measures;
- perceives consciously;
- represents;
- captures a valid image;
- proves existence;
- proves accuracy;
- causes;
- participates-in;
- part-of.

## Semantic Boundary

**Observes is the GIOP relation for an observer observing an eligible target. It must remain distinct from measurement, perception, representation, participation, and causation.**
