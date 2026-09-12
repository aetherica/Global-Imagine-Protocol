# Biometrics Closure Audit

**Status:** IMPLEMENTATION-COMPLETE — V3.1 SEED / CANDIDATE DOMAIN

## Implemented Core

- Biometric Characteristic — `SEM-BIOMETRIC-CHARACTERISTIC-001`
- Biometric Reference — `SEM-BIOMETRIC-REFERENCE-001`
- Biometric Template — `SEM-BIOMETRIC-TEMPLATE-001`

## Retained Domain Concepts in README Seed Register

Biometric Modality, Biometric Sample, Biometric Verification, Biometric Identification.

## Routing

Verification and identification are operational biometric tasks and should become Activity/Process/Workflow entries rather than parallel ontologies. Sample is an acquired representation and should remain cross-linked with Representation and Capture/Observation. Biometric Reference is a biometric role, while Template is a particular processed representation that may serve that role.

## Boundary

Biometrics does not own generic Identity, Representation, Measurement, Computational Method, Implementation, or BIL integrity semantics.

## Evidence Basis

ISO/IEC 24745:2022 defines security/privacy requirements around biometric information and secure binding of biometric references to identity references. ISO/IEC DIS 19795-1 (2026) separates enrolment, verification, identification transactions, comparisons, decisions, and biometric performance testing. citeturn454778search3turn167886search0

## Completion Determination

The BIL material has been semantically routed rather than copied. No BIL-native candidate was moved into Biometrics.

Canonical promotion remains subject to Gate-J.
