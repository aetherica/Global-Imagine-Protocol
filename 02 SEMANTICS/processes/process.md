# Process

> **Identity:** A Process is an organized temporal course of interrelated or interacting activities that uses, transforms, or coordinates inputs toward one or more results.

## Canonical Identity

- **ID:** `SEM-PROCESS-GENERIC-001`
- **TITLE:** Process
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Organized temporal course / transformation / progression
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer
- **PROVENANCE:** Semantic synthesis from GIOP Activity semantics and external process models
- **VALIDATION:** Foundation authoring rules; canonical boundary validation; cross-layer validation; retrieval and lifecycle gates
- **RELATED IDS:** `SEM-ACTIVITY-GENERIC-001`; `SEM-REPRESENTATION-GENERIC-001`; `SEM-STATE-GENERIC-001`

## What

A Process is a semantic concept for an organized temporal course in which activities are interrelated or interacting and collectively transform, use, develop, maintain, or coordinate inputs toward one or more results.

The concept is intentionally broader than any particular industrial, computational, scientific, organizational, or imaging methodology. A Process can be planned or emergent, physical or informational, manual or computational, short or long, simple or composite. Those characteristics do not by themselves create separate canonical Process types.

ISO 9000 defines process in terms of interrelated or interacting activities that use or transform inputs to deliver a result. W3C PROV-O independently models an Activity as something occurring over a period of time that acts upon or with entities. GIOP uses these sources as evidence while preserving its own Activity/Process boundary. citeturn0search7turn0search6

## Why

Process semantics are required because occurrence-level Activities alone do not adequately describe an organized course spanning multiple activities, transformations, stages, or results. Conversely, treating every long-running Activity as a Process collapses two different levels of temporal organization.

The Process layer therefore provides a coordination level between individual Activities and broader domain descriptions without replacing Procedure, Workflow, Result, State, or Representation semantics.

## Structure

A Process may be understood as:

```text
Process
├── temporal course
├── interrelated / interacting activities
├── inputs or resources
├── transformations / progression / coordination
└── intended or realized result(s)
```

This is a semantic coordination model, not a mandatory filesystem hierarchy and not a claim that every Process has all five components explicitly recorded.

## How

A Process can organize or involve multiple Activities. Activities are occurrence-level phenomena; the Process is the broader organized course that gives those occurrences a process-level interpretation.

A Process may use or transform information, physical objects, materials, resources, measurements, representations, or other entities. The semantic identity of those entities remains owned by their respective canonical layers.

A Process may produce, contribute to, or lead toward a Result. Result identity is independent of the Process and can persist after the Process ends.

A Process can be described by a Procedure, but a Procedure is not the Process. A Procedure specifies a prescribed or intended way of performing an operation; a Process denotes the organized course that occurs or is realized.

## Where

Process semantics apply across imaging, optics, hardware engineering, software, computation, scientific research, measurement, production, preservation, broadcasting, AI pipelines, organizational operations, and other domains where activities form an organized temporal course.

Domain-specific process concepts should be authored in domain-specific semantic layers only after their responsibility can no longer be represented adequately by the generic Process concept.

## Who

Processes may involve people, organizations, machines, software systems, instruments, environments, or combinations of these. The participating entity is not itself a Process.

CIDOC CRM provides evidence that activity/event modelling can include complex and long-lasting courses as well as short-lived actions; GIOP does not import CIDOC CRM's class hierarchy as a universal GIOP hierarchy. citeturn0search50

## Formal Semantic Responsibility

The primary responsibility of Process is **organized temporal course**.

A concept belongs in Process when the semantic claim primarily concerns the organization, progression, transformation, coordination, or development of interrelated activities over time.

A concept should not be routed to Process when its primary responsibility is:

| Responsibility | Route |
|---|---|
| actual occurrence of an operation | Activity |
| prescribed way of performing an operation | Procedure / applicable semantic layer |
| generated information/output | Result |
| recognized mode at a temporal locus | State |
| environmental or operational circumstance | Condition |
| interpretive setting or frame | Context |
| information-bearing form | Representation |
| computational method | Algorithm / applicable semantic layer |
| executable implementation | Software / applicable semantic layer |
| measurable characteristic | Quantity / Property |

## Process and Activity Boundary

```text
Activity = occurrence-level doing
Process  = organized course involving/interrelating activities
```

An Activity may participate in a Process. A Process may be realized through multiple Activities. Neither term is automatically equivalent to the other.

The GIOP Activity layer explicitly preserves this distinction: Activity is the occurrence layer, while Process is the broader transformation, development, progression, or organized temporal course. citeturn88file0

## Process and Procedure Boundary

```text
Procedure = specification / prescribed method
Process   = organized course realized or occurring over time
```

A Procedure can constrain or guide a Process, but GIOP does not introduce a new process-specific relation solely to express that dependency.

## Process and Result Boundary

A Result is information or an output associated with an occurrence or process. It is not the process itself. A process may contribute to multiple results, and a result may be reused or represented independently of the process that generated it.

## Process and State Boundary

A Process is temporal organization/change; State is a recognized mode or condition of a bearer at a temporal locus. A process may change states, operate while a particular state holds, or be evaluated by state transitions, but state identity remains separate.

## Process and Condition Boundary

A Condition specifies relevant circumstances under which something exists, operates, is observed, measured, or evaluated. A Process is the organized course of activity. Environmental conditions can qualify a Process without becoming part of the Process's semantic identity.

## Process and Representation Boundary

A Process can create, transform, exchange, or preserve information that has one or more Representations. Representation remains the information-bearing form. A process is not a file, encoding, serialization, package, display, or other representational artifact.

## Composite and Nested Processes

Processes may be composite. A higher-level Process may organize lower-level processes and activities. This does not require a universal recursive subclass hierarchy. Granularity is determined by the semantic scope of the assertion and its intended level of analysis.

## Inputs, Resources, and Results

Inputs and resources are contextual participants in a Process rather than new Process subclasses. A process may transform an input into a result, use an entity without transforming it, or coordinate activities whose outputs become inputs to later stages.

ISO's process approach explicitly treats inputs and outputs/results as connected across processes. GIOP retains that systems-level insight without creating new relation authority in the Process folder. citeturn0search48turn0search7

## Relation Use

Only existing canonical relations may be used where their semantics apply. Relevant examples include:

- `part-of` — when a process is genuinely part of a larger canonical whole
- `participates-in` — when an eligible entity participates in a process
- `derived-from` — when a result or representation is derived from process-related source material
- `represents` — when a representation represents process-related information
- `has-result` — where the existing Activity/Result semantics legitimately apply

Terms such as `has-input`, `has-output`, `contains-activity`, `transforms`, `follows`, `implements`, and `conforms-to` are not introduced here as new canonical relations.

## Trust, Provenance, and Evidence

A Process description must distinguish between:

- source statement
- recovered knowledge
- evidence
- inference
- semantic synthesis
- implementation observation
- historical statement
- canonical decision

The existence of a process claim in a source does not by itself make the claim GIOP-canonical. Canonical status requires GIOP validation and promotion.

## Lifecycle

Supported lifecycle states remain Foundation-controlled. This entry is **Active** after scoped Process-batch validation. Future specialized Process concepts must pass their own promotion gates.

```text
AUTHORED → INTEGRATED → VALIDATED → APPROVED → ACTIVE CANONICAL
```

## Limitations

- Process is not intended to encode every domain-specific workflow vocabulary.
- A sequence of activities is not automatically a Process unless an organized-course interpretation is semantically justified.
- A long duration does not automatically imply Process.
- A process diagram, workflow file, software package, or dataset is not itself a Process merely because it describes or supports one.
- Visitor Universe does not create alternate Process identities.

## Retrieval Anchors

`SEM-PROCESS-GENERIC-001`, `PROCESS`, `ORGANIZED TEMPORAL COURSE`, `INTERRELATED ACTIVITIES`, `INTERACTING ACTIVITIES`, `INPUT`, `TRANSFORMATION`, `PROGRESSION`, `RESULT`, `ACTIVITY`, `PROCEDURE`, `STATE`, `REPRESENTATION`, `PROVENANCE`
