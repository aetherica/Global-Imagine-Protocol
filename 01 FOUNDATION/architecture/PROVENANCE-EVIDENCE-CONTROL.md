# GIOP V3.1 — Provenance and Evidence Control

**Status:** ACTIVE CONTROL FOR PILOT PROMOTION
**Scope:** Semantic pilot and subsequent canonical content promotion

## Purpose

This control closes the provenance/evidence readiness gap identified during semantic pilot validation without creating a second semantic authority layer.

## Required metadata

Every substantive canonical record must distinguish, where applicable:

- provenance source(s);
- evidence type;
- validation state;
- authority tier;
- confidence/review state;
- historical status;
- validation date/version;
- unresolved questions.

## Provenance rule

Repository location is never semantic authority. Provenance identifies where a claim or definition came from; canonical semantic identity remains controlled by GIOP governance and semantic records.

## Evidence rule

A claim may be promoted only when its supporting evidence is recorded or the record explicitly identifies the claim as an internal semantic definition rather than an externally asserted fact.

## Validation rule

Validation state must be explicit. `Provisional`, `Validated`, and `Active` are lifecycle states and must not be silently treated as synonyms.

## Authority rule

Evidence source, source authority, and GIOP canonical authority are separate dimensions. External standards may provide evidence without automatically becoming the GIOP semantic definition.

## Pilot application

The current semantic pilot batch has been reviewed for semantic boundaries and cross-layer responsibility. External factual claims remain subject to source-specific evidence where applicable; internal semantic distinctions are recorded as GIOP design decisions.

## Audit rule

Any future change that materially alters a promoted semantic definition must update provenance/evidence metadata and pass the applicable validation gate before activation.
