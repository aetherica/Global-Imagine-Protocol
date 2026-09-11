# GIOP V3.1 — State Semantic Boundary Rule

## Status

**CANONICAL — V3.1 STATE CROSS-LAYER BOUNDARY RULE**

## Governing Rule

> **A candidate belongs to the State semantic layer only when its primary GIOP responsibility is to denote a recognized mode or condition occupied by an eligible bearer at a defined temporal locus.**

Surface wording does not determine semantic ownership.

## 1. State vs Condition

- Condition describes an applicable circumstance, setting, or contextual condition.
- State describes a recognized bearer-centered mode or condition.

Examples:

- low illumination → Condition;
- high ambient temperature → Condition;
- camera in Standby → State candidate;
- sensor Active → State candidate.

## 2. State vs Property

- Property describes an attributable characteristic.
- State describes a recognized temporal mode or condition.

Examples:

- spectral response → Property;
- linearity → Property;
- camera Ready → State candidate.

## 3. State vs Status

Administrative, lifecycle, governance, validation, or reported standing is not automatically State.

Examples requiring separate analysis:

- calibrated;
- validated;
- approved;
- current;
- expired.

These are deferred until Status-related semantic responsibility is established.

## 4. State vs Quantity / Value

A numeric or otherwise measurable value is not a State.

```text
85 °C → quantity/value
Overheated → possible State
```

A State may be derived from values, but the derivation must not erase the distinction between Value and State.

## 5. State vs Activity

Activity denotes an action performed. A State may characterize the mode in which an action occurs.

```text
capture image → Activity
camera = Recording → possible State
```

## 6. State vs Process

Process denotes transformation or progression. State denotes the recognized mode/condition during which a process may occur.

## 7. State vs Event

Event denotes an occurrence or change boundary. State may persist through an interval.

An event may establish, end, or change a State without becoming the State itself.

## 8. State vs Transition

Transition is a directed change from one State to another within a state model.

```text
Ready → Running
```

The transition is not itself a State.

## 9. State vs Disposition

Disposition denotes capability, tendency, or potential realization. State denotes the recognized current mode/condition.

```text
has disposition to overheat → Disposition
is overheated → possible State
```

## 10. State vs Configuration

Configuration describes arrangement, settings, selected composition, or configuration structure. A configuration can support or produce a State, but `Configured` is not automatically a State.

## 11. State vs Context

Context defines the situational frame in which a State assertion is interpreted. State does not replace Context semantics.

## 12. State vs Relation

A State is not a typed connection. Any bearer-to-State assertion or temporal qualification requiring a Relation must use Relation semantics independently.

## 13. State vs Mode

Mode and State overlap in systems engineering and applied models. GIOP V3.1 does not impose a universal State/Mode hierarchy. Mode remains deferred.

## 14. State vs State Value

State Value may be used by an application-level state model to enumerate possible qualitative values. It is not automatically an independent GIOP State semantic entry.

## 15. State vs State Machine

A State Machine is a model structure organizing states, transitions, current state and optional substates. It is not the semantic definition of State.

## 16. State vs State Assertion

A State concept defines meaning. A State Assertion applies that meaning to a particular bearer at a temporal locus.

```text
State concept: Ready
State assertion: Camera-01 is Ready at t₁
```

## 17. Multiple State Dimensions

GIOP does not require a bearer to have only one State. A model may define multiple independent or concurrent State dimensions.

```text
Camera
├── Power State: On
├── Recording State: Recording
└── Network State: Connected
```

These are illustrative model dimensions, not a universal ontology hierarchy.

## 18. State Exclusivity

Mutual exclusivity is model-specific. A state machine may specify exclusive alternatives, parallel state regions, nested states, or substates.

The generic State concept does not require exclusivity.

## 19. State Hierarchy

A broader/narrower State hierarchy is organizational/model-specific. It must not be treated as universal semantic inheritance.

## 20. Admission Test

Before canonical promotion, answer all applicable questions:

1. What is the bearer?
2. What recognized mode/condition is represented?
3. What is the temporal locus?
4. Is the term bearer-centered?
5. Is it primarily State rather than Condition?
6. Is it primarily State rather than Property?
7. Is it primarily State rather than Status?
8. Is it not a Quantity/Value?
9. Is it not an Activity/Process/Event?
10. Is it not a Disposition/Capability?
11. Is it not merely Configuration?
12. Is the meaning reusable beyond one implementation?
13. Is there sufficient evidence and synthesis?
14. Are conflicts retained and resolved or explicitly deferred?

## 21. Routing Rule

When the primary responsibility is not State, route the knowledge to its responsible semantic layer while retaining the evidence and decision in the appropriate registry.

Repository placement is the result of semantic decision, not the decision itself.

## 22. Non-Canonicality Rule

The following do not establish State status by themselves:

- presence of the word `state` in a term;
- use of the term in a standard;
- use of the term in an API;
- use by a vendor;
- use in a device UI;
- representation as boolean or enumeration;
- usefulness for navigation;
- frequency of search.

## 23. Visitor Universe Boundary

Visitor relevance never establishes State semantics.

Visitor Universe may influence entry depth and navigation, but cannot turn a visitor-specific interpretation into a State semantic concept.

## 24. Machine Boundary

Machines must resolve semantic identity through stable identifiers and explicit semantic metadata. They must not infer State from folder name, lexical label, or runtime field name alone.

## 25. V3.1 Decision

The only first-wave canonical State semantic concept is `SEM-STATE-GENERIC-001` — State.

All other State-related constructs remain structural, candidate, deferred, or routed until independent GIOP responsibility is demonstrated.
