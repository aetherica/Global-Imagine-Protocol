# Representations

**Semantic Area:** Representation and Information-Bearing Forms  
**Status:** Active Canonical Scope  
**Version:** 1.0.0  
**Primary Responsibility:** Information-bearing forms through which canonical information, results, resources, or other semantic content are expressed, exchanged, stored, presented, or made available for interpretation.

## Scope

The `representations` semantic area defines the canonical meaning of Representation and the principal semantic concepts required to describe information-bearing forms without collapsing representation, format, encoding, storage, presentation, perception, or conformance into one layer.

The semantic nucleus is:

`SEM-REPRESENTATION-GENERIC-001 — Representation`

The folder also contains the existing canonical Display entry and may contain representation-adjacent concepts only when their primary semantic responsibility is independently justified.

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
```

This is a coordination model, not a universal subclass hierarchy. Format, Encoding, Media Type, Serialization, Compression, Packaging, Display, Profile, and Conformance have distinct semantic responsibilities.

## Core Boundary

Representation is not synonymous with:

- Information or Knowledge;
- Result;
- Dataset;
- File or Bitstream;
- Format;
- Encoding;
- Serialization activity;
- Media Type;
- Compression;
- Packaging;
- Display;
- Observation;
- Perception;
- Measurement Result;
- Conformance.

A related concept must be linked through an appropriate relation or cross-layer reference rather than absorbed into the Representation definition.

## Canonical Entry Set

| Semantic ID | Preferred Name | Responsibility | Status |
|---|---|---|---|
| `SEM-REPRESENTATION-GENERIC-001` | Representation | Information-bearing form | Active |
| `SEM-DISPLAY-001` | Display | Presentation system / mechanism | Active |

The following are prepared as controlled representation-related concepts and require their own boundary and evidence treatment before canonical promotion:

- Format
- Encoding
- Serialization
- Media Type
- Compression
- Packaging
- Profile

Conformance is treated primarily as a relation/assertion concern and must not become a duplicate relation authority in this folder.

## Visitor Universe and Entry Depth

Visitor Universe does not create separate representation ontologies or audience-specific semantic copies.

The same canonical entries support different entry depths:

```text
CANONICAL REPRESENTATION KNOWLEDGE
              |
         VISITOR UNIVERSE
              |
          ENTRY DEPTH
              |
     HUMAN / MACHINE CONSUMPTION
```

General visitors can use the identity and orientation sections. Learners and creative practitioners can use distinctions and examples. Engineers and scientists can use structure, transformation, provenance, and validation detail. Machine/API consumers can use stable IDs, relations, profiles, constraints, and deterministic retrieval anchors.

No ordinary semantic entry should contain a separate `Visitor Universe` section merely to duplicate this routing model.

## Authoring Standard

Representation entries follow the Foundation authoring pattern while remaining artifact-specific:

1. Identity / metadata
2. 5W1H orientation where useful
3. Semantic definition
4. Scope and structure
5. Core distinctions
6. Boundary cases
7. Technical and cross-domain significance
8. Relations
9. Provenance and evidence
10. Trust / validation
11. Lifecycle
12. Retrieval anchors

Normative statements, explanations, examples, historical material, and implementation notes must remain explicitly distinguishable.

## Provenance and Evidence

External standards are evidence sources, not copied GIOP definitions. Important reference families include:

- RFC 9110 — HTTP Semantics;
- W3C RDF 1.2 Concepts and Abstract Data Model;
- W3C DCAT;
- W3C PROV / PROV-O;
- W3C Profiles Vocabulary;
- PREMIS Data Dictionary;
- ISO 14721:2025 (OAIS);
- relevant IANA media-type registrations and format specifications.

Where sources use the same term with materially different scope, GIOP preserves the distinction and records the synthesis rather than silently averaging definitions.

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

A representation-related topic is not canonical merely because a file exists. Canonical status requires semantic classification, evidence review, boundary validation, relation validation, lifecycle assignment, and compliance with the applicable Foundation gates.
