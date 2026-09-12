# GIOP V3.1 — Biological Integrity Lock (BIL) Implementation Readiness

**Status:** PREPARATION ONLY — NOT CANONICAL BIL PROMOTION
**Branch:** `v3.1-tree-architecture`
**Scope:** Preparation for implementation of the `02 SEMANTICS/BIL` domain after semantic and Gate-J approval.

## 1. Purpose

This document prepares the implementation architecture for the Biological Integrity Lock (BIL) domain without prematurely turning research findings, prompt-derived implementation details, or profile-specific methods into canonical semantic entries.

The governing principle is:

> **BIL is a cross-layer integrity-control framework. It consumes canonical GIOP semantics and context-specific evidence to determine whether a declared biological/configurational reference remains consistent under permitted transformation.**

BIL is not a replacement semantic ontology for Class, Property, Condition, State, Quantity, Activity, Process, Relation, Representation, Temporal, Result, Workflow, Computational Method, Implementation, or Provenance.

## 2. Architectural source rule

The current BIL investigation is informed by the Module 05 reference-extraction strategy from the Meta Genesis engineering prompt, external scientific/standards research, and existing GIOP semantic boundaries.

Module 05 is treated as an **implementation exemplar and research stimulus**, not as the canonical definition of BIL.

Prompt-specific constants, models, thresholds, vendor mixtures, model names, and numerical tolerances are not BIL-wide invariants unless independently validated and promoted.

## 3. Canonicalization gate

No substantive BIL concept should be promoted directly from research discovery.

Required path:

```text
DISCOVERY
  ↓
RETAIN / RESEARCH REGISTRY
  ↓
SEMANTIC CLASSIFICATION
  ↓
EXISTING-LAYER / DUPLICATE CHECK
  ↓
BOUNDARY ANALYSIS
  ↓
EVIDENCE + CONFLICT REVIEW
  ↓
BIL-NATIVE CANDIDATE DECISION
  ↓
AUTHORING PROFILE
  ↓
VALIDATION GATES A–I
  ↓
GATE J PROMOTION APPROVAL
  ↓
ACTIVE CANONICAL
```

This follows the Foundation knowledge-entry rule and the current lifecycle/promotion controls. Repository placement does not determine semantic authority.

## 4. Proposed BIL core responsibility

The current working responsibility is:

> **Interpret and evaluate the integrity of a declared biological or biologically relevant configuration across observation, representation, transformation, interaction, and time, using explicit reference, evidence, invariance, permitted-variation, uncertainty, and decision controls.**

This is a working architectural statement, not yet a canonical semantic definition.

## 5. BIL core candidate domains

The following are implementation candidates, not yet promoted semantic entries:

| Candidate domain | Intended responsibility | Likely status |
|---|---|---|
| Integrity Reference | Declares the reference context against which a claim may be evaluated | BIL-native candidate |
| Integrity Claim | Expresses a bounded claim about preservation/consistency | BIL-native candidate |
| Invariant | Identifies information expected to persist under a declared context | BIL-native candidate |
| Permitted Variation | Defines context/intent-bounded change that does not constitute failure | BIL-native candidate |
| Integrity Evidence | Records the evidence pathway supporting an integrity assessment | BIL-native candidate |
| Evidence Sufficiency | Determines whether evidence supports the intended claim | BIL-native candidate |
| Integrity Evaluation | Evaluates a claim against reference/evidence/rules | BIL-native candidate |
| Integrity Decision | Records the resulting interpretation/status | BIL-native candidate |
| Evidence Conflict / Adjudication | Handles materially conflicting evidence or unresolved judgement | BIL-native candidate |
| Integrity Profile | Declares context-dependent integrity scope and policy | BIL profile/control candidate |

No candidate becomes canonical merely because this table exists.

## 6. External semantic ownership

BIL consumes but does not absorb existing GIOP semantic responsibilities.

| Domain | Primary owner | BIL role |
|---|---|---|
| Entity type | `classes/` | Integrity relevance target |
| Characteristic | `properties/` | Characteristic-level evidence/claim target |
| Contextual circumstance | `conditions/` | Context qualification |
| State | `states/` | State consistency target |
| Measurable concept | `quantities/` | Measurement/evidence source |
| Action/occurrence | `activities/` | Validation/evaluation activities |
| Transformation | `processes/` | Change source |
| Typed connection | `relations/` | Configuration/interaction evidence |
| Information-bearing form | `representations/` | Reference/evidence/output form |
| Time | `temporal/` | Temporal qualification |
| Output/result | `results/` | Evaluation output/result |
| Procedure | `workflows/` | Reusable validation/evaluation procedure |
| Computational method | `computational-methods/` | Evaluation/inference method |
| Implementation | `implementations/` | Operational realization |
| Provenance/evidence | Foundation + provenance controls | Trust and traceability input |

This preserves the current GIOP integration map and prevents BIL from becoming a parallel semantic authority.

## 7. BIL data model preparation

The implementation should separate five layers:

```text
REFERENCE
   ↓
CLAIM
   ↓
EVIDENCE
   ↓
EVALUATION
   ↓
DECISION
```

Each layer may be qualified by:

- subject/context scope;
- temporal scope;
- representation scope;
- transformation intent;
- observability;
- confidence/uncertainty;
- provenance;
- lifecycle state.

The design must not collapse these into a single `integrity_score`.

## 8. Integrity dimensions

A BIL profile may activate one or more dimensions:

- identity;
- structure/anatomy;
- state;
- appearance/material;
- interaction/contact;
- configuration/composition;
- physical consistency;
- optical consistency;
- temporal consistency;
- species/biological consistency;
- contextual/environmental consistency;
- cross-view / cross-representation consistency;
- provenance/trust support.

A profile does not need every dimension.

## 9. Invariance model

For every evaluated element or relationship, the implementation should classify the expected change behaviour as one of:

- invariant;
- conditionally invariant;
- permitted variation;
- declared transformation;
- unconstrained;
- unknown / unobservable.

This prevents the false rule that every visible difference is an integrity failure.

## 10. Evidence model

Evidence should retain its epistemic mode at minimum:

- directly observed;
- measured/derived;
- inferred;
- reconstructed;
- external reference;
- multimodal/cross-view;
- provenance evidence;
- expert adjudication.

Evidence status must remain separate from authority, confidence, lifecycle, and canonical identity.

## 11. Observability model

The implementation must distinguish:

`OBSERVED → PARTIAL → OCCLUDED → INFERRED → RECONSTRUCTED → AMBIGUOUS → UNAVAILABLE`

The absence of direct evidence must never automatically be classified as contradiction or failure.

## 12. Transformation model

BIL evaluations must declare the transformation context where relevant, for example:

- relighting;
- recoloring;
- crop/scale;
- pose/expression change;
- body/shape modification;
- object addition/removal/replacement;
- background/environment transformation;
- rendering/VFX;
- animation;
- image-to-video/video-to-video;
- 3D/4D reconstruction.

The same observed difference can therefore have different integrity interpretations under different declared transformation policies.

## 13. Profile model

BIL profiles are application/context profiles, not new semantic truths.

Candidate profiles include:

- human portrait;
- wildlife;
- sports;
- dance/performance;
- group/crowd;
- fashion;
- digital human;
- synthetic creature/VFX;
- scientific/medical imaging;
- macro/biological imaging;
- still image;
- video;
- 3D/4D.

Profiles may activate different evidence, invariance, transformation, and validation rules while referencing the same canonical BIL core.

## 14. Visitor Universe architecture

Visitor Universe is a routing/entry-depth system, not a parallel BIL knowledge base.

```text
BIL CANONICAL KNOWLEDGE
        ↓
VISITOR UNIVERSE
        ↓
ENTRY / DEPTH PROFILE
        ↓
HUMAN OR MACHINE CONSUMPTION
```

The same BIL identity, definition, evidence, provenance, lifecycle, and decisions must remain invariant across visitor depths.

The novice receives orientation and core distinctions. Practitioners receive profile and operational detail. Specialists receive evidence models, validation and limitations. Engineers/AI systems receive stable IDs, machine-readable relationships, profile parameters, evidence status and deterministic retrieval anchors.

No audience-specific BIL semantic duplicates are permitted.

## 15. Proposed canonical-source shape

When BIL authoring is authorized, substantive records should use UTF-8 Markdown with the shared GIOP identity envelope and profile-specific sections.

Expected identity envelope:

- ID;
- TITLE;
- ARTIFACT TYPE;
- PRIMARY RESPONSIBILITY;
- STATUS;
- VERSION;
- AUTHORITY;
- PROVENANCE;
- VALIDATION;
- RELATED IDS.

Profile-specific material then defines scope, reference model, evidence model, invariance/variation, evaluation, limitations, and retrieval anchors as applicable.

## 16. Data registry before canonical pages

The initial BIL dataset should be stored as a research/registry-oriented inventory until semantic status is resolved.

Minimum candidate fields:

`candidate_id`
`preferred_term`
`aliases`
`source_context`
`subject_scope`
`configuration_scope`
`proposed_responsibility`
`existing_giop_owner`
`bil_native_candidate`
`evidence_type`
`reference_requirement`
`invariance_type`
`transformation_sensitivity`
`observability`
`validation_modes`
`provenance`
`confidence`
`conflicts`
`status`
`destination`
`unresolved_questions`

This registry is a decision/retention layer, not a second canonical knowledge base.

## 17. Retrieval and machine-readiness

Every later canonical BIL entry must remain self-contained when retrieved outside its parent document. Stable identifiers, definition, primary responsibility, status, evidence, relations, and validation must remain locally interpretable.

Profile-specific parameters must be machine-readable without being mistaken for universal BIL semantics.

## 18. Formula and threshold control

Module-specific formulas, thresholds, constants, metric targets, and model parameters must remain profile/model records unless separately promoted.

No numerical tolerance becomes a universal BIL law merely because it appeared in an implementation prompt.

## 19. Implementation separation

BIL semantic records must not silently contain implementation authority for:

- OpenPose;
- 3DMM variants;
- BSSRDF models;
- Gabor/Hair models;
- cloth simulators;
- neural embedding models;
- VFX software;
- rendering engines;
- validation libraries.

Those belong to Computational Method, Implementation, Scientific Model, Workflow, or evidence/profile artifacts as appropriate.

## 20. Required validation before BIL promotion

The eventual BIL batch must pass, at minimum:

- Gate A — identity resolved;
- Gate B — responsibility assigned;
- Gate C — authoring structure compliant;
- Gate D — provenance recorded;
- Gate E — claims/models reviewed;
- Gate F — cross-references resolve;
- Gate G — duplicate-authority check;
- Gate H — lifecycle/supersession valid;
- Gate I — trust/integrity metadata ready;
- Gate J — explicit promotion approval.

Additional BIL stress tests must cover at least:

- human vs animal/wildlife;
- single vs group/crowd;
- still vs video;
- real vs synthetic creature;
- visible vs occluded subject;
- component integrity vs configuration integrity;
- identity preservation vs permitted transformation;
- biological fidelity vs physical plausibility;
- biological integrity vs provenance authenticity;
- evidence insufficiency vs failure;
- profile-specific threshold vs universal semantic rule.

## 21. Readiness decision

**READY FOR STRUCTURED BIL RESEARCH REGISTRY / ARCHITECTURE PILOT.**

**NOT READY FOR ACTIVE CANONICAL BIL SEMANTIC PROMOTION.**

The next implementation stage should therefore build the controlled BIL candidate registry and visitor-universe routing specification first, then perform candidate-level boundary validation before any BIL semantic pages are promoted.
