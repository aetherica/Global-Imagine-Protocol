# GIOP V3.1 — State Semantic Layer

## Status

**CANONICAL — V3.1 STATE SEMANTIC LAYER**

The `states/` directory defines the authoritative GIOP semantics for recognized states of eligible semantic bearers. It is intentionally narrower than a runtime state store, state-machine implementation, lifecycle database, status registry, or catalogue of device settings.

## Governing Question

> **What recognized mode or condition is an eligible bearer in at a specified temporal locus?**

## Canonical State Definition

**State is a reusable canonical semantic concept denoting a recognized mode or condition in which an eligible bearer exists or operates at a specified temporal locus.**

The definition is semantic rather than metaphysical. GIOP does not require every State to be treated as an independently existing physical or ontological entity.

## Architectural Position

```text
CANONICAL SEMANTIC KNOWLEDGE
        ↓
STATE SEMANTICS
        ↓
STATE ASSERTION / QUALIFICATION
        ↓
HUMAN / MACHINE CONSUMPTION
```

State is one semantic layer in the canonical knowledge system. State assertions may be qualified by time, context, evidence, provenance, observation, measurement, inference, or other relations owned by their responsible semantic layers.

## Core Boundaries

```text
STATE          → recognized bearer mode / condition
CONDITION      → applicable circumstance / contextual condition
PROPERTY       → attributable characteristic
STATUS         → assigned / reported standing or determination
QUANTITY       → measurable concept
VALUE          → particular value or magnitude
ACTIVITY       → action performed
PROCESS        → transformation / progression
EVENT          → occurrence / change boundary
DISPOSITION    → capability, tendency, or potential realization
CONFIGURATION  → arrangement / settings / selected composition
CONTEXT        → situational frame
RELATION       → typed semantic connection
```

A term is not classified as State merely because its surface wording contains `state`, `mode`, `condition`, `status`, or similar language.

## V3.1 Canonical Nucleus

The first-wave V3.1 State semantic nucleus contains one canonical semantic concept:

- `SEM-STATE-GENERIC-001` — State

The following remain structural, methodological, candidate, or deferred rather than independent V3.1 semantic entries:

- State Assertion;
- State Value;
- State of Interest;
- State Machine;
- Transition;
- State Variable;
- State History;
- State Hierarchy;
- Substate;
- Mode.

Common vocabulary such as On, Off, Open, Closed, Ready, Running, Standby, Idle, Active, Faulted, Recording, and similar terms remains subject to candidate audit and is not admitted merely by external usage.

## Visitor Universe and Entry Depth

State semantics are visitor-neutral. Visitor Universe affects how the same canonical State knowledge is entered, navigated, and consumed; it does not create audience-specific State meanings.

General visitors may need the What/Why distinction. Learners may need State versus Condition and Property. Practitioners may need operational examples and transition implications. Engineers, scientists, and metrology users may need temporal qualification, evidence, observation, inference, and cross-layer boundaries. AI, data, API, and system consumers may need stable IDs, assertion patterns, provenance, and validation metadata.

No separate `Visitor Universe` semantic payload is required in ordinary State entries.

## Machine Interpretation

Machines must distinguish at minimum:

- State concept ID;
- preferred name;
- semantic definition;
- bearer scope;
- temporal qualification;
- assertion status;
- candidate/canonical status;
- related structural concepts;
- evidence/provenance;
- validation;
- lifecycle state.

Folder placement alone must never be treated as proof of semantic type.

## Evidence and Trust

External standards and models provide evidence for terminology, structure, and use. They do not automatically determine GIOP canonical identity.

Important reference families include ISO/IEC/IEEE systems-engineering terminology, ETSI SAREF state modelling, OPC UA state-machine modelling, W3C SSN/SOSA observation/property modelling, W3C PROV provenance semantics, and BFO/DOLCE ontological comparisons.

The GIOP decision must distinguish source statement, evidence, inference, synthesis, and canonical decision.

## Lifecycle

State semantic entries follow the Foundation lifecycle and validation controls. Changes that materially alter the semantic identity or boundary of State require revalidation of dependent indexes, examples, relations, and cross-layer decisions.

## Implementation Boundary

`states/` does not become:

- a live device telemetry database;
- an event log;
- a transition log;
- a state-machine implementation;
- a status registry;
- a lifecycle database;
- a property-value catalogue;
- a vendor-specific state vocabulary;
- an audience-specific knowledge base.

Those are implementation or other semantic responsibilities.

## Retrieval Anchors

`STATE`, `STATE SEMANTICS`, `STATE ASSERTION`, `STATE VALUE`, `STATE OF INTEREST`, `STATE MACHINE`, `TRANSITION`, `CURRENT STATE`, `TEMPORAL STATE`, `STATE BEARER`, `STATE CONDITION`, `OPERATING STATE`, `OPERATIONAL STATE`, `STATE BOUNDARY`.

## Reference Basis

This folder was prepared from the GIOP Foundation rules and cross-domain research including:

- ISO/IEC/IEEE 29148:2018, systems and software engineering terminology;
- ETSI SAREF Core, State / StateValue / StateOfInterest modelling;
- OPC UA Parts 10 and 16, state-machine modelling;
- W3C SSN/SOSA, property and observation semantics;
- W3C PROV, temporal event/provenance semantics;
- BFO 2020, process/disposition distinctions;
- DOLCE comparative state/process modelling.

External sources are evidence inputs. The canonical GIOP definition is a GIOP synthesis, not a source quotation.
