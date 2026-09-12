# Quantities

The Quantity semantic layer defines reusable canonical concepts for measurable aspects of entities, phenomena, systems, materials, spaces, and other eligible bearers.

**Semantic Layer:** Quantity  
**Version:** 3.1  
**Status:** CLOSED — CURRENT V3.1 QUANTITY NUCLEUS  
**Primary Responsibility:** Measurable semantic concept  
**Repository:** Global Imagine Protocol  
**Branch:** `v3.1-tree-architecture`

## What

A Quantity is a reusable canonical semantic concept denoting a measurable aspect whose magnitude can be expressed through an appropriate value and reference structure.

Quantity answers the semantic question: **what measurable aspect is being quantified?**

A Quantity is not the numerical value assigned to that aspect, the unit used to express the value, the measurement activity that establishes it, or the measurement result that records the outcome.

## Structure

`Quantity Concept → Quantity Value → Unit / Reference → Measurement or other establishment activity → Measurement Result / Representation`

Supporting constructs such as quantity kind, quantity dimension, scale/reference system, mathematical structure, temporal scope, spatial scope and domain constraints are introduced as distinct concepts only where independent semantic responsibility is demonstrated.

## Canonical nucleus

The active nucleus is registered in `QUANTITY-INDEX.md` and includes the generic Quantity concept together with the currently admitted domain quantities: Distance, Temperature, Focal Length, Wavelength, Exposure Time, Illuminance, Luminance, Radiance, Irradiance and Spatial Frequency.

## Candidate and deferred knowledge

Controlled candidates and deferred concepts remain explicitly retained. They are not promoted merely because they are numerical, measurable, commonly reported, or important in a domain.

## Core boundaries

`Quantity ≠ Quantity Value`  
`Quantity ≠ Unit`  
`Quantity ≠ Measurement`  
`Quantity ≠ Measurement Result`  
`Quantity ≠ Property`  
`Quantity ≠ State`  
`Quantity ≠ Condition`  
`Quantity ≠ Relation`  
`Quantity ≠ Result`

A quantity may quantify a property, state, condition or other semantic element without becoming identical to it.

## Validation and lifecycle

The current nucleus is closed at its present scope. Identity, duplicate authority, boundary, evidence, relation authority, Visitor Universe, retrieval, lifecycle and cross-layer checks are recorded in `QUANTITY-FOLDER-CLOSURE-AUDIT.md`.

Future Quantity additions require candidate-specific semantic validation and explicit promotion.

## Visitor Universe

The same canonical Quantity knowledge is available at different entry depths. Visitor categories do not create alternate Quantity identities or audience-specific semantic definitions.

## Retrieval anchors

`QUANTITY`, `MEASURABLE QUANTITY`, `PHYSICAL QUANTITY`, `MEASURABLE ASPECT`, `QUANTITY CONCEPT`, `QUANTITY VALUE`, `QUANTITY KIND`, `QUANTITY DIMENSION`, `UNIT`, `MEASUREMENT`, `MEASUREMENT RESULT`
