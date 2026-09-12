# Quantity Cross-Layer Validation

**Artifact Type:** Cross-Layer Semantic Validation  
**Semantic Layer:** Quantity  
**Version:** 1.0.0  
**Status:** Active

## Purpose

This artifact validates Quantity ownership against completed GIOP semantic layers and prevents semantic duplication during corpus expansion.

## Responsibility Matrix

| Layer | Primary question | Quantity boundary |
|---|---|---|
| Class | What kind of entity is this? | Quantity is not an entity class |
| Property | What characteristic is attributable? | A Property may be quantified; it is not automatically a Quantity |
| Condition | What circumstance/condition applies? | A Quantity may describe or qualify a Condition |
| State | What recognized mode exists at a temporal locus? | A Quantity can characterize a State |
| Relation | What typed connection exists? | Quantity may be the subject/object/value of a Relation |
| Context | In what frame is something interpreted/measured? | Quantity is specified and measured within Context |
| Facet | How are concepts organized? | Quantity concepts may be facet members |
| Activity | What action is performed? | Measurement is an Activity; Quantity is its target/measurand where applicable |
| Process | What transformation occurs? | Quantity can characterize inputs/outputs/process conditions |
| Representation | How is information encoded? | A quantity can be represented in many formats |
| Perception | What is experienced/interpreted perceptually? | Perceived attributes are not automatically physical Quantities |

## Critical Test Cases

### Temperature

`Temperature` → Quantity  
`Temperature Condition` → Condition

A temperature value may qualify a condition without changing the condition's semantic type.

### Distance

`Distance` → Quantity  
`Viewing Distance` → Relation / relation-qualified quantity

The quantity expresses separation; the viewing relation specifies the semantic connection between viewer and viewed target.

### Focal Length

`Focal Length` → Quantity

It may function as an optical-system parameter in an engineering model, but that role does not make `Parameter` its canonical semantic owner.

### Optical Distortion

`Optical Distortion` → Property

A numerical measurement associated with distortion does not retroactively convert the Property concept into Quantity.

### Sensitivity

`Sensitivity` requires controlled classification because the term can denote a characteristic, response property, or quantity-like measurable concept depending on domain and normative definition.

### Resolution

`Resolution` remains deferred because imaging, display, metrology, and product-specification uses do not guarantee one stable semantic responsibility.

### Dynamic Range

`Dynamic Range` remains deferred pending resolution of its ratio, logarithmic, performance, and metric usages.

### Noise / SNR

`Noise` and `SNR` remain deferred because their physical, statistical, performance, and derived-metric interpretations require context-sensitive classification.

## Measurement Boundary

A Quantity can be the target of measurement. The measurement activity, measuring system, measurement result, uncertainty, method, and provenance remain separately identifiable.

## Context Boundary

A Quantity can be interpreted in capture, measurement, viewing, operational, processing, or application contexts. Context qualifies use; it does not become Quantity identity.

## Condition Boundary

Environmental and optical conditions can affect quantity values and measurement validity. Condition remains the contextual circumstance rather than the measurable aspect itself.

## State Boundary

A state may have quantitative characteristics. Quantitative characterization does not make the state a Quantity.

## Machine Validation Rules

A compliant machine interpretation should reject these equivalences:

`Quantity = Value`  
`Quantity = Unit`  
`Quantity = Measurement`  
`Quantity = Result`  
`Quantity = Property`  
`Quantity = Metric`  
`Quantity = Parameter`  
`Quantity = Variable`  
`Quantity = Condition`  
`Quantity = State`

It should instead model the concepts as related but distinct where evidence requires.

## Visitor Universe Validation

All 45 Visitor Universe categories consume the same Quantity concepts. The layer must not create category-specific Quantity meanings.

Entry depth may vary:

`orientation → practical use → formal semantics → metrology/technical detail → machine reasoning`

The semantic ID and canonical definition remain unchanged.

## Validation Result

Quantity has a distinct semantic responsibility and can coexist cleanly with the completed Conditions, Classes, Properties, Relations, Contexts, Facets, and States layers when the boundaries above are enforced.
