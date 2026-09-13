# Material — Analysis Specification

**Status:** IMPLEMENTATION-COMPLETE — CLASS-ROUTED DOMAIN COORDINATION
**Canonical owner:** `SEM-CLASS-MATERIAL-001`

## Analysis Objective

Determine the semantic responsibility of Material-related knowledge without creating a duplicate semantic layer beneath or beside the canonical Material Class.

## Research Dimensions

1. Chemistry and terminology: substance, material, composition, and reference-material meanings.
2. Materials science and engineering: material as a physically realized substance/form distinct from a generic physical object and from its properties.
3. Formal ontology: material/entity distinctions and material participation in larger objects.
4. Metrology and characterization: measurement, reference material, quantity, result, and evidence boundaries.
5. Imaging and optics: material-dependent interaction with radiation and distinction between material and observed appearance.
6. Textile and garment domains: textile/material boundaries and prevention of generic Material absorbing textile-specific semantics.
7. GIOP internal architecture: Class, Property, Condition, State, Quantity, Activity, Process, Representation, Result, Provenance, Textile, and Garment.

## Evidence Synthesis

IUPAC uses context-dependent meanings for material. Its 2025 Gold Book entry for `material` gives a thermal-analysis meaning tied to the substance studied and sampled; its `chemical substance` entry separately defines constant-composition matter. IUPAC's 2024 recommendation on materials chemistry emphasizes design, preparation, characterization, processing, and useful properties, showing that material terminology spans entity, activity, and property dimensions and therefore cannot be reduced to one of those dimensions alone. citeturn852642search2turn852642search5turn852642search0

EMMO domain guidance similarly distinguishes Material from ChemicalSubstance and PhysicalObject, treating material as a physical realization with composition, structure, and form while a physical object is a particular entity existing in space and time. NIST's materials schema takes a pragmatic sample/specimen/material view and supports the observation that application context changes the precise granularity of material descriptions. citeturn852642search1turn852642search3

Scientific representation literature shows that models, photographs, diagrams, measurements, and other information artifacts can represent materials or material-dependent phenomena without becoming the represented material. This supports GIOP's existing non-collapse between Material and Representation. citeturn827914search0turn827914search1

## Competing Interpretations

### A — Material as a separate semantic layer
Rejected. GIOP already assigns Material to the canonical Class layer. Creating a second `Material` layer would violate the established primary-responsibility rule.

### B — Material as a Property
Rejected. Material identifies a physical entity or substance/medium; properties characterize it.

### C — Material as a Quantity or Measurement Result
Rejected. Material can be the measurand or subject of characterization; measured values and results remain Quantity/Activity/Result semantics.

### D — Material as Object
Rejected as a general collapse. A particular object may be made from material, contain material, or present a material surface, but Material and Object have distinct identity responsibilities.

### E — Material as Chemical Substance
Not universally valid. Chemical substance is one important scientific interpretation, but engineering materials can be defined by physical form, structure, processing, morphology, or application context beyond chemical composition alone. citeturn852642search5turn852642search1

### F — Material as a domain coordination subject routed to the existing Class
Retained. This is the GIOP-compatible interpretation.

## Candidate Vocabulary

Retain as controlled domain vocabulary, not automatic top-level concepts:

- material type
- engineering material
- optical material
- reference material
- material sample
- specimen
- composite material
- coating material
- porous material
- biological material
- textile material

Each term requires independent ownership analysis before promotion.

## Semantic Ownership Decision

Primary responsibility remains `SEM-CLASS-MATERIAL-001`. The material folder is a coordination, routing, and governance surface, not an alternate authority.

## Promotion Decision

No new `SEM-MATERIAL-*` concept is admitted by this pass. Any future specialized material concept must demonstrate independent semantic responsibility, non-collapse from the existing Material Class, and a need for a distinct lifecycle, evidence, and retrieval model.
