# Biometric Template

**Semantic ID:** `SEM-BIOMETRIC-TEMPLATE-001`  
**Preferred Name:** Biometric Template  
**Semantic Class:** Biometrics Concept  
**Domain:** Biometrics  
**Status:** CANONICAL CANDIDATE — V3.1 SEED  
**Version:** 0.2.0

## 5W1H Orientation

### What
A Biometric Template is a structured or encoded representation derived from biometric information for a defined biometric comparison, recognition, or related system purpose.

### Why
Templates provide a system-usable representation of biometric information for later comparison or processing and may allow systems to operate without retaining the original source sample in the same form.

### Who
Applicable to biometric recognition and enrollment systems, comparison engines, evaluation systems, protected repositories, forensic systems, and machine-readable biometric infrastructures.

### Where
Templates may be generated, stored, transmitted, compared, evaluated, or protected within declared biometric systems.

### When
A template is generated under a defined representation method and system context. Changes in algorithms, versions, source data, quality, or operating conditions may affect compatibility and may require re-enrollment or template renewal.

### How
Feature extraction, encoding, normalization, quality processing, and system-specific transformation can contribute to template generation. These are methods or implementations, not the semantic identity of the template concept.

## Semantic Definition

**Biometric Template** is a system-purpose representation derived from biometric information for subsequent biometric comparison, recognition, decision support, or related processing.

## Scope / Boundary

Biometric Template owns the semantic concept of the derived system-purpose representation. It does not own:

- the underlying Biometric Characteristic;
- the acquired Sample;
- the comparison-reference role itself;
- Identity;
- generic Representation semantics;
- the computational algorithm or implementation used to generate it;
- the recognition/verification decision;
- BIL integrity evaluation.

Template format, encoding, dimensionality, model architecture, and algorithm version remain implementation- or method-specific unless separately promoted.

## Core Distinctions

### Template vs Sample
A template is a derived system-purpose representation; a sample is an acquired instance of biometric information.

### Template vs Feature
A feature is a selected measurable or derived characteristic; a template is the representation package used by a defined biometric system.

### Template vs Reference
Reference denotes a comparison role; template denotes a representation form. A template may serve as a biometric reference.

### Template vs Identity
A template can support identity-related comparison but does not constitute identity.

## Cross-Domain Significance

`Biometric Characteristic → Acquisition / Sample → Representation → Template → Reference / Comparison → Assessment / Decision → Identity`

Computational Method, Implementation, Provenance, Security/Privacy, and BIL remain external authorities consumed by this domain.

## Trust / Evidence

Template assertions should identify source context, generation method/version where known, quality information, representation compatibility, transformation history, protection status, and provenance. ISO/IEC 24745 is relevant to protection and renewability/revocability considerations for biometric information.

## Visitor Universe

**Novice:** template versus sample, feature, reference, and identity.  
**Intermediate:** derivation, compatibility, quality, storage, and template lifecycle.  
**Expert:** representation invariance, algorithm/version dependence, protection, renewability, revocability, interoperability, and provenance.  
**Machine:** stable ID, source links, method/version, representation metadata, reference role, lifecycle state, provenance, and uncertainty.

## Lifecycle

Candidate seed → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`BIOMETRIC TEMPLATE`, `BIOMETRIC TEMPLATE DATA`, `TEMPLATE REPRESENTATION`, `BIOMETRIC TEMPLATE FORMAT`, `FEATURE TEMPLATE`
