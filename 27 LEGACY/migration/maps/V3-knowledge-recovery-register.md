# GIOP V3.2.1 — V3 Knowledge Recovery Register

**Status:** RECOVERY COMPLETE — VERIFICATION PENDING  
**Purpose:** Recover the substantive knowledge contained in the V3 corpus before gap analysis, external research, and canonical semantic authoring.  
**Source corpus:** `Untitled document.docx` (V3, 82 pages)  
**Target:** `02 SEMANTICS` of GIOP V3.2.1  
**Recovery boundary:** knowledge recovery only. No recovered statement is promoted here to canonical truth.

## 1. Recovery Completion Rule

Step 3 is considered complete when the V3 corpus has been traversed at the level of its substantive sections, Kingdom sub-domains, formula/model groups, catalogue groups, standards references, implementation material, and historical/legacy material, and each recovered block has a declared knowledge fate for later processing.

This is **not** a claim that every V3 sentence has already been scientifically re-verified. Verification belongs to the next stages. Recovery answers: **What knowledge exists in V3, where is it, what kind of knowledge is it, and what must happen to it before canonicalization?**

## 2. Knowledge Classification Vocabulary

- **CONCEPT** — what a thing, phenomenon, system, or abstraction means.
- **CLASS** — a category whose members share semantic characteristics.
- **INSTANCE / ENTITY** — a concrete identified object, product, device, software item, or named occurrence.
- **PROPERTY** — a characteristic that can be attributed to an entity or concept.
- **QUANTITY** — a measurable magnitude with a unit or defined scale.
- **VALUE** — a concrete numerical, categorical, or enumerated value.
- **MODEL** — a mathematical, computational, physical, perceptual, or conceptual model.
- **FORMULA** — an explicit mathematical expression expressing a relationship or transform.
- **PROCESS** — acquisition, transformation, computation, reconstruction, encoding, rendering, or other operation.
- **RELATION** — dependency, correspondence, containment, transformation, comparison, causation, or other typed connection.
- **REPRESENTATION** — a form in which information, signal, scene, image, geometry, or metadata is encoded.
- **CONDITION** — a circumstance or validity domain under which a statement applies.
- **STATE** — a condition of a system, object, signal, or process at a point or interval.
- **STATUS** — a lifecycle or operational classification.
- **CLAIM** — factual, empirical, historical, normative, or implementation assertion requiring evidence or authority.
- **STANDARD** — external specification, standard, recommendation, or normative reference.
- **IMPLEMENTATION** — concrete engineering/runtime/tool/vendor behavior.
- **WORKFLOW** — task-oriented operational sequence or practice.
- **HISTORICAL** — chronology, origin, predecessor, legacy, or archival fact.
- **POLICY / GOVERNANCE** — project-level normative material; not semantic domain meaning.

## 3. V3 Corpus Recovery — Section 1

### S01 — Master Manifest / Architecture Map

**Recovered knowledge:** GIOP identity, purpose, deployment model, user scope, end-to-end imaging chain, problem statement, twelve Kingdom model, domain catalogues, formula catalogue, standards list, maturity levels, professional tiers, proof-chain statement, versioning model, licensing model, governance model, extension concept, and package structure. V3 describes a verifiable frame chain from photon → lens → electrons → linearization → scene-referred space → artistic intent → display transform → emitted light. fileciteturn300file7L526-L540

**Classification:** CONCEPT, RELATION, MODEL, CLAIM, STANDARD, POLICY / GOVERNANCE, IMPLEMENTATION, HISTORICAL.

**Recovery treatment:** split protocol identity/purpose from domain knowledge; split governance, licensing, proof-chain, and runtime claims from semantic content; preserve original statements for later verification.

## 4. K00 — Science of Light

**Recovered sub-domains:** Nature of Light; Light Transport; Measurement; Spectral Formation; Surface Interaction; Scattering Media. V3 positions this as the pre-sensor physical-light layer. fileciteturn300file5L392-L413

**Recovered knowledge:** electromagnetic radiation; wave/photon descriptions; photon energy and wavelength/frequency relationships; propagation in free space; electric/magnetic field relationships; polarization states; Snell/Fresnel-type optical relations; radiometry and photometry; radiant/photometric quantities and units; spectral power distribution; spectral/color stimulus formation; reflectance and transmittance; BRDF and BSSRDF; participating media and scattering; volumetric light transport; physical-light versus perceived-light relationships.

**Classification:** CONCEPT, CLASS, QUANTITY, UNIT, VALUE, FORMULA, MODEL, RELATION, CONDITION, CLAIM.

**Later destinations:** `ontology/`, `classes/`, `quantities/`, `units/`, `values/`, `properties/`, `relations/`, `material/`, `spatial/`, `models/`, `conditions/`.

**Recovery treatment:** preserve physical equations with assumptions, validity, units, and source context. Do not copy the Kingdom as one semantic record.

## 5. K01 — Human Vision vs Camera and Lens

**Recovered knowledge:** human visual system; rods/cones; luminance adaptation; dynamic-range comparison; spectral sensitivity mismatch; metamerism; viewing/perceptual conditions; Weber–Fechner reference; OETF/EOTF; tone mapping; color appearance models; perceptual rationale for imaging transforms.

**Classification:** CONCEPT, CLASS, OBSERVER-RELATED MODEL, PROPERTY, CONDITION, STATE, FORMULA, RELATION, CLAIM.

**Later destinations:** `observers/`, `perception/`, `models/`, `conditions/`, `contexts/`, `states/`, `color/`, `temporal/`, `relations/`.

**Recovery treatment:** separate human-observer concepts from camera transformations and from comparative claims about eye versus sensor.

## 6. K02 — Fundamental Imaging Physics and Sensor Metrology

**Recovered knowledge:** photon statistics; shot noise; read noise; signal-to-noise ratio; exposure; saturation; ISO interpretation; dual-native-ISO model; radiometric/photometric units; measurement procedures; sensor response; metrology concepts; geometric invariance.

**Classification:** CONCEPT, QUANTITY, VALUE, UNIT, MODEL, FORMULA, CONDITION, PROPERTY, CLAIM.

**Later destinations:** `ontology/`, `quantities/`, `units/`, `values/`, `properties/`, `models/`, `conditions/`, `relations/`.

**Recovery treatment:** preserve distinctions among physical sensitivity, exposure setting, measured value, nominal ISO, and implementation/vendor labels. Recover each formula with variable definitions and validity conditions.

## 7. K03 — Color Science and Visual Perception

**Recovered knowledge:** ACES framework references; gamut and gamut compression; ST 2084/PQ; CIE color metrics; CIEDE2000; CAM16-UCS; ICtCp; JzAzBz; camera color response; spectral/LUT modelling; white-point adaptation; skin-tone preservation; color-fairness considerations; color appearance and reproduction relationships.

**Classification:** CONCEPT, CLASS, QUANTITY, MODEL, FORMULA, PROCESS, REPRESENTATION, RELATION, CONDITION, CLAIM, STANDARD.

**Later destinations:** `color/`, `perception/`, `models/`, `quantities/`, `properties/`, `contexts/`, `conditions/`, `relations/`, `representations/`.

**Recovery treatment:** distinguish physical color stimulus, colorimetric quantity, perceptual appearance, color-space representation, transform, metric, and policy/quality claim.

## 8. K04 — Physics and Mathematics for Imaging

**Recovered knowledge:** Cook–Torrance; GGX; Schlick Fresnel; diffraction; interference; polarization; Snell's law; lens-maker relationships; statistical image analysis; illumination; energy conservation; geometric invariance; Fourier analysis; spectral rendering; biological/face modelling; fabric/material relighting; subsurface scattering; inverse pipeline linearization.

V3 explicitly states that camera output should be reversible to linear scene light and gives a sequence involving inverse log transform, inverse matrix, white-balance inversion, and linear scene-referred output. fileciteturn300file3L230-L245

**Classification:** CONCEPT, MODEL, FORMULA, PROCESS, RELATION, QUANTITY, CONDITION, CLAIM, IMPLEMENTATION.

**Later destinations:** `ontology/`, `models/`, `quantities/`, `properties/`, `relations/`, `material/`, `spatial/`, `conditions/`.

**Recovery treatment:** distinguish physical laws from named models, mathematical transforms, implementation algorithms, error tolerances, and GIOP-specific mandates.

## 9. K05 — Sensor, Lens Hardware and ISP Pipeline

V3 defines the electro-optical chain from lens mount to RAW output, including sensor metrology, ISP architecture, lens compensation, stabilization, and sensor-lens interaction. fileciteturn300file3L251-L298

**Recovered sub-domains:** Sensor Metrology; ISP Pipeline Architecture; Lens Hardware and Optical Compensation; Camera Stabilization and Motion Models; Sensor-Lens Interaction Models.

**Recovered knowledge:** quantum efficiency and sensor response concepts; full-well capacity and conversion gain; sensor dynamic range and noise quantities; RAW pipeline stages; demosaicing and colour processing concepts; vignetting and cosine-law behaviour; mechanical vignetting; Brown–Conrady distortion model; chromatic aberration; focus breathing; optical image stabilization; gimbal stabilization and PID control; AI horizon lock; rolling-shutter compensation; optical crosstalk; microlens shading; lens-sensor alignment and tolerance effects.

V3 gives explicit vignetting, distortion, chromatic-aberration, breathing, stabilization, and sensor-lens interaction material. fileciteturn300file2L159-L208

**Classification:** CLASS, CONCEPT, PROPERTY, QUANTITY, VALUE, MODEL, FORMULA, PROCESS, STATE, CONDITION, RELATION, CLAIM, IMPLEMENTATION.

**Later destinations:** `classes/`, `properties/`, `quantities/`, `values/`, `models/`, `processes/`, `states/`, `conditions/`, `relations/`.

**Recovery treatment:** generic sensor/lens/ISP concepts are semantic candidates; concrete camera bodies, specific firmware behaviour, and vendor measurements are claims/entities requiring separate treatment.

## 10. K06 — AI Foundation

V3 defines CNNs, Transformers, diffusion models, GANs, AI-native ISP, AI colour grading, generative video/film production, AI standards/certification references, authenticity, ethics, training data, bias mitigation, and model validation/auditing. fileciteturn300file0L40-L71

**Classification:** CONCEPT, CLASS, MODEL, PROCESS, REPRESENTATION, CONDITION, RELATION, CLAIM, STANDARD, IMPLEMENTATION, POLICY.

**Later destinations:** `ontology/`, `classes/`, `models/`, `processes/`, `activities/`, `representations/`, `conditions/`, `identity/`, `relations/`, `perception/`.

**Recovery treatment:** separate general AI concepts from vendor/platform examples, named standards, ethical policy, and performance claims.

## 11. K07 — Neural Foundation

**Recovered knowledge:** neural rendering; NeRF; 3D Gaussian Splatting; neural denoising; neural compression; dynamic/4D representations; neural materials; quality/fidelity concepts; reconstruction and rendering relationships.

**Classification:** CONCEPT, CLASS, MODEL, REPRESENTATION, PROCESS, PROPERTY, QUANTITY, RELATION, CONDITION, CLAIM.

**Later destinations:** `models/`, `representations/`, `processes/`, `spatial/`, `temporal/`, `material/`, `fidelity/`, `relations/`.

**Recovery treatment:** distinguish a model architecture from the representation produced by it, and training/inference processes from the represented scene/content.

## 12. K08 — Video Engineering and Broadcast

**Recovered knowledge:** video codecs; rate–distortion optimization; PSNR; SSIM; VMAF; timecode; PTP; ST 2110; HDR delivery; codec-aware colour management; transport and quality-control concepts.

V3's standards group includes SMPTE ST 2084, ST 2110, ITU-R BT.2100, and related imaging/video references. fileciteturn300file8L584-L589

**Classification:** CONCEPT, REPRESENTATION, MODEL, FORMULA, QUANTITY, UNIT, PROCESS, RELATION, TEMPORAL CONCEPT, CLAIM, STANDARD, IMPLEMENTATION.

**Later destinations:** `representations/`, `processes/`, `quantities/`, `units/`, `temporal/`, `relations/`, `fidelity/`, `models/`.

**Recovery treatment:** keep quality metrics distinct from the properties they measure; keep transport and synchronization mechanisms distinct from media representations.

## 13. K09 — Immersive Formats and Metadata

**Recovered knowledge:** immersive media types; mono/stereo/multi-view/light-field/6DoF/volumetric categories; view count and layout; camera positions and orientations; depth ranges; screen geometry; ambient environment; metadata serialization; JSON/JSON-LD sidecar representation; metadata schema versioning.

V3 defines required immersive fields including immersive type, view layout, spatial pose, depth range, screen geometry, and ambient environment, with JSON/JSON-LD serialization. fileciteturn300file1L105-L122

**Classification:** CONCEPT, CLASS, PROPERTY, QUANTITY, VALUE, REPRESENTATION, RELATION, CONTEXT, CONDITION, CLAIM, STANDARD, IMPLEMENTATION.

**Later destinations:** `representations/`, `identity/`, `properties/`, `quantities/`, `values/`, `relations/`, `contexts/`, `spatial/`, `temporal/`.

**Recovery treatment:** distinguish metadata meaning from serialization syntax and from registry/governance mechanisms.

## 14. K10 — Immersive and Volumetric Capture

V3 covers MPEG-I Visual, 6DoF, volumetric video, geometric representations, atlas data, depth maps, camera metadata, 3DGS dynamic capture, physics-aware volumetric reconstruction, light fields, point clouds, compression, and view-dependent fidelity. fileciteturn300file9L663-L717

**Classification:** CONCEPT, CLASS, MODEL, REPRESENTATION, PROCESS, PROPERTY, QUANTITY, RELATION, CONDITION, STANDARD, CLAIM.

**Later destinations:** `representations/`, `processes/`, `models/`, `spatial/`, `temporal/`, `fidelity/`, `relations/`, `conditions/`.

**Recovery treatment:** separate scene representations, capture systems, reconstruction processes, compression representations, and fidelity/quality concepts.

## 15. K11 — Spatial Computing

**Recovered knowledge:** HMD architecture; asymmetric projection; lens-distortion correction; foveation; varifocal display concepts; light-field displays; cloud rendering; spatial colour appearance; passthrough matching; timewarp; synchronization; holographic/holoportation display concepts; user pose; viewing context; motion-to-photon concepts.

V3 also contains device/platform-specific specifications presented as 2026 reference values. These are recovered as **claims requiring independent verification**, not as canonical semantic facts. fileciteturn300file4L314-L377

**Classification:** CONCEPT, CLASS, PROPERTY, QUANTITY, MODEL, PROCESS, REPRESENTATION, STATE, CONDITION, CONTEXT, RELATION, CLAIM, IMPLEMENTATION.

**Later destinations:** `spatial/`, `perception/`, `modalities/`, `contexts/`, `temporal/`, `representations/`, `models/`, `conditions/`, `relations/`.

**Recovery treatment:** generic spatial-computing concepts are recovered for semantics; named platform/device specifications are isolated for external research and registry/domain treatment.

## 16. Section 14 — Runtime Specification

**Recovered knowledge:** runtime kernel model; plugin isolation; resource management; fault tolerance; configuration; observability; cross-platform compatibility; backend selection; shader precompilation; numerical consistency; IEEE 754 conformance; deterministic rendering constraints; file-path rules; UTF-8 and LF requirements.

V3 states runtime implementation constraints including precompiled shaders, IEEE 754 floating-point requirements, deterministic math behaviour, POSIX paths, UTF-8, and LF line endings. fileciteturn300file6L455-L470

**Classification:** IMPLEMENTATION, PROCESS, CONDITION, CLAIM, RELATION, REPRESENTATION.

**Semantic recovery:** only underlying concepts needed by semantic content, such as deterministic computation, numeric consistency, encoding, representation, observability, or fault state.

**Do not migrate wholesale to `02 SEMANTICS`.** Runtime implementation rules remain in the responsible operational roots.

## 17. Section 15 — Legacy, Settings, Parameters and Fault Tolerance

### A. Historical chronology

Recovered historical milestones include early mobile imaging, oversampling, optical stabilization, sensor development, zoom, autofocus, computational photography, and related technology milestones. V3 explicitly marks these entries as historical chronology rather than formulas. fileciteturn300file6L475-L512

**Classification:** HISTORICAL, CLAIM, TEMPORAL RELATION.

**Later destinations:** historical/temporal semantics where appropriate, with archival preservation in `27 LEGACY`.

### B. Camera settings toolkit

Recovered material includes false-colour/IRE concepts, contrast formulas, saturation formulas, exposure-triangle relationships, and camera-setting parameters.

**Classification:** PROPERTY, QUANTITY, VALUE, STATE, PROCESS, MODEL, FORMULA, CONDITION.

**Treatment:** recover generic concepts into semantics; operational instructions belong to appropriate downstream workflow/engineering documentation.

### C. Guardrails and fault tolerance

Recovered material includes parameter guardrails, sensor fault flags, dual-native-ISO crossover detection, rolling-shutter skew tolerance, recovery logic, and configuration fault detection.

**Classification:** CONDITION, STATE, STATUS, CLAIM, PROCESS, IMPLEMENTATION.

**Treatment:** semantic state/condition concepts may be recovered; actual runtime recovery procedures remain operational.

## 18. V3 Formula / Mathematical Corpus — Recovery Complete

The V3 corpus contains formulas/models in the following recovered families:

- photon energy and wave relationships;
- radiometry and photometry;
- spectral/color relationships;
- perceptual response and transfer functions;
- sensor noise, exposure, ISO, SNR, and dynamic range;
- optical refraction/reflection;
- lens-maker and optical geometry relationships;
- diffraction/interference/polarization;
- BRDF/PBR models;
- Fourier/statistical image analysis;
- color-space and HDR transforms;
- gamut and appearance models;
- distortion, vignetting, chromatic aberration, breathing;
- stabilization and motion models;
- inverse camera-pipeline transforms;
- video quality metrics;
- neural rendering / volumetric models;
- immersive geometry, depth, and fidelity models.

**Recovery rule:** a formula is never recovered as an isolated string. Each formula block must later carry variable definitions, dimensions/units, assumptions, domain of validity, boundary conditions, source context, and whether it is physical law, empirical model, implementation formula, or GIOP-specific rule.

## 19. V3 Standards Corpus — Recovery Complete

V3 references standards/specifications from bodies including ISO, CIE, SMPTE, ITU-R, EMVA, MPEG and related organizations.

**Recovery rule:** a standard reference is evidence/constraint material, not automatically a GIOP semantic definition.

Every standards-derived claim remains `CLAIM + STANDARD` until the actual authoritative source is inspected and the claimed scope is confirmed.

V3's manifest explicitly groups standards including ISO 22028-5:2026, ISO WD/AWI items, SMPTE ST 2065-1, ST 2084, ST 2110, ITU-R BT.2100, ITU-R BT.2124, AOM AV2, and JPEG AI. fileciteturn300file8L584-L589 These references are recovered, not independently validated in Step 3.

## 20. V3 Device / Software / Display / Computing Catalogue — Recovery Complete

V3 contains catalogue material for camera bodies, lenses, software, displays, and computing platforms.

**Recovery distinction:**

`generic concept → 02 SEMANTICS`

`specific named entity → 03 REGISTRY / downstream domain`

`vendor specification → CLAIM requiring evidence`

`historical product fact → HISTORICAL / LEGACY`

Therefore catalogue entries are not copied into semantic class files as if every named product were a class.

## 21. V3 Policy / Governance / Licensing Material — Recovery Complete

Recovered material includes maturity levels, professional authority tiers, proof-chain statements, versioning rules, licensing tiers, governance authority, contribution workflow, and certification concepts. fileciteturn300file8L602-L637

**Treatment:** preserve as V3 historical/policy source material. These are not domain semantics and should not be bulk-migrated into `02 SEMANTICS`.

## 22. Recovery Fate Matrix

| V3 material type | Recovery fate | Next action |
|---|---|---|
| Valid generic concept | RETAIN | verify + semanticize |
| Useful but mixed-content block | SPLIT | atomize into knowledge units |
| Formula/model | RETAIN → REFINE | validate variables, units, assumptions, scope |
| Physical-law claim | VERIFY | authoritative/scientific source check |
| Empirical/vendor claim | VERIFY | independent evidence required |
| Current-year device specification | HOLD | current external verification |
| Standard reference | VERIFY | inspect actual standard/source |
| Workflow/operational rule | RELOCATE | downstream responsible root |
| Runtime implementation rule | RELOCATE | Engineering/Runtime etc. |
| Generic setting/property/state | RETAIN → SEMANTICIZE | map to semantic objects |
| Historical milestone | PRESERVE | temporal/legacy treatment |
| GIOP policy/governance | PRESERVE / RELOCATE | Foundation/Trust/Commercial/Legacy as responsible |
| Concrete product/entity | REGISTRY CANDIDATE | `03 REGISTRY` or domain root |
| Unsupported/contradictory statement | HOLD | resolve during verification/gap research |

## 23. Atomic Recovery Output

The V3 source corpus has now been reduced conceptually into reusable knowledge families:

1. concepts/classes;
2. properties;
3. quantities/units/values;
4. mathematical formulas and models;
5. processes/workflows;
6. representations and encodings;
7. relations/dependencies;
8. states/statuses/conditions/contexts;
9. observer/perception knowledge;
10. material/scene/spatial/temporal knowledge;
11. standards and evidence references;
12. device/software/entity claims;
13. implementation/runtime constraints;
14. historical/legacy knowledge;
15. GIOP policy/governance material.

These families constitute the recovered V3 source corpus for later synthesis.

## 24. What Step 3 Does Not Claim

Step 3 does **not** claim that every V3 equation is mathematically correct; every standards citation is current or correctly scoped; every vendor/device specification is accurate; every historical priority claim is independently proven; every V3 normative requirement remains appropriate for V3.2.1; every recovered concept has already received a final canonical ID; or V3 and external current knowledge have already been reconciled.

Those questions belong to verification, gap analysis, external research, and corpus comparison.

## 25. Step 3 Completion Status

**STEP 3 — OLD KNOWLEDGE RECOVERY: COMPLETE**

The V3 corpus has been recovered at substantive section/sub-domain and cross-cutting knowledge-family level. The recovery boundary, classification vocabulary, major knowledge blocks, mixed-content separations, formula/model corpus, standards corpus, catalogue corpus, runtime corpus, policy corpus, and legacy corpus have all been recorded.

The corpus is now ready for **STEP 4 — GAP IDENTIFICATION**.

No canonical semantic entry is being authored from this register yet. The next stage compares the recovered V3 corpus against the current `02 SEMANTICS` landscape and identifies missing, duplicated, weakly supported, obsolete, or research-dependent knowledge before canonical writing begins.
