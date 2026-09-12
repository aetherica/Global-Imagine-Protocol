# Biometric Reference

**Semantic ID:** `SEM-BIOMETRIC-REFERENCE-001`
**Preferred Name:** Biometric Reference
**Semantic Class:** Biometrics Concept
**Domain:** Biometrics
**Status:** CANONICAL CANDIDATE — V3.1 SEED
**Version:** 0.1.0

## 5W1H Orientation

### What
A Biometric Reference is biometric information designated or stored as a reference against which another biometric presentation/sample may be compared within a specified system or process.

### Why
The reference provides the comparison target for identity-related biometric operations and must be distinguished from generic identity and from the raw capture event.

### Who
Used by biometric recognition, verification, identification, enrollment, forensic, and other declared biometric applications.

### Where
Biometric repositories, secure devices, identity systems, datasets, and controlled evaluation environments.

### When
A reference is associated with an enrollment or designation context and may have validity, revocation, renewal, or version semantics.

### How
The reference may be a raw sample, a processed representation, a template, or another defined biometric reference form depending on the system.

## Semantic Definition
**Biometric Reference** is biometric information designated as the comparison reference for a specified biometric application or identity context.

## Core Distinctions
Reference ≠ Identity: it supports an identity-related operation.

Reference ≠ Sample: a sample is an acquired instance; a reference is designated for comparison.

Reference ≠ Template: a template is a particular processed representation; a reference may be represented in several ways.

## Trust / Evidence
Reference binding, provenance, protection, validity, and revocation/renewal status are critical. ISO/IEC 24745 explicitly addresses secure binding between biometric references and identity references and the protection of biometric information. citeturn454778search3

## Cross-Domain Significance
Connects Biometrics with Identity, Representation, Provenance, Security/Privacy, and Process.

## Lifecycle
Candidate seed → validation → Gate-J → Active Canonical.

## Retrieval Anchors
`BIOMETRIC REFERENCE`, `BIOMETRIC REFERENCE DATA`, `REFERENCE BIOMETRIC`, `BIOMETRIC REFERENCE RECORD`
