# GIOP V3.1 — Canonical Identity Ledger
Status: WORKING
Source baseline: main at 1b4668b323ea9dbd42e4a36e70492becdd15db28
Purpose: classify current V3 artifacts before any controlled content promotion.

RULES
- No V3 source deletion or overwrite.
- SEMANTICS defines meaning; REGISTRY defines canonical identity.
- Responsibility roots provide views, not competing truths.
- Historical material remains preservable under 27 LEGACY/v3.
- Destination assignment is not migration.

CAMERA BODIES
All bodies/* are compound artifacts. Canonical identity -> 03 REGISTRY/devices; sensor characterization -> 06 SENSOR-SCIENCE; acquisition -> 07 CAPTURE.
Arri Alexa 35: REVIEW-REQUIRED compound profile: identity, LogC4, AWG4/ACES, WB, ISO, dual gain, metadata, validation.
Blackmagic Gen5: MAP-ONLY; camera identity + capture + sensor/color views.
Canon C700: MAP-ONLY; camera identity + capture + sensor/color views.
Canon MS 510: REVIEW-REQUIRED exact device classification.
DJI: REVIEW-REQUIRED family/product identity resolution.
Fujifilm GFX: REVIEW-REQUIRED family-vs-instance resolution.
Hasselblad HNCS HDR: REVIEW-REQUIRED identity/color separation.
Leica SL: MAP-ONLY; camera identity + capture + sensor/color views.
Nikon Z9 N-Raw: MAP-ONLY; camera identity + capture + sensor/color views.
Panasonic Lumix: REVIEW-REQUIRED family/product identity resolution.
Raytheon Fence: REVIEW-REQUIRED; filename alone is insufficient classification.
Red V-Raptor: MAP-ONLY; camera identity + capture + sensor/color views.
Sony Venice 2: MAP-ONLY; camera identity + capture + sensor/color views.

LENSES
Primary -> 08 LENS-SYSTEMS; canonical identity -> 03 REGISTRY; physical optical models -> 05 OPTICS.
anamorphic/Anamorphic Characters Generic: DECOMPOSE.
anamorphic/Optical Breathing Suppression: DECOMPOSE.
computational/Achromatic MetaLens: REVIEW-REQUIRED.
computational/Bio Inspired Optical Attention Mechanism: REVIEW-REQUIRED.
computational/Lensless Imaging via FNO: REVIEW-REQUIRED.
computational/MetaLens Phase Gradient: DECOMPOSE.
computational/Optical Attention Mechanism: REVIEW-REQUIRED.
spherical/Canon RF, Nikon Nikkor Z, Sony G Master, Zeiss Otus: MAP-ONLY product/lens profiles.

FORMULAS
registered formula identity -> 03 REGISTRY/formulas; semantic definition -> 02 SEMANTICS; implementation -> 10 COMPUTATION; normative provenance -> 22 STANDARDS.
Color Science Standard: DECOMPOSE.
Geometry and Motion: DECOMPOSE.
Neural Rendering: DECOMPOSE.
Optic Physics: DECOMPOSE.
Video Engineering: DECOMPOSE.

KINGDOMS
Kingdoms are V3 packaging units, not V4 roots.
00 Science of Light -> 04 PHYSICS + 05 OPTICS.
01 Human Vision vs Camera and Lens -> 12 VISION + 05 OPTICS + 02 SEMANTICS.
02 Fundamental Imaging Physics and Sensor Metrology -> 06 SENSOR-SCIENCE + 04 PHYSICS.
03 Color Science and Visual Perception -> 02 SEMANTICS + 10 COMPUTATION + 12 VISION + 22 STANDARDS.
04 Physics and Mathematics for Imaging -> 04 PHYSICS + 05 OPTICS + 10 COMPUTATION.
05 Sensor, Lens Hardware and ISP Pipeline -> 06 SENSOR-SCIENCE + 07 CAPTURE + 08 LENS-SYSTEMS + 23 ENGINEERING.
06 AI Foundation -> 11 AI + 21 RESEARCH + 22 STANDARDS + 26 TRUST.
07 Neural Foundation -> 11 AI + 09 REPRESENTATION + 10 COMPUTATION.
08 Video Engineering and Broadcast Standards -> 18 MEDIA + 22 STANDARDS + 10 COMPUTATION.
09 Immersive Formats and Metadata Standards -> 17 IMMERSIVE + 18 MEDIA + 22 STANDARDS + 03 REGISTRY.
10 Immersive and Volumetric Capture -> 07 CAPTURE + 09 REPRESENTATION + 17 IMMERSIVE.
11 Spatial Computing -> 17 IMMERSIVE + 24 RUNTIME + 20 SENSOR-ECOSYSTEM.
Kingdom appendix/Quantum Ghost Imaging (BNL X-ray): REVIEW-REQUIRED.

DISPLAYS
displays/* -> 19 DISPLAY; canonical identity -> 03 REGISTRY/devices or products; conformance -> 22 STANDARDS.
Apple Pro XDR; Micro LED; QD OLED; Quantum Dot; Quantum Dot Micro LED; Samsung Dynamic Amoled 2X; Sony BVM-HX3110: MAP-ONLY pending validation.

COMPUTING
computing/* -> 24 RUNTIME/compute + 23 ENGINEERING + 03 REGISTRY/components.
All current computing artifacts are MAP-ONLY until family/product identity and claims are validated.

SOFTWARE
software/* -> 23 ENGINEERING; runtime behavior -> 24 RUNTIME; vendor/product identity -> 03 REGISTRY/products.
Implementation/workflow/API references require REVIEW-REQUIRED classification before canonical registration.

STANDARDS
standards/* -> 22 STANDARDS; canonical identity -> 03 REGISTRY/standards; verification -> 21 RESEARCH + conformance.
Current titles are source artifact names; canonical promotion requires standards verification.

RUNTIME
runtime/Runtime Specifications -> 24 RUNTIME; related engineering -> 23 ENGINEERING; integrity/security -> 26 TRUST.

LEGACY
legacy/Legacy, Settings Parameters and Fault Tolerance -> 27 LEGACY.
Historical chronology remains historical. Settings/fault-tolerance material requires explicit classification before becoming active V4 normative content.

PROMOTION GATE
Before promotion: canonical identity, primary responsibility, secondary views, provenance, validation, maturity, supersession/legacy relationship, registry identifier.
