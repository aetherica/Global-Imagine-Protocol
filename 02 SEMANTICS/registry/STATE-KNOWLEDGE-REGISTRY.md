# GIOP State Knowledge Registry

## Status

**CANONICAL RETENTION / AUDIT RECORD — V3.1**

## Purpose

This registry preserves recovered State knowledge, alternative classifications, candidate vocabulary, structural constructs, unresolved semantic boundaries, evidence, conflicts, and GIOP decisions before or alongside canonical publication.

The registry is a retention and decision layer. It is not a parallel State ontology.

## Governing Rules

`VERIFIED ≠ CANONICAL`

`DEFERRED ≠ DELETED`

`FILTERED ≠ DISCARDED`

Canonical semantic folders remain authoritative for canonical meaning. Registry records preserve the reasoning and retained knowledge that support those decisions.

## Record Contract

Each material record should expose, where applicable:

- stable registry ID;
- preferred term;
- recovered meaning;
- semantic/structural type;
- epistemic status;
- canonical status;
- scope/applicability;
- evidence/provenance;
- competing meanings or classifications;
- GIOP decision;
- destination;
- cross-layer references;
- reconsideration trigger.

## Canonical Record

### STATE-001 — State

**Preferred term:** State  
**Semantic type:** STATE / CANONICAL SEMANTIC CONCEPT  
**Epistemic status:** VERIFIED GIOP SYNTHESIS WITH STRONG EXTERNAL SUPPORT  
**Canonical status:** CANONICAL / PROVISIONAL  
**Destination:** `02 SEMANTICS/states/state.md`

**Synthesized meaning:** A reusable canonical semantic concept denoting a recognized mode or condition in which an eligible bearer exists or operates at a specified temporal locus.

**Primary boundaries:** Condition, Property, Status, Quantity/Value, Activity, Process, Event, Disposition, Configuration, Context, Relation.

**Evidence basis:** ISO/IEC/IEEE systems-engineering terminology; comparative ontology evidence from BFO and DOLCE; applied State modelling in ETSI SAREF and OPC UA; observation/property modelling in W3C SSN/SOSA; event/provenance modelling in W3C PROV.

## Structural / Deferred Records

### STATE-002 — State Assertion

**Semantic type:** ASSERTION / STRUCTURAL CONSTRUCT  
**Canonical status:** DEFERRED AS INDEPENDENT SEMANTIC ENTRY  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A bearer-specific assertion that a particular entity, system, function, or semantic element is in a specified State at a temporal locus.

**GIOP decision:** Retain as an assertion pattern rather than a separate State semantic entry.

### STATE-003 — State Value

**Semantic type:** STRUCTURAL / VALUE MODEL  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A qualitative value that may represent one allowable state within a particular State model.

**GIOP decision:** Retain for interoperability analysis with SAREF and future value semantics. Do not create a separate V3.1 semantic entry yet.

### STATE-004 — State of Interest

**Semantic type:** BEARER-SPECIFIC STATE PATTERN  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A state usage associated with a particular feature or bearer.

**GIOP decision:** Retain as a modelling pattern. Independent semantic responsibility is not yet required.

### STATE-005 — State Machine

**Semantic type:** STRUCTURAL MODEL  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A model specifying states, transitions, current state and optionally substates.

**Evidence:** OPC UA state-machine modelling.

**GIOP decision:** Keep outside the canonical State semantic nucleus.

### STATE-006 — Transition

**Semantic type:** STRUCTURAL CHANGE CONSTRUCT  
**Canonical status:** DEFERRED / CROSS-LAYER REVIEW  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A directed change from one State to another within a particular State Machine or state model.

**GIOP decision:** Do not classify as State. Future Relation/Process/Activity/Temporal analysis may refine its canonical home.

### STATE-007 — State Variable

**Semantic type:** COMPUTATIONAL / MODEL CONSTRUCT  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A model variable representing current state in an implementation or computational system.

**GIOP decision:** Runtime/model construct, not primary State semantic authority.

### STATE-008 — State History

**Semantic type:** TEMPORAL / HISTORY CONSTRUCT  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A record or model of state succession over time.

**GIOP decision:** Retain for future temporal/provenance integration.

### STATE-009 — State Hierarchy / Substate

**Semantic type:** STRUCTURAL ORGANIZATION  
**Canonical status:** DEFERRED  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** Hierarchical or nested organization of State models.

**GIOP decision:** Model-specific; not a universal State semantic hierarchy.

### STATE-010 — Mode

**Semantic type:** NEIGHBORING SEMANTIC CONSTRUCT  
**Canonical status:** DEFERRED / CANDIDATE  
**Destination:** `states/STATE-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A way of operating or functioning used in systems-engineering and applied state models.

**Conflict:** External literature does not establish one stable State-versus-Mode boundary.

**GIOP decision:** Do not promote into a State hierarchy without future independent semantic analysis.

## Strong Generic State Candidates

| ID | Preferred term | Status | Evidence / boundary |
|---|---|---|---|
| STATE-CAND-011 | On | CANDIDATE | Recurs in applied state models; may also be modelled as a State Value. |
| STATE-CAND-012 | Off | CANDIDATE | Recurs in applied state models; may also be modelled as a State Value. |
| STATE-CAND-013 | Open | CANDIDATE | Recurrent state/value usage; W3C SSN and SAREF illustrate different modelling responsibilities. |
| STATE-CAND-014 | Closed | CANDIDATE | Same Open/Closed modelling boundary. |
| STATE-CAND-015 | Ready | CANDIDATE | Recurrent state-machine usage; exact readiness criteria remain model-specific. |
| STATE-CAND-016 | Running | CANDIDATE | Recurrent state-machine usage; must be separated from running Process/Activity. |
| STATE-CAND-017 | Stopped | CANDIDATE | Recurrent operational State; may overlap with event/process outcome. |
| STATE-CAND-018 | Suspended | CANDIDATE | Recurrent state-machine State; model-specific semantics. |
| STATE-CAND-019 | Standby | CANDIDATE | Common device/operational State; may overlap with power or Mode semantics. |

## Medium / Operational Candidates

| ID | Preferred term | Status | Boundary |
|---|---|---|---|
| STATE-CAND-020 | Idle | CANDIDATE | State vs Mode/Status depends on model. |
| STATE-CAND-021 | Active | CANDIDATE | State vs Status/Property ambiguity. |
| STATE-CAND-022 | Initializing | CANDIDATE | State vs Process/Transition ambiguity. |
| STATE-CAND-023 | Maintenance | DEFERRED / CANDIDATE | State vs Activity/Lifecycle stage. |
| STATE-CAND-024 | Processing | DEFERRED / CANDIDATE | State vs Process/Activity. |
| STATE-CAND-025 | Degraded | DEFERRED / CANDIDATE | State vs diagnostic Condition/Status. |
| STATE-CAND-026 | Unavailable | DEFERRED | State vs Status/availability semantics. |

## High-Risk Candidates

| ID | Preferred term | Status | Boundary |
|---|---|---|---|
| STATE-CAND-027 | Configured | DEFERRED | Configuration/Status/State overlap. |
| STATE-CAND-028 | Connected | DEFERRED | Relation/State/Status overlap. |
| STATE-CAND-029 | Available | DEFERRED | State/Status/Capability overlap. |
| STATE-CAND-030 | Calibrated | DEFERRED | Calibration activity, result, status, condition, and State may all be expressed by the term. |
| STATE-CAND-031 | Validated | DEFERRED / STATUS-RELATED | Validation standing is not automatically a State. |
| STATE-CAND-032 | Faulted | DEFERRED | Diagnostic State/Condition/Status/Failure boundary. |
| STATE-CAND-033 | Failed | DEFERRED | Failure event/phenomenon/State boundary. |
| STATE-CAND-034 | Recording | DEFERRED | State/Activity/Process/Mode overlap. |
| STATE-CAND-035 | Capturing | DEFERRED | State/Activity/Process overlap. |

## Domain-Specific Candidates

### Imaging / Capture

- Capture State;
- Recording State;
- Streaming State;
- Exposure State;
- Focus State;
- Sensor State;
- Display State;
- Image Pipeline State;
- Calibration State.

**Decision:** Retain as domain candidates only. Each requires independent responsibility analysis against Activities, Processes, Properties, Conditions, Statuses, Contexts, Quantities, and future domain-specific layers.

## Evidence and Conflict Notes

External standards and models demonstrate that State terminology is used differently for different modelling purposes. In particular:

- ISO/IEC/IEEE systems engineering uses State as a time-qualified system or element condition;
- SAREF distinguishes State, StateOfInterest, and StateValue;
- OPC UA uses State within formal state-machine structures and separates Transition;
- W3C SSN/SOSA may model terms such as open state from a Property/observation perspective;
- BFO does not require a universal State top-level category and emphasizes distinctions among process, quality, disposition, and related entities;
- DOLCE provides a comparative State/Process treatment.

GIOP therefore treats these sources as evidence inputs and synthesizes a model-neutral semantic responsibility rather than copying one ontology.

## Canonical Decision

`State` is canonical for V3.1.

No current candidate term is promoted to a second V3.1 State semantic entry. Candidate vocabulary remains retained for future term-by-term review.

## Reconsideration Triggers

Revisit candidates when:

1. independent reusable semantic responsibility is demonstrated;
2. a candidate recurs across multiple validated contexts with stable meaning;
3. a stable machine-retrievable identity is required;
4. existing layers cannot represent the concept without semantic loss;
5. new evidence resolves current conflicts;
6. future `statuses/`, `temporal/`, `values/`, `processes/`, or related layers establish a clearer canonical home.

## Visitor Universe Relevance

Visitor relevance affects retrieval and entry depth only.

- General visitors use State for basic orientation.
- Learners inspect distinctions.
- Practitioners use examples and operational models.
- Engineers/researchers inspect temporal, evidentiary, and boundary semantics.
- AI/data/API consumers resolve stable IDs, assertion patterns, provenance, and validation.

No visitor category is itself a State semantic type.
