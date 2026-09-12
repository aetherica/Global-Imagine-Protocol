# Quantity Boundary Rule

**Artifact Type:** Semantic Boundary Rule  
**Semantic Layer:** Quantity  
**Version:** 1.0.0  
**Status:** Active

## 1. Governing Responsibility

Quantity owns the reusable semantic concept of a measurable aspect whose magnitude can be expressed through an appropriate value-and-reference structure.

## 2. Non-Equivalence Rules

### Quantity ≠ Quantity Value

Quantity identifies what is quantified. Quantity Value identifies a particular magnitude associated with it.

### Quantity ≠ Unit

Unit is an expression/reference convention for quantity values.

### Quantity ≠ Measurement

Measurement is an activity for establishing a value of a quantity.

### Quantity ≠ Measurement Result

A measurement result is information produced by measurement and may contain quantity values, uncertainty, context, and provenance.

### Quantity ≠ Property

Property denotes a characteristic; Quantity denotes a measurable aspect. A property may be quantified without becoming identical to a quantity.

### Quantity ≠ Metric

A metric is an evaluative/calculative construct unless its own responsibility is established as a reusable measurable aspect.

### Quantity ≠ Parameter

Parameter is a model or operational role. A parameter may carry a quantity but is not automatically a Quantity concept.

### Quantity ≠ Variable

Variable is a mathematical/modeling role. A variable may take quantity values without being the Quantity itself.

### Quantity ≠ State

A State denotes a recognized mode or condition of a bearer at a temporal locus. A quantity may characterize a state but is not the state.

### Quantity ≠ Condition

A Condition describes a relevant circumstance or condition under which something exists, operates, is observed, measured, or evaluated. A quantity can qualify a condition.

### Quantity ≠ Context

Context is a situational frame. Quantity can be specified or measured within a context.

### Quantity ≠ Status

Status expresses a lifecycle, administrative, operational, or validation standing. It is not a measurable aspect merely because it may be encoded numerically or categorically.

## 3. Numerical Eligibility Rule

A number does not establish Quantity identity.

`numeric field → inspect semantic responsibility → classify`

Product specifications, database fields, API parameters, spreadsheet columns, and test outputs must not be promoted automatically.

## 4. Measurability Rule

The fact that something can be measured does not prove that the term itself is a Quantity concept. The term may denote a Property, Condition, performance characteristic, metric, result, or another construct.

## 5. Value Completeness Rule

A quantity value should be interpretable with its Quantity identity and relevant unit/reference information. A bare number should not be treated as a universally meaningful quantity value.

## 6. Dimension Rule

Quantity dimension supports dimensional reasoning but does not determine semantic identity by itself. Dimensionless quantities remain eligible for Quantity classification when their measurable semantic responsibility is established.

## 7. Scale Rule

Nominal, ordinal, interval, and ratio scales describe measurement-scale characteristics. They do not replace Quantity identity.

## 8. Uncertainty Rule

Uncertainty qualifies knowledge about a value or result. It does not become the measured Quantity merely because it is numerically expressed.

## 9. Interval / Range Rule

An interval or range is a bounded set or region of values. It may constrain or qualify a quantity value, specification, condition, or result; it is not automatically a Quantity concept.

## 10. Imaging Classification Rule

Common imaging terms must be routed according to semantic responsibility.

| Candidate | Default V3.1 routing | Reason |
|---|---|---|
| Distance | Quantity | measurable spatial separation |
| Focal Length | Quantity | defined optical distance quantity |
| Wavelength | Quantity | measurable spectral-period quantity |
| Exposure Time | Quantity | measurable temporal duration |
| Illuminance | Quantity | photometric quantity |
| Luminance | Quantity | photometric quantity |
| Radiance | Quantity | radiometric quantity |
| Irradiance | Quantity | radiometric quantity |
| Spatial Frequency | Quantity | measurable spatial periodicity/frequency |
| Resolution | Deferred | responsibility varies by test/specification context |
| MTF | Deferred | transfer/performance construct requiring method context |
| SFR | Deferred | derived/test-method construct |
| Noise | Deferred | physical/statistical/performance meanings diverge |
| SNR | Deferred | derived comparison/metric semantics |
| Dynamic Range | Deferred | ratio/performance/metric usages diverge |
| Sensitivity | Candidate / cross-layer | may denote Property or quantity-like response depending context |

## 11. Existing Layer Protection

Quantity must not absorb concepts already owned by Conditions, Properties, Relations, Contexts, Facets, or States merely because those concepts have measurable attributes.

Examples:

`Temperature Condition → Condition`  
`Temperature → Quantity`

`Optical Distortion → Property`  
`measured distortion value → Quantity Value / Result context`

`Viewing Distance → Relation`  
`Distance → Quantity`

## 12. Canonicalization Test

A candidate fails Quantity admission when any of the following is true:

- its meaning depends primarily on a particular product field;
- it is only a value or literal;
- it is only a unit;
- it denotes the measurement activity;
- it denotes a measurement result;
- it is primarily an assessment metric;
- it is merely a model parameter or variable;
- its semantic responsibility is owned by another canonical layer;
- its meaning cannot be stabilized without an application-specific model.

## 13. Visitor Neutrality Rule

Visitor Universe categories must never determine Quantity identity. Audience-specific explanations may change entry depth, but the semantic concept, ID, boundaries, and canonical responsibility remain stable.
