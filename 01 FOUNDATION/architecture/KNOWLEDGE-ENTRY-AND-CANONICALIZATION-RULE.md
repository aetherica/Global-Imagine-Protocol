# GIOP V3.1 — Knowledge Entry & Canonicalization Rule

Status: CANONICAL FOUNDATION RULE  
Scope: This document defines the required method for converting newly learned, recovered, researched, or externally verified information into GIOP repository knowledge.

## 1. Purpose

GIOP must not treat every newly discovered statement as a canonical knowledge entry.

A new piece of knowledge becomes repository knowledge only after its semantic responsibility, evidence status, relationship to existing knowledge, and canonical destination have been resolved.

The governing rule is:

```text
NEW KNOWLEDGE
    ↓
RECOVERED KNOWLEDGE
    ↓
SEMANTIC KNOWLEDGE REGISTRY
    ↓
CLASSIFY
    ↓
VERIFY / CONFLICT ANALYSIS
    ↓
SEMANTIC SYNTHESIS
    ↓
CANONICAL DECISION
    ↓
CANONICAL ENTRY / UPDATE
    ↓
VALIDATION
```

Repository placement is the result of semantic decision, not the decision itself.

## 2. Governing principle

A newly learned item must first be understood as knowledge before it is written as an information entry.

The author must determine:

- what the knowledge is;
- what semantic responsibility it has;
- whether it extends an existing concept or requires a new concept;
- what evidence supports it;
- whether sources agree or conflict;
- whether the knowledge is canonical, candidate, deferred, routed elsewhere, unverified, or conflicted;
- where its canonical semantic home belongs;
- how it relates to existing canonical knowledge.

No new folder, file, or term is justified merely because new information was discovered.

## 3. First question: What kind of knowledge is this?

Before authoring, classify the discovered knowledge according to its primary semantic responsibility.

Use the existing GIOP semantic architecture. Typical responsibilities include:

```text
CLASS         → What kind of entity is this?
PROPERTY      → What characteristic can be attributed?
CONDITION     → What contextual condition applies?
STATE         → What state does an entity or concept occupy?
RELATION      → What typed connection exists?
QUANTITY      → What measurable concept is involved?
ACTIVITY      → What action is performed?
PROCESS       → What transformation or progression occurs?
REPRESENTATION → What information-bearing form represents something?
PERCEPTION    → What perceptual experience or interpretation is involved?
CONTEXT       → Within what setting, circumstance, purpose, perspective, or situational frame is it understood?
```

This classification prevents semantic collapse between neighboring layers.

## 4. Existing-entry rule

The first authoring question is whether the new knowledge belongs to an existing canonical entry.

If an existing entry already carries the same semantic identity, update or extend that entry rather than creating a duplicate.

Create a new canonical entry only when the evidence and semantic analysis establish a distinct reusable concept with its own responsibility and boundary.

```text
NEW KNOWLEDGE
    ↓
MATCH EXISTING CANONICAL IDENTITY?
    ├─ YES → UPDATE / EXTEND EXISTING ENTRY
    └─ NO  → CONTINUE SEMANTIC CLASSIFICATION
```

Duplicate definitions created for convenience, discoverability, or folder organization are not permitted.

## 5. Source and evidence separation

Discovered information must be retained with its provenance before canonical promotion.

Distinguish explicitly between:

- source statement;
- recovered knowledge;
- evidence;
- inference;
- synthesis;
- implementation observation;
- historical statement;
- canonical decision.

A verified statement is not automatically a canonical GIOP concept.

A non-canonical statement is not automatically false.

A deferred item is not deleted knowledge.

A filtered candidate is not discarded evidence.

## 6. Registry-before-canonical rule

Material recovered knowledge that may influence canonical architecture should first be retained in the appropriate semantic knowledge registry when its final destination or status is not yet resolved.

The registry records knowledge such as:

- recovered concept or claim;
- semantic type;
- source/provenance;
- evidence status;
- epistemic status;
- canonical status;
- conflicts;
- GIOP decision;
- intended destination;
- unresolved questions.

The registry is a retention and decision layer. It must not become a parallel canonical knowledge base.

Canonical semantic folders remain authoritative for canonical semantic content.

## 7. Verification and conflict analysis

Before canonical promotion, evaluate the material against relevant evidence.

Verification should determine, as applicable:

- whether the source is authoritative or informative;
- whether independent sources converge;
- whether terminology differs while meaning is shared;
- whether apparently identical terms carry different meanings;
- whether competing definitions exist;
- whether the difference is substantive, contextual, historical, or merely terminological;
- whether the claim belongs to another semantic layer;
- what uncertainty must remain visible.

Conflicting sources must not be silently averaged into an invented definition.

Where conflict remains unresolved, retain the conflict and assign an appropriate non-canonical status.

## 8. Semantic synthesis

When multiple verified sources describe the same reusable concept, synthesize them into one GIOP semantic interpretation rather than copying source language independently into multiple entries.

Synthesis should preserve:

- the common semantic core;
- meaningful distinctions;
- domain boundaries;
- exceptions and constraints;
- evidence limitations;
- terminology differences where useful;
- provenance of material claims.

The canonical definition is a GIOP semantic decision supported by evidence. It is not a source quotation and must not be presented as one.

## 9. Canonical decision states

After classification, verification, conflict analysis, and synthesis, assign the appropriate destination/status.

Possible outcomes include:

```text
CANONICAL
CANONICAL CANDIDATE
ROUTED TO ANOTHER SEMANTIC LAYER
DEFERRED
UNVERIFIED
CONFLICTED
HISTORICAL / PRESERVED
```

Status must not be promoted merely because a page has been written.

## 10. Canonical entry authoring standard

Once a concept is approved for canonical authoring, use the shared GIOP content strategy established by the Foundation architecture.

The default progression is:

```text
IDENTITY / METADATA
        ↓
5W1H ORIENTATION
        ↓
SEMANTIC DEFINITION / CORE DISTINCTIONS
        ↓
DOMAIN-SPECIFIC TECHNICAL DEPTH
        ↓
TRUST / EVIDENCE / VALIDATION
        ↓
LIFECYCLE
        ↓
RELATIONS / RETRIEVAL ANCHORS
```

The exact headings are profile-dependent. The semantic information architecture is not required to be mechanically identical across every artifact.

A canonical entry must be understandable at multiple entry depths without creating multiple underlying truths.

## 11. Entry depth rule

GIOP does not create different canonical knowledge bases for different audiences.

```text
CANONICAL KNOWLEDGE
        ↓
VISITOR UNIVERSE
        ↓
ENTRY DEPTH
        ↓
HUMAN / MACHINE CONSUMPTION
```

Entry depth is produced by how much of the same canonical entry a reader or machine requires.

Do not create a separate `Visitor Universe` knowledge section inside ordinary semantic entries merely to encode audience categories.

Audience relevance should emerge naturally from the entry's orientation, distinctions, technical depth, trust information, relations, examples, and retrieval anchors.

The novice and the expert are not given different knowledge. They are given different entry depths into the same knowledge.

## 12. Machine and AI interpretation

Canonical entries must remain recoverable by machines without depending on hidden conversational context.

At minimum, the canonical identity and definition must remain locally intelligible and expose stable retrieval anchors such as:

- ID;
- title;
- type;
- status;
- version;
- definition;
- primary responsibility;
- relations;
- provenance;
- validation.

Machine readability does not justify flattening semantic distinctions for convenience.

## 13. Canonical semantic boundary rule

Every new entry must state or make recoverable its semantic boundary.

The author must be able to answer:

- what this concept means;
- what it does not mean;
- which neighboring concepts are distinct;
- which layer owns each neighboring responsibility;
- when a related concept should be linked rather than merged.

A new entry is incomplete when its boundary depends only on an author's unstated intuition.

## 14. Cross-layer routing

If newly learned information belongs to another semantic layer, route it there rather than forcing it into the current folder.

Examples:

```text
Measured value      → quantity / value semantics
Typed connection    → relation
Observed condition  → condition
Situational frame   → context
Perceptual meaning  → perception
Transformation      → process
Action performed     → activity
Information-bearing form → representation
```

Cross-references should preserve the relationship without duplicating semantic authority.

## 15. Folder completion rule

When a semantic folder is actively being authored, complete and validate the folder's canonical scope before moving to the next authoring unit where practical.

Research for later folders may be retained in registries or preserved research material, but incomplete canonical fragments must not be allowed to masquerade as finished ontology.

## 16. Validation before publication

Before publishing a new or materially revised canonical entry, validate at minimum:

1. Identity is stable.
2. Primary semantic responsibility is correct.
3. Existing duplicate concepts were checked.
4. Definition is explicit and bounded.
5. Neighboring concepts are distinguished.
6. Provenance/evidence is represented appropriately.
7. Uncertainty or conflict remains visible where applicable.
8. Lifecycle/status is correct.
9. Relations resolve to canonical identities.
10. Retrieval anchors are sufficient for isolated machine retrieval.
11. The entry does not silently redefine another semantic layer.
12. The entry follows the applicable content-formatting/profile requirements.

Failure of a material validation gate blocks canonical promotion.

## 17. Change and update rule

Learning continues after publication.

When new evidence materially changes an existing concept, do not create a competing page merely to preserve the new interpretation.

Instead:

```text
NEW EVIDENCE
    ↓
RE-EVALUATE EXISTING ENTRY
    ↓
COMPARE WITH CURRENT DEFINITION
    ↓
REVISE / EXTEND / SUPERSEDE AS JUSTIFIED
    ↓
RECORD PROVENANCE AND CHANGE
    ↓
REVALIDATE CROSS-REFERENCES
```

Historical decisions must remain traceable. Silent semantic rewriting is prohibited where the change affects established meaning or proof history.

## 18. Minimal operational checklist

For every newly learned item, the author should be able to answer:

```text
1. What did we learn?
2. Where did it come from?
3. What evidence supports it?
4. Is it new knowledge or an extension of an existing concept?
5. What semantic layer owns it?
6. Are there conflicts or competing meanings?
7. What is the GIOP semantic synthesis?
8. What is its canonical status?
9. Where is its canonical home?
10. What existing entries must it relate to?
11. What boundary must be explicit?
12. Has the resulting entry passed validation?
```

If these questions cannot be answered, the material remains research/registry knowledge rather than completed canonical knowledge.

## 19. Authoring law

The operational law of GIOP knowledge entry is:

```text
LEARN → RETAIN → CLASSIFY → VERIFY → RESOLVE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE
```

Never:

```text
LEARN → IMMEDIATELY CREATE A PAGE
```

Canonical knowledge is the result of semantic processing, not a dump of discovered information.

## 20. Relationship to Foundation architecture

This rule operationalizes the existing GIOP Foundation principles for:

- one canonical knowledge model;
- identity and metadata;
- 5W1H orientation;
- artifact-specific technical depth;
- differentiated trust;
- visible lifecycle;
- self-contained retrieval;
- controlled terminology;
- separation of canonical semantics from research evidence and registry identity;
- preservation of historical material.

It does not replace the Content Authoring Readiness Specification, the Content Formatting & Authoring Specification, or the Format System Validation Matrix. It defines the controlled transition from newly learned information into those authoring and validation systems.
