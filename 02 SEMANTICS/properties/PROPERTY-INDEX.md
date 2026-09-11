# GIOP Canonical Property Index

## Status

**CANONICAL**

This index lists the current canonical Property vocabulary published in `02 SEMANTICS/properties/`.

## Canonical Property Set

| ID | Property | Status | Primary semantic boundary |
|---|---|---|---|
| SEM-PROPERTY-OPTICAL-DISTORTION-001 | Optical Distortion | CANONICAL | characteristic vs measured distortion quantity/result |
| SEM-PROPERTY-CHROMATIC-ABERRATION-001 | Chromatic Aberration | CANONICAL | characteristic vs measured aberration parameters |
| SEM-PROPERTY-SPECTRAL-RESPONSE-001 | Spectral Response | CANONICAL | characteristic vs response curve/values |
| SEM-PROPERTY-SENSITIVITY-001 | Sensitivity | CANONICAL | characteristic vs sensitivity quantity/value |
| SEM-PROPERTY-LINEARITY-001 | Linearity | CANONICAL | characteristic vs linearity error/result |
| SEM-PROPERTY-TRANSPARENCY-001 | Transparency | CANONICAL | physical characteristic vs transmittance/clarity/perception |
| SEM-PROPERTY-CHROMATICITY-001 | Chromaticity | CANONICAL | colour-stimulus property vs coordinates/values |
| SEM-PROPERTY-DYNAMIC-RANGE-CHARACTERISTIC-001 | Dynamic-Range Characteristic | CANONICAL | characteristic vs dynamic-range quantitative realization |

## Scope

The Property layer contains reusable characteristic concepts. It does not function as a catalogue of all important technical terms in imaging.

Terms that are quantitative, process-oriented, state-oriented, result-oriented, measurement-specific, unresolved, or otherwise outside the Property boundary remain retained in the GIOP semantic registry and are routed to the appropriate layer when that layer is canonicalized.

## Current Exclusions From the Property Layer

Examples intentionally not duplicated here include:

- focal length;
- optical power;
- responsivity;
- quantum efficiency;
- field of view;
- reflectance;
- transmittance;
- noise level;
- resolution;
- accuracy;
- precision;
- calibration;
- measurement;
- measurement result.

These are retained as evaluated knowledge through the semantic registry and their declared destination semantics.

## Canonicalization Rule

A term may enter this index only when:

1. its semantic identity is sufficiently established;
2. its Property-level abstraction is distinct from quantitative values and measurement results;
3. its bearer and applicability are defined;
4. adjacent semantic boundaries are explicit;
5. the GIOP definition is an independent semantic synthesis rather than copied source wording.

## Relation to Registry

The registry remains the evidence and decision-retention mechanism. The index is the authoritative published Property surface.

`registry → verification and routing`

`properties → canonical semantic publication`
