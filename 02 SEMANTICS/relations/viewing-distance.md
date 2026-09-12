# Viewing Distance

**Semantic ID:** `SEM-RELATION-VIEWING-DISTANCE-001`  
**Preferred Name:** Viewing Distance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Relation  
**Domain:** Imaging / Display / Visual Observation  
**Status:** Active  
**Version:** 1.0.0

> Viewing Distance is a typed spatial relation specifying the distance between a defined observer viewing point and the object, surface, display, or other target being viewed.

## What

Viewing Distance specifies a spatial separation between two defined references, normally an observer's eye or viewing point and a viewed target.

## Why

Viewing distance affects visual geometry and interpretation of displays, objects, scenes, and measurement or observation setups. It must remain distinct from focal length, object distance in an optical imaging equation, display size, field of view, and angular size.

## Structure

Canonical form:

`Reference A ↔ viewing-distance ↔ Reference B`

The relation may carry or resolve to a distance quantity value. The references must be explicitly identified.

## How

A viewing-distance statement is established by identifying the observer/viewing reference, the viewed target, the applicable spatial frame, and the distance quantity and unit.

## Where

The concept applies to display viewing, photography, cinematography, visual inspection, human factors, laboratory observation, metrology, simulation, and other visual contexts.

## Who

It is relevant to observers, photographers, cinematographers, display engineers, human-factors specialists, metrologists, imaging scientists, and machine-readable systems.

## When

Viewing Distance is context-dependent and may vary over time as the observer, target, or configuration changes.

## Core Distinctions

### Viewing Distance vs Focal Length

Focal length is an optical-system parameter. Viewing distance is a spatial relation between a viewing reference and a viewed target.

### Viewing Distance vs Object Distance

Object distance in a camera or optical model is defined by a particular optical geometry. Viewing distance is defined by the viewing relationship and should not be silently substituted for object distance.

### Viewing Distance vs Field of View

Field of view is an angular or geometric optical quantity. Viewing distance is a spatial relation.

### Viewing Distance vs Angular Size

Angular size depends on spatial geometry and object dimensions. It is not identical to viewing distance.

## Relations

Potential canonical relations include `observes`, `views`, `has-viewing-distance`, `targets`, and `has-distance-value`.

## Trust

A technical statement should identify both endpoints of the relation and the spatial reference used. A bare distance value without endpoints does not by itself establish viewing distance.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`VIEWING DISTANCE`, `VIEWING DISTANCE RELATION`, `OBSERVATION DISTANCE`, `VIEWING POINT`, `DISPLAY VIEWING DISTANCE`, `DISTANCE`, `ANGULAR SIZE`, `FIELD OF VIEW`
