# Biometric Characteristic

**Semantic ID:** `SEM-BIOMETRIC-CHARACTERISTIC-001`  
**Preferred Name:** Biometric Characteristic  
**Semantic Class:** Biometrics Concept  
**Domain:** Biometrics  
**Status:** CANONICAL CANDIDATE — V3.1 SEED  
**Version:** 0.2.0

## 5W1H Orientation

### What
A Biometric Characteristic is a biological or behavioural characteristic whose measurable manifestation is used as a basis for biometric recognition or comparison within a declared application.

### Why
Biometric systems require a defined characteristic whose manifestations can be observed, acquired, represented, and compared. The characteristic must remain distinct from the sample, template, identity, and recognition decision derived from it.

### Who
Applicable to biometric-system designers, biometric researchers, sensor specialists, recognition systems, forensic and authentication applications, evaluation systems, and machine-readable biometric datasets.

### Where
It applies across physical observation, sensor acquisition, biometric datasets, recognition systems, evaluation environments, forensic applications, and declared identity-related workflows.

### When
A characteristic may vary with time, subject condition, behaviour, environment, acquisition conditions, sensor properties, and application context. Such variability does not by itself invalidate the characteristic.

### How
A characteristic becomes relevant to a biometric application through acquisition, measurement or observation, representation, comparison, and an application-specific recognition process. Those operations belong to their respective GIOP layers.

## Semantic Definition

**Biometric Characteristic** is a biological or behavioural characteristic whose measurable manifestation is used for biometric recognition, comparison, or related biometric processing within a specified application scope.

## Scope / Boundary

Biometric Characteristic owns the domain meaning of the characteristic used as the biometric basis. It does not own:

- Identity or identity resolution;
- a particular acquired Sample;
- a Biometric Template representation;
- generic Property or Quantity semantics;
- Observation or Measurement activities;
- recognition/verification/identification workflows;
- BIL integrity evaluation;
- a particular sensor, algorithm, model, or implementation.

## Core Distinctions

### Characteristic vs Sample
The characteristic is the underlying biological/behavioural phenomenon; a sample is an acquired instance or representation produced from an observation/acquisition event.

### Characteristic vs Template
A template is a system-purpose representation derived from biometric information; it is not the characteristic itself.

### Characteristic vs Identity
A characteristic may provide evidence for an identity-related determination but does not constitute identity.

### Characteristic vs Modality
A modality is a declared classification of biometric acquisition/recognition based on a characteristic or technique; the characteristic is the underlying domain phenomenon.

## Cross-Domain Significance

`Biological / Behavioural Phenomenon → Observation / Measurement → Biometric Characteristic → Sample / Representation → Template → Identity-related Process / Decision`

The Biometrics domain consumes generic GIOP semantics rather than redefining them.

## Trust / Evidence

A biometric characteristic assertion should declare the application scope, subject population, acquisition context, expected variability, and intended task. Measurability or observability must not be confused with identity certainty. Evidence quality is handled by the applicable acquisition, measurement, assessment, and provenance semantics.

## Visitor Universe

**Novice:** characteristic versus identity, sample, and template.  
**Intermediate:** physiological versus behavioural characteristics and acquisition variability.  
**Expert:** characteristic scope, observability, population variability, quality, comparison context, and cross-representation consistency.  
**Machine:** stable semantic ID, characteristic class, modality references, acquisition context, evidence, provenance, and uncertainty.

## Lifecycle

Candidate seed → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`BIOMETRIC CHARACTERISTIC`, `BIOLOGICAL CHARACTERISTIC`, `BEHAVIOURAL BIOMETRIC`, `PHYSIOLOGICAL BIOMETRIC`, `BIOMETRIC BASIS`
