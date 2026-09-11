# Temperature

**Semantic ID:** `SEM-QUANTITY-TEMPERATURE-001`  
**Preferred Name:** Temperature  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Semantic Class:** Physical Quantity  
**Domain:** General Physics / Optical Imaging  
**Status:** Provisional  
**Version:** 0.1.0  
**Related IDs:** `SEM-CONDITION-TEMPERATURE-001`

> Temperature is a physical quantity describing the thermodynamic state relevant to a defined physical system, region, or material; it must be distinguished from color temperature and correlated color temperature.

## What

Temperature is a measurable physical quantity used to characterize thermodynamic state in a defined system or region.

## Why

Temperature can affect material behavior, optical-system behavior, detector and electronic response, environmental stability, and measurement conditions. Its numerical value belongs to the quantity layer rather than the condition, result, or representation layer.

## Structure

A temperature quantity requires a defined quantity context and an appropriate temperature scale or reference. A reported value becomes meaningful only with its reference, units, and scope.

## How

Temperature may be established through an appropriate measurement procedure and measuring system. A measurement result may contain one or more temperature quantity values together with relevant uncertainty and provenance.

## Where

Temperature may characterize objects, materials, environments, sensors, optical components, measurement systems, laboratories, or other physical systems.

## Who

The concept is relevant to imaging engineers, sensor engineers, optical scientists, metrologists, photographers, cinematographers, laboratory personnel, and computational systems using temperature-dependent models.

## When

Temperature may be specified at an instant, over an interval, or as a time-varying quantity.

## Core Distinctions

### Temperature vs Temperature Condition

Temperature is the physical quantity. Temperature Condition describes the contextual circumstance in which that quantity applies.

### Temperature vs Measurement Result

A temperature quantity is the measured or modeled physical quantity. A measurement result is the information produced by a measurement activity and may contain a temperature quantity value together with uncertainty and other relevant information.

### Temperature vs Color Temperature

Color temperature describes the chromatic appearance of radiation in relation to a reference radiator. It is not interchangeable with thermodynamic temperature of the emitting or illuminated system.

### Temperature vs Correlated Color Temperature

Correlated color temperature (CCT) is a colorimetric concept and is not a general substitute for physical temperature.

## Units and Constraints

Temperature values must use an identified temperature scale and unit/reference. Unit conversion must preserve the meaning of the underlying physical quantity and must not silently convert a temperature value into a color-temperature interpretation.

## Relations

Potential canonical relations include `has-temperature`, `measured-by`, `has-value`, `has-unit`, `has-condition`, and `influences`.

These relations are resolved independently in the GIOP semantic relation domain.

## Trust

A technical temperature statement should identify the relevant physical system or region, temporal scope, scale/reference, method or source, and uncertainty where applicable.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`TEMPERATURE`, `THERMODYNAMIC TEMPERATURE`, `TEMPERATURE QUANTITY`, `KELVIN`, `CELSIUS`, `TEMPERATURE CONDITION`, `COLOR TEMPERATURE`, `CORRELATED COLOR TEMPERATURE`, `CCT`
