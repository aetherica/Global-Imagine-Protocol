# Participates In

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-PARTICIPATES-IN-001`
- **Preferred Term:** `participates-in`
- **Artifact Type:** Canonical Relation Concept
- **Semantic Family:** Participation
- **Primary Responsibility:** Involvement of an eligible participant in an activity, process, event, or occurrence.
- **Status:** ACTIVE — SCOPED CANONICAL
- **Version:** 1.0.0
- **Authority:** GIOP canonical semantic synthesis

## 5W1H Orientation
**What:** A directed involvement relation.
**Why:** To represent participation without implying structure, causality, control, or observation.
**Who/What:** Subject is the participant; object is the qualifying occurrence.
**Where:** Activities, processes, workflows, measurements, production, validation, and events.
**When:** Often requires temporal or stage qualification.
**How:** Identify participant and occurrence and establish actual involvement with evidence.

## Semantic Definition
**Participates In specifies that the subject is involved in an eligible activity, process, event, or other qualifying occurrence.**

Participation does not by itself specify role, causal contribution, control, necessity, or structural membership.

## Relation Contract
- **Domain:** Eligible participant/entity/agent/system.
- **Range:** Eligible activity/process/event/occurrence.
- **Direction:** `PARTICIPANT → OCCURRENCE`.
- **Inverse:** `has-participant` (inverse/retrieval term; not independently canonicalized here).
- **Characteristics:** Not symmetric and not generally transitive. No causal inference is authorized.

## Qualification / Context
Temporal interval, process stage, role, participation mode, and evidence may qualify an assertion.

## Core Distinctions
`participates-in` ≠ `part-of`, `observes`, `uses`, `causes`, or generic `associated-with`. A participant in an activity is not thereby a component of it, its cause, or its observer.

## Inference Boundary
No transitive, causal, structural, observational, ownership, control, or necessity inference follows from participation alone.

## Cross-Layer Significance
Links entity-oriented concepts to Activity/Process concepts, e.g. `Camera participates-in Image Capture Activity` or `Measuring System participates-in Measurement Activity`.

## Trust / Validation
Use workflow records, process documentation, measurement procedures, production records, system descriptions, or equivalent evidence. Mention alone is insufficient.

## Machine / AI Interpretation
Encode directed involvement from participant to occurrence and preserve any role/time qualification. Do not infer causality or structure.

## Lifecycle
ACTIVE — semantic changes require explicit review, versioning, and preservation.

## Retrieval Anchors
`participates in`, `participates-in`, `participation`, `participant`, `has participant`, `has-participant`, `activity involvement`, `event participation`

## Semantic Boundary
**Participates In is the GIOP relation for involvement in an eligible occurrence and must remain distinct from structural constitution, causation, observation, control, and operational use.**
