# Biometric Reference

**Semantic ID:** `SEM-BIOMETRIC-REFERENCE-001`  
**Preferred Name:** Biometric Reference  
**Semantic Class:** Biometrics Concept  
**Domain:** Biometrics  
**Status:** CANONICAL CANDIDATE — V3.1 SEED  
**Version:** 0.2.0

## 5W1H Orientation

### What
A Biometric Reference is biometric information designated as a comparison reference for a specified biometric application, subject, or identity-related context.

### Why
A biometric system needs a defined comparison target. The reference role must remain distinct from the biological characteristic, the acquired sample, the template representation, and the identity determination supported by the reference.

### Who
Applicable to biometric-system designers, enrollment and recognition systems, forensic applications, authentication systems, protected repositories, evaluation datasets, and governance processes.

### Where
It may exist in enrollment systems, protected repositories, devices, controlled datasets, identity systems, and other declared biometric infrastructures.

### When
A reference is associated with a designation or enrollment context and may have validity, version, renewal, revocation, replacement, or retention semantics.

### How
The reference role may be fulfilled by a sample, template, or another defined biometric representation depending on system design. The representation format and generation process are implementation concerns.

## Semantic Definition

**Biometric Reference** is biometric information designated as the comparison reference for a specified biometric application or identity-related context.

## Scope / Boundary

Biometric Reference owns the semantic role of designated comparison information. It does not own:

- Identity itself or identity resolution;
- Biometric Characteristic semantics;
- a particular Sample or Template format;
- authentication protocols;
- generic Representation semantics;
- provenance or security mechanisms;
- BIL integrity decisions.

The same reference role may be represented differently across systems; role and representation must not be conflated.

## Core Distinctions

### Reference vs Identity
A reference supports an identity-related operation; it is not the identity.

### Reference vs Sample
A sample is an acquired instance; a reference is information assigned the comparison-reference role.

### Reference vs Template
Template describes a representation form. Reference describes the comparison role. A template can serve as a biometric reference.

### Reference vs Evidence
A reference can be evidence in an assessment, but the reference role itself does not establish truth or decision validity.

## Cross-Domain Significance

`Biometric Characteristic → Acquisition / Sample → Representation / Template → Biometric Reference → Comparison / Assessment → Identity-related Decision`

Reference binding, lifecycle, protection, and provenance connect Biometrics with Identity and Foundation governance without duplicating those authorities.

## Trust / Evidence

Reference assertions should declare source/designation context, subject or identity scope where applicable, representation form, generation history, validity status, protection requirements, and provenance. ISO/IEC 24745 is particularly relevant to binding biometric references to identity references and protecting biometric information.

## Visitor Universe

**Novice:** reference versus sample, template, and identity.  
**Intermediate:** enrollment, designation, validity, renewal, and reference lifecycle.  
**Expert:** reference binding, protection, revocation/renewal, cross-system representation, provenance, and privacy.  
**Machine:** stable ID, reference role, representation links, lifecycle state, provenance, protection metadata, and uncertainty.

## Lifecycle

Candidate seed → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`BIOMETRIC REFERENCE`, `REFERENCE BIOMETRIC`, `BIOMETRIC REFERENCE DATA`, `BIOMETRIC REFERENCE RECORD`, `ENROLMENT REFERENCE`
