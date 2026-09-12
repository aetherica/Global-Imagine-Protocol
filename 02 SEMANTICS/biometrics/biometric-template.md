# Biometric Template

**Semantic ID:** `SEM-BIOMETRIC-TEMPLATE-001`
**Preferred Name:** Biometric Template
**Semantic Class:** Biometrics Concept
**Domain:** Biometrics
**Status:** CANONICAL CANDIDATE — V3.1 SEED
**Version:** 0.1.0

## 5W1H Orientation

### What
A Biometric Template is a structured or encoded representation derived from biometric data for a defined biometric recognition/comparison purpose.

### Why
Templates enable systems to compare biometric evidence without necessarily retaining the full source sample in the same form.

### Who
Biometric systems, recognition engines, enrollment systems, evaluation systems, and secure repositories use templates.

### Where
Storage, comparison engines, enrollment records, evaluation datasets, and protected biometric infrastructures.

### When
A template is generated from an input representation under a defined algorithm/version and may require renewal when representation or system conditions change.

### How
Feature extraction, encoding, normalization, quality control, and system-specific transformation may produce the template. These are computational/implementation methods, not the semantic definition.

## Semantic Definition
**Biometric Template** is a system-purpose representation derived from biometric information for subsequent biometric comparison, decision, or related processing.

## Scope / Boundary
A template is not synonymous with a biometric characteristic, raw sample, biometric reference, or identity. Its representation format and generation method remain implementation-dependent.

## Core Distinctions
**Template vs Sample:** transformed/system-use representation versus acquired source instance.

**Template vs Feature:** a feature may be an extracted characteristic; a template is the representation package used by a defined biometric system.

**Template vs Reference:** a reference is a role; a template can serve as the representation of that reference.

## Trust / Evidence
Generation algorithm/version, source context, quality, transformation history, protection, and revocability matter. ISO/IEC 24745 emphasizes protection and renewability/revocability of biometric information. citeturn454778search3

## Cross-Domain Significance
Connects Biometrics with Representation, Computational Method, Implementation, Identity, Provenance, and Security/Privacy.

## Lifecycle
Candidate seed → validation → Gate-J → Active Canonical.

## Retrieval Anchors
`BIOMETRIC TEMPLATE`, `BIOMETRIC TEMPLATE DATA`, `TEMPLATE REPRESENTATION`, `FEATURE TEMPLATE`
