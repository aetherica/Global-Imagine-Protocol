# Object-Centric Representation

**Semantic ID:** `SEM-REPRESENTATION-OBJECT-CENTRIC-001`  
**Preferred Name:** Object-Centric Representation  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Object-organized information-bearing form  
**Domain:** Computer Vision / Robotics / AI / Scene Understanding / Information Representation  
**Status:** Active  
**Version:** 1.0.0  
**Authority:** GIOP Canonical Semantic Layer — Representation  
**Provenance:** Semantic synthesis from object-centric representation-learning research, embodied robotics, scene understanding, and GIOP Representation boundary analysis.  
**Validation:** Identity, primary responsibility, existing-entry, boundary, evidence, relation authority, cross-layer, lifecycle, and retrieval gates passed.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-RELATION-CENTRIC-001`, `SEM-REPRESENTATION-SCENE-001`, `SEM-PERCEPTION-GENERIC-001`, `SEM-STATE-GENERIC-001`

> An Object-Centric Representation is an information-bearing form organized around distinct identified or hypothesized objects or entities, together with selected attributes, states, parts, or object-level information associated with them.

## What

Object-Centric Representation expresses information by organizing it around object-level units rather than treating an entire scene, signal, document, or observation as an undifferentiated whole.

An object-centric representation may contain one object, multiple objects, object slots, object records, object tokens, object graphs, structured object descriptions, or learned object-level latent variables. The particular computational realization does not determine the semantic identity.

The representation may encode identity hypotheses, category, geometry, pose, appearance, attributes, state information, uncertainty, parts, or other object-associated information when those elements are part of the representation's declared scope.

## Why

Object-level organization supports semantic separation, compositional reasoning, tracking, manipulation, interaction, scene understanding, and transfer across varying scenes and configurations.

Contemporary object-centric learning commonly seeks representations in which a scene is decomposed into distinct entities or object-like slots. Robotics systems also use object-level representations for pose estimation, manipulation, affordance reasoning, and task-oriented learning. These uses demonstrate a recurring representation responsibility distinct from the perceptual process or learning procedure that produces the representation.

## Who

The concept is relevant to computer-vision researchers, roboticists, AI/ML engineers, imaging scientists, scene-understanding systems, dataset engineers, simulation developers, and machine-readable consumers.

Audience does not alter the semantic identity of Object-Centric Representation. Entry depth changes according to the Visitor Universe routing model.

## Where

Object-Centric Representations occur in visual scene understanding, 2D and 3D perception, robotic manipulation, object tracking, simulation, world-model systems, multimodal AI, structured prediction, knowledge representation, and machine-readable scene descriptions.

## When

An Object-Centric Representation may be static or dynamically updated. It may describe an observed scene, a reconstructed environment, a simulated world, an inferred object configuration, a task state, or another object-organized information domain.

Temporal information may be included, but a temporal trajectory is not automatically an Object-Centric Representation; responsibility depends on whether object organization or temporal evolution is primary.

## How

An Object-Centric Representation organizes represented information around object-level units and may associate each unit with attributes, state information, geometry, identity hypotheses, uncertainty, parts, or relations.

A common abstract structure is:

```text
Represented scene / domain information
                |
                v
      Object-Centric Representation
                |
        +-------+--------+
        |       |        |
        v       v        v
     Object   Object   Object
      unit     unit     unit
        |       |        |
     attributes / states / geometry / uncertainty
        |
        +---- optional typed relations ----+
```

This is a semantic coordination model, not a universal object ontology or inheritance hierarchy.

## Semantic Definition

**Object-Centric Representation** is an information-bearing form whose organization treats distinct objects or entities as primary representational units and associates selected object-level information with those units.

The represented objects may be physical, digital, simulated, conceptual, or hypothesized, provided the representation has an explicit object-level organizing responsibility.

The representation may be symbolic, structured, statistical, neural, latent, geometric, graph-based, or otherwise computationally realized. A particular realization does not by itself establish semantic validity as an Object-Centric Representation.

## Core Distinctions

### Object-Centric Representation vs Representation

Representation is the generic semantic category. Object-Centric Representation is a specialized Representation whose primary organizing responsibility is object-level organization.

### Object-Centric Representation vs Object

An Object is the represented entity or semantic unit. Object-Centric Representation is the information-bearing form used to express information about one or more such entities.

### Object-Centric Representation vs Perception

Perception concerns an observer-relative perceptual phenomenon or outcome. Object-Centric Representation may encode the output of perception or information derived from it, but the representation is not the perceptual phenomenon.

### Object-Centric Representation vs Observation

Observation is an activity/occurrence involving an observer and a stimulus or target. An Object-Centric Representation may be produced from observations, but it is not the observation event itself.

### Object-Centric Representation vs State

State denotes a recognized mode or condition of a bearer at a temporal locus. An Object-Centric Representation may encode object states, but state semantics remain in the State layer.

### Object-Centric Representation vs State Representation

State Representation specifically expresses a state. Object-Centric Representation organizes information around objects. A representation may satisfy both responsibilities only when both semantic roles are independently justified; object-centric organization must not be treated as a replacement for State semantics.

### Object-Centric Representation vs Relation-Centric Representation

Object-Centric Representation makes objects/entities the primary organizing units. Relation-Centric Representation makes typed relations among entities or semantic elements primary. An object-centric representation may contain relations without becoming relation-centric.

### Object-Centric Representation vs Scene Representation

Scene Representation has scene-level responsibility for representing entities, geometry, semantics, structure, or relationships of a scene. An Object-Centric Representation may be one realization or organization of scene information, but the two concepts are not automatically equivalent. Promotion of Scene Representation remains independently controlled.

### Object-Centric Representation vs Model

A model may define, infer, predict, or constrain object-level structure. The object-centric representation is the information-bearing form resulting from or used by that model. A learned model is not automatically an Object-Centric Representation.

### Object-Centric Representation vs Representation Learning

Representation Learning is a process or learning paradigm. Object-Centric Representation is the resulting or otherwise used information-bearing form. The learning method does not determine the representation's semantic identity.

### Object-Centric Representation vs Object Detection / Segmentation

Detection and segmentation are task or activity-level responsibilities. Their outputs may form or populate an Object-Centric Representation, but the tasks themselves are not the representation.

### Object-Centric Representation vs Dataset / File / Bitstream

A dataset, file, or bitstream may carry an Object-Centric Representation. Storage or carrier identity does not replace the representation's semantic responsibility.

## Object Identity and Hypothesis

Object-level organization does not require that every represented object be independently verified as an externally existing physical object.

An object unit may be:

- a confirmed or identified entity;
- an inferred entity;
- a tracked hypothesis;
- a simulated entity;
- an object-like latent unit;
- a task-defined entity.

Trust requirements should make the epistemic status explicit. An object hypothesis must not be silently treated as verified external-world identity.

## Attributes, States, and Relations

An Object-Centric Representation may carry:

- object identifiers or identity hypotheses;
- category or semantic labels;
- geometry, pose, or spatial extent;
- appearance or material-related descriptors;
- object-level properties;
- object states;
- uncertainty or confidence information;
- parts or sub-objects;
- typed relations to other represented entities.

These contents do not collapse the corresponding GIOP semantic layers into Representation. The representation carries or organizes the information; canonical semantics for properties, states, relations, quantities, or classes remain independently governed.

## Learned and Latent Realizations

Object-centric representations may be learned using slot-based, object-file-like, factorized, neural, probabilistic, or other methods.

A latent vector is not automatically an Object-Centric Representation merely because a paper describes it as object-centric. The representation should have documented object-level semantics or organizing responsibility rather than relying only on a method name.

Conversely, an object-centric representation need not be interpretable in human-readable form. Semantic responsibility can be established through declared structure, training objective, task semantics, validation, or documented correspondence between representational units and object-level entities.

## Uncertainty and Multiple Hypotheses

Object-centric representations may encode uncertainty about object existence, identity, pose, attributes, or correspondence across observations.

Uncertainty does not convert the representation into Belief Representation automatically. Agent-relative epistemic responsibility must be independently established. Where uncertainty explicitly represents an agent's belief over object hypotheses, the same information may participate in or instantiate a Belief Representation under the applicable semantic qualification.

## Boundary Cases

### Scene represented as object slots

If the primary semantic responsibility is the decomposition of scene information into object-level units, Object-Centric Representation is justified. If the primary responsibility is broader scene structure including geometry, topology, semantics, and relations as a scene-level whole, Scene Representation remains a separate candidate.

### Object detector output

A detector execution is an activity or computational process. Its object detections may populate an Object-Centric Representation.

### Object track

A track is temporal information about an object's evolution. It may be represented in object-centric form, but Trajectory Representation remains independently responsible for ordered temporal/spatial evolution when that is the primary organizing role.

### Object graph

An object graph may qualify as Object-Centric Representation when objects are the primary units and relations are supporting structure. If typed relations themselves are the primary organizing responsibility, Relation-Centric Representation may be more appropriate.

### Object-centric latent slots

Latent slots may qualify when each slot has documented object-level representational semantics. Merely using multiple latent vectors is insufficient.

### Object category taxonomy

A taxonomy or class hierarchy organizes concepts or categories. It is not automatically an Object-Centric Representation simply because its nodes refer to objects.

## Technical and Cross-Domain Significance

Object-Centric Representation provides a semantic bridge across:

`Perception / Observation → Object-level information → Object-Centric Representation → Reasoning / Tracking / Interaction / Action`

It is particularly important where compositionality, object identity, object-level state, multi-object interaction, manipulation, and scene variation must be represented without collapsing the entire environment into one undifferentiated signal.

## Relations

Existing canonical relation concepts should be used where applicable, including `represents`, `derived-from`, `part-of`, `participates-in`, and other already-authorized relations when their semantic conditions are satisfied.

No new relation authority is introduced by this entry.

## Provenance and Evidence

The semantic synthesis is informed by object-centric representation-learning literature, computer-vision research, embodied robotics, and scene-understanding practice. Evidence includes recent surveys of object-centric robotic manipulation and contemporary object-centric visual representation-learning work demonstrating object-level slots or object-file-like representations.

Representative evidence families include peer-reviewed robotics surveys, CVPR object-centric representation-learning research, academic technical reports on unsupervised object-centric representation learning, and GIOP cross-layer analysis.

These sources support semantic synthesis and do not become GIOP authority.

## Trust and Validation

An Object-Centric Representation claim should identify, where relevant:

- what constitutes an object unit;
- whether object identity is observed, inferred, simulated, or hypothesized;
- the correspondence between representational units and represented entities;
- included attributes, states, geometry, and relations;
- uncertainty and confidence semantics;
- temporal scope and update behavior;
- provenance and derivation;
- model or learning dependence;
- validation method and known limitations.

Object-level organization must not be inferred solely from a filename, tensor shape, model architecture, or product terminology.

## Lifecycle

**Current state:** Active canonical semantic entry.

The definition remains subject to controlled revision when stronger evidence, a materially clearer boundary, or a justified architectural change is established. Any specialized subtype or realization family requires independent canonicalization review.

## Retrieval Anchors

`OBJECT-CENTRIC REPRESENTATION`, `OBJECT-CENTRIC REPRESENTATIONS`, `OBJECT-CENTRIC LEARNING`, `OBJECT FILE`, `OBJECT SLOT`, `OBJECT-LEVEL REPRESENTATION`, `ENTITY-CENTRIC REPRESENTATION`, `OBJECT-ORGANIZED REPRESENTATION`, `OBJECT-CENTRIC SCENE REPRESENTATION`
