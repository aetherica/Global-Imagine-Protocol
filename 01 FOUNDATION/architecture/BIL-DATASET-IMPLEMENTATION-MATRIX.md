# GIOP V3.1 — BIL Dataset Implementation Matrix

**Status:** PREPARATION ONLY — RESEARCH / REGISTRY DESIGN
**Branch:** `v3.1-tree-architecture`
**Scope:** Controlled schema for implementing the discovered BIL topic universe without prematurely canonizing every topic.

## 1. Purpose

The BIL investigation produced a very large topic universe spanning biological subjects, animals, wildlife, sports, dance, groups, clothing, fabric, phone/bag/props, water, surfaces, optics, interaction, temporal continuity, transformation, evidence, validation, uncertainty, threats, and provenance.

This matrix defines how that heterogeneous material is stored, classified, routed, and later promoted.

The implementation rule is:

> **Store first as structured candidate knowledge; assign canonical semantic ownership only after boundary and duplicate-authority analysis.**

## 2. Candidate record schema

Every material BIL candidate should be representable with these fields:

| Field | Purpose |
|---|---|
| `candidate_id` | Stable research/registry identifier |
| `preferred_term` | Current preferred human-facing label |
| `aliases` | Search and terminology variants |
| `artifact_class` | Semantic definition, research evidence, scientific model, profile, workflow, validation record, etc. |
| `subject_scope` | Human, animal, plant, synthetic biological, multi-organism, etc. |
| `configuration_scope` | Individual, pair, group, subject-object, environment, sequence, etc. |
| `context_profile` | Portrait, wildlife, sports, dance, VFX, scientific, video, etc. |
| `integrity_dimension` | Identity, structure, state, interaction, appearance, temporal, physical, contextual, etc. |
| `candidate_responsibility` | What the item is trying to mean/do |
| `existing_giop_owner` | Class / Property / Condition / State / Quantity / Activity / Process / Relation / Representation / Temporal / Result / Workflow / Method / Implementation / Foundation |
| `bil_native_candidate` | Whether a distinct BIL responsibility is suspected |
| `reference_requirement` | None / partial / exact / multi-view / sequence / external reference |
| `evidence_type` | Observed / measured / inferred / reconstructed / multimodal / provenance / expert |
| `observability` | Observed / partial / occluded / inferred / reconstructed / ambiguous / unavailable |
| `invariance_class` | Invariant / conditional / permitted variation / declared transformation / unconstrained / unknown |
| `transformation_sensitivity` | What transformations can alter interpretation |
| `validation_mode` | Geometry / photometric / optical / temporal / physical / relational / semantic / human review |
| `provenance` | Source and evidence lineage |
| `confidence` | Review confidence or uncertainty |
| `conflicts` | Competing evidence/definitions |
| `status` | Research / candidate / routed / deferred / conflicted / validated / etc. |
| `destination` | Intended canonical destination if resolved |
| `related_ids` | Canonical or candidate dependencies |
| `unresolved_questions` | Known open issues |
| `change_history` | Material research/decision history |

## 3. Artifact class routing

The discovered material must first be assigned an artifact class.

### Semantic definition
Used when the primary responsibility is defining reusable meaning.

### Scientific model
Used for biological, optical, physical, anatomical, material, or mathematical models.

### Research evidence / claim
Used for externally sourced empirical findings or claims not yet synthesized into canonical semantics.

### Profile
Used for context-specific policy, scope, or parameterization such as Wildlife, Sports, Dance, VFX, or Digital Human.

### Validation record
Used for test methods, metrics, tolerances, comparison protocols, and evaluation evidence.

### Workflow / Procedure
Used for reusable operational evaluation sequences.

### Computational method / AI model / implementation
Used for algorithms, model families, software, libraries, or engine-specific realizations.

### Trust / provenance record
Used for source history, content binding, audit, or provenance evidence.

These artifact classes follow the Foundation authoring readiness model and must not be merged merely because they occur in the same BIL pipeline.

## 4. Subject taxonomy is not semantic ownership

Subject labels such as Human, Animal, Wildlife, Bird, Mammal, Plant, Phone, Bag, Fabric, Water, Surface, Vehicle, Camera, or Environment are classification/routing metadata unless independent semantic analysis establishes another GIOP responsibility.

They must not automatically generate BIL semantic pages.

## 5. Context taxonomy

Candidate context/profile values include:

- Portrait
- Fashion
- Sports
- Dance
- Performance
- Wildlife
- Nature
- Documentary
- Scientific
- Medical
- Macro
- Group/Crowd
- VFX
- Virtual Production
- Digital Human
- Synthetic Creature
- Fantasy
- Sci-Fi
- Horror
- Historical/Retro
- Commercial
- Still
- Video
- 3D/4D

Profiles change relevance, evidence requirements, and permitted variation. They do not create alternate canonical meanings.

## 6. Integrity-dimension taxonomy

Current research dimensions:

- Identity
- Structure/Anatomy
- Anthropometric/Morphometric
- State
- Behavior/Action
- Motion
- Group/Collective
- Appearance/Material
- Interaction/Contact
- Configuration/Composition
- Optical
- Spatial
- Physical
- Temporal
- Species/Biological
- Contextual/Environmental
- Cross-view
- Cross-representation
- Provenance/Trust

These are integrity evaluation dimensions, not automatically semantic classes.

## 7. Evidence taxonomy

Evidence should be stored with its epistemic mode:

```text
DIRECT OBSERVATION
MEASUREMENT / DERIVATION
GEOMETRIC INFERENCE
PHYSICAL INFERENCE
SEMANTIC CLASSIFICATION
TEMPORAL CORRESPONDENCE
MULTI-VIEW CORRESPONDENCE
MULTIMODAL EVIDENCE
EXTERNAL REFERENCE
PROVENANCE EVIDENCE
EXPERT ADJUDICATION
```

Evidence source, authority, validation state, confidence, and historical status remain separate fields.

## 8. Reference taxonomy

The implementation must distinguish:

`source image/frame`
`sample`
`feature`
`template`
`model`
`reference configuration`
`identity binding`
`profile reference`
`validation reference`

A single source may support one claim but be insufficient for another. Reference sufficiency must therefore be evaluated per claim.

## 9. Claim-centric implementation

The preferred implementation unit is:

```text
CLAIM
  ↓
REFERENCE REQUIREMENT
  ↓
EVIDENCE SET
  ↓
INVARIANCE / PERMITTED VARIATION
  ↓
EVALUATION PROCEDURE
  ↓
DECISION
```

This prevents a generic `integrity score` from hiding which claim failed or which evidence was missing.

## 10. Example candidate rows

| Candidate | Primary owner | BIL role |
|---|---|---|
| Face identity | Domain/identity semantics | Integrity claim target |
| Skin scattering | Property/scientific model | Appearance evidence |
| Phone | Class/Object | Interaction component |
| Hand-phone grasp | Relation/Activity + BIL | Configuration integrity |
| Water | Material/Condition | Environmental interaction evidence |
| Wet fur | State/Property/Material context | Biological appearance integrity |
| Dance formation | Relation/State/Activity + BIL | Collective configuration integrity |
| Wildlife stripe pattern | Biological feature/evidence | Individual/species integrity |
| Morphing | Security/attack research | Integrity threat context |
| CIEDE2000 | Measurement/validation method | Validation instrument |
| 3DMM | Scientific/computational method | Evidence/reconstruction method |
| C2PA provenance | Trust/provenance | Supporting provenance evidence |

These rows illustrate routing only. They are not canonical decisions for every future instance.

## 11. Candidate decision states

Until Gate-J approval, candidate material may use:

`RESEARCH`
`CANONICAL CANDIDATE`
`ROUTED`
`DEFERRED`
`UNVERIFIED`
`CONFLICTED`
`PRESERVED HISTORICAL`
`VALIDATED PILOT`

A written page is not itself a promotion.

## 12. Deduplication rules

Before creating a BIL-native candidate:

1. Search for an existing canonical GIOP identity.
2. Search for an existing candidate with the same responsibility.
3. Check whether the term is only a context/profile label.
4. Check whether the term is merely an implementation method.
5. Check whether the term is a validation metric rather than a semantic concept.
6. Check whether the term belongs to provenance/security rather than biological integrity.
7. Preserve aliases and historical terms without creating duplicate semantic authority.

## 13. Visitor Universe routing fields

The dataset may carry navigation metadata:

`entry_depth`
`task`
`profile`
`expertise_band`
`retrieval_intent`
`machine_mode`

These are derived routing fields. They must never change the canonical semantic identity.

## 14. Retrieval projections

The same underlying dataset should support:

- orientation retrieval;
- concept retrieval;
- profile retrieval;
- evidence retrieval;
- validation retrieval;
- failure-mode retrieval;
- engineering retrieval;
- machine/API retrieval.

Every projected result must retain `candidate_id` or canonical ID and status so that routing cannot sever provenance or lifecycle.

## 15. Security and trust separation

The implementation must preserve the distinctions:

`biological integrity`
`identity authenticity`
`provenance authenticity`
`cryptographic integrity`
`model confidence`
`validation status`

They may be related, but they must not be represented as interchangeable scores or labels.

## 16. Threshold and formula storage

Numerical thresholds, model parameters, equations, constants, tolerances, and test vectors must be attached to the relevant profile, scientific model, validation method, or implementation artifact.

They must not become universal BIL semantic definitions unless separately validated and promoted.

## 17. Implementation phases

### Phase A — Candidate registry

Capture the complete discovered topic universe without canonical promotion.

### Phase B — Ownership mapping

Assign every candidate to existing GIOP semantic ownership or mark it BIL-native candidate.

### Phase C — Boundary stress tests

Test candidate boundaries across human, wildlife, sports, dance, group, VFX, still, video, 3D/4D, occlusion, interaction, and transformation cases.

### Phase D — BIL-native synthesis

Synthesize only candidates whose responsibility remains distinct after cross-layer analysis.

### Phase E — Profile construction

Build context-specific integrity profiles from the canonical BIL core.

### Phase F — Validation and Gate-J

Run full Foundation gates and scoped promotion approval.

## 18. Completion criteria for the preparation stage

Preparation is complete when:

- the discovered topic space has a stable candidate schema;
- every candidate has an ownership/routing status;
- Visitor Universe fields are defined as projections, not alternate semantics;
- reference/evidence/claim/decision boundaries are explicit;
- implementation methods are separated from semantic definitions;
- formula/threshold controls are separated from universal semantics;
- unresolved conflicts remain visible;
- a deterministic path to Gate-J promotion exists.

## 19. Current status

**PREPARATION STRUCTURE READY.**

The dataset is ready to be populated as controlled BIL research/registry material. It is not yet a canonical BIL semantic corpus.
