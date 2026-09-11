# GIOP Property Research — Retained Candidate Registry

## Purpose

This registry preserves the recovered Property research corpus while separating semantic classification from canonical admission to `properties/`.

This file is an index and decision record. It is **not** the canonical Property vocabulary.

The working recovery pipeline is:

`RECOVERED KNOWLEDGE → CLASSIFY → VERIFY → RECONCILE → SEMANTICALLY SYNTHESIZE → CANONICALIZE`

A term remains retained even when routed away from the Property layer or deferred.

## Retained Candidate Index

| Term | Epistemic | Semantic type | Property-layer decision | Destination / note |
|---|---|---|---|---|
| optical-distortion | VERIFIED | PROPERTY | CANONICAL | `properties/optical-distortion.md` |
| chromatic-aberration | VERIFIED | PROPERTY | CANONICAL | `properties/chromatic-aberration.md` |
| spectral-response | VERIFIED | PROPERTY | CANONICAL | `properties/spectral-response.md` |
| sensitivity | VERIFIED | PROPERTY | CANONICAL | `properties/sensitivity.md` |
| linearity | VERIFIED | PROPERTY | CANONICAL | `properties/linearity.md` |
| transparency | VERIFIED | PROPERTY | CANONICAL | `properties/transparency.md` |
| chromaticity | VERIFIED | PROPERTY | CANONICAL | `properties/chromaticity.md` |
| dynamic-range-characteristic | VERIFIED | PROPERTY CANDIDATE | CANONICAL CANDIDATE | exact canonical wording still under reconciliation |
| focal-length | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/`; no Property duplication |
| optical-power | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| responsivity | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| quantum-efficiency | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| field-of-view | VERIFIED / boundary pending | QUANTITY / deferred | DEFERRED | quantity destination pending |
| reflectance | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| transmittance | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| noise | UNDER VERIFICATION | CONCEPT / FAMILY | DEFERRED | hierarchy reconciliation required |
| noise-level | VERIFIED | QUANTITY | NOT PROPERTY | future `quantities/` |
| resolution | VERIFIED | MEASUREMENT / QUANTITY CONCEPT | DEFERRED | measurement-oriented; not a Property seed |
| sharpness | UNDER VERIFICATION | PROPERTY / MEASUREMENT BOUNDARY | DEFERRED | further reconciliation required |
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
| scattering-characteristic | UNDER VERIFICATION | PROPERTY CANDIDATE | DEFERRED | reconciliation required |
| noise-characteristic | UNDER VERIFICATION | PROPERTY CANDIDATE | DEFERRED | hierarchy reconciliation required |
| surface-roughness | UNDER VERIFICATION | PROPERTY / SURFACE-TEXTURE HIERARCHY | DEFERRED | texture/roughness/waviness boundary unresolved |
| dynamic-range | VERIFIED | QUANTITY / PERFORMANCE MEASURE | NOT PROPERTY | quantitative realization |

## Current Canonical Property Seed

The verified Property seed currently published in `properties/` is:

1. `optical-distortion`
2. `chromatic-aberration`
3. `spectral-response`
4. `sensitivity`
5. `linearity`
6. `transparency`
7. `chromaticity`

`dynamic-range-characteristic` remains a controlled candidate and is not yet published.

## Interpretive Rules

### Verified does not mean canonical

Verification concerns evidential support for the recorded concept or semantic interpretation. Canonicalization is a separate GIOP decision.

### Excluded from Property does not mean discarded

Every row is retained knowledge. `NOT PROPERTY` and `DEFERRED` are routing decisions, not deletion.

### Deferred is active

A deferred concept remains discoverable and may later be promoted without reconstructing the original research.

### Families require hierarchy

`noise`, `resolution`, `scattering`, `surface-roughness`, and `colorimetric-characteristic` may cover families rather than atomic Properties. Vocabulary coverage must not be created by prematurely splitting unresolved families into many canonical files.

### Quantitative realization remains separate

Characteristic concepts and their numerical quantities, values, measurement results, formulas, and thresholds remain distinct semantic objects.

## Explicitly Protected Knowledge

The following remain intentionally retained outside the current Property seed: optical power, responsivity, quantum efficiency, field of view, reflectance, transmittance, noise, noise level, resolution, sharpness, exposure, accuracy, precision, calibration status, calibration, measurement, measurement result, capability, scattering, aperture, appearance, colorimetric characteristics, scattering characteristics, noise characteristics, surface roughness, and dynamic range.

Their absence from `properties/` is an intentional semantic routing decision.
