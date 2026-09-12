# Modality

> A recognized semantic mode, channel, or manner through which information, signals, phenomena, acquisition, interaction, expression, representation, or experience are differentiated or accessed.

**Semantic ID:** `SEM-MODALITY-GENERIC-001`  
**Preferred Name:** Modality  
**Artifact Type:** Semantic Definition  
**Semantic Class:** Modality  
**Primary Responsibility:** Recognized semantic mode/channel/manner for differentiating or characterizing access, acquisition, interaction, expression, representation, or experience  
**Status:** PROVISIONAL  
**Version:** 1.0.0  
**Authority:** GIOP V3.1 Semantic Layer  
**Scope:** Cross-layer semantic nucleus; domain-specific modality families remain separately governed.  
**Provenance:** GIOP semantic synthesis informed by DICOM modality terminology, HL7 FHIR ImagingStudy modality semantics, W3C Multimodal Interaction work, neuroscience/perception literature, and multimodal AI literature.  
**Validation:** Initial scoped validation completed; promotion to ACTIVE requires folder-level validation gates.  
**Related IDs:** `SEM-CLASS-OBSERVER-001`, `SEM-PERCEPTION-GENERIC-001`, `SEM-ACTIVITY-GENERIC-001`, `SEM-ACTIVITY-OBSERVATION-001`, `SEM-ACTIVITY-ACQUISITION-001`, `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-FORMAT-001`, `SEM-REPRESENTATION-ENCODING-001`, `SEM-CONTEXT-GENERIC-001`, `SEM-PROCESS-GENERIC-001`

## 5W1H Orientation

### What

Modality identifies a recognized mode, channel, or manner in which a phenomenon, signal, information, interaction, acquisition, expression, representation, or experience is differentiated or accessed.

It is a semantic descriptor rather than a universal device, activity, process, format, or perceptual entity.

### Why

Imaging and information systems use the word modality across multiple domains. Without a generic semantic boundary, equipment types, acquisition techniques, sensory pathways, data types, formats, and interaction channels can be incorrectly treated as equivalent concepts.

GIOP uses Modality as a common semantic nucleus while preserving domain-specific meanings and terminology under controlled status.

### Who

The concept is relevant to general visitors, learners, educators, imaging practitioners, camera and sensor engineers, imaging and color scientists, computer-vision and AI researchers, multimodal-system engineers, standards professionals, archivists, and machine-readable consumers.

### Where

Modality may characterize sensing, imaging acquisition, observation, perception, human-computer interaction, information exchange, data organization, representation use, display or other domains where a recognized mode/channel distinction is meaningful.

### When

A modality designation applies within a defined semantic, operational, technical, perceptual, or application scope. A modality may remain stable across an activity or representation, or may vary when the relevant mode changes.

### How

A modality is established by identifying the recognized mode/channel/manner that differentiates the relevant access, acquisition, interaction, expression, representation, or experience. The designation must be interpreted with its domain, scope, evidence, and terminology authority.

## Semantic Definition

**Modality** is a reusable semantic concept denoting a recognized mode, channel, or manner through which information, signals, phenomena, acquisition, interaction, expression, representation, or experience are differentiated or accessed.

Modality does not, by itself, identify the bearer, device, activity, process, representation, format, encoding, perception, or context in which the modality occurs.

A modality designation may be domain-specific. The same lexical term may therefore have different but related technical uses across imaging, sensing, interaction, perception, and data/AI systems. Such uses must not be silently collapsed into one domain-specific definition.

## Primary Semantic Responsibility

The primary responsibility of this concept is to provide a stable cross-layer semantic identity for **mode/channel/manner differentiation**.

It supports controlled description of how a relevant phenomenon, information flow, acquisition, interaction, or experience is distinguished without becoming the semantic authority for the participating entity or activity.

## Core Semantic Structure

```text
Modality
    ├── recognized mode / channel / manner
    ├── domain or scope
    ├── applicable semantic target
    ├── terminology / authority
    ├── evidence and provenance
    └── optional contextual or temporal qualification
```

A modality concept may participate in assertions concerning an Activity, Process, Observer, Perception, Representation, Context, or other eligible semantic element. The assertion and its qualification remain distinct from the Modality concept itself.

## Core Distinctions

### Modality vs Class

A Class identifies a kind of entity. Modality identifies a recognized mode/channel/manner. A camera, lens, sensor, display, observer, or measuring system is not automatically a modality.

### Modality vs Property

A Property denotes an attributable characteristic. Modality is not a generic physical or measurable characteristic. A sensor's spectral response may be a Property while the sensing modality identifies the recognized sensing mode.

### Modality vs Condition

A Condition describes a contextual condition or circumstance. Modality describes the relevant mode/channel. A low-light condition may affect an imaging activity conducted using a particular modality; the condition and modality remain distinct.

### Modality vs State

A State denotes a recognizable mode/condition occupied by a bearer at a temporal locus. Modality identifies a semantic mode/channel of access, acquisition, interaction, expression, or experience. Similar language does not make the concepts equivalent.

### Modality vs Context

Context specifies the setting, circumstance, purpose, perspective, or situational frame. Modality specifies the relevant mode/channel within or across that frame.

### Modality vs Activity

An Activity is an actual occurrence. Modality describes the mode/channel in which an activity may occur or the semantic mode relevant to that activity. Modality is not the activity itself.

### Modality vs Process

A Process is an organized temporal course involving activities, transformations, or progression. A process may involve one or more modalities; a modality is not a process.

### Modality vs Procedure / Technique

A Procedure specifies a prescribed way of carrying out an activity. A Technique is a domain-specific way of performing something. A modality may characterize the mode/channel of an operation without specifying the complete procedure or technique.

### Modality vs Representation

A Representation is an information-bearing form. A modality may characterize the information or access mode represented or used, but it is not the representation itself.

### Modality vs Format

A Format specifies structural or syntactic organization. JPEG, PNG, DICOM serialization structures, and similar format concepts are not modalities merely because they carry data associated with a modality.

### Modality vs Encoding

Encoding concerns coding or transformation of representation data. Encoding does not become a modality merely because a modality-specific representation uses it.

### Modality vs Perception

Perception concerns perceptual interpretation or experience. A sensory or perceptual modality can characterize the mode of access, but modality is not the resulting perceptual experience.

## Domain Interpretations

The following are controlled domain families, not automatically promoted GIOP subtypes:

| Domain family | Meaning in its domain | GIOP status |
|---|---|---|
| Imaging Modality | Recognized imaging/acquisition mode or modality terminology | CANONICAL CANDIDATE / DEFERRED |
| Sensory Modality | Recognized sensory mode/pathway through which information is sensed or experienced | CANONICAL CANDIDATE / DEFERRED |
| Interaction Modality | Recognized interaction communication/input/output mode or channel | CANONICAL CANDIDATE / DEFERRED |
| Data Modality | Recognized informational/data mode used to distinguish multimodal data or inputs/outputs | CANONICAL CANDIDATE / DEFERRED |

Domain terminology must retain its originating authority and must not be promoted merely because the lexical form is common.

## Multimodality Boundary

`Multimodal` is not a single Modality subtype. It characterizes the use or combination of multiple modalities.

Similarly, `cross-modal`, `transmodal`, `supramodal`, and related terms should not be treated as generic Modality values without an independent semantic decision.

## Cross-Layer Significance

Modality can serve as a semantic pivot across:

```text
Sensing / Acquisition
        ↓
Observation
        ↓
Perception / Interaction
        ↓
Information / Data
        ↓
Representation / Display
        ↓
Computational / AI use
```

This does not create a new universal relation vocabulary. Cross-layer connections must use only relations already admitted by the GIOP Relations authority.

## Technical and Domain Boundaries

A modality designation must be interpreted with its domain and scope. In particular:

- DICOM modality terminology may identify equipment type, function, or technique within DICOM; this is evidence for domain usage, not a universal GIOP definition.
- Acquisition modality is a specialized imaging usage and is not automatically identical to generic Modality.
- Sensory modality and perceptual experience are distinct semantic responsibilities.
- Data modality and Representation/Format/Encoding are distinct layers.
- Interaction modality and the software/hardware component implementing it are distinct.
- A modality may be associated with more than one representation or activity without becoming those representations or activities.

## Trust

A modality term can be authoritative within a domain without being a universal ontology identity.

Terminology from standards, scientific literature, vendors, implementations, and historical sources must retain provenance and authority scope. Lexical agreement is not sufficient evidence of semantic identity.

A source-supported modality term is not automatically a GIOP canonical subtype. Promotion requires independent semantic responsibility, boundary, provenance, duplicate-authority, relation, and validation review.

## Evidence and Provenance

Primary evidence classes for this entry include:

- standards terminology and information models;
- scientific and neuroscience terminology;
- multimodal interaction specifications;
- multimodal AI research terminology;
- existing GIOP semantic architecture and neighboring canonical entries.

The evidence supports a cross-domain semantic nucleus while also demonstrating that domain-specific definitions vary. The GIOP definition is a semantic synthesis, not a quotation or direct copy of any external source.

## Lifecycle

**Current state:** PROVISIONAL semantic entry.

The entry is authored as the generic Modality nucleus. Promotion to `ACTIVE` is contingent on successful folder-level validation and closure.

Domain families remain `CANONICAL CANDIDATE / DEFERRED` pending independent semantic promotion decisions.

## Relations / Dependencies

Potential cross-layer references must resolve to existing canonical GIOP identities. No new relation authority is introduced by this entry.

Relevant existing semantic dependencies include Activity, Observation, Acquisition, Perception, Representation, Context, Process, Class, and Property semantics.

## Retrieval Anchors

`MODALITY`, `SEM-MODALITY-GENERIC-001`, `SEMANTIC MODE`, `SEMANTIC CHANNEL`, `MODE`, `CHANNEL`, `IMAGING MODALITY`, `ACQUISITION MODALITY`, `SENSORY MODALITY`, `INTERACTION MODALITY`, `DATA MODALITY`, `MULTIMODAL`, `CROSS-MODAL`, `REPRESENTATION`, `FORMAT`, `ENCODING`, `PERCEPTION`, `OBSERVATION`, `ACQUISITION`
