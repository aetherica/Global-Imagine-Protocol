# GIOP V3.1 — Modality Knowledge Registry

**Version:** 1.0.0  
**Status:** PROVISIONAL REGISTRY  
**Purpose:** Retain semantic decisions, evidence status, candidate families, conflicts, routing, and unresolved promotion questions without becoming a parallel canonical knowledge base.

## Registry Principle

The registry records the decision history around Modality. Canonical semantic meaning remains in `modality.md`.

## Registry Records

| ID | Recovered concept / claim | Semantic type | Evidence status | Canonical status | GIOP decision |
|---|---|---|---|---|---|
| `SEM-MODALITY-GENERIC-001` | Modality as recognized mode/channel/manner | Semantic concept | Multi-domain convergence with meaningful domain variation | PROVISIONAL | Canonical nucleus authored; folder validation required |
| `SEM-MODALITY-IMAGING-001` | Imaging Modality | Domain semantic concept | Strong standards/imaging usage | CANONICAL CANDIDATE / DEFERRED | Retain for independent subtype analysis |
| `SEM-MODALITY-SENSORY-001` | Sensory Modality | Scientific semantic concept | Strong neuroscience/perception usage | CANONICAL CANDIDATE / DEFERRED | Retain; distinguish from Perception and Observer |
| `SEM-MODALITY-INTERACTION-001` | Interaction Modality | Interaction semantic concept | Strong W3C usage | CANONICAL CANDIDATE / DEFERRED | Retain; distinguish from Activity and implementation component |
| `SEM-MODALITY-DATA-001` | Data Modality | AI/data semantic concept | Strong multimodal AI usage | CANONICAL CANDIDATE / DEFERRED | Retain; distinguish from Representation/Format/Encoding |

## Evidence Interpretation

DICOM demonstrates modality terminology for equipment type, function, and technique within a controlled imaging vocabulary. HL7 FHIR demonstrates modality as an imaging-study/series semantic field. W3C demonstrates modality as an interaction communication mode/channel. Scientific literature demonstrates sensory modality usage. Multimodal AI literature demonstrates data/information modality usage.

These sources converge on recognized mode/channel differentiation while differing in domain scope. GIOP therefore synthesizes a cross-layer nucleus and retains domain families as candidates.

## Conflict / Ambiguity Record

No unresolved contradiction blocks the generic nucleus.

The principal ambiguity is lexical: `modality` can denote equipment-related, acquisition-related, sensory, interaction, or data-related meanings depending on domain. This is treated as scope variation, not silently averaged into a single domain-specific definition.

## Routing Decisions

`Format`, `Encoding`, `Media Type`, and `Representation` → Representation layer.  
`Observation`, `Acquisition`, `Processing`, and other actual occurrences → Activities.  
`Process` → Processes.  
`Perception` → Perception layer.  
`Condition`, `State`, `Context`, `Property`, `Quantity`, `Class`, and `Relation` → their existing semantic layers.

## Unresolved Promotion Questions

1. Does each candidate constitute a stable reusable subtype rather than a domain vocabulary family?
2. Is its semantic axis genuinely subordinate to generic Modality?
3. Can its boundary remain stable across relevant GIOP domains?
4. Does it require a distinct canonical identity or only terminology mapping?
5. Which existing canonical relations are sufficient for its assertions?

## Registry Non-Authority Rule

This registry does not create semantic authority. Candidate entries remain non-canonical until independently promoted.
