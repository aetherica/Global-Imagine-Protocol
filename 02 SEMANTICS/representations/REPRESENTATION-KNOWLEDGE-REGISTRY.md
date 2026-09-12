# Representation Knowledge Registry

**Status:** Active Semantic Knowledge Registry  
**Version:** 1.2.0  
**Purpose:** Retain representation-related concepts, decisions, evidence status, and routing without becoming a parallel canonical knowledge base.

## Registry Rules

The registry follows the GIOP Knowledge Entry & Canonicalization Rule:

`RETAIN → CLASSIFY → VERIFY → CONFLICT ANALYSIS → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE`

A registry record is not automatically canonical. Canonical semantic content is authoritative only in the appropriate semantic entry.

## Active Canonical Registry

| Candidate | Semantic responsibility | GIOP decision | Destination | Status |
|---|---|---|---|---|
| Representation | Information-bearing form | Distinct reusable semantic concept | `representation.md` | Active |
| Display | Presentation mechanism | Existing identity preserved | `display.md` | Active |
| Format | Structural/syntactic specification | Distinct from Representation | `format.md` | Active |
| Encoding | Coding/transformation scheme | Distinct from Format and Representation | `encoding.md` | Active |
| Serialization | Abstract-to-concrete expression | Distinct from resulting Representation and Activity | `serialization.md` | Active |
| Media Type | Interoperable data-type identification | Distinct from Format and Representation | `media-type.md` | Active |
| Compression | Representation-data transformation | Distinct from Encoding, Representation, and Fidelity | `compression.md` | Active |
| Packaging | Aggregation/containerization | Distinct from Representation and File | `packaging.md` | Active |
| Profile | Specification specialization | Distinct from Format and Conformance | `profile.md` | Active |

## Advanced Extension Intake

The following concepts were identified as meaningful coverage gaps in AI, robotics, computational representation, scene/world modeling, agent interaction, and programming-language practice. They are retained as controlled candidates pending independent promotion rather than being promoted merely from lexical prevalence.

| Candidate ID | Preferred Name | Primary responsibility | Decision |
|---|---|---|---|
| `SEM-REPRESENTATION-BELIEF-001` | Belief Representation | Representation of an agent's uncertain/probabilistic beliefs | Candidate — high priority |
| `SEM-REPRESENTATION-OBJECT-CENTRIC-001` | Object-Centric Representation | Representation organized around distinct objects/entities | Candidate — high priority |
| `SEM-REPRESENTATION-RELATION-CENTRIC-001` | Relation-Centric Representation | Representation organized around typed relations | Candidate — high priority |
| `SEM-REPRESENTATION-AFFORDANCE-001` | Affordance Representation | Representation of action possibilities/opportunities | Candidate — high priority |
| `SEM-REPRESENTATION-ACTION-001` | Action Representation | Information-bearing form encoding actions and their structure/parameters | Candidate — high priority |
| `SEM-REPRESENTATION-EVENT-001` | Event Representation | Information-bearing form encoding event occurrence and attributes | Candidate — high priority |
| `SEM-REPRESENTATION-SPATIOTEMPORAL-001` | Spatiotemporal Representation | Joint representation of spatial and temporal structure/change | Candidate — high priority |
| `SEM-REPRESENTATION-CAUSAL-001` | Causal Representation | Representation of causal variables/dependencies/structure | Candidate — high priority |
| `SEM-REPRESENTATION-PREDICTIVE-001` | Predictive Representation | Representation structured for prediction of future states/observations/outcomes | Candidate — high priority |
| `SEM-REPRESENTATION-NEURAL-FIELD-001` | Neural Field Representation | Field-based learned representation mapping inputs/coordinates to represented information | Candidate — high priority |
| `SEM-REPRESENTATION-PROGRAM-001` | Program Representation | Information-bearing form expressing program instructions/structure | Candidate — high priority |
| `SEM-REPRESENTATION-INTERMEDIATE-001` | Intermediate Representation | Computational representation used between program abstraction levels | Candidate — high priority |
| `SEM-REPRESENTATION-DIGITAL-TWIN-001` | Digital-Twin Representation | Representation of a physical/operational counterpart in a digital-twin system | Candidate — boundary review |
| `SEM-REPRESENTATION-SKILL-001` | Skill Representation | Information-bearing form expressing reusable skill structure/parameters | Candidate — Action/Model review |
| `SEM-REPRESENTATION-TRAJECTORY-001` | Trajectory Representation | Representation of ordered spatial/temporal evolution | Candidate — high priority |
| `SEM-REPRESENTATION-SCENE-001` | Scene Representation | Representation of scene entities, geometry, semantics, and relationships | Candidate — high priority |
| `SEM-REPRESENTATION-WORLD-001` | World Representation | Representation of broader environment/world state, structure, or dynamics | Candidate — Model boundary review |
| `SEM-REPRESENTATION-MAP-001` | Map Representation | Representation of spatial organization for mapping/navigation | Candidate — high priority |

## Routed / Dimensional Terms

Digital/Physical, Visual/Textual/Audio/Video, Multimodal, Structured/Unstructured, Machine-Readable/Interpretable/Actionable/Executable, Representation Granularity, Representation Abstraction, Representation Quality, and Representation Learning are not automatically independent canonical Representation concepts. Their primary responsibility may be modality, structural classification, property/evaluation, capability, or process.

Feature, Embedding, Latent, Tensor, and Neural Representation remain routed candidates because they can denote realizations or computational forms whose exact responsibility varies by field.

## Cross-Layer Controls

- State is not replaced by State Representation.
- Action execution remains an Activity; Action Representation is its information-bearing form.
- Process/Activity remain occurrences or temporal courses; process descriptions are Representations.
- Model remains a formal explanatory/predictive construct; representation of a model is not automatically the Model.
- Dataset, File, and Bitstream remain distinct storage/information entities.
- Perception remains the perceptual phenomenon/outcome; a representation of perceptual information is separate.

## Evidence Notes

The intake was informed by multiple source traditions: HTTP and Web standards, RDF/DCAT/PROV, preservation models, media-type practice, robotics scene/world representation, representation learning, world models, embodied AI, event-based sensing, and compiler/intermediate-representation practice. Source traditions are evidence for semantic synthesis, not GIOP authority.

## Promotion Rule

Every candidate must independently pass identity, primary responsibility, existing-entry check, boundary, evidence, relation authority, cross-layer validation, lifecycle, and retrieval gates before canonical promotion.

## Visitor Universe Note

No visitor-specific duplicate concepts are registered. Audience relevance remains entry depth and retrieval routing only.
