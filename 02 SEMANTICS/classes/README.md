# GIOP Semantic Classes

## Purpose

The `classes/` directory establishes the principal kinds of entities recognized by GIOP within its canonical semantic knowledge.

Its governing question is:

> **What kind of entity is this?**

A class identifies an entity category. It does not, by itself, define the entity's properties, conditions, states, quantities, activities, processes, relationships, perceptual outcomes, or representational encoding.

## Canonical Class Set

The current compact class set is:

1. **Camera** — system-level capture entity.
2. **Lens** — optical component or optical assembly.
3. **Sensor** — sensing element or sensing subsystem.
4. **Light Source** — radiative source entity.
5. **Surface** — spatial boundary or interface region.
6. **Material** — physical substance or medium.
7. **Observer** — observing entity or explicitly defined observer model.
8. **Scene** — contextually bounded configuration of entities and circumstances.
9. **Object** — contextually identifiable entity.
10. **Measuring System** — configured measurement apparatus or coordinated system.
11. **Representation** — information-bearing representational entity.

## Semantic Layer Boundary

GIOP distinguishes semantic responsibilities as follows:

`ENTITY TYPE → CLASS`

`CHARACTERISTIC → PROPERTY`

`CONTEXTUAL OPTICAL OR OTHER CIRCUMSTANCE → CONDITION`

`TEMPORAL / CONFIGURATIONAL MODE → STATE`

`RELATIONSHIP → RELATION`

`MEASURABLE CONCEPT → QUANTITY`

`ACTION → ACTIVITY`

`TRANSFORMATION / DEVELOPMENT → PROCESS`

`INFORMATION FORM → REPRESENTATION`

`PERCEPTUAL EXPERIENCE / INTERPRETATION → PERCEPTION`

These distinctions prevent category errors such as treating measurement as an entity, a property as a class, an image as the same thing as the physical scene, or a sensor as equivalent to a complete camera.

## Ontological Heterogeneity

The eleven classes are intentionally not restricted to one physical ontological kind. They include physical entities, engineered systems, contextual entities, observing entities or models, and information-bearing entities.

This is valid because each class explicitly declares its semantic nature and boundary. GIOP does not claim that every class is a physical object or that every class has identical ontological status.

## Camera Classification

The familiar term **Camera** is retained for usability and interoperability. Its semantic class is explicitly system-level:

`Capture System → Camera → application-specific camera type`

A camera is therefore not silently reduced to a sensor, lens, image, or measurement system.

## Measurement Classification

**Measurement is not a class topic.** Measurement belongs to the activity/process domain.

**Measuring System is a class topic.** It identifies the configured apparatus or coordinated system used for measurement.

This distinction is fundamental to GIOP semantic precision.

## Representation Classification

**Representation** is intentionally broader than **image**. An image, video, text, dataset, signal, 3D model, or other information form may be a representation depending on its semantic role.

The representation must remain distinct from the entity, scene, object, surface, measurement result, or phenomenon that it represents.

## Human and Machine Interpretation

The class layer is designed to be understandable to humans while remaining deterministic enough for machine and AI interpretation.

Class membership alone must not be used to infer unsupported properties. For example, class membership does not establish:

- numerical performance;
- calibration status;
- measurement validity;
- manufacturer identity;
- physical composition;
- spectral range;
- perceptual outcome;
- provenance;
- authenticity;
- operating condition.

Such claims require explicit semantic attributes and appropriate evidence.

## Evidence and Trust

GIOP class definitions are semantic syntheses informed by authoritative standards, scientific literature, technical documentation, and domain practice. External sources provide evidence; GIOP provides semantic synthesis.

A class definition therefore does not imply that GIOP is the original inventor of the underlying technical concept. Its canonical responsibility is to define a stable semantic boundary and integrate the concept consistently into the GIOP knowledge model.

## Visitor Universe Compatibility

The same canonical class knowledge is intended to support the complete GIOP Visitor Universe. Visitors are not assigned different truths or separate class definitions. They enter the same canonical knowledge at different depths according to expertise, task, and navigation path.

The governing model is:

`CANONICAL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

The novice and the expert are not given different knowledge. They are given different entry depths into the same knowledge.

## Expansion Rule

The class set is intentionally compact. A new class should be introduced only when a durable semantic responsibility cannot be represented accurately by an existing class or by an appropriate concept in another semantic layer.

Additional domain terms should not become classes merely because they are important nouns. They should first be evaluated as possible properties, conditions, states, quantities, relations, activities, processes, representations, roles, or other appropriate semantic concepts.

## Directory

- `camera.md`
- `lens.md`
- `sensor.md`
- `light-source.md`
- `surface.md`
- `material.md`
- `observer.md`
- `scene.md`
- `object.md`
- `measuring-system.md`
- `representation.md`
