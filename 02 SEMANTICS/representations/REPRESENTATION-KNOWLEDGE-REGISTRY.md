# Representation Knowledge Registry

**Status:** Active Semantic Knowledge Registry  
**Version:** 1.3.0  
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
| Belief Representation | Agent-relative belief, uncertainty, or epistemic-state representation | Distinct reusable specialized Representation concept | `belief-representation.md` | Active |

## Advanced Extension Intake

The following concepts remain controlled candidates pending independent promotion:

| Candidate ID | Preferred Name | Primary responsibility | Decision |
|---|---|---|---|
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

`SEM-REPRESENTATION-BELIEF-001` has been removed from this controlled-candidate table because it passed independent promotion review and is now Active canonical.

## Routed / Dimensional Terms

Digital/Physical, Visual/Textual/Audio/Video, Multimodal, Structured/Unstructured, Machine-Readable/Interpretable/Actionable/Executable, Representation Granularity, Representation Abstraction, Representation Quality, and Representation Learning are not automatically independent canonical Representation concepts. Their primary responsibility may be modality, structural classification, property/evaluation, capability, or process.

Feature, Embedding, Latent, Tensor, and Neural Representation remain routed candidates because they can denote realizations or computational forms whose exact responsibility varies by field.

## Cross-Layer Controls

- State is not replaced by State Representation.
- Belief Representation expresses an agent-relative epistemic state; it does not replace `SEM-STATE-GENERIC-001`.
- Action execution remains an Activity; Action Representation is its information-bearing form.
- Process/Activity remain occurrences or temporal courses; process descriptions are Representations.
- Model remains a formal explanatory/predictive construct; representation of a model is not automatically the Model.
- Dataset, File, and Bitstream remain distinct storage/information entities.
- Perception remains the perceptual phenomenon/outcome; a representation of perceptual information is separate.

## Evidence Notes

The intake was informed by multiple source traditions: HTTP and Web standards, RDF/DCAT/PROV, preservation models, media-type practice, robotics scene/world representation, representation learning, world models, embodied AI, event-based sensing, compiler/intermediate-representation practice, formal epistemology, and POMDP/probabilistic decision systems. Source traditions are evidence for semantic synthesis, not GIOP authority.

Belief Representation promotion was specifically supported by formal treatments of qualitative and graded belief representation, POMDP belief-state formulations in which beliefs represent probability distributions over possible world states, and robotics/AI work using learned or approximate belief representations for decision-making under partial observability.

## Promotion Rule

Every candidate must independently pass identity, primary responsibility, existing-entry check, boundary, evidence, relation authority, cross-layer validation, lifecycle, and retrieval gates before canonical promotion.

Belief Representation passed these gates without creating a new relation authority or collapsing belief, state, observation, measurement, model, or action semantics.

## Visitor Universe Note

No visitor-specific duplicate concepts are registered. Audience relevance remains entry depth and retrieval routing only.
