# GIOP Context Knowledge Registry

## Status

**CANONICAL RETENTION / AUDIT RECORD — V3.1**

## Purpose

This registry preserves the complete recovered Context knowledge corpus while separating evidence, semantic classification, canonical admission, and routing. It is an audit and retention layer, not a parallel canonical ontology.

## Governing Rule

**No recovered knowledge is discarded because it is not currently canonical in `contexts/`.**

`VERIFIED ≠ CANONICAL`

`NOT CANONICAL HERE ≠ NOT KNOWLEDGE`

`DEFERRED ≠ DELETED`

Every retained item has a semantic type, epistemic status, canonical status, evidence/provenance, GIOP decision, and destination or reconsideration condition.

## Registry Record Contract

Each record should contain:

- Stable GIOP registry ID;
- preferred term;
- recovered meaning;
- semantic type/family;
- epistemic status;
- canonical status;
- domain/range or contextual applicability where meaningful;
- evidence/provenance;
- conflicts and open questions;
- GIOP semantic decision;
- primary destination;
- cross-layer references;
- Visitor Universe relevance and entry guidance where useful;
- reconsideration trigger.

## Status Vocabulary

### Epistemic Status

- `VERIFIED`
- `UNDER VERIFICATION`
- `UNVERIFIED`
- `CONFLICTED`

### Canonical Status

- `CANONICAL`
- `CANONICAL CANDIDATE`
- `DEFERRED`
- `ROUTED ELSEWHERE`
- `HISTORICAL/NON-CANONICAL`

## Canonical Context Seed

### CTX-001 — Context

**Preferred term:** Context  
**Semantic type:** CONTEXT / CONTEXT-FAMILY ROOT  
**Epistemic status:** VERIFIED AS GIOP SYNTHESIS WITH STRONG EXTERNAL SUPPORT  
**Canonical status:** CANONICAL  
**Destination:** `02 SEMANTICS/contexts/context.md`

**Synthesized meaning:** A reusable semantic construct specifying the relevant setting, circumstance, purpose, perspective, or situational frame within which a semantic element is defined, interpreted, used, evaluated, observed, measured, represented, or otherwise understood.

**Evidence:** ISO/IEC 11179 context definitions; context-aware computing literature; GIOP Foundation architecture; cross-domain imaging, observation, measurement, viewing, and assessment evidence.

**Boundary decision:** Context is a frame, not a condition, state, quantity, relation, representation, or visitor category.

**Visitor frame:** All Visitor Universe classes may encounter Context; entry depth varies from orientation to specialist/research and machine retrieval.

### CTX-002 — Domain Context

**Semantic type:** DOMAIN-SPECIFIC CONTEXT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `contexts/domain-context.md`

**Synthesized meaning:** The knowledge universe, subject domain, disciplinary scope, or conceptual field under which an item is defined or interpreted.

**Evidence:** ISO/IEC 11179 context tradition; terminology and data-governance practice; GIOP architectural synthesis.

**Boundary decision:** Domain Context is not the same as a subject category, class, ontology, or physical environment.

### CTX-003 — Application Context

**Semantic type:** APPLICATION CONTEXT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `contexts/application-context.md`

**Synthesized meaning:** The concrete purpose, task, use scenario, or application setting in which a semantic element is used or evaluated.

**Boundary decision:** Application Context is narrower than generic Context and must not replace domain, task, or workflow semantics.

### CTX-004 — Capture Context

**Semantic type:** IMAGING APPLICATION CONTEXT  
**Epistemic status:** UNDER VERIFICATION AS CROSS-DOMAIN GIOP SYNTHESIS  
**Canonical status:** CANONICAL CANDIDATE / V3.1 SEED  
**Destination:** `contexts/capture-context.md`

**Synthesized meaning:** The contextual frame governing an imaging capture event or capture configuration, including relevant scene/object, camera/lens/sensor, illumination, environmental conditions, observer/operator, geometry, timing, settings, and purpose.

**Boundary decision:** Capture Context is not Camera, Exposure, Illumination Condition, Capture Activity, or a single configuration parameter.

### CTX-005 — Measurement Context

**Semantic type:** MEASUREMENT CONTEXT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `contexts/measurement-context.md`

**Synthesized meaning:** The contextual frame in which a measurement is planned, performed, interpreted, or compared, including relevant quantity/measurand, measuring system, procedure, conditions, influence quantities, configuration, timing, operator, traceability, and result interpretation.

**Evidence:** VIM; ISO/IEC 17025 practice; EMVA 1288 measurement methodology; imaging measurement standards.

**Boundary decision:** Measurement Context is broader than measurement condition, reference operating condition, or measurement procedure.

### CTX-006 — Viewing Context

**Semantic type:** VIEWING / PERCEPTUAL CONTEXT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `contexts/viewing-context.md`

**Synthesized meaning:** The contextual frame in which a visual stimulus or representation is viewed, including relevant stimulus, background, surround, adaptation, display, geometry, distance, observer, illumination, environment, and purpose.

**Evidence:** CIE viewing/color-appearance work; ITU-R BT.500; high-fidelity colorimetry requirements.

**Boundary decision:** Viewing Context is not equivalent to Viewing Condition, Perception, Display, Observer, or Illumination Condition.

### CTX-007 — Assessment Context

**Semantic type:** EVALUATION / ASSESSMENT CONTEXT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `contexts/assessment-context.md`

**Synthesized meaning:** The methodological and situational frame in which an assessment or evaluation is conducted, including task, test material, assessor/observer, procedure, session, anchors/reference, service-use scenario, and relevant environment.

**Evidence:** ITU-R BT.500 assessment-context concepts; subjective assessment methodology; GIOP synthesis.

**Boundary decision:** Assessment Context may include Viewing Context but is not synonymous with it.

### CTX-008 — Processing Context

**Semantic type:** COMPUTATIONAL / PIPELINE CONTEXT  
**Epistemic status:** UNDER VERIFICATION AS GIOP SYNTHESIS  
**Canonical status:** CANONICAL CANDIDATE / V3.1 SEED  
**Destination:** `contexts/processing-context.md`

**Synthesized meaning:** The contextual frame governing interpretation or execution of an imaging/computational processing operation, including input representation, processing stage, algorithm/model configuration, parameters, dependencies, runtime constraints, intended output, and relevant provenance.

**Boundary decision:** Processing Context is not Process, Algorithm, Software, Model, or Result.

### CTX-009 — Operational Context

**Semantic type:** SYSTEM / OPERATIONAL CONTEXT  
**Epistemic status:** UNDER VERIFICATION AS GIOP SYNTHESIS  
**Canonical status:** CANONICAL CANDIDATE / V3.1 SEED  
**Destination:** `contexts/operational-context.md`

**Synthesized meaning:** The contextual frame describing the circumstances and constraints under which a system, component, workflow, or activity operates, including relevant environment, configuration, resources, interfaces, operating constraints, actors, timing, and intended operating purpose.

**Boundary decision:** Operational Context is not Operating Condition, System, Workflow, or State.

## Retained Non-Seed and Cross-Layer Knowledge

### CTX-R10 — Observation Context

**Epistemic status:** VERIFIED EXTERNAL CONCEPT; GIOP RESPONSIBILITY UNDER ANALYSIS  
**Canonical status:** ROUTED ELSEWHERE / CROSS-REFERENCE  
**Primary destination:** Relations / Observation semantics

ISO 19156 uses ObservationContext for dependencies between observations that are important to understanding an observation or result. WaterML examples include support and derived observations. GIOP therefore retains this as a contextual relation pattern rather than automatically equating it with generic Context.

### CTX-R11 — Situation

**Epistemic status:** VERIFIED AS GENERAL TERM; SEMANTIC BOUNDARY UNSTABLE  
**Canonical status:** DEFERRED

Retain for later distinction between context frame, situation instance/configuration, and contextual information.

### CTX-R12 — Discourse Context

**Epistemic status:** VERIFIED GENERAL SEMANTIC TERM  
**Canonical status:** DEFERRED

Retained for later analysis of linguistic/documentary interpretation frames and relation to terminology/documentation semantics.

### CTX-R13 — Reference Context

**Epistemic status:** VERIFIED GENERAL PATTERN  
**Canonical status:** DEFERRED

Retained pending separation from reference systems, baselines, standards, and measurement reference concepts.

### CTX-R14 — Evaluation Context

**Epistemic status:** VERIFIED GENERAL PATTERN  
**Canonical status:** DEFERRED / POSSIBLE SUBDOMAIN OF ASSESSMENT CONTEXT

Retained until evaluation, assessment, validation, benchmarking, and measurement-result interpretation boundaries are reconciled.

### CTX-R15 — System Context

**Epistemic status:** VERIFIED GENERAL SYSTEMS PATTERN  
**Canonical status:** DEFERRED

Retained pending cross-analysis with Classes, operational semantics, architecture, and system-boundary concepts.

### CTX-R16 — Environmental Context

**Epistemic status:** VERIFIED PATTERN  
**Canonical status:** DEFERRED / OVERLAP RISK

Retained because environmental information can be a legitimate contextual frame, but existing Environmental Optical Conditions and Conditions must not be duplicated.

### CTX-R17 — Optical Context

**Epistemic status:** GIOP SYNTHESIS / UNDER VERIFICATION  
**Canonical status:** DEFERRED

Retained pending boundary analysis against `conditions/optical-condition.md` and `conditions/environmental-optical-conditions.md`.

### CTX-R18 — Contextual Information

**Epistemic status:** VERIFIED GENERAL INFORMATION-CONCEPT PATTERN  
**Canonical status:** DEFERRED / ROUTING PENDING

Retained because information describing a situation may be context without itself constituting a Context semantic frame.

### CTX-R19 — Spatial Context

**Epistemic status:** VERIFIED PATTERN  
**Canonical status:** ROUTED ELSEWHERE / CROSS-LAYER
**Primary destination:** future `spatial/`

Spatial information may qualify a Context, but spatial relations and quantities remain spatial-layer responsibilities.

### CTX-R20 — Temporal Context

**Epistemic status:** VERIFIED PATTERN  
**Canonical status:** ROUTED ELSEWHERE / CROSS-LAYER
**Primary destination:** future `temporal/`

Temporal information may qualify a Context, but temporal relations and quantities remain temporal-layer responsibilities.

## External Semantic Patterns Retained

The registry also preserves these evidence patterns without treating them as automatic GIOP canonical classes:

- ISO/IEC 11179 context as a universe of discourse and as circumstance/purpose/perspective of definition or use;
- ISO 19156 ObservationContext as observation-to-observation contextual dependency;
- OGC/W3C observation models linking feature, property, procedure/system, phenomenon time, result time, result, quality, and related observations;
- VIM measurement context requirements implied by measurand, procedure, calibrated measuring system, measurement conditions, and influence quantities;
- EMVA 1288 controlled imaging measurement setups and temperature/illumination/configuration dependencies;
- CIE stimulus/background/surround/adaptation viewing context;
- ITU-R BT.500 assessment context and viewing/observer/environment/test-material factors;
- high-fidelity colorimetry requirements involving source, object, camera, transmission, viewing, display, and system context;
- context-aware computing dimensions such as identity, activity, location, time, and relations;
- PROV-O qualification patterns for contextualized usage, generation, association, and derivation.

## Visitor Universe Mapping Rule

Visitor relevance does not determine canonicality. It determines access and presentation.

Each canonical or retained record may be mapped to:

- primary visitor classes;
- secondary visitor classes;
- likely visitor intent;
- entry depth;
- prerequisites;
- navigation anchors;
- machine/API retrieval use cases.

Unverified or conflicted knowledge remains visible to appropriate expert/research visitors with its uncertainty explicitly represented.

## Routing Principle

A retained term is routed according to semantic responsibility, not according to the word “context” in its name. Future folder creation must promote routed knowledge into a primary canonical semantic entry when that folder is authored and the concept meets its admission criteria.
