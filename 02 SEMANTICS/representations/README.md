# Representations

**Semantic Area:** Representation and Information-Bearing Forms  
**Status:** Active Canonical Scope + Controlled Extension Intake  
**Version:** 1.2.0  
**Primary Responsibility:** Information-bearing forms through which canonical information, results, resources, or other semantic content are expressed, exchanged, stored, presented, or made available for interpretation.

## Scope

The `representations` semantic area defines the canonical meaning of Representation and the principal semantic concepts required to describe information-bearing forms without collapsing representation, format, encoding, storage, presentation, perception, or conformance into one layer.

The generic nucleus is:

`SEM-REPRESENTATION-GENERIC-001 — Representation`

The current canonical batch also includes Display, Format, Encoding, Serialization, Media Type, Compression, Packaging, Profile, Belief Representation, and Object-Centric Representation. Their distinct responsibilities are preserved; the folder does not treat them as a universal inheritance hierarchy.

## Semantic Model

```text
Canonical Information / Result / Resource
                 |
                 v
          Representation
                 |
       +---------+---------+
       |         |         |
       v         v         v
     Format   Encoding   Display
       |         |
       v         v
 Media Type  Compression
       |
       v
 Serialization / Concrete Expression
                 |
                 v
              Packaging
                 |
                 v
            File / Stream

      Specialized Representation responsibilities
          ├── Belief Representation
          └── Object-Centric Representation
```

This is a coordination model, not a universal subclass hierarchy.

## Core Boundary

Representation is not synonymous with Information/Knowledge, Result, Dataset, File/Bitstream, Format, Encoding, Serialization activity, Media Type, Compression, Packaging, Display, Observation, Perception, Measurement Result, or Conformance.

A related concept must be routed through its own semantic responsibility or an appropriate relation/cross-layer reference rather than absorbed into Representation.

## Canonical Entry Set

| Semantic ID | Preferred Name | Responsibility | Status |
|---|---|---|---|
| `SEM-REPRESENTATION-GENERIC-001` | Representation | Information-bearing form | Active |
| `SEM-DISPLAY-001` | Display | Presentation system / mechanism | Active |
| `SEM-REPRESENTATION-FORMAT-001` | Format | Structural/syntactic specification | Active |
| `SEM-REPRESENTATION-ENCODING-001` | Encoding | Coding/transformation scheme | Active |
| `SEM-REPRESENTATION-SERIALIZATION-001` | Serialization | Abstract-to-concrete expression | Active |
| `SEM-REPRESENTATION-MEDIA-TYPE-001` | Media Type | Interoperable representation-data identification | Active |
| `SEM-REPRESENTATION-COMPRESSION-001` | Compression | Representation-data transformation | Active |
| `SEM-REPRESENTATION-PACKAGING-001` | Packaging | Aggregation/containerization | Active |
| `SEM-REPRESENTATION-PROFILE-001` | Profile | Specification constraint/extension/guidance | Active |
| `SEM-REPRESENTATION-BELIEF-001` | Belief Representation | Agent-relative belief, uncertainty, or epistemic state representation | Active |
| `SEM-REPRESENTATION-OBJECT-CENTRIC-001` | Object-Centric Representation | Object-organized information-bearing form | Active |

## Advanced Extension Intake

A first controlled extension dataset has been added for AI, robotics, computational, spatial, temporal, agent/action, and advanced information-bearing forms. It records material coverage gaps without prematurely forcing orthogonal dimensions into one hierarchy.

See `REPRESENTATION-ADVANCED-EXTENSION-CATALOG.md`.

The intake continues to prioritize Relation-Centric, Affordance, Action, Event, Spatiotemporal, Causal, Predictive, Neural Field, Program, Intermediate, Digital-Twin, Skill, Trajectory, Scene, World, and Map representations for independent promotion review.

Belief Representation and Object-Centric Representation have already passed independent promotion review. No remaining candidate is promoted by association.

## Multidimensional Organization Rule

Representation families must not be modeled as a single flat taxonomy when their classification dimensions are orthogonal. Digital/physical realization, modality, symbolicity, structure, abstraction, temporal scope, referent, agent coupling, uncertainty, and computational realization may intersect.

Therefore:

`Representation → multidimensional classification / specialized responsibility`

is preferred over a universal single-inheritance tree such as `Digital → Visual → Structured → ...`.

## Visitor Universe and Entry Depth

Visitor Universe does not create separate representation ontologies or audience-specific semantic copies. The same canonical entries support different entry depths and retrieval patterns. No ordinary semantic entry should contain a separate Visitor Universe section merely to duplicate this routing model.

## Authoring Standard

Representation entries follow the Foundation authoring pattern while remaining artifact-specific: identity/metadata, 5W1H orientation where useful, semantic definition, scope/structure, distinctions, boundary cases, technical significance, relations, provenance/evidence, trust/validation, lifecycle, and retrieval anchors.

Normative statements, explanations, examples, historical material, and implementation notes remain explicitly distinguishable.

## Provenance and Evidence

Evidence is drawn across standards, information architecture, preservation, data/AI, robotics, computer vision, programming-language, and world-model traditions. External specifications remain evidence sources rather than GIOP authority.

Important evidence families include RFC 9110; W3C RDF, DCAT, PROV, and Profiles; PREMIS; ISO 14721:2025; IANA media-type practice; robotics scene/world representation literature; representation-learning and world-model research; compiler/intermediate-representation practice; formal epistemology; and POMDP/probabilistic decision systems.

Object-Centric Representation promotion additionally draws on contemporary object-centric visual representation-learning research and peer-reviewed embodied-robotics surveys covering object-level representations, object slots/object files, pose, affordance, and manipulation.

## Cross-Layer Routing

- measurable aspect → `quantities`
- measured value → quantity/value semantics
- typed connection → `relations`
- actual action → `activities`
- transformation/progression → `processes`
- situational frame → `contexts`
- condition → `conditions`
- state → `states`
- perceptual outcome → `perception`
- entity identity → `classes`
- information-bearing form → `representations`

## Completion Principle

A representation-related topic is not canonical merely because a file exists or because it is common in research. Each extension requires semantic classification, existing-entry check, evidence review, boundary validation, relation validation, lifecycle assignment, and Foundation-gate compliance.
