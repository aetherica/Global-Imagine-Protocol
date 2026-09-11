# GIOP Property Research — Retained Candidate Registry

## Purpose

This registry preserves the recovered Property research corpus while separating semantic classification from canonical admission to `properties/`.

This file is an index and decision record. It is **not** the canonical Property vocabulary.

The current working principle is:

`RECOVERED KNOWLEDGE → CLASSIFY → VERIFY → RECONCILE → CANONICALIZE`

A term can therefore remain fully retained even when it is routed away from the Property layer or deferred.

## Decision Dimensions

- **Epistemic**: current evidence status.
- **Semantic type**: current semantic destination or best current classification.
- **Canonical decision**: whether the concept belongs in the canonical Property layer.
- **Destination**: intended or provisional next layer.

## Retained Candidate Index

| Term | Epistemic | Semantic type | Property-layer decision | Destination / note |
|---|---|---|---|---|
| optical-distortion | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; measurement boundary retained |
| chromatic-aberration | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; quantitative measurements remain separate |
| spectral-response | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; response curves/values are quantitative realizations |
| sensitivity | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; specific coefficients/thresholds remain quantitative |
| linearity | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; linearity error remains a quantitative measurement |
| transparency | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/` |
| chromaticity | VERIFIED | PROPERTY | CANONICAL CANDIDATE | `properties/`; coordinates/values remain quantitative |
| dynamic-range-characteristic | VERIFIED | PROPERTY CANDIDATE | CANONICAL CANDIDATE | `properties/` only as a characteristic abstraction |
| focal-length | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/`; do not duplicate as Property |
| optical-power | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| responsivity | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| quantum-efficiency | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| field-of-view | VERIFIED / boundary pending | QUANTITY / deferred | DEFERRED | `quantities/` or future reconciled destination |
| reflectance | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| transmittance | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| noise | UNDER VERIFICATION | CONCEPT / FAMILY | DEFERRED | requires hierarchy reconciliation |
| noise-level | VERIFIED | QUANTITY | NOT PROPERTY | `quantities/` |
| resolution | VERIFIED | MEASUREMENT / QUANTITY CONCEPT | DEFERRED | not admitted as Property; measurement-oriented |
| sharpness | UNDER VERIFICATION | PROPERTY / MEASUREMENT BOUNDARY | DEFERRED | requires semantic reconciliation |
| exposure | UNDER VERIFICATION | QUANTITY / PROCESS / CONDITION | DEFERRED | boundary unresolved |
| accuracy | VERIFIED | MEASUREMENT CONCEPT | NOT PROPERTY | measurement domain |
| precision | VERIFIED | MEASUREMENT CONCEPT | NOT PROPERTY | measurement domain |
| calibration-status | VERIFIED | STATE / STATUS | NOT PROPERTY | states/statuses |
| calibration | VERIFIED | ACTIVITY / PROCESS | NOT PROPERTY | activities/processes |
| measurement | VERIFIED | ACTIVITY | NOT PROPERTY | activities/processes |
| measurement-result | VERIFIED | RESULT | NOT PROPERTY | results |
| capability | VERIFIED | CAPABILITY | NOT PROPERTY | separate semantic category |
| scattering | VERIFIED | PHENOMENON / PROCESS | DEFERRED | characteristic form deferred |
| aperture | UNDER VERIFICATION | DEFERRED | DEFERRED | semantic destination pending |
| appearance | UNDER VERIFICATION | DEFERRED | DEFERRED | semantic destination pending |
| colorimetric-characteristic | VERIFIED | PROPERTY FAMILY | DEFERRED FOR SEED | controlled expansion later |
| scattering-characteristic | UNDER VERIFICATION | PROPERTY CANDIDATE | DEFERRED | requires further reconciliation |
| noise-characteristic | UNDER VERIFICATION | PROPERTY CANDIDATE | DEFERRED | requires hierarchy reconciliation |
| surface-roughness | UNDER VERIFICATION | PROPERTY / SURFACE-TEXTURE HIERARCHY | DEFERRED | broader texture/roughness/waviness boundary unresolved |
| dynamic-range | VERIFIED | QUANTITY / PERFORMANCE MEASURE | NOT PROPERTY | quantitative realization; characteristic abstraction handled separately |
| transmittance | VERIFIED | QUANTITY | NOT PROPERTY | ratio-based quantitative concept |

## Interpretive Rules

### Verified does not mean canonical

Verification records the evidential status of the concept or interpretation. Canonicalization is a separate GIOP decision.

### Excluded from Property does not mean discarded

Every row in this registry is retained knowledge. A row marked `NOT PROPERTY` or `DEFERRED` remains searchable and auditable.

### Deferred is an active state

`DEFERRED` means that GIOP is deliberately preserving the concept while withholding a final canonical placement or seed admission. Deferred records may later be promoted without reconstructing the original research.

### Families require hierarchy before expansion

Terms such as `noise`, `resolution`, `scattering`, `surface roughness`, and `colorimetric-characteristic` may represent families of related concepts rather than one atomic canonical Property. They MUST NOT be split into numerous Property files merely to preserve vocabulary coverage.

### Quantitative realization remains separate

Where a technical concept has a measurable magnitude, the registry preserves the distinction between a characteristic abstraction and its quantity, value, measurement result, formula, or threshold.

Examples:

- `dynamic-range-characteristic` → Property candidate; `dynamic-range` → quantitative realization.
- `chromaticity` → Property; chromaticity coordinates → quantitative realization.
- `spectral-response` → Property; response curve values → quantitative realization.

## Current Canonical Property Seed

The current verified Property seed emerging from this registry is:

1. `optical-distortion`
2. `chromatic-aberration`
3. `spectral-response`
4. `sensitivity`
5. `linearity`
6. `transparency`
7. `chromaticity`

`dynamic-range-characteristic` remains a controlled Property candidate whose exact canonical wording should be settled during Property Layer Specification rather than prematurely creating a conflicting quantitative entry.

## Explicitly Protected Knowledge

The following concepts are intentionally protected from deletion even though they are not current Property entries:

- optical power
- responsivity
- quantum efficiency
- field of view
- reflectance
- transmittance
- noise
- noise level
- resolution
- sharpness
- exposure
- accuracy
- precision
- calibration status
- calibration
- measurement
- measurement result
- capability
- scattering
- aperture
- appearance
- colorimetric characteristics
- scattering characteristics
- noise characteristics
- surface roughness
- dynamic range

Their presence in this registry means that the knowledge has been retained; their absence from `properties/` is an intentional semantic routing decision.

## Future Promotion Rule

Promotion from this registry to a canonical semantic layer requires, at minimum:

1. stable identity;
2. explicit semantic classification;
3. adequate evidence for the relevant claim;
4. resolved or explicitly bounded conflicts;
5. clear layer boundary;
6. GIOP semantic synthesis rather than source copying;
7. canonical destination decision.

Only then should an individual canonical semantic document be created or updated.
