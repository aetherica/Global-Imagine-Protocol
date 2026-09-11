# Result

**Semantic ID:** `SEM-RESULT-001`  
**Preferred Name:** Result  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Result / Output  
**Domain:** Measurement / Observation / Computation  
**Status:** Provisional  
**Version:** 0.1.0

> A Result is information produced by an execution, observation, measurement, or computational operation and attributed to that producing activity with its relevant context, values, quality information, and provenance.

## What

A Result is the output information made available by a defined execution or operation. Depending on the producing context, it may contain a quantity value, classification, geometry, image data, derived information, or another structured output.

## Why

Result must remain distinct from the activity that produced it, from an individual quantity value, and from the representation used to encode or present it.

## Structure

A result may include:

- result identity;
- producing execution or activity;
- value or values;
- units or reference system where applicable;
- uncertainty or quality information;
- phenomenon time;
- result time;
- provenance;
- representation or encoding.

## How

Canonical relation:

`Execution → has-result → Result`

and its inverse:

`Result → is-result-of → Execution`

The result may then be represented or displayed without becoming identical to that representation or display.

## Where

The concept applies to scientific measurement, sensor observation, image processing, algorithmic computation, machine vision, rendering, and other execution-driven contexts.

## Core Distinctions

### Result vs Measurement

Measurement is an activity or process. Result is information produced by that activity.

### Result vs Quantity Value

A quantity value expresses magnitude. A result can contain one or more quantity values together with relevant information.

### Result vs Representation

A representation encodes or expresses information. The result is the produced information object or outcome; a representation may encode that result.

### Result vs Display

A display presents information. Displaying a result does not change the result into a display.

### Result vs Execution

Execution is the act of carrying out a procedure or computation. Result is information produced by that execution.

## Relations

Potential canonical relations include `has-result`, `is-result-of`, `derived-from`, `represented-by`, `has-quality`, `has-phenomenon-time`, and `has-result-time`.

## Provenance / Validation

A result should preserve its producing execution, procedure or computational method where relevant, source inputs, version information, and validation or quality metadata appropriate to the producing domain.

## Trust

A result should never be presented without sufficient context to determine what produced it, what it represents, and which assumptions or quality information materially affect interpretation.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`RESULT`, `OUTPUT`, `HAS RESULT`, `IS RESULT OF`, `MEASUREMENT RESULT`, `OBSERVATION RESULT`, `COMPUTATIONAL RESULT`, `RESULT TIME`, `PHENOMENON TIME`
