# GIOP V3.1 — Modality Analysis Specification

**Status:** PROVISIONAL AUTHORING SPECIFICATION  
**Scope:** `02 SEMANTICS/modalities/`  
**Canonical Nucleus:** `SEM-MODALITY-GENERIC-001`

## 1. Purpose

This specification defines the semantic scope, authoring controls, candidate policy, evidence handling, visitor-depth behavior, and validation expectations for the Modality semantic folder.

The folder is a cross-layer semantic nucleus, not a catalogue of every imaging, sensory, interaction, or data modality.

## 2. Semantic Question

The governing question is:

> What recognized mode, channel, or manner distinguishes how information, signals, phenomena, acquisition, interaction, expression, representation, or experience is accessed or characterized?

The answer is the responsibility of Modality.

## 3. Canonical Responsibility

`SEM-MODALITY-GENERIC-001` owns the generic semantic responsibility for recognized mode/channel/manner differentiation.

Domain-specific terminology remains subject to separate evidence and promotion decisions.

## 4. Semantic Model

```text
MODALITY
  → recognized semantic mode/channel/manner
       → may characterize
          Acquisition / Observation / Perception / Interaction /
          Information or Data / Representation use
```

A Modality concept is not the bearer, occurrence, transformation, representation, or context that it characterizes.

## 5. Candidate Families

| Candidate ID | Preferred Name | Status | Decision basis |
|---|---|---|---|
| `SEM-MODALITY-IMAGING-001` | Imaging Modality | CANONICAL CANDIDATE / DEFERRED | Strong standards and imaging usage; requires independent generic-subtype test |
| `SEM-MODALITY-SENSORY-001` | Sensory Modality | CANONICAL CANDIDATE / DEFERRED | Strong scientific usage; requires boundary with Perception and Observer |
| `SEM-MODALITY-INTERACTION-001` | Interaction Modality | CANONICAL CANDIDATE / DEFERRED | Strong W3C usage; requires boundary with Activity and implementation components |
| `SEM-MODALITY-DATA-001` | Data Modality | CANONICAL CANDIDATE / DEFERRED | Strong AI usage; requires boundary with Representation, Format, and Data semantics |

No candidate is Active solely because it is common terminology.

## 6. Non-Candidates / Routed Semantics

`Multimodal` is not a single modality subtype; it concerns multiple modalities.

`Format`, `Encoding`, `Media Type`, and `Representation` remain in the Representation layer.

`Activity`, `Observation`, `Acquisition`, and `Processing` remain in Activities.

`Process` remains in Processes.

`Perception` remains in Perception.

`Condition`, `State`, `Context`, `Property`, `Quantity`, `Class`, and `Relation` retain their existing semantic responsibilities.

## 7. Evidence Policy

External standards and research are evidence for domain usage and semantic synthesis. They are not copied as GIOP definitions without analysis.

Relevant evidence includes DICOM modality terminology, HL7 FHIR ImagingStudy modality semantics, W3C Multimodal Interaction requirements/architecture, scientific sensory-modality literature, and multimodal AI literature.

Source statement, evidence, inference, synthesis, and canonical decision remain distinct.

## 8. Visitor Universe / Entry Depth

The same canonical record supports all visitor classes.

| Entry depth | Typical need | Required projection |
|---|---|---|
| Orientation | General/Curious | concise definition, simple examples, basic exclusions |
| Conceptual | Student/Educator/Enthusiast | distinctions, structure, terminology |
| Applied | Creative/Imaging/Science | imaging, sensing, observation, interaction examples |
| Technical | Engineering/AI/Systems | cross-layer mappings, domain ambiguity, validation |
| Formal | Standards/QA/Preservation/Machine | identity, status, provenance, evidence, validation, stable IDs |

Visitor categories do not create separate semantic entries.

## 9. Authoring Pattern

Canonical entries should use:

```text
Identity
→ 5W1H Orientation
→ Semantic Definition
→ Primary Responsibility
→ Core Semantic Structure
→ Core Distinctions
→ Domain Interpretations
→ Cross-Layer Significance
→ Technical / Domain Boundaries
→ Trust
→ Evidence and Provenance
→ Lifecycle
→ Relations / Dependencies
→ Retrieval Anchors
```

The sequence follows the established GIOP content architecture while allowing artifact-specific sections.

## 10. Machine Retrieval

Every substantive record must expose stable retrieval anchors for ID, title, type, status, version, definition, primary responsibility, relations, provenance, and validation.

A retrieved chunk must remain semantically intelligible without hidden conversational context.

## 11. Promotion Rule

Promotion requires:

1. stable identity;
2. independent semantic responsibility;
3. explicit definition;
4. boundary against neighboring concepts;
5. duplicate-authority check;
6. source/evidence provenance;
7. relation authority compliance;
8. lifecycle validity;
9. visitor-depth compatibility;
10. folder-level validation and Gate-J decision.

## 12. Exclusions

This folder must not become:

- a list of DICOM modality codes;
- a list of sensory organs;
- a list of AI data types;
- a format/media-type registry;
- a hardware/device catalogue;
- a procedure or technique library;
- a second Perception ontology;
- a multimodality relationship ontology.

## 13. Change Control

Material new evidence must first be evaluated against `SEM-MODALITY-GENERIC-001` and the candidate registry. A competing page must not be created merely to preserve an alternative interpretation.
