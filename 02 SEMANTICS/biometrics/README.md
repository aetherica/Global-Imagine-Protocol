# Biometrics Semantic Domain

**Semantic Domain:** Biometrics
**Status:** IMPLEMENTATION-COMPLETE — V3.1 SEED / CANDIDATE DOMAIN
**Authority Boundary:** Biometrics owns concepts specific to biometric characteristics, modalities, samples, references/templates, and biometric-system semantics. It does not own generic identity, generic image representation, generic measurement, or BIL integrity.

## Domain Principle

Biometrics concerns measurable biological and behavioural characteristics used for recognition-related purposes. A biometric characteristic can be an input to identity processes, but biometric evidence does not equal identity.

## Core Seed Concepts

1. Biometric Characteristic — the biological or behavioural characteristic used as biometric information.
2. Biometric Modality — a defined category of biometric characteristic/acquisition, such as face, fingerprint, iris, voice, gait, or another modality.
3. Biometric Sample — acquired biometric data representing a biometric characteristic at a particular capture event.
4. Biometric Reference — stored or designated biometric information used as a reference for comparison.
5. Biometric Template — processed/encoded representation derived from biometric sample/reference for a specified system purpose.
6. Biometric Verification — one-to-one biometric decision activity; route to Activity/Process when formalized.
7. Biometric Identification — one-to-many biometric decision activity; route to Activity/Process when formalized.

## Boundary Rules

- Generic identity stays in `identity/`.
- Generic representation stays in `representations/`.
- Generic measurement stays in `quantities/` and `activities/`.
- Biometric comparison/verification/identification are operational processes, not a reason to duplicate the Process layer.
- BIL consumes biometric evidence where integrity evaluation needs it; BIL does not become the owner of biometric semantics.

## Evidence Basis

ISO/IEC 24745:2022 treats biometric references as distinct information bound to identity references and addresses confidentiality, integrity, renewability/revocability, and privacy. ISO/IEC 19795-1:2026 draft formalizes biometric enrolment, verification, identification transactions, comparison scores, decisions, and performance testing. These are domain evidence, not a license to duplicate every operational concept as a semantic page. citeturn454778search3turn167886search0

## Lifecycle

Seed concepts remain candidate until cross-layer validation and Gate-J. Domain closure means implementation completeness, not automatic canonical promotion.

## Retrieval Anchors

`BIOMETRICS`, `BIOMETRIC CHARACTERISTIC`, `BIOMETRIC MODALITY`, `BIOMETRIC SAMPLE`, `BIOMETRIC REFERENCE`, `BIOMETRIC TEMPLATE`, `BIOMETRIC VERIFICATION`, `BIOMETRIC IDENTIFICATION`
