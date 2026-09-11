# Observer

**GIOP Semantic Class ID:** `SEM-CLASS-OBSERVER-001`

## Identity

**Preferred Name:** Observer  
**Artifact Class:** Observing Entity or Observer Model  
**Artifact Type:** Observer  
**Primary Domain:** Observation, vision, and interpretation  

## 5W1H Orientation

**What:** An observer is an entity or explicitly defined observer model that receives, examines, or evaluates information about something of interest.

**Why:** Observation provides a semantic role through which information is acquired, compared, interpreted, or evaluated.

**Who:** An observer may be a human, instrument, computational system, machine, formal observer model, or another explicitly defined observing entity.

**Where:** Observers occur in human vision, scientific observation, imaging systems, machine vision, computer vision, metrology, inspection, and automated decision systems.

**When:** Observation occurs within a defined context and may depend on time, conditions, modality, task, and observer configuration.

**How:** An observer receives or accesses information and produces an observation, interpretation, classification, decision, or other observer-dependent output.

## Semantic Definition

An **Observer** is an entity or formally specified observer model that participates in observation by receiving, examining, or evaluating information about a target or phenomenon.

The class intentionally covers both actual observing entities and explicitly defined formal observer models, provided their identity is stated clearly.

## Principal Types

Examples include:

- human observer;
- instrumental observer;
- machine observer;
- computational observer;
- computer-vision observer;
- formal observer model;
- standardized colorimetric observer;
- scientific observer.

A formal observer model is not automatically equivalent to an actual human observer.

## Distinctions

### Observer vs Sensor

A sensor is directly affected by an input and produces a sensing output. An observer is defined by an observation role. A sensor may support an observer but is not necessarily itself an observer.

### Observer vs Perception

Observer identifies the observing entity or model. Perception describes an experience, interpretation, or perceptual state.

### Observer vs Camera

A camera is a capture system. An observer is an observing entity or model. A camera may provide input to an observer.

### Observer vs Measurement

Measurement is an activity. An observer may participate in measurement, but observer identity and measurement activity are distinct.

## Observation Scope

Observation may concern:

- physical scenes;
- objects;
- surfaces;
- images;
- signals;
- measurements;
- representations;
- visual or non-visual phenomena;
- computationally derived information.

Observation does not imply that the observed information is physically direct or free from interpretation.

## Technical Characteristics

Relevant observer characteristics may include:

- observation modality;
- spectral or sensory sensitivity;
- spatial and temporal resolution;
- task definition;
- adaptation state;
- viewing or observation conditions;
- decision criteria;
- model parameters;
- training or calibration state;
- uncertainty or confidence;
- computational architecture where applicable.

These are properties, conditions, states, or model characteristics rather than the observer class itself.

## Trust and Validation

Observer-related claims should identify whether the observer is:

- directly observed;
- instrumentally represented;
- computationally modeled;
- standardized;
- inferred;
- experimentally characterized.

A formal observer model should not be presented as a literal human experience unless the relevant equivalence is established and justified.

## Lifecycle

`Definition / Formation → Configuration → Calibration / Training → Observation → Evaluation → Update / Adaptation → Retirement`

For human observers, lifecycle semantics may differ from those of computational or instrumental observers.

## Relations

An observer may:

- observe a scene;
- observe an object or surface;
- receive a representation;
- use a camera or sensor as an input channel;
- perform or support measurement;
- produce an observation;
- produce an interpretation or decision;
- be constrained by viewing conditions;
- exhibit a perceptual state.

## Machine and AI Interpretation

A machine must distinguish an actual observer from a formal observer model. It should not infer human perception from the mere presence of an observer class. Claims concerning human visual response require explicit human-vision or observer-model semantics and evidence.

## Retrieval Anchors

Primary terms: `observer`, `observing entity`, `observer model`.

Related terms: `human observer`, `machine observer`, `standard observer`, `computational observer`, `instrumental observer`.

## Semantic Boundary

This class establishes **what an observer is as an observing entity or model**. It does not define perception, observation conditions, sensor properties, camera identity, measurement activity, or interpretation results.
