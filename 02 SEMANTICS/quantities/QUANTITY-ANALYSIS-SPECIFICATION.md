# Quantity Analysis Specification

**Artifact Type:** Semantic Analysis / Governance Specification  
**Semantic Layer:** Quantity  
**Version:** 1.0.0  
**Status:** Active  
**Primary Responsibility:** Define the semantic analysis and admission criteria for Quantity concepts

## 1. Purpose

This specification governs classification of measurable concepts into the GIOP Quantity layer. It prevents numerical representation, measurement practice, application terminology, and implementation vocabulary from being mistaken for Quantity identity.

## 2. Governing Question

The primary question is:

> What reusable measurable semantic aspect is being quantified?

The answer must identify a concept, not merely a number, field, unit, measurement procedure, metric name, parameter label, or implementation variable.

## 3. Core Model

`Quantity Concept → Quantity Value → Unit / Reference`

A measurement activity may establish a value for a quantity:

`Measurement Activity → Measurement Result → Quantity Value(s) + qualification/provenance`

Observation, modelling, calculation, simulation, or declaration may also establish or communicate a quantity value depending on context. Establishment mechanism does not redefine the Quantity concept.

## 4. Quantity vs Quantity Value

A Quantity identifies what is being quantified. A Quantity Value expresses a particular magnitude associated with that Quantity.

Example:

`Focal Length` = Quantity concept  
`50 mm` = quantity value expression containing magnitude and unit/reference

A value without an identified quantity is semantically incomplete unless its meaning is supplied by an enclosing structure.

## 5. Quantity vs Unit

A Unit is a reference convention used to express quantity values. It is not the measurable aspect itself.

`Distance` may be expressed in metres.  
`Temperature` may be expressed using kelvin or an appropriately defined temperature scale.

The presence of a unit does not determine the Quantity concept.

## 6. Quantity vs Measurement

Measurement is an activity/process by which a quantity value is established. Quantity identifies what is measured.

A measurement may target a quantity, but the measurement activity is not the quantity.

## 7. Quantity vs Measurement Result

A Measurement Result is an information object produced by measurement and may contain one or more quantity values, uncertainty information, conditions, context, and provenance.

The Quantity concept remains reusable independently of any one result.

## 8. Quantity vs Property

A Property denotes a reusable characteristic. A Quantity denotes a measurable aspect.

Some characteristics can be quantified; that does not make every Property identical to a Quantity.

For example, `Optical Distortion` is a Property concept in GIOP. A particular distortion metric or measured geometric deviation may involve one or more quantities, but the property concept itself is not automatically replaced by those quantities.

Conversely, a quantity such as focal length has a measurable magnitude and is not promoted into Property merely because it can characterize an optical system.

## 9. Quantity vs Metric

A metric is a calculated or defined measure used for assessment, comparison, monitoring, or evaluation. A metric may be dimensioned or dimensionless and may depend on multiple inputs.

A metric becomes a Quantity concept only if its semantic responsibility is itself a reusable measurable aspect rather than a named evaluation construct. Common imaging metrics therefore require candidate-level review.

## 10. Quantity vs Parameter

Parameter is a role term whose meaning varies by model. A parameter may be a Quantity, a Value, a constant, a configuration setting, or another model element.

`Parameter` is therefore not a sufficient semantic owner for a candidate concept.

## 11. Quantity vs Variable

Variable is a formal/modeling role representing something whose value may vary. A variable can carry a Quantity Value but is not thereby a Quantity concept.

`Variable` is therefore not an automatic Quantity classification.

## 12. Quantity Kind

Quantity Kind describes the kind of quantity being considered, such as length, duration, temperature, or another recognized kind.

Quantity Kind is conceptually related to Quantity but should not automatically be treated as a second canonical ontology layer in V3.1. A separate canonical Quantity Kind construct requires independent governance responsibility.

## 13. Quantity Dimension

Quantity Dimension captures dimensional structure used in physical quantity systems, such as length, time, mass, or combinations thereof.

Dimension supports unit compatibility and dimensional reasoning. It does not replace Quantity identity.

A dimensionless quantity can still be a Quantity; dimensionality is not an eligibility test by itself.

## 14. Scalar, Vector, and Tensor Structure

Quantity values may have scalar or structured mathematical form. A vector or tensor value does not require a new Quantity ontology layer merely because its representation is non-scalar.

The semantic question remains what measurable aspect the structure expresses. Mathematical structure belongs to value/representation semantics when appropriate.

## 15. Reference Systems and Scales

Quantity values may require a reference system, scale, datum, coordinate frame, standard reference, or defined comparison basis.

Reference information qualifies the value. It does not automatically become the Quantity concept.

Temperature is a key example: a temperature quantity and its scale/reference must remain distinguishable.

## 16. Uncertainty

Uncertainty characterizes knowledge about a measured or estimated value. It is not normally the Quantity being measured.

Uncertainty belongs with measurement/result/value qualification unless a separate canonical semantic responsibility is established.

## 17. Interval and Range

An interval or range describes a set or bounded region of possible/allowed values. It is not automatically a new Quantity concept.

A range can qualify a Quantity Value, specification, condition, constraint, or result.

## 18. Measurement Scale

Nominal, ordinal, interval, and ratio scale classifications describe properties of measurement scales and the permissible operations on values. They should not be conflated with Quantity identity.

A Quantity can participate in a measurement scale without the scale becoming its semantic owner.

## 19. Imaging Candidate Analysis

Candidate terms are classified by responsibility, not by numerical appearance.

### High-confidence Quantity examples

- Distance
- Focal Length
- Wavelength
- Exposure Time
- Illuminance
- Luminance
- Radiance
- Irradiance
- Reflectance, where the intended standard-defined quantity is established
- Transmittance, where the intended standard-defined quantity is established
- Spatial Frequency

### Controlled candidates

- Pixel Pitch
- Aperture Diameter
- Temporal Frequency
- Frame Rate
- F-number
- absorptance and related ratio quantities

### High-risk / deferred candidates

- Resolution
- SFR
- MTF
- OTF
- Noise
- Dynamic Range
- SNR
- Sharpness
- Acutance
- Sensitivity

These terms may have different meanings across metrology, engineering, imaging evaluation, product specifications, and perception research.

## 20. Focal Length Routing

Focal Length is routed to Quantity because its normative optical meaning is a distance-related measurable quantity. It may function operationally as an optical-system parameter, but `parameter` is a usage role rather than the semantic owner.

Therefore:

`Focal Length → Quantity`

and not:

`Focal Length → generic Property`

## 21. Resolution Routing

Resolution is deliberately not admitted automatically as a Quantity. Depending on domain and standard, it may denote a performance characteristic, a limit, a criterion, a spatial-frequency-related capability, or a result/metric derived from a test method.

The candidate must therefore be resolved against the responsible measurement method and specification context before canonicalization.

## 22. Dynamic Range Routing

Dynamic Range may be expressed as a ratio, logarithmic quantity, performance characteristic, or derived system metric depending on context. The term cannot be canonicalized merely because numerical values are commonly reported.

## 23. Noise and SNR

Noise and Signal-to-Noise Ratio require special handling. Noise can refer to a physical/stochastic phenomenon, a signal component, a variance-like quantity, or a performance concept. SNR is generally a derived comparison involving signal and noise quantities.

Neither is automatically admitted into the generic Quantity nucleus.

## 24. Admission Criteria

A candidate should be promoted only when:

1. its semantic responsibility is measurable and reusable;
2. it is distinguishable from Property, Value, Unit, Measurement, Result, Metric, Parameter, Variable, State, Condition, and Context;
3. authoritative evidence supports the interpretation;
4. conflicting usages have been analyzed;
5. no existing canonical Quantity already owns the same responsibility;
6. the concept can be machine-identified independently of a particular value or implementation;
7. its relations and lifecycle can be governed without duplicating another layer.

## 25. Canonicalization Decision Classes

`CANONICAL` — responsibility established.  
`CANDIDATE` — plausible but requiring further validation.  
`DEFERRED` — retained because responsibility remains ambiguous, domain-dependent, or insufficiently bounded.  
`ROUTED-ELSEWHERE` — belongs primarily to another semantic layer.  
`NON-EQUIVALENT` — superficially similar but semantically distinct.

## 26. Machine Interpretation

A machine should treat the following as separate nodes or roles when present:

`Quantity Concept`  
`Quantity Value`  
`Unit`  
`Measurement`  
`Measurement Result`  
`Uncertainty`  
`Reference / Scale`  
`Context`  
`Condition`  
`Property`  
`State`

The lexical token `value`, `parameter`, `metric`, or `measurement` must not override the canonical semantic type.

## 27. Visitor Universe Interpretation

The Quantity layer provides the same canonical knowledge at different entry depths. Visitor categories do not become Quantity subclasses and are not recorded as semantic identity fields.

A novice may consume the What/Why layer; a practitioner may need units and application constraints; a scientist or metrologist may require reference, uncertainty, and measurement semantics; an AI consumer may require stable IDs, relations, and machine-readable distinctions.

## 28. Final Decision Rule

`NUMERIC ≠ QUANTITY`

`MEASURABLE ≠ AUTOMATICALLY QUANTITY`

`MEASURED ≠ MEASUREMENT`

`VALUE ≠ QUANTITY`

`UNIT ≠ QUANTITY`

`METRIC ≠ AUTOMATICALLY QUANTITY`

`PARAMETER ≠ AUTOMATICALLY QUANTITY`

`VARIABLE ≠ QUANTITY`

Quantity admission is a semantic decision, not a formatting decision.
