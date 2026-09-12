# Exposure Time

**Semantic ID:** `SEM-QUANTITY-EXPOSURE-TIME-001`  
**Preferred Name:** Exposure Time  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Imaging / Photography / Camera Systems  
**Status:** Active  
**Version:** 1.0.0

> Exposure Time is a temporal duration over which a defined imaging receiver is exposed to the relevant radiation or signal under a specified capture configuration.

## What

Exposure Time describes the duration associated with an imaging exposure. It is a time quantity, not a camera state, measurement result, or representation.

## Why

Exposure time affects captured signal, motion integration, blur, noise behavior, dynamic response, and imaging workflow. It is therefore a fundamental quantity for camera and sensor characterization.

## Structure

A complete statement identifies the receiving system or exposure process, temporal interval or duration, value and unit, and relevant capture conditions.

## How

Exposure time may be specified by a capture configuration or established from system behavior or measurement. Actual effective integration time may differ from a nominal setting depending on the device and operating mode.

## Where

It applies to still imaging, electronic sensors, cameras, scientific detectors, scanning systems, and other systems with defined exposure/integration intervals.

## Who

Photographers, cinematographers, camera engineers, sensor engineers, imaging scientists, metrologists, and computational imaging systems use the concept.

## When

Exposure Time is intrinsically temporal and normally refers to a duration. Exact temporal boundaries may require context when exposure mechanisms are complex.

## Core Distinctions

### Exposure Time vs Exposure State

Exposure State describes a recognized mode of a system. Exposure Time is the duration associated with exposure.

### Exposure Time vs Frame Rate

Frame rate describes temporal frequency of frames or sampling events. Exposure time describes an exposure duration and is not equivalent to frame interval.

### Exposure Time vs Shutter Speed

Shutter speed is a practical control/notation commonly used for exposure duration. It may encode a reciprocal duration but should not be treated as a distinct semantic Quantity without independent responsibility.

### Exposure Time vs Measurement Result

A reported exposure-time value may appear in a result, but the Quantity remains distinct from the result information object.

## Units and Value Semantics

Exposure Time is expressed in a unit of time, such as seconds or compatible submultiples.

## Technical Depth

Exposure duration interacts with sensor integration, shutter mechanism, readout, rolling-shutter behavior, source modulation, and temporal scene variation. These effects belong to relevant contexts and technical models rather than changing Quantity identity.

## Constraints / Assumptions

Do not assume nominal camera settings equal effective photon-integration duration in every architecture. Do not equate exposure time with frame period.

## Evidence / Trust / Validation

Exposure Time is a high-confidence temporal Quantity in imaging. Reported values should identify whether they are configured, nominal, calibrated, measured, or inferred when that distinction matters.

## Relations

Potential relations include association with capture activity, sensor, exposure state, frame, and measurement context. Canonical relation identities are governed independently.

## Machine / AI Interpretation

`Exposure Time` resolves to `SEM-QUANTITY-EXPOSURE-TIME-001`. A value such as `1/100 s` is a quantity value expression associated with this concept.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`EXPOSURE TIME`, `EXPOSURE DURATION`, `INTEGRATION TIME`, `EXPOSURE TIME QUANTITY`, `SHUTTER SPEED`, `EXPOSURE INTERVAL`
