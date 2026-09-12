# GIOP V3.1 — BIL Visitor Universe Implementation Specification

**Status:** PREPARATION ONLY — ARCHITECTURE PILOT
**Branch:** `v3.1-tree-architecture`
**Scope:** Visitor Universe routing and entry-depth control for the future BIL canonical knowledge base.

## 1. Governing principle

```text
ONE BIL CANONICAL KNOWLEDGE BASE
        ↓
VISITOR UNIVERSE
        ↓
ENTRY DEPTH / NAVIGATION PATH
        ↓
HUMAN OR MACHINE CONSUMPTION
```

Visitor Universe does not create alternate BIL truths, alternate definitions, audience-specific identifiers, or duplicated semantic entries.

The novice and the expert are not given different knowledge. They are given different entry depths into the same knowledge.

## 2. What changes by visitor

Visitor routing may change:

- orientation length;
- terminology density;
- example selection;
- technical depth;
- evidence detail;
- validation detail;
- profile visibility;
- dependency traversal;
- retrieval granularity;
- machine-readable projection depth.

Visitor routing must not change:

- semantic identity;
- canonical definition;
- primary responsibility;
- evidence identity;
- provenance history;
- lifecycle status;
- canonical relation semantics;
- validation result;
- canonical decision.

## 3. BIL entry-depth model

### Depth 0 — Orientation

For general visitors.

Expose:

- what BIL addresses;
- why it exists;
- what kinds of integrity questions it answers;
- one or two intuitive examples;
- basic boundary: BIL is not a second semantic ontology for all biological content.

### Depth 1 — Conceptual

For learners and creative practitioners.

Add:

- reference;
- claim;
- invariant/variation;
- evidence;
- evaluation;
- decision;
- profile/context dependence;
- examples for human, wildlife, sports, dance, VFX, and object interaction.

### Depth 2 — Applied / Professional

For practitioners and domain specialists.

Add:

- selected BIL profile;
- evidence requirements;
- observability limitations;
- permitted transformation rules;
- applicable validation dimensions;
- representative examples and failure modes;
- cross-layer GIOP dependencies.

### Depth 3 — Technical / Engineering

For imaging scientists, engineers, ML engineers, technical directors, and system designers.

Add:

- evidence models;
- quantitative measures;
- model assumptions;
- uncertainty;
- threshold/profile parameters;
- cross-view/temporal/physical consistency;
- workflow and computational dependencies;
- machine-readable relation graph;
- validation/test vectors.

### Depth 4 — Formal / Machine

For AI/API/data/system consumers.

Expose deterministic structures:

- BIL ID;
- artifact type;
- profile ID;
- claim ID;
- reference ID;
- evidence ID;
- evaluation ID;
- decision ID;
- subject/configuration scope;
- observability state;
- invariance class;
- permitted transformation class;
- provenance;
- lifecycle;
- related canonical IDs;
- machine validation status.

## 4. Visitor routing dimensions

Visitor routing should be multi-dimensional rather than a fixed audience hierarchy.

Primary dimensions:

`TASK`
`EXPERTISE`
`CONTENT PROFILE`
`EVIDENCE DEPTH`
`TECHNICAL DEPTH`
`MACHINE/HUMAN MODE`
`RETRIEVAL INTENT`

Examples:

A beginner asking “What is BIL?” should receive Depth 0–1.

A wildlife photographer evaluating an animal reference should enter a Wildlife profile at Depth 1–2.

A VFX supervisor examining a digital creature should enter the Synthetic Creature/VFX profile at Depth 2–3.

A validation engineer should enter at Depth 3–4 with evidence and test specifications.

An AI retrieval agent should receive self-contained canonical identity, profile, evidence, validation and relationship structures without being forced through human narrative order.

## 5. Profile routing

Profiles are navigation/context specifications, not duplicate semantic ontologies.

Candidate profile identifiers:

- `BIL-PROFILE-HUMAN`
- `BIL-PROFILE-WILDLIFE`
- `BIL-PROFILE-SPORTS`
- `BIL-PROFILE-DANCE`
- `BIL-PROFILE-GROUP`
- `BIL-PROFILE-FASHION`
- `BIL-PROFILE-VFX`
- `BIL-PROFILE-DIGITAL-HUMAN`
- `BIL-PROFILE-SYNTHETIC-CREATURE`
- `BIL-PROFILE-SCIENTIFIC`
- `BIL-PROFILE-MEDICAL`
- `BIL-PROFILE-STILL`
- `BIL-PROFILE-VIDEO`
- `BIL-PROFILE-3D4D`

These identifiers are preparation candidates only.

A profile may activate different dimensions of the same BIL core.

## 6. Profile-specific depth without semantic duplication

Example:

```text
CANONICAL CONCEPT:
Integrity Reference

HUMAN PORTRAIT ENTRY:
face identity + asymmetry + anatomy reference

WILDLIFE ENTRY:
species + individual markings + pose-aware reference

SPORTS ENTRY:
athlete identity + action configuration + equipment interaction

DANCE ENTRY:
member identity + group formation + coordinated motion

VFX ENTRY:
declared synthetic morphology + transformation intent + temporal continuity
```

The underlying BIL concept remains one.

## 7. Retrieval model

A retrieval system should be able to enter BIL through:

- concept;
- subject;
- profile;
- integrity dimension;
- evidence type;
- transformation type;
- failure mode;
- validation method;
- relation;
- provenance.

Retrieval results must return canonical identity and enough local context to prevent semantic ambiguity.

## 8. Projection model

The canonical BIL record is the source. Visitor projections are derived views.

```text
CANONICAL RECORD
   ├── GENERAL ORIENTATION PROJECTION
   ├── PRACTITIONER PROJECTION
   ├── EXPERT PROJECTION
   ├── ENGINEERING PROJECTION
   └── MACHINE / API PROJECTION
```

A projection may omit information for relevance, but must not rewrite canonical meaning.

## 9. Visitor-state metadata

Visitor state should be treated as navigation metadata rather than semantic content.

Possible runtime values:

`entry_depth`
`task`
`profile`
`expertise_band`
`retrieval_intent`
`machine_mode`

These values must not alter semantic IDs or canonical definitions.

## 10. Example navigation paths

### Beginner

`BIL → What is integrity? → Simple example → Human/Wildlife contrast → Core boundaries`

### Photographer

`BIL → Profile: Wildlife → Reference → Integrity dimensions → Observability → Validation examples`

### Sports/VFX practitioner

`BIL → Profile: Sports/VFX → Configuration → Interaction → Permitted transformation → Failure modes`

### Imaging engineer

`BIL → Integrity Reference → Evidence model → Invariance model → Validation → Uncertainty → Workflow/Method dependencies`

### AI / machine

`BIL ID → Profile ID → Claim → Reference → Evidence → Evaluation → Decision → Provenance → Related IDs`

## 11. Machine retrieval rule

No machine projection should depend on a preceding paragraph for semantic identity.

The retrieved object must expose, at minimum:

`ID`
`TITLE`
`TYPE`
`STATUS`
`VERSION`
`PRIMARY RESPONSIBILITY`
`DEFINITION`
`PROFILE SCOPE`
`EVIDENCE`
`VALIDATION`
`PROVENANCE`
`RELATED IDS`

## 12. Accessibility rule

Visitor depth must not be implemented only through color, hidden UI states, or styling. Semantic headings, explicit labels, stable anchors, and readable Markdown/structured data must carry the meaning.

## 13. Governance rule

Visitor projections are not allowed to become parallel sources of truth.

If a projection exposes an apparent contradiction, the canonical record is re-evaluated and the projection corrected. Do not create a visitor-specific semantic exception merely to preserve a projection.

## 14. Implementation validation

Before BIL Visitor Universe is promoted into canonical repository policy, test at least:

- one concept across Depth 0–4;
- one human profile;
- one wildlife profile;
- one sports profile;
- one dance/group profile;
- one VFX/synthetic profile;
- one still-image path;
- one video path;
- one machine retrieval path;
- one isolated chunk retrieval path;
- one ambiguous/uncertain evidence case;
- one permitted-transformation case;
- one contradiction/provenance conflict case.

Pass condition:

Different routes produce different entry depth and navigation, but the same canonical semantic identity, evidence status, provenance, lifecycle, and decision.

## 15. Current status

**Visitor Universe architecture is READY FOR PILOT IMPLEMENTATION DESIGN.**

It is not yet a canonical audience taxonomy and does not authorize audience-specific semantic pages.
