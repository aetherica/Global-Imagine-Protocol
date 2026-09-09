# GIOP V3.1 — V3 → V4 Migration Mapping Manifest

Status: WORKING BASELINE
Source baseline: GIOP v3.0 on main
Target architecture: approved GIOP V4.0 27-root architecture
Scope: mapping only; no V3 source migration is performed by this manifest.

## 1. Preservation Rules

1. The V3 baseline remains intact on main.
2. Existing V3 source artifacts are not deleted or overwritten by mapping work.
3. V4 responsibility roots are architectural boundaries, not semantic identities.
4. SEMANTICS and REGISTRY are the canonical semantic/identity boundary.
5. A single canonical entity may have multiple responsibility views.
6. Historical V3 material remains preservable under 27 LEGACY/v3/.
7. Generated, API, SDK, site, and docs surfaces are projections or operational interfaces.
8. New responsibility roots are not introduced by migration.

## 2. Primary V3 → V4 Responsibility Map

| V3 surface | Primary V4 destination | Secondary V4 views | Disposition |
|---|---|---|---|
| Master Manifest and Architecture Map | 01 FOUNDATION/architecture | 03 REGISTRY, 27 LEGACY/v3 | preserve source; derive architecture reference |
| kingdoms/Science of Light | 04 PHYSICS | 05 OPTICS, 02 SEMANTICS, 21 RESEARCH | decompose by responsibility |
| kingdoms/Human Vision vs Camera and Lens | 12 VISION | 05 OPTICS, 02 SEMANTICS | decompose; no single-folder equivalence |
| kingdoms/Fundamental Imaging Physics and Sensor Metrology | 06 SENSOR-SCIENCE | 04 PHYSICS, 21 RESEARCH | decompose |
| kingdoms/Color Science and Visual Perception | 02 SEMANTICS | 10 COMPUTATION, 12 VISION, 22 STANDARDS | separate meaning, transforms, perception, provenance |
| kingdoms/Physics and Mathematics for Imaging | 04 PHYSICS | 05 OPTICS, 10 COMPUTATION | decompose |
| kingdoms/Sensor, Lens Hardware and ISP Pipeline | 06 SENSOR-SCIENCE | 07 CAPTURE, 08 LENS-SYSTEMS, 23 ENGINEERING | decompose |
| kingdoms/AI Foundation | 11 AI | 12 VISION, 21 RESEARCH | decompose |
| kingdoms/Neural Foundation | 11 AI | 09 REPRESENTATION, 10 COMPUTATION | decompose |
| kingdoms/Video Engineering and Broadcast Standards | 18 MEDIA | 22 STANDARDS, 10 COMPUTATION | separate media engineering from standards |
| kingdoms/Immersive Formats and Metadata Standards | 17 IMMERSIVE | 18 MEDIA, 22 STANDARDS, 03 REGISTRY | decompose |
| kingdoms/Immersive and Volumetric Capture | 07 CAPTURE | 09 REPRESENTATION, 17 IMMERSIVE | decompose |
| kingdoms/Spatial Computing | 17 IMMERSIVE | 24 RUNTIME, 20 SENSOR-ECOSYSTEM | decompose |
| bodies/ | 03 REGISTRY/devices | 06 SENSOR-SCIENCE, 07 CAPTURE | identity in registry; scientific/capture views elsewhere |
| lenses/ | 08 LENS-SYSTEMS | 03 REGISTRY/products, 05 OPTICS | identity and optical responsibility separated |
| displays/ | 19 DISPLAY | 03 REGISTRY/devices/products, 22 STANDARDS | display profile remains a view of canonical identity |
| computing/ | 24 RUNTIME/compute | 23 ENGINEERING, 03 REGISTRY/components | silicon identity separated from runtime use |
| formulas/ | 03 REGISTRY/formulas | 02 SEMANTICS, 10 COMPUTATION, 22 STANDARDS | distinguish formula identity, meaning, implementation, source |
| software/ | 23 ENGINEERING | 24 RUNTIME, 03 REGISTRY/products | implementation/integration surface |
| standards/ | 22 STANDARDS | 03 REGISTRY/standards, 21 RESEARCH | preserve source provenance |
| runtime/ | 24 RUNTIME | 23 ENGINEERING, 03 REGISTRY | primary operational contract |
| legacy/ | 27 LEGACY | 21 RESEARCH | historical preservation; no silent deletion |

## 3. Canonical Entity Handling

Camera body:
03 REGISTRY/devices/ → canonical identity
06 SENSOR-SCIENCE/ → sensor characterization
07 CAPTURE/ → acquisition role
02 SEMANTICS/ → properties, states, relations, metadata semantics

Lens:
03 REGISTRY/products/ or devices/ → canonical identity
08 LENS-SYSTEMS/ → optical-system responsibility
05 OPTICS/ → physical/optical models
02 SEMANTICS/ → optical properties and relations

Formula:
03 REGISTRY/formulas/ → canonical registered formula identity
02 SEMANTICS/ → mathematical meaning and relationships
10 COMPUTATION/ → implementation/transform usage
22 STANDARDS/ → external normative provenance where applicable

Display:
03 REGISTRY/devices/products/ → identity
19 DISPLAY/ → characterization and calibration
22 STANDARDS/ → conformance and standards relations

## 4. Migration Priority

Phase A — structural baseline
- approved 27-root scaffold
- supporting infrastructure surfaces
- preservation of main/V3

Phase B — mapping
- artifact inventory
- canonical entity identification
- V3 → V4 responsibility classification
- legacy classification
- provenance/claim classification

Phase C — semantic preparation
- ontology classes/properties/relations
- registry identity records
- schema definitions
- migration validation tests

Phase D — controlled content migration
- migrate only after mapping is validated
- retain V3 provenance
- retain superseded/historical material
- validate cross-references

Phase E — V4 implementation
- API/SDK/site projections
- runtime/engineering implementation
- automated conformance and regression

## 5. Current V3 Artifacts Requiring Special Review

- ALEXA 35 body profile: contains identity, LogC4, AWG4, matrix, white balance, ISO, dual-gain, metadata and validation in one artifact. It must be decomposed without creating duplicate canonical truths.
- Generic anamorphic characteristics: combines optical geometry, flare spectral characteristics, distortion, bokeh and breathing; primary destination is LENS-SYSTEMS with linked OPTICS semantics.
- Color Science Standards: contains normative color equations; formula identity, computation, and standards provenance must be separated.
- Runtime Specification: contains kernel, IPC, plugins, scheduling, resource management, fault tolerance, configuration, observability and compatibility; primary destination is RUNTIME.
- Legacy/Settings/Fault Tolerance: historical chronology and operational guardrails must remain distinguishable; historical content is not automatically current normative truth.

## 6. Non-Goals for This Stage

This manifest does not:
- delete V3 files;
- rewrite V3 mathematical content;
- certify the factual correctness of every V3 claim;
- perform full ontology instantiation;
- migrate every V3 artifact into its final V4 location;
- create new responsibility roots.

## 7. Acceptance Criteria

A V3 artifact is migration-ready only when:
- its canonical identity is known or explicitly unresolved;
- its primary responsibility is assigned;
- secondary views are recorded;
- provenance is retained;
- legacy disposition is recorded;
- validation requirements are identified;
- no duplicate semantic authority is introduced.

