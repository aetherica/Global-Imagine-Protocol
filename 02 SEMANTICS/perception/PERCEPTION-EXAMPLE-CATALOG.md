# GIOP V3.1 — Perception Example Catalog

**Artifact Type:** Semantic Example Catalog  
**Semantic Layer:** Perception  
**Version:** 1.0.0  
**Status:** Active  
**Authority:** GIOP

## Purpose

This catalog demonstrates semantic boundaries and Visitor Universe entry-depth behavior. Examples are explanatory and are not themselves canonical definitions.

## Example 1 — Brightness

### Orientation
Brightness is a perceptual attribute concerning how bright a stimulus or object appears to an observer.

### Expert Boundary
Brightness is not identical to photometric luminance. Luminance belongs to Quantity semantics; brightness is a perceptual attribute that may depend on stimulus, adaptation, surround, and observer conditions.

### Machine Routing
`Brightness → Perception / Perceptual Attribute`  
`Luminance → Quantity`  
`Brightness Rating → Response / Value / Result`

## Example 2 — Color Appearance

### Orientation
Colour appearance concerns how colour is perceptually experienced under relevant viewing and observer conditions.

### Expert Boundary
Colour appearance is not identical to the physical spectral stimulus or to a colourimetric representation. A colour appearance model may represent or predict aspects of it without becoming the appearance itself.

### Machine Routing
`Color Appearance → controlled Perception specialization`  
`Spectral Response → Property`  
`Wavelength → Quantity`  
`Observer Model → Model`

## Example 3 — Perceptual Organization

### Orientation
Perceptual organization concerns the organization of sensory information into coherent perceptual structures.

### Expert Boundary
Grouping, figure-ground organization, contour integration, and completion are phenomena within this research family. They are not automatically separate canonical roots.

### Machine Routing
`Perceptual Organization → Perception candidate`

## Example 4 — Perceptual Constancy

### Orientation
Perceptual constancy concerns relative stability of perceptual appearance or experience despite relevant changes in input or conditions.

### Expert Boundary
Colour, size, and shape constancy are research families. Constancy is not a physical property and is not synonymous with invariance of the stimulus.

### Machine Routing
`Perceptual Constancy → Perception candidate`  
`Condition → Condition`  
`Stimulus change → input/physical semantics`

## Example 5 — Motion Perception

### Orientation
Motion perception concerns perceived movement or motion-related perceptual phenomena.

### Expert Boundary
Measured velocity or temporal frequency belongs to Quantity semantics when appropriate. Motion perception remains observer-relative.

### Machine Routing
`Motion Perception → Perception candidate`  
`Velocity → Quantity`  
`Temporal Context → Context`

## Example 6 — Image-Quality Perception

### Orientation
Image-quality perception concerns observer-relative perceptual evaluation of image quality.

### Expert Boundary
A quality rating is evidence or result data. A quality metric or prediction model is not identical to the perceptual phenomenon.

### Machine Routing
`Image-Quality Perception → Perception candidate`  
`Quality Rating → Value / Result`  
`Quality Metric → Metric`  
`Prediction Model → Model`

## Example 7 — Illusion

### Orientation
A perceptual illusion is a perceptual phenomenon in which experienced appearance does not straightforwardly correspond to an assumed physical interpretation.

### Expert Boundary
An illusion is not automatically measurement error, corrupted data, or a false representation.

### Machine Routing
`Perceptual Illusion → Perception candidate`

## Visitor Universe Entry-Depth Example

The same canonical concept can be exposed at different depths:

| Entry depth | Perception presentation |
|---|---|
| Beginner | What perception means and why it differs from observation and measurement |
| Practitioner | Major phenomena, perceptual attributes, conditions, and application relevance |
| Expert | Observer/task dependence, psychophysics, evidence, formal boundaries, and specialized research families |
| Machine / AI | Stable ID, definition, primary responsibility, relations, provenance, validation, and retrieval anchors |

These are access-depth projections of one knowledge source, not separate semantic variants.

## Non-Canonical Examples

The following must not be treated as canonical Perception identities merely because they appear in examples:

- `Perception under low illumination` — normally Perception qualified by a Condition.
- `Perception at 2 degrees` — normally Perception qualified by spatial/viewing parameters.
- `Observer response = 4` — response/value/result semantics, not Perception.
- `Model predicts brightness = 4` — model output, not Perception itself.
- `Image file containing a perceptual label` — Representation, not Perception.
