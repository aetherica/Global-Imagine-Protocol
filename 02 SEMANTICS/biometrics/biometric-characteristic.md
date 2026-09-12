# Biometric Characteristic

## Identity / Metadata
- GIOP ID: SEM-BIOMETRIC-CHARACTERISTIC-001
- Semantic Layer: Domain Semantic Layer
- Domain: Biometrics
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Class, Property, Quantity, State, Representation, Identity

## 5W1H Orientation

### What
A Biometric Characteristic is a measurable or observable biological or behavioral characteristic that can be used as a biometric signal for recognition, verification, identification, or related purposes.

### Why
Biometric characteristics provide evidence that can support distinguishing or relating subjects. Their usefulness depends on distinctiveness, measurability, persistence, capture conditions, population variability, and the intended biometric task.

### Who
Characteristics may be obtained from humans or, in domain-specific systems, other biological subjects. Sensors, observers, biometric systems, and analysts may capture or evaluate them.

### Where
They occur in the biological subject and become observable through a capture modality such as image, audio, physiological sensing, behavioral observation, or another measurement channel.

### When
A characteristic may vary over time because of pose, expression, aging, injury, health, environment, behavior, or capture conditions. Its temporal behavior must therefore be distinguished from identity persistence.

### How
A characteristic is captured or measured, represented as data, subjected to quality assessment, and potentially converted into a biometric reference or template. The method and modality determine what portion of the characteristic is observable.

## Semantic Definition
A Biometric Characteristic is a biological or behavioral characteristic used as a biometric signal because it can be observed or measured for subject-related comparison or recognition.

## Scope / Boundary
Biometric Characteristic owns biometric-domain characteristic semantics. Generic Property and Quantity own general properties and measurements. Identity owns the referent. Biometric Reference and Template own derived representations. BIL evaluates relevant biometric integrity but does not redefine the characteristic.

## Core Distinctions
- Characteristic ≠ biometric sample.
- Characteristic ≠ biometric template.
- Characteristic ≠ identity.
- Observable characteristic ≠ invariant characteristic.
- Measurement error ≠ biological change.

## Cross-Domain Significance
Biometric characteristics connect biology, measurement, representation, identity, machine learning, and evaluation. They can serve as evidence in identity resolution or integrity assessment without becoming proof by themselves.

## Trust / Evidence
Interpretation depends on capture quality, sensor characteristics, population context, measurement uncertainty, provenance, and method. A characteristic observation is evidence, not automatically an identity decision.

## Visitor Universe
Novices need characteristic-versus-template clarity. Experts need modality, persistence, discriminability, quality, variability, uncertainty, and performance implications. Machines need typed characteristic, modality, sample, and measurement references.

## Lifecycle
The characteristic itself is part of the subject; its observations and representations have capture, processing, validation, retention, and retirement lifecycles.

## Retrieval Anchors
biometric characteristic, biometric trait, biometric signal, biological characteristic, behavioral biometric characteristic
