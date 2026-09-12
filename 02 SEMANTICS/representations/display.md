# Display

**Semantic ID:** `SEM-DISPLAY-001`  
**Preferred Name:** Display  
**Artifact Type:** Display / Presentation Definition  
**Primary Responsibility:** Presentation System / Mechanism  
**Domain:** Display / Imaging / Visual Observation  
**Status:** Active  
**Version:** 1.0.0  
**Authority:** GIOP Canonical Semantic Layer  
**Provenance:** Existing GIOP canonical semantic entry, integrated with the Representation semantic model.  
**Validation:** Representation boundary and cross-layer validation applied; existing semantic identity preserved.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-CONTEXT-VIEWING-001`, `SEM-PERCEPTION-GENERIC-001`

> A Display is a system or mechanism that presents information through an observable output under defined display and viewing conditions.

## What

A Display presents information to an observer or receiving system. It may convert a digital or physical information source into an observable visual output.

## Why

Display must remain distinct from the information being displayed, from its representation or encoding, and from the observer's perception of that information.

## Structure

A display context may involve:

- input information;
- representation or encoding;
- display system;
- display state or configuration;
- viewing conditions;
- observer or receiving system;
- resulting perception or observation.

## How

A common semantic chain is:

`Result / Information → Representation → Display → Viewing Conditions → Observer → Perception`

The display is one stage in that chain, not the information itself.

## Where

The concept applies to electronic displays, projection systems, instrument displays, virtual-production environments, simulation systems, and other information-presentation contexts.

## Who

It is relevant to display engineers, photographers, cinematographers, interface designers, imaging scientists, human-factors specialists, observers, and machine-readable systems.

Visitor category does not change the semantic identity of Display. Different visitors may enter the same canonical entry at different depths.

## Semantic Definition

**Display** is a system or mechanism that presents information through an observable output under defined display and viewing conditions.

The displayed information may originate from a Representation, Result, data source, or other information-bearing source. The Display is the presentation mechanism rather than the represented content.

## Core Distinctions

### Display vs Representation

Representation is an information-bearing form. Display is the system or mechanism presenting that information.

### Display vs Result

A result is produced by an execution or measurement. A display presents information from that result; it does not become the result.

### Display vs Perception

Perception is an observer-dependent outcome. Display provides stimulus or presentation conditions but does not define perception.

### Display vs Viewing Conditions

Viewing conditions describe the circumstances under which a display is observed. They are not identical to the display system.

### Display vs Encoding

Encoding describes a coding scheme or transformation. A Display may consume encoded information but is not an encoding scheme.

## Context Dimensions

Where relevant, Display interpretation should be qualified by:

- display system and configuration;
- input representation;
- viewing environment;
- illumination and surrounding conditions;
- observer or receiving system;
- calibration state;
- intended task;
- temporal state;
- measurement or validation context.

## Boundary Cases

A rendered frame, pixel array, or encoded image is not automatically the Display. A monitor, projector, or virtual display mechanism may be a Display, while the information presented by it remains a separate Representation.

A displayed visual stimulus is not identical to the observer's perception of that stimulus.

## Relations

Existing GIOP relations should be used to connect Display to Representation, Context, Observer, Perception, and relevant Activities. Candidate relation names must not become authoritative merely by appearing in this entry.

## Trust

Technical claims about a Display should identify display characteristics, configuration, viewing conditions, calibration state, and relevant measurement or validation context where these affect interpretation.

A displayed result should not be treated as proof of the underlying source or representation without appropriate validation.

## Lifecycle

**Current state:** Active canonical semantic entry.

The semantic identity is preserved from the existing canonical Display entry; future changes must follow the GIOP canonicalization and validation rules.

## Retrieval Anchors

`DISPLAY`, `DISPLAY SYSTEM`, `PRESENTATION SYSTEM`, `VISUAL DISPLAY`, `VIEWING CONDITIONS`, `REPRESENTATION`, `PERCEPTION`, `DISPLAY CALIBRATION`
