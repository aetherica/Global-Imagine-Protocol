# GIOP V3.1 — Perception Analysis Specification

**Artifact Type:** Semantic Layer Analysis Specification  
**Semantic Layer:** Perception  
**Version:** 1.1.0  
**Status:** Active  
**Authority:** GIOP

## 1. Purpose

This specification converts verified research and GIOP Foundation rules into an implementable semantic contract for the Perception layer.

The layer is intentionally broad in subject matter but narrow in semantic responsibility. It owns reusable semantics whose primary responsibility is an observer-relative perceptual phenomenon, experience, organization, appearance, or perceptual attribute.

## 2. Evidence Basis

The implementation is informed by:

- CIE International Lighting Vocabulary and colour terminology for visual sensation, perceived colour, appearance, brightness, lightness, colourfulness, chroma, and contrast distinctions.
- Vision-science literature on perceptual organization, grouping, figure-ground organization, constancy, illusion, depth, motion, and material perception.
- Psychophysics and subjective image-quality methodology for the distinction among stimulus, task, observer, response, measurement, and perceptual phenomenon.
- Observer-model literature for the distinction between a perceptual phenomenon and a mathematical, computational, ideal, or empirical model of observer response.
- Multisensory and perception-action literature for domain breadth and for avoiding a visual-only definition.
- GIOP Foundation architecture, authoring, provenance, lifecycle, canonicalization, and cross-layer controls.

External evidence establishes or supports semantic distinctions; it does not by itself determine GIOP canonical identity.

## 3. Primary Semantic Responsibility

**Perception** denotes an observer-relative perceptual phenomenon, experience, organization, appearance, or perceptual attribute associated with sensory or other input information under relevant qualifying conditions.

The generic concept does not require a particular biological mechanism, conscious report, numerical response, or implementation.

## 4. Scope Model

Perception may concern:

- perceptual experience;
- perceptual organization;
- perceptual appearance;
- perceptual attributes;
- spatial and temporal perceptual phenomena;
- perceptual constancy and transformation;
- perceptual illusion and other non-veridical phenomena;
- specialized perceptual domains such as visual, colour, material, image-quality, and multisensory perception.

These are semantic content families, not an automatic universal ontology hierarchy.

## 5. Governing Semantic Chain

A useful evidence and qualification pattern is:

`Input / Stimulus → Observer + Task + Context / Condition → Perceptual Phenomenon`

A research establishment pattern may extend to:

`Stimulus → Procedure / Task → Observer → Response / Evidence → Measurement / Analysis → Scoped Perceptual Claim`

The latter is an evidence pathway, not a definition of perception.

## 6. Perceptual Experience

Perceptual experience concerns the experienced aspect of perception without making consciousness a universal identity criterion.

A perceptual concept must not be defined solely as a conscious verbal report. Reportability, awareness, and consciousness may qualify a perceptual assertion but are not interchangeable with perception itself.

## 7. Perceptual Organization

Perception includes organization of input into perceptually coherent structures. Relevant research phenomena include grouping, figure-ground organization, contour integration, completion, segmentation, and related structural organization.

These phenomena remain content families unless an independently reusable semantic responsibility justifies canonical promotion.

## 8. Perceptual Appearance

Appearance concerns how an entity, surface, object, image, or stimulus is perceptually experienced with respect to attributes such as colour, size, shape, texture, gloss, transparency, or opacity.

Visual Appearance and Color Appearance are strong controlled specializations. They must remain distinct from physical Property, Quantity, stimulus, and Representation semantics.

## 9. Perceptual Attributes

Perceptual attributes are characteristics of perceptual experience or appearance, not automatically physical properties or quantities.

Research-backed examples include hue, brightness, lightness, colourfulness, and chroma.

Example boundary:

`Luminance → Quantity`  
`Brightness → Perceptual Attribute`  
`Brightness Rating → Response / Value / Result semantics`

A perceptual attribute may be quantified without becoming identical to the quantity or metric used to quantify it.

## 10. Spatiotemporal Perception

Spatial, temporal, depth, and motion perception are recognized content families.

They may be qualified by spatial field, viewing geometry, temporal regime, stimulus dynamics, and task. Physical spatial or temporal quantities remain in their appropriate semantic layers.

## 11. Perceptual Constancy and Transformation

Perceptual constancy concerns relative stability of perceptual experience or appearance despite relevant changes in input or conditions. Colour, size, and shape constancy are representative research families.

Perceptual illusion and other non-veridical perceptual phenomena are also within scope when the primary responsibility is the perceptual phenomenon rather than measurement error or false data.

## 12. Observer, Stimulus, Task, and Qualifiers

A perceptual assertion may be qualified by:

- observer or observer population;
- stimulus or input;
- task or purpose;
- spatial field and viewing geometry;
- temporal regime;
- adaptation;
- illumination and surround;
- capture or display conditions;
- expectation or prior experience;
- relevant context and condition;
- reporting or measurement method.

Qualifiers do not become Perception concepts merely because they occur in a perceptual assertion.

## 13. Psychophysical Establishment

Psychophysics provides methods for investigating perceptual phenomena by controlling stimuli and tasks and recording observer responses. Thresholds, ratings, response times, sensitivity measures, discrimination results, and derived metrics are evidence or characterization outputs.

`Psychophysical response ≠ Perception`  
`Measurement result ≠ Perception`  
`Metric ≠ Perception`

## 14. Cognition Boundary

Perception and cognition may interact closely. GIOP therefore does not impose a universal physiological pipeline or claim that perception is independent of cognition.

However, recognition, categorization, understanding, reasoning, decision, and action are not automatically Perception. They require their own responsibility analysis when introduced as canonical concepts.

## 15. Sensation Boundary

Sensation and perception are distinguished as semantic responsibilities while acknowledging that scientific usage and physiological models vary.

`Sensation ≠ Perception`

GIOP does not require a universal serial pipeline from sensation to perception; it only requires that the concepts not be silently collapsed.

## 16. Model Boundary

Observer Model, computational observer, ideal observer, or other predictive/explanatory models may model perceptual response. They are not the perceptual phenomenon itself.

`MODELED ≠ EXPERIENCED`

## 17. Representation Boundary

Images, reports, datasets, labels, equations, feature vectors, and software objects may represent perceptual information. None becomes Perception solely by representing it.

## 18. Canonicalization Criteria

A candidate should enter the Perception layer only when:

1. Its primary responsibility is perceptual phenomenon, experience, organization, appearance, or perceptual attribute.
2. It has an independently reusable semantic boundary.
3. It is not a duplicate of Observer, Sensation, Property, Quantity, Value, Condition, Context, State, Observation, Activity, Process, Model, Representation, Metric, or cognition-level responsibility.
4. Evidence supports the intended scope.
5. Context, observer, task, and condition can be represented as qualifiers where appropriate rather than forcing unnecessary concept proliferation.

## 19. Candidate Disposition

High-confidence controlled candidates include Visual Perception, Color Perception, Visual Appearance, Color Appearance, Spatial Perception, Temporal Perception, Depth Perception, Motion Perception, Material Perception, Multisensory Perception, Image-Quality Perception, Perceptual Organization, Perceptual Constancy, and Perceptual Illusion.

Additional research-backed candidates include Ensemble Perception, Perceptual Similarity, Visual Comfort, Naturalness, Sense of Presence, and Affordance Perception.

Recognition, Scene Understanding, Categorization, Perceptual Decision, Perceptual Report, Perceptual Metric, Perceptual Capability, and Machine Perception remain deferred or cross-layer candidates until independent responsibility is established.

## 20. Visitor Universe Implementation

Visitor Universe is an access-depth and retrieval concern. It does not create visitor-specific semantic variants.

The same canonical Perception concept should support progressively deeper access:

- orientation: identity, plain-language definition, key distinctions;
- practical: major perceptual phenomena and qualifiers;
- expert: psychophysics, evidence, boundaries, and specialized terminology;
- machine: stable ID, definition, relations, provenance, validation, and deterministic retrieval anchors.

No ordinary canonical Perception entry should contain a `Visitor Universe` semantic section.

## 21. Validation Requirements

Before canonical promotion or closure, verify:

- identity and responsibility are stable;
- research claims are distinguished from GIOP synthesis;
- all cross-layer references resolve;
- no candidate is silently promoted by common usage alone;
- evidence scope and limitations are visible;
- lifecycle and version are valid;
- machine retrieval remains self-contained;
- Visitor Universe remains outside semantic identity.

## 22. Open Questions

Future work may determine whether individual specialized concepts require canonical promotion. Such promotion must be independently gated and must not reopen the generic Perception identity without evidence of semantic failure.
