# GIOP V3.1 — Format System Validation Matrix

Status: PREPARATION ONLY  
Purpose: Validate the emerging GIOP content-formatting philosophy before the canonical design-principles document is finalized.

> The novice and the expert are not given different knowledge. They are given different entry depths into the same knowledge.

## 1. Role of this document

This document is a validation instrument, not a final formatting specification and not a substantive content authoring template.

It records:
- principles currently accepted for testing;
- artifact types that must stress-test those principles;
- boundaries and questions that remain open;
- implementation decisions that may change the principles;
- criteria for promoting a tested principle into the canonical design policy.

The document may be revised during implementation when a real artifact exposes a limitation, contradiction, ambiguity, or missing requirement.

## 2. Current working model

The current authoring model is:

```text
IDENTITY / METADATA
        ↓
5W1H ORIENTATION
        ↓
DOMAIN-SPECIFIC TECHNICAL DEPTH
        ↓
TRUST
        ↓
LIFECYCLE
        ↓
RELATIONS / RETRIEVAL
```

Cross-cutting controls:

```text
CONTROLLED VOCABULARY
CROSS-REFERENCES
RETRIEVAL ANCHORS
VERSIONING
ACCESSIBILITY
MACHINE-READABLE METADATA
```

The sequence is a working information architecture. It is not a requirement that every artifact expose identical headings or identical content depth.

## 3. Validation principles

### P1 — One canonical knowledge base

Different reader entry depths must not create different underlying truths.

Test question: Can beginner-oriented, professional, expert, and machine-oriented views refer to the same canonical identity, definitions, relations, and evidence?

### P2 — Human and machine layers coexist

Human-readable narrative and machine-readable identity metadata must reinforce one another rather than compete.

Test question: Can a machine identify the record reliably without making the human explanation unreadable?

### P3 — 5W1H is an orientation layer

5W1H should provide human orientation where useful, but it is not a rigid six-field form.

Test question: Does forcing a missing or irrelevant 5W1H field make an artifact less precise?

### P4 — Technical depth is profile-specific

Technical structure must adapt to the artifact rather than forcing every artifact into one generic technical template.

Test question: Does the same core model remain valid for a camera, formula, vocabulary term, workflow, and research claim without semantic distortion?

### P5 — Trust is explicit and differentiated

Provenance, evidence, validation, authority, confidence, and historical status must not be silently collapsed into one label.

Test question: Can a reader distinguish where information came from, what evidence supports it, whether it has been validated, and what authority level applies?

### P6 — Lifecycle is visible

A record must communicate its lifecycle state and relevant supersession/history without confusing historical preservation with active normative status.

Test question: Can a retrieved record be interpreted correctly without opening an unrelated history document?

### P7 — Retrieval survives context loss

A major section should remain semantically intelligible when retrieved outside its parent page.

Test question: Does a standalone retrieved chunk retain enough identity and local context to avoid ambiguity?

### P8 — Accessibility is structural

Logical heading hierarchy, descriptive headings, semantic Markdown, readable tables, and text-based labels must carry meaning without depending on presentation styling.

Test question: Does the artifact remain comprehensible in plain Markdown and assistive-technology-oriented navigation?

### P9 — Terminology is controlled

Preferred terms, aliases, synonyms, abbreviations, vendor terminology, and historical terms must remain distinguishable.

Test question: Can a reader understand ordinary language while automation still resolves canonical terminology deterministically?

### P10 — Repository placement is not semantic authority

Paths organize the repository; canonical identity, semantic definition, registry identity, and controlled relations establish authority.

Test question: Can a record survive repository reorganization without changing its identity or meaning?

## 4. Required stress-test artifacts

### Test A — Camera

Purpose: Validate the human-to-professional entry-depth model.

Must test:
- ordinary-language definition;
- identity envelope;
- capture-system classification;
- beginner-to-expert accessibility;
- technical parameters;
- operational/use context;
- lifecycle and validation;
- relationships to lens, sensor, exposure, image representation, and related concepts.

Critical question:
Can the record begin with the familiar concept of a camera without sacrificing the precision required by trainers, engineers, manufacturers, and researchers?

### Test B — Lens

Purpose: Validate an optical component/profile with technical equations and parameters.

Must test:
- human orientation;
- optical terminology;
- focal length, aperture, field of view, image formation, and related parameters where applicable;
- units and dimensions;
- equations;
- domain of validity;
- implementation notes;
- provenance and validation.

Critical question:
Can intuitive optical explanation and formal optical characterization coexist without duplicating or contradicting one another?

### Test C — Sensor

Purpose: Validate a hardware/measurement artifact whose meaning depends on measurable characteristics.

Must test:
- identity and classification;
- physical and electronic properties;
- measurement context;
- units/dimensions;
- noise/response terminology where applicable;
- characterization data;
- validation/evidence distinctions.

Critical question:
Does the format separate what the sensor is, what it measures, how it is characterized, and how trustworthy each claim is?

### Test D — Formula

Purpose: Validate mathematical content as a first-class knowledge artifact.

Must test:
- Formula ID and name;
- definition;
- equation;
- variables;
- units/dimensions;
- assumptions;
- domain of validity;
- boundary/edge conditions;
- numerical considerations;
- examples;
- implementation notes;
- validation/test references;
- provenance.

Critical question:
Can an equation remain mathematically canonical while explanations, examples, and implementations vary by audience?

### Test E — Vocabulary Term

Purpose: Validate the terminology layer as a shared language system rather than a substitute for semantics or registry.

Must test:
- preferred term;
- definition;
- scope;
- aliases/synonyms;
- abbreviations;
- vendor terms;
- historical terms;
- related terms;
- canonical identifier;
- provenance;
- lifecycle.

Critical question:
Can a term be understood by humans and resolved deterministically by machines without becoming a duplicate semantic authority layer?

## 5. Documentation-profile stress test

The same underlying knowledge should be capable of producing different documentation modes without changing canonical truth.

Minimum profiles to test:
- Reference;
- Tutorial;
- How-to;
- Explanation;
- Machine artifact.

For each profile, test:
1. What changes in presentation?
2. What must remain invariant?
3. What metadata remains mandatory?
4. Which sections become optional or profile-specific?
5. How are relations, provenance, and lifecycle preserved?

## 6. Boundary tests

The following questions remain intentionally open until implementation evidence exists.

### 6.1 Mandatory versus conditional sections

Which fields are universally required, and which are required only for particular artifact classes?

### 6.2 5W1H terminology

Should the visible headings literally be `What`, `Why`, `How`, `Where`, `Who`, and related labels in every applicable artifact, or should profile-specific equivalents be permitted while preserving the underlying orientation model?

### 6.3 Trust vocabulary

Which trust dimensions must be first-class fields in the Core Envelope, and which belong only to specialized profiles?

Candidate dimensions currently under consideration:
- provenance;
- evidence;
- validation;
- authority;
- confidence;
- historical status.

### 6.4 Audience vocabulary

Whether audience/reader depth should be encoded as a controlled field, expressed through documentation profiles, or both.

### 6.5 Content type versus documentation mode

The artifact's semantic/content identity should remain distinct from the way that artifact is documented.

Example:
`Camera` may be a content type while `Reference` is a documentation mode.

### 6.6 Retrieval granularity

The minimum self-contained retrieval unit remains to be established through real-world testing.

## 7. Decision protocol during implementation

When an actual artifact reveals a problem:

```text
OBSERVATION
    ↓
PROBLEM STATEMENT
    ↓
ALTERNATIVES
    ↓
IMPLEMENTATION DECISION
    ↓
VALIDATION AGAINST OTHER ARTIFACTS
    ↓
POLICY UPDATE, IF NEEDED
```

No implementation convenience may silently override a canonical principle.

Conversely, a principle that repeatedly fails under valid artifact requirements must be reconsidered rather than defended merely because it was written earlier.

## 8. Promotion criteria

A principle should be promoted into the canonical design-principles document only when:

- its meaning is unambiguous;
- it survives the relevant artifact stress tests;
- it does not conflict with canonical semantics, registry identity, terminology, provenance, or lifecycle requirements;
- it remains useful across multiple documentation profiles where intended;
- exceptions can be described without destroying the general rule;
- its implementation consequences are understood.

## 9. Current status ledger

| Principle / Question | Status | Evidence Needed |
|---|---|---|
| One canonical knowledge model | ACCEPTED FOR TESTING | Multi-artifact confirmation |
| Different entry depths, same knowledge | ACCEPTED FOR TESTING | Camera + cross-profile testing |
| Identity/Metadata as identity layer | ACCEPTED FOR TESTING | All pilot artifacts |
| 5W1H as orientation, not rigid form | ACCEPTED FOR TESTING | Camera + Formula + Vocabulary |
| Domain-specific technical depth | ACCEPTED FOR TESTING | Multi-artifact comparison |
| Trust as differentiated dimensions | OPEN FOR VALIDATION | Formula + Sensor + Claim testing |
| Lifecycle visibility | ACCEPTED FOR TESTING | Supersession/legacy scenarios |
| Retrieval self-containment | ACCEPTED FOR TESTING | Isolated chunk tests |
| Controlled terminology layer | ACCEPTED FOR TESTING | Vocabulary Term test |
| Content type ≠ documentation mode | ACCEPTED FOR TESTING | Profile stress test |
| Mandatory/conditional field boundary | OPEN | Pilot implementation |
| Audience encoding strategy | OPEN | Pilot implementation |
| Minimum retrieval unit | OPEN | Retrieval tests |

## 10. Relationship to existing V3.1 preparation documents

This matrix does not replace the existing authoring-readiness or formatting/authoring specifications.

The readiness specification establishes prerequisites and validation gates. The formatting/authoring specification establishes the current preparation draft. This matrix exists to test whether those principles hold under real artifact conditions before a canonical core design policy is finalized.

Until validation is complete, this document remains PREPARATION ONLY.
