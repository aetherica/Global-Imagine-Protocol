# Time

**Semantic ID:** `SEM-TEMPORAL-TIME-001`  
**Preferred Name:** Time  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Temporal Semantics  
**Domain:** General / Imaging / Measurement  
**Status:** Active  
**Version:** 1.0.0

> Time provides the temporal semantics needed to identify instants, intervals, durations, ordering, and temporal context across phenomena, acquisition, processing, result generation, and presentation.

## What

Time is a foundational temporal concept used to describe when an event, state, observation, execution, acquisition, result, or presentation occurs or persists.

## Why

Imaging and measurement systems contain multiple potentially different temporal references. Phenomenon time, acquisition time, exposure or integration interval, processing time, result time, and presentation time must not be silently collapsed into one timestamp.

## Structure

Relevant temporal constructs include:

- Instant;
- Interval;
- Duration;
- Temporal position;
- Temporal order or relation;
- Temporal reference system.

## How

A temporal statement identifies the relevant event or entity, its temporal reference, and whether the statement concerns an instant, interval, duration, or relation. Where required, clock, time scale, synchronization, and uncertainty must be specified.

## Where

Time applies across scenes, phenomena, capture, sensing, measurement, algorithm execution, software execution, result generation, storage, representation, display, and observation.

## Who

It is relevant to all GIOP semantic domains because temporal interpretation crosses physical, measurement, computational, representational, and perceptual layers.

## Core Distinctions

### Phenomenon Time vs Result Time

Phenomenon time describes when the observed phenomenon occurred. Result time identifies when a result became available or was generated. They may differ substantially.

### Acquisition Time vs Processing Time

Acquisition time concerns capture or sensing. Processing time concerns computational transformation after acquisition.

### Instant vs Interval

An instant identifies a temporal point; an interval identifies a span with temporal extent.

### Duration vs Timestamp

Duration measures elapsed temporal extent; a timestamp or temporal position locates an event in a reference system.

## Relations

Potential canonical relations include `before`, `after`, `during`, `starts`, `ends`, `overlaps`, `has-temporal-position`, `has-duration`, `has-phenomenon-time`, and `has-result-time`.

## Trust

Temporal claims require an identified temporal reference system whenever clock differences, synchronization, time scale, or ordering can affect interpretation.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`TIME`, `TEMPORAL SEMANTICS`, `INSTANT`, `INTERVAL`, `DURATION`, `PHENOMENON TIME`, `ACQUISITION TIME`, `PROCESSING TIME`, `RESULT TIME`, `PRESENTATION TIME`
