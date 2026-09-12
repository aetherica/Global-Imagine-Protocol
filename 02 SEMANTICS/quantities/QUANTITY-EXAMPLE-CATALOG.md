# Quantity Example Catalog

**Artifact Type:** Semantic Example / Boundary Test Catalog  
**Semantic Layer:** Quantity  
**Version:** 1.0.0  
**Status:** Active

## Canonical Examples

| Concept | Semantic ID | Decision | Primary reason |
|---|---|---|---|
| Quantity | `SEM-QUANTITY-GENERIC-001` | Canonical | reusable measurable semantic concept |
| Distance | `SEM-QUANTITY-DISTANCE-001` | Canonical | measurable spatial separation |
| Temperature | `SEM-QUANTITY-TEMPERATURE-001` | Canonical | physical thermodynamic quantity |
| Focal Length | `SEM-QUANTITY-FOCAL-LENGTH-001` | Canonical | defined optical distance quantity |
| Wavelength | `SEM-QUANTITY-WAVELENGTH-001` | Canonical | measurable wave spatial period |
| Exposure Time | `SEM-QUANTITY-EXPOSURE-TIME-001` | Canonical | measurable temporal duration in imaging |
| Illuminance | `SEM-QUANTITY-ILLUMINANCE-001` | Canonical | photometric quantity |
| Luminance | `SEM-QUANTITY-LUMINANCE-001` | Canonical | photometric directional quantity |
| Radiance | `SEM-QUANTITY-RADIANCE-001` | Canonical | radiometric directional quantity |
| Irradiance | `SEM-QUANTITY-IRRADIANCE-001` | Canonical | radiometric incident power density |
| Spatial Frequency | `SEM-QUANTITY-SPATIAL-FREQUENCY-001` | Canonical | measurable spatial frequency |

## Deferred / Controlled Examples

### Resolution

Deferred because the term can denote a performance characteristic, limiting capability, criterion, or method-specific result.

### MTF

Deferred from generic Quantity because it is a transfer-function/performance characterization dependent on method and system context.

### SFR

Deferred because the term commonly denotes a derived test/analysis construct rather than an unqualified Quantity concept.

### Noise

Deferred because physical noise phenomena, statistical descriptors, signal components, and performance uses can diverge semantically.

### SNR

Deferred because it is generally a derived comparison between signal and noise quantities and may function as a metric.

### Dynamic Range

Deferred because ratio, logarithmic, performance, and specification usages require context-sensitive routing.

### Sensitivity

Controlled candidate because it can denote a characteristic or response concept and may be quantified in domain-specific ways.

### Pixel Pitch

Controlled candidate. The term can denote a physical spatial separation within a sensor/display structure and should be validated against the relevant Class, Property, and Quantity responsibilities before final admission.

### Frame Rate

Controlled candidate. It is naturally frequency-like but may be used as a system operating specification or temporal sampling characteristic. A dedicated canonical entry requires cross-layer validation.

### F-number

Controlled candidate. It is a dimensionless optical ratio used as a camera/lens parameter and may have strong Quantity characteristics, but its canonical responsibility must be separated from parameter/configuration semantics.

## Routed Elsewhere / Negative Examples

### Quantity Value

Not a Quantity concept. It expresses a magnitude associated with a Quantity.

### Unit

Not a Quantity concept. It provides a measurement/reference convention for expressing values.

### Measurement

Not a Quantity concept. It denotes the activity by which a value is established.

### Measurement Result

Not a Quantity concept. It is information produced by a measurement activity.

### Optical Distortion

Property-layer concept in current GIOP architecture. Numerical distortion results may involve quantities but do not change Property identity.

### Temperature Condition

Condition-layer concept. A temperature value can characterize it, but the contextual condition is not the Quantity.

### Viewing Distance

Relation-layer concept in the current corpus. Distance is the associated Quantity.

### Focus State

State-layer concept. Focal length remains a Quantity.

## Boundary Test Questions

For any new candidate ask:

1. What measurable aspect does the term identify?
2. Is that aspect reusable independently of a particular value?
3. Is it distinct from a Property?
4. Is it distinct from a Value and Unit?
5. Is it distinct from Measurement and Measurement Result?
6. Is it merely a Metric, Parameter, or Variable role?
7. Does an existing Quantity already own the responsibility?
8. Does the candidate remain stable across relevant domains?
9. Can its value be interpreted with an explicit reference/scale where required?
10. Can machines resolve its identity independently of a particular implementation?

## Visitor Universe Test

Every example must remain semantically identical for all 45 Visitor Universe categories. Only explanatory depth and navigation may change.
