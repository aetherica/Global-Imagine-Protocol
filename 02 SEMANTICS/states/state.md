# State

**Semantic ID:** `SEM-STATE-GENERIC-001`  
**Preferred Name:** State  
**Semantic Class:** State  
**Domain:** Cross-Domain Semantic Infrastructure / Imaging  
**Status:** Provisional  
**Version:** 0.1.0

## 5W1H Orientation

### What

A State is a recognized mode or condition in which an eligible semantic bearer exists or operates at a specified temporal locus.

The concept describes a semantic state of a bearer. It does not by itself define a runtime record, event log, measurement value, status report, state-machine implementation, or physical object.

### Why

Imaging and technical systems are frequently described through conditions such as ready, operating, standby, open, closed, active, or suspended. Without a canonical State concept, such terms can be incorrectly mixed with environmental Conditions, Properties, Values, Statuses, Activities, Processes, Events, or Configurations.

### Who

The concept is relevant to general visitors, learners, practitioners, engineers, imaging scientists, metrology professionals, system integrators, AI and data systems, API consumers, simulation systems, and machine-readable knowledge systems.

### Where

A State may characterize an eligible entity, system, subsystem, component, function, or other bearer in a physical, optical, computational, measurement, operational, simulated, or digital-twin setting.

### When

A State is interpreted relative to a specified point in time or temporal interval. The temporal qualification may be instantaneous, interval-based, sequence-based, or otherwise defined by the responsible temporal model.

### How

A State is established by semantic identification of the bearer, the recognized mode or condition, and the temporal locus. The state may be directly observed, derived from measurement, inferred from evidence or rules, or reported by a system, provided that the basis of the assertion remains distinguishable from the State concept itself.

## Semantic Definition

**State is a reusable canonical semantic concept denoting a recognized mode or condition in which an eligible bearer exists or operates at a specified temporal locus.**

The definition is semantic rather than metaphysical. GIOP does not require every State to be treated as an independently existing physical or universal ontological entity.

## Scope

State applies to recognizable bearer-centered modes or conditions that can be meaningfully qualified by time or temporal context.

The bearer may be a physical entity, system, subsystem, function, computational element, or other eligible semantic element. State semantics do not depend on a specific implementation technology or vendor vocabulary.

## Core Distinctions

### State vs Condition

A Condition describes a relevant circumstance that applies to an entity, system, observation, measurement, or situation. A State describes the recognized mode or condition occupied by the bearer.

An environmental condition such as low illumination remains a Condition. A camera being in standby or a sensor being active may be represented as a State.

### State vs Property

A Property is an attributable characteristic. A State is a recognized mode or condition at a temporal locus.

Spectral response and linearity are Properties. Ready, standby, or operating may be State candidates when their primary responsibility is current bearer mode rather than a characteristic.

### State vs Status

A Status is an assigned, reported, administrative, lifecycle, validation, or governance standing where that responsibility belongs to status semantics. A State concerns the recognized condition or mode of the bearer.

A device being in Recording may be a State. A statement that its calibration status is current is not automatically a State.

### State vs Quantity or Value

A Quantity denotes a measurable kind and a Value denotes a particular value or magnitude. A State is not itself a measured magnitude.

A temperature measurement of 85 °C is not a State. A derived classification such as overheated may be a State when the system defines that as a recognized bearer condition.

### State vs Activity

An Activity denotes an action performed. A State describes the bearer mode in which that action may be occurring.

Capturing an image may be an Activity. A camera being in a capture-ready or recording state may be a State.

### State vs Process

A Process denotes transformation or progression. A State denotes the recognized condition or mode during which a process may occur.

Recording as an unfolding process is distinct from a State in which the camera is recording.

### State vs Event

An Event denotes an occurrence or change boundary. A State can persist across time; an Event may establish, end, or change a State.

### State vs Transition

A Transition is a change from one State to another within a state model. Transition semantics do not redefine either State.

### State vs Disposition

A Disposition concerns capability, tendency, or potential realization. A State concerns the current recognized mode or condition.

A sensor may have a disposition to overheat; an observed or inferred overheated condition may constitute a State.

### State vs Configuration

A Configuration concerns arrangement, selected settings, component composition, or other configured structure. A configured arrangement may support a State, but configuration is not automatically State.

### State vs Context

A Context specifies the relevant setting, circumstance, purpose, perspective, or situational frame. A State is the bearer-centered mode or condition interpreted within such a context.

### State vs Relation

A Relation is a typed connection between semantic elements. State describes a bearer condition; any relation connecting a bearer to a State assertion must remain separately typed.

## Temporal Characterization

State semantics are temporally qualified. The same bearer may occupy different States at different times, and different State dimensions may coexist at the same time.

GIOP does not require one bearer to have exactly one State across all dimensions. Exclusivity, concurrency, hierarchy, and transition rules belong to a particular state model rather than to the generic State concept.

## State Establishment

A State assertion may be established through different evidentiary paths:

- **Direct observation:** the State is explicitly observed or reported.
- **Measurement-derived:** measurements provide evidence used to classify the State.
- **Inference:** rules, models, or analysis derive the State from evidence.
- **Declaration/reporting:** an authorized system or source reports the State.

The establishment mechanism is not part of the State meaning and must not silently become semantic authority for the State concept.

## Structural Usage

The following constructs are recognized as useful State-model structures but are not independent V3.1 canonical State semantic entries:

- State Assertion — bearer-specific assertion that a bearer is in a State.
- State Value — a qualitative value used by a particular state model.
- State of Interest — bearer-specific state usage pattern.
- State Machine — model that organizes possible States and transitions.
- Transition — directed change between States.
- State Variable — computational representation of current State.
- State History — record of State succession over time.
- State Hierarchy / Substate — model-specific organization of States.
- Mode — neighbouring construct with unresolved universal boundary against State.

## Multiple State Dimensions

A bearer may participate in multiple State dimensions simultaneously. For example, an imaging system may simultaneously have a power State, recording State, network State, or subcomponent State where the relevant model defines those dimensions.

Multiple State assertions do not imply that the generic State concept itself defines a universal multi-state hierarchy.

## State Hierarchy and Concurrency

Hierarchical State models and mutually exclusive State sets are model-specific. A state machine may define exclusive alternatives, substates, parallel regions, or other structures without changing the meaning of the generic State concept.

## Imaging Examples

Examples below are semantic validation examples rather than additional V3.1 canonical entries:

```text
Camera → Standby
Camera → Ready
Camera → Recording

Sensor → Idle
Sensor → Active

Display → On
Display → Off
```

Each candidate must still be tested against State, Activity, Process, Status, Property, Condition, and configuration responsibilities before canonical promotion.

## Semantic Relations

Potential relation patterns include connections between a bearer and a State assertion, temporal qualification, evidence, context, or transition. Such relations are resolved through the independent GIOP Relation layer rather than embedded as State definitions.

The State concept does not itself introduce new canonical Relation IDs.

## Cross-Domain Significance

State provides a controlled semantic bridge between physical and computational systems, imaging hardware, measurement and observation systems, operational workflows, digital twins, simulation, control models, and AI/data systems.

The common pattern is:

`Bearer → Recognized State → Temporal Qualification → Evidence / Context / Relations`

The surrounding concepts remain owned by their responsible semantic layers.

## Trust

A State definition establishes semantic meaning; it does not certify that a particular State assertion is true.

State assertions should preserve, where materially relevant:

- bearer identity;
- temporal locus;
- observation or measurement basis;
- inference or classification basis;
- reporting source;
- validation status;
- provenance.

External standards establish terminology and modelling evidence. They do not automatically establish a GIOP State as canonical.

## Lifecycle

**Current state:** Provisional canonical semantic entry.

Changes to the semantic identity or core boundary of State require revalidation of the State index, registry, examples, cross-layer validation, and dependent relations or retrieval structures.

## Limitations

State does not provide a universal ontology for every condition-like expression. Particular terms may legitimately be routed to Condition, Property, Status, Quantity/Value, Activity, Process, Event, Disposition, Configuration, Context, or another future semantic layer depending on their primary semantic responsibility.

Surface terminology alone is insufficient for canonical State admission.

## Retrieval Anchors

`STATE`, `STATE SEMANTICS`, `STATE CONCEPT`, `STATE ASSERTION`, `STATE VALUE`, `STATE OF INTEREST`, `STATE MACHINE`, `TRANSITION`, `CURRENT STATE`, `TEMPORAL STATE`, `STATE BEARER`, `OPERATING STATE`, `OPERATIONAL STATE`, `STATE CONDITION`
