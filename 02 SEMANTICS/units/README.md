# Units

**Semantic Layer:** Unit
**Version:** 3.1
**Status:** IMPLEMENTATION-COMPLETE — V3.1 CANDIDATE NUCLEUS
**Primary Responsibility:** Measurement-unit semantics and system organization
**Branch:** `v3.1-tree-architecture`

## What

The Unit semantic layer defines reusable concepts for measurement units: conventionally governed reference quantities used to express quantity values, together with the system-level organization needed to distinguish base, derived, and coherent derived units.

## Structure

`Quantity Concept → Quantity Value → Unit → Measurement / Establishment → Measurement Result → Representation`

A Unit is the reference structure used to express a quantity value. It is not the quantity being measured, the numerical value, the measurement activity, or the recorded result.

## Core nucleus

- `SEM-UNIT-GENERIC-001` — Unit
- `SEM-UNIT-BASE-001` — Base Unit
- `SEM-UNIT-DERIVED-001` — Derived Unit
- `SEM-UNIT-COHERENT-DERIVED-001` — Coherent Derived Unit
- `SEM-UNIT-SYSTEM-001` — System of Units

These are authored as a V3.1 candidate nucleus. Canonical promotion remains subject to cross-layer validation and Gate-J.

## Controlled supporting scope

Unit composition, multiples/submultiples, prefixes, conversion relationships, unit symbols and codes are retained as supporting or controlled candidate concerns. They are not silently promoted to independent canonical semantic classes.

## Boundaries

`Unit ≠ Quantity`
`Unit ≠ Quantity Value`
`Unit ≠ Quantity Dimension`
`Unit ≠ Measurement`
`Unit ≠ Measurement Result`
`Unit ≠ Measuring Instrument`
`Unit ≠ Unit Symbol`
`Unit ≠ Unit Code`
`Unit ≠ Prefix`
`Unit ≠ Conversion`

Quantity Dimension remains owned by the Quantity layer. Symbols, codes and expressions are representational/structural forms rather than alternate Unit identities.

## Visitor Universe

Visitor depth changes orientation and retrieval only; it does not create alternate Unit identities or audience-specific definitions.

## Lifecycle

Core entries are implementation-complete candidate knowledge. Future additions require candidate-specific semantic validation, boundary synchronization, evidence review, and explicit promotion.

## Retrieval anchors

`UNIT`, `MEASUREMENT UNIT`, `UNIT OF MEASUREMENT`, `BASE UNIT`, `DERIVED UNIT`, `COHERENT DERIVED UNIT`, `SYSTEM OF UNITS`, `UNIT SYMBOL`, `UNIT CODE`, `UNIT CONVERSION`
