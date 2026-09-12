# Representation Cross-Layer Validation

**Scope:** Representation semantic area  
**Status:** Active Validation Specification  
**Version:** 1.0.0

## Purpose

This document prevents representation-related concepts from silently redefining neighboring GIOP semantic layers.

## Validation Matrix

| Concept under review | Must remain distinct from | Validation question |
|---|---|---|
| Representation | Result | Is this the information-bearing form rather than the information produced by an activity? |
| Representation | Dataset | Is the concept a form of a collection rather than the collection itself? |
| Representation | File | Is storage incidental rather than the defining responsibility? |
| Representation | Format | Is this an instance/form rather than the structural specification? |
| Representation | Encoding | Is this the resulting information-bearing form rather than the coding scheme? |
| Representation | Serialization | Is this the concrete form rather than the production operation? |
| Representation | Display | Is this the presented information/form rather than the presentation mechanism? |
| Representation | Perception | Is this independent of observer-dependent perceptual outcome? |
| Representation | Quantity | Is this not a measurable aspect/value? |
| Representation | Condition | Is this not a situational/physical condition? |
| Representation | State | Is this not a recognized mode of an entity? |
| Representation | Relation | Is this not a typed connection between semantic elements? |
| Representation | Activity | Is this not an occurrence/action? |
| Representation | Process | Is this not a transformation/progression itself? |
| Representation | Profile | Is this not a specification constraint/extension layer? |
| Representation | Conformance | Is this not a compliance assertion? |

## Required Gates

### Identity Gate

Stable semantic ID and preferred name exist.

### Responsibility Gate

Primary responsibility is explicitly information-bearing form.

### Existing-Entry Gate

No existing canonical concept carries the same semantic identity.

### Boundary Gate

At least the relevant adjacent concepts are explicitly distinguished.

### Provenance Gate

Material external claims have traceable source/evidence classification.

### Relation Gate

Relations point to existing semantic authorities and do not create silent duplicate relation vocabulary.

### Visitor Gate

No audience-specific semantic duplicate has been introduced.

### Retrieval Gate

The identity and definition remain understandable in isolation.

### Lifecycle Gate

Status accurately reflects evidence and validation state.

## Representation-Specific Test Cases

### Test A — File

Input: “A TIFF file is a representation.”

Result: conditionally acceptable as an instance-level description only when the file is treated as a carrier of a defined representation. The semantic concepts File, Format, and Representation remain distinct.

### Test B — JPEG

Input: “JPEG is a representation.”

Result: reject as an unqualified canonical definition. JPEG may refer to a coding/format family or an encoded image instance depending on context. Primary responsibility must be resolved before classification.

### Test C — Display

Input: “The monitor is the representation.”

Result: reject. Monitor/display is a presentation mechanism; the displayed representation is distinct.

### Test D — Serialization

Input: “JSON serialization is a representation.”

Result: distinguish the serialization operation from its concrete serialized output. The output may be a Representation.

### Test E — Conformance

Input: “This representation is a conformance.”

Result: reject. Conformance is an assertion relating an artifact to requirements/profile/specification.

## Promotion Rule

A candidate may become Active only when all material gates pass and its status is consistent with the GIOP canonicalization rule.
