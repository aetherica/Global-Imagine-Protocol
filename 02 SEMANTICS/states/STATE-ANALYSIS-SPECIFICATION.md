# GIOP V3.1 — State Analysis Specification

## Status

**CANONICAL — V3.1 STATE ORGANIZATION SPECIFICATION**

## Purpose

This specification defines how GIOP identifies, classifies, validates, and routes State-related knowledge without turning the `states/` directory into a general repository for condition-like terminology.

## Governing Principle

State analysis is responsibility-driven. A term is not a State merely because its wording contains `state`, `mode`, `condition`, or `status`.

```text
CANDIDATE KNOWLEDGE
        ↓
IDENTIFY BEARER
        ↓
IDENTIFY RECOGNIZED MODE / CONDITION
        ↓
IDENTIFY TEMPORAL LOCUS
        ↓
CLASSIFY PRIMARY RESPONSIBILITY
        ↓
CHECK NEIGHBORING LAYERS
        ↓
VERIFY / RECONCILE EVIDENCE
        ↓
GIOP DECISION
        ↓
CANONICAL / CANDIDATE / STRUCTURAL / ROUTED
```

## 1. State Analysis Questions

For every candidate, determine:

1. What bearer has or occupies the proposed State?
2. What recognized mode or condition distinguishes it?
3. At what point or interval in time does the State apply?
4. Is the candidate describing current mode/condition rather than potential capability?
5. Is the candidate a measurable quantity or value instead?
6. Is it an administrative, lifecycle, validation, or governance standing instead?
7. Is it an action, transformation, event, or transition instead?
8. Is a configuration or contextual frame being mistaken for a State?
9. Is the proposed State directly observed, measurement-derived, inferred, or declared?
10. Does the same semantic responsibility remain stable across relevant domains?

## 2. Canonical State Test

A candidate satisfies the core State test when all of the following are materially supported:

- an eligible semantic bearer can be identified;
- the candidate denotes a recognizable mode or condition of that bearer;
- the candidate is meaningfully qualified by time or temporal interval;
- its primary responsibility is State rather than a neighboring semantic layer;
- the candidate is reusable beyond a single implementation field or vendor label;
- evidence and GIOP synthesis support the interpretation.

Failure does not make the term false. It means that the term must be routed, deferred, retained, or classified under another semantic responsibility.

## 3. State Concept vs State Assertion

A State concept defines what a recognized State means.

A State assertion says that a particular bearer is in that State at a particular temporal locus.

```text
STATE CONCEPT
→ Ready

STATE ASSERTION
→ Camera-01 is Ready at t₁
```

State Assertion is retained as a structural pattern, not a separate V3.1 semantic nucleus.

## 4. Direct, Derived, Inferred, and Reported State

A State may be established by different routes:

### Direct observation

The State is explicitly observed by an eligible observer or system.

### Measurement-derived

Measured quantities provide evidence from which a State is classified.

### Inferred

A rule, model, algorithm, or reasoning process derives the State from evidence.

### Declared / reported

An authorized system or source declares the current State.

The establishment route is evidence/provenance metadata. It does not redefine the State concept.

## 5. Candidate Decision Matrix

| Question | State | Condition | Property | Status | Quantity / Value | Activity | Process | Event | Disposition | Configuration |
|---|---|---|---|---|---|---|---|---|---|---|
| What is central? | Bearer mode/condition | Applicable circumstance | Attributable characteristic | Assigned/reporting standing | Measurable kind/value | Action | Transformation/progression | Occurrence/change boundary | Capability/potential | Arrangement/settings |
| Time-sensitive? | Typically yes | Often yes | Not inherently | Often lifecycle-qualified | Value-dependent | May be | Yes | Point/interval event | Not necessarily | Configuration-dependent |
| Bearer-centered? | Yes | Not necessarily | Bearer-centered | Usually | Quantity-system dependent | Agent/action dependent | Process participant dependent | Event participant dependent | Bearer-centered | System/structure centered |

## 6. State vs Condition

Do not create a State merely because an expression is condition-like. Determine whether the primary meaning is a circumstance applying to a situation or the recognized mode occupied by a bearer.

Examples:

- low illumination → Condition;
- high ambient temperature → Condition;
- camera in standby → State candidate;
- sensor active → State candidate.

## 7. State vs Property

Property denotes an attributable characteristic. A property may be observed while a bearer is in a State, but the property itself is not automatically a State.

Example:

- spectral response → Property;
- linearity → Property;
- camera ready → State candidate.

## 8. State vs Status

Administrative, validation, governance, lifecycle, or externally assigned standing should not be admitted as State without independent semantic evidence.

Examples requiring caution:

- calibrated;
- validated;
- approved;
- current;
- expired.

These terms remain deferred pending Status-layer analysis where appropriate.

## 9. State vs Quantity / Value

A measured quantity or value is not a State.

```text
Sensor temperature = 85 °C
→ Quantity / Value semantics

Sensor = overheated
→ possible State assertion
```

A State may be derived from quantities, but derivation does not collapse the semantic layers.

## 10. State vs Activity / Process

The wording of a verb does not determine semantic type.

```text
capture image
→ Activity candidate

image acquisition process
→ Process

camera = recording
→ possible State
```

Each candidate requires responsibility analysis.

## 11. State vs Event / Transition

An Event is an occurrence or change boundary. A Transition changes the State within a state model.

```text
Ready
  ↓ transition
Running
```

Neither Event nor Transition is a State definition.

## 12. State vs Disposition

Disposition concerns capability, tendency, or potential realization.

A bearer can have a disposition to overheat without currently being in an overheated State.

```text
Disposition → potential
State       → recognized current mode/condition
Process     → realization/unfolding
```

## 13. State vs Configuration

Configuration describes arrangement, selected settings, component composition, or configured structure.

A configured system may be in a State, but `Configured` is not automatically canonical State.

## 14. State vs Context

Context defines the situational frame in which a State assertion is interpreted. Context is not replaced by State and State does not contain Context semantics.

## 15. State vs Mode

Mode and State overlap in engineering literature. GIOP does not assume a universal hierarchy between them.

`Mode` remains a deferred candidate pending independent semantic analysis.

## 16. Multiple States and Concurrency

GIOP does not impose a universal rule that a bearer must have exactly one State.

A particular system may define exclusive states, parallel state dimensions, substates, or nested State machines. Such constraints belong to the relevant state model.

Example:

```text
Camera
├── Power State: On
├── Recording State: Recording
└── Network State: Connected
```

This is a model example, not a universal GIOP requirement.

## 17. State Hierarchy and Substates

A State hierarchy is model-specific. Broader/narrower organization must not be mistaken for universal State ontology.

`Substate` is therefore a structural construct rather than a first-wave canonical semantic entry.

## 18. State Value

Applied vocabularies such as SAREF distinguish a reusable State concept from possible qualitative State values. GIOP retains this distinction as a structural interoperability pattern.

No independent V3.1 `State Value` semantic page is required yet. Coordination with future value, quantity, temporal, and representation semantics remains necessary.

## 19. State Machine

A State Machine may specify possible states, transitions, substates, and current-state behavior. This is a model of State organization, not the State semantic itself.

No V3.1 State Machine ontology is introduced by this folder.

## 20. Candidate Admission Criteria

A candidate should not be promoted merely because:

- a standard exposes it;
- an API returns it;
- a device UI displays it;
- a vendor uses it;
- the term is common in engineering;
- the term can be represented as a boolean or enumeration.

Promotion requires a distinct reusable semantic responsibility, evidence, boundary analysis, stable identity, and validation.

## 21. Candidate Rejection / Routing Criteria

Route or defer a term when:

- its primary meaning is a Condition;
- it denotes an attributable Property;
- it is a Quantity or Value;
- it denotes an Activity or Process;
- it denotes an Event or Transition;
- it expresses a Disposition or Capability;
- it is an administrative or lifecycle Status;
- it is merely a Configuration label;
- its semantic responsibility is unresolved;
- the term is only implementation-specific.

## 22. Evidence and Conflict Handling

When sources disagree, preserve the competing interpretations in the State knowledge registry. Do not average incompatible meanings into a synthetic term.

External terminology is evidence for use. GIOP canonical meaning results from semantic synthesis and explicit canonical decision.

## 23. Canonical Decision States

Use the Foundation disposition categories:

- CANONICAL;
- CANONICAL CANDIDATE;
- STRUCTURAL / METHODOLOGICAL;
- ROUTED TO ANOTHER SEMANTIC LAYER;
- DEFERRED;
- UNVERIFIED;
- CONFLICTED;
- HISTORICAL / PRESERVED.

## 24. Machine Interpretation

Machine consumers should be able to recover:

- State concept ID;
- preferred name;
- definition;
- bearer scope;
- temporal scope;
- assertion pattern;
- candidate/canonical status;
- structural relationships;
- evidence/provenance;
- validation state.

Machine systems must not infer State type solely from folder placement or lexical label.

## 25. Visitor-Depth Interpretation

The same State semantic knowledge supports different entry depths:

```text
GENERAL
→ What is a State?

LEARNING
→ State vs Condition / Property / Status

PRACTICE
→ Operational examples and model implications

ENGINEERING / RESEARCH
→ Temporal qualification, evidence, inference, concurrency, boundaries

MACHINE / AI
→ Stable IDs, assertion structure, qualification, provenance, validation
```

These are consumption depths, not different State definitions.

## 26. V3.1 Boundary Decision

V3.1 canonicalizes `State` as the State semantic nucleus.

State Assertion, State Value, State of Interest, State Machine, Transition, State Variable, State History, State Hierarchy, Substate, and Mode remain structural/deferred pending evidence for distinct GIOP responsibility.

Common state vocabulary remains candidate knowledge until term-by-term responsibility analysis is complete.
