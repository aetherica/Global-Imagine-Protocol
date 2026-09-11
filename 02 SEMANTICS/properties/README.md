# GIOP Canonical Properties

## Purpose

The `properties/` directory contains canonical GIOP semantic concepts describing characteristics attributable to eligible entities or concepts.

A Property is not a class, quantity, value, state, condition, relation, activity, process, measurement result, or implementation claim.

## Canonical Boundary

`ENTITY TYPE → CLASS`

`CHARACTERISTIC → PROPERTY`

`MEASURABLE CONCEPT → QUANTITY`

`VALUE / MEASUREMENT RESULT → VALUE / RESULT`

`STATE / STATUS → STATE / STATUS`

`ACTION → ACTIVITY`

`TRANSFORMATION → PROCESS`

## Current Seed Vocabulary

The initial verified seed consists of:

- `optical-distortion`
- `chromatic-aberration`
- `spectral-response`
- `sensitivity`
- `linearity`
- `transparency`
- `chromaticity`

`dynamic-range-characteristic` remains a controlled candidate pending final wording reconciliation.

## Quantification Boundary

A Property may have quantitative realizations, but the Property document does not become a value or measurement record merely because the characteristic is measurable.

Examples:

- spectral response → wavelength-dependent response values;
- chromaticity → chromaticity coordinates;
- linearity → linearity error or other measurement-derived quantities;
- sensitivity → sensitivity coefficient or threshold;
- optical distortion → measured distortion parameters.

## Knowledge Retention

Important technical terms that are not canonical Property entries are not discarded. They are retained in `../registry/`, with their epistemic status, semantic classification, evidence, and destination decision.

Thus:

`VERIFIED ≠ CANONICAL`

and:

`NOT A PROPERTY ≠ NOT KNOWLEDGE`

## Authoring Rule

Canonical Property pages are semantic syntheses. External standards and technical literature provide evidence; source wording is not copied as the GIOP definition.

Each Property page should preserve stable identity, definition, bearer/applicability, distinctions, quantification boundary, evidence/provenance, relations, machine interpretation, lifecycle, and semantic boundary.
