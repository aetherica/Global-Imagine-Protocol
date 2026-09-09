# GIOP V3.1 — V3 Artifact Register

Status: WORKING MIGRATION REGISTER
Source: GIOP v3.0 specification and current main repository.
Purpose: record intended disposition of V3 artifacts before controlled content migration.

## Artifact classes

| V3 artifact class | V3 role | V4 primary home | Treatment |
|---|---|---|---|
| Master Manifest and Architecture Map | protocol architecture and mandate | 01 FOUNDATION/architecture | preserve V3 source; derive V4 references |
| Kingdom 00 — Science of Light | physical light foundation | 04 PHYSICS | decompose physics/optics/semantic concepts |
| Kingdom 01 — Human Vision vs Camera and Lens | HVS and perceptual imaging | 12 VISION | decompose perceptual/optical/semantic material |
| Kingdom 02 — Fundamental Imaging Physics and Sensor Metrology | sensor physics/metrology | 06 SENSOR-SCIENCE | decompose metrology, noise, exposure, sampling |
| Kingdom 03 — Color Science and Visual Perception | color science and perception | 02 SEMANTICS | separate semantic definitions, computation, perception, standards |
| Kingdom 04 — Physics and Mathematics for Imaging | imaging mathematics/physical models | 04 PHYSICS | computational implementations map to 10 COMPUTATION |
| Kingdom 05 — Sensor, Lens Hardware and ISP Pipeline | sensor, ISP, lens, stabilization | 06 SENSOR-SCIENCE | split capture, optics, engineering responsibilities |
| Kingdom 06 — AI Foundation | AI architectures and governance | 11 AI | separate research, standards, trust views |
| Kingdom 07 — Neural Foundation | neural representations/rendering | 11 AI | representation models also map to 09 REPRESENTATION |
| Kingdom 08 — Video Engineering and Broadcast Standards | codec, transport, sync, QC | 18 MEDIA | standards map to 22 STANDARDS |
| Kingdom 09 — Immersive Formats and Metadata Standards | immersive metadata and formats | 17 IMMERSIVE | split media, standards and registry views |
| Kingdom 10 — Immersive and Volumetric Capture | volumetric capture/reconstruction | 07 CAPTURE | representations map to 09 REPRESENTATION |
| Kingdom 11 — Spatial Computing | HMD/spatial rendering/transport | 17 IMMERSIVE | runtime/connected-system views split |
| Runtime Specification | runtime contract | 24 RUNTIME | preserve V3 source; decompose requirements |
| Legacy, Settings Parameters and Fault Tolerance | history, settings, guardrails, faults | 27 LEGACY | preserve history; classify current guardrails |

## Domain catalogue register

Camera bodies: canonical device identity → 03 REGISTRY/devices; sensor characterization → 06 SENSOR-SCIENCE; acquisition role → 07 CAPTURE.

Lenses: canonical product/device identity → 03 REGISTRY; optical-system responsibility → 08 LENS-SYSTEMS; physical optical models → 05 OPTICS.

Formulas: registered formula identity → 03 REGISTRY/formulas; semantic definitions → 02 SEMANTICS; implementation → 10 COMPUTATION; normative provenance → 22 STANDARDS.

Displays: canonical identity → 03 REGISTRY/devices or products; characterization/calibration → 19 DISPLAY; conformance → 22 STANDARDS.

Computing: canonical component identity → 03 REGISTRY/components; runtime compute profiles → 24 RUNTIME/compute; engineering integration → 23 ENGINEERING.

Software: vendor/product identity → 03 REGISTRY/products; integration/reference implementation → 23 ENGINEERING; runtime behavior → 24 RUNTIME.

Standards: primary home → 22 STANDARDS; canonical standard identity → 03 REGISTRY/standards; verification → 21 RESEARCH/evidence and validation.

## Special compound artifacts

ALEXA 35 body profile: identity, sensor, LogC4, AWG4/ACES matrices, white balance, ISO/dual gain, metadata, validation. Decompose by responsibility; never duplicate canonical identity.

Generic anamorphic characteristics: squeeze/desqueeze, bokeh, spectral streak, distortion, breathing. Primary → 08 LENS-SYSTEMS; linked models → 05 OPTICS; transforms → 10 COMPUTATION.

Color Science Standards: PQ, HLG, ACES AP1, luminance, CIEDE2000, Dolby Vision mapping. Separate registered formula identity, semantic meaning, implementation, and standards provenance.

Runtime Specification: kernel, IPC, events, plugins, resource management, scheduling, faults, configuration, observability, compatibility. Primary → 24 RUNTIME; implementation → 23 ENGINEERING; integrity/security → 26 TRUST.

Legacy/Settings/Fault Tolerance: historical chronology plus operational guardrails. Historical portions remain in 27 LEGACY; current normative material requires explicit classification before promotion.

## Migration state vocabulary

PRESERVE-V3 = V3 artifact remains source/historical material.
MAP-ONLY = destination assigned; no content move.
DECOMPOSE = compound artifact contains multiple V4 responsibilities.
PROMOTE-CANONICAL = validated semantic or identity fragment becomes canonical.
PROJECT = derived documentation/API/site/SDK representation.
LEGACY-PRESERVE = retain historical or superseded material.
REVIEW-REQUIRED = validation needed before promotion.

## Current rule

Assigning a destination path does not constitute migration. Content promotion requires canonical identity, responsibility, provenance, validation requirements, and legacy disposition.
