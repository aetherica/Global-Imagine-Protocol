# Context

**GIOP ID:** `SEM-CONTEXT-GENERIC-001`  
**Artifact Type:** Canonical Semantic Concept  
**Status:** CANONICAL  
**Primary Responsibility:** Contextual frame

## 5W1H Orientation

**What:** A reusable semantic frame specifying the setting, circumstance, purpose, perspective, or situation relevant to understanding something.

**Why:** Context constrains interpretation without replacing the meaning of the contextualized entity, claim, observation, measurement, representation, activity, or process.

**How:** By identifying relevant contextual components and dimensions and relating them to the element being interpreted, used, observed, measured, represented, or evaluated.

**Where:** In semantic interpretation, observation, measurement, imaging capture, processing, viewing, assessment, operations, documentation, and other knowledge uses.

**Who:** Any eligible entity, actor, system, observer, procedure, or information artifact may participate in or be interpreted within a context.

**When:** Whenever circumstances, purpose, perspective, or situational frame materially affect meaning, use, evaluation, or interpretation.

## Canonical Semantic Definition

**Context is a reusable canonical semantic construct that specifies the relevant setting, circumstance, purpose, perspective, or situational frame within which a semantic element is defined, interpreted, used, evaluated, observed, measured, represented, or otherwise understood.**

## Scope

Context is deliberately broad. It may qualify a concept, entity, relation, observation, measurement, result, representation, activity, process, workflow, or claim. It does not absorb the semantics of those things.

Context is a frame, not merely a list of metadata fields and not automatically a physical container or parent class.

## Context Target

The target is the semantic element whose interpretation or use is being contextualized. A target may be an entity, concept, assertion, observation, result, representation, process, activity, or other eligible semantic element.

## Context Family

GIOP uses **Context Family** as the current grouping mechanism. Specific context types require their own semantic boundary and are not declared subclasses solely because their names contain “context.”

Current seed members include Domain Context, Application Context, Capture Context, Measurement Context, Viewing Context, Assessment Context, Processing Context, and Operational Context.

## Contextual Components and Dimensions

Depending on purpose, a Context can reference:

- participating entities and their identities;
- domain or knowledge universe;
- application purpose or task;
- spatial setting;
- temporal setting;
- conditions and states;
- environmental or optical circumstances;
- procedures and measuring systems;
- observer/operator characteristics;
- capture configuration;
- viewing and display circumstances;
- processing configuration and computational resources;
- assessment method, material, assessor, and session;
- relations among contextual components;
- relevant provenance, reference, or traceability information.

No single universal list is mandatory.

## Applicability

A context is applicable when its frame is materially relevant to the semantic interpretation or use under consideration. Relevance is contextual; the existence of a possible surrounding fact does not by itself establish that it is part of the applicable Context.

## Distinctions

**Context vs Condition:** Condition describes a relevant circumstance or condition. Context specifies the broader frame in which something is understood or used. A condition may be a contextual component.

**Context vs State/Status:** State or status describes a mode or status of an entity/process. Context describes the frame surrounding interpretation or use.

**Context vs Relation:** A relation specifies a typed connection. Context can contain or qualify relations but is not itself every relation within the frame.

**Context vs Metadata:** Metadata is information about an item; Context is a semantic frame. Metadata can describe a Context but is not synonymous with it.

**Context vs Situation:** Situation is retained as a related but unresolved term because it may denote an instantiated configuration rather than the reusable frame itself.

**Context vs Visitor Universe:** Visitor Universe controls entry, navigation, and retrieval. It does not alter canonical semantic meaning.

## Cross-Layer Relations

A Context may relate to:

- `conditions/` for contextual circumstances;
- `classes/` for participating entity types;
- `relations/` for typed contextual connections;
- `quantities/` and `values/` for measurable contextual parameters and their realizations;
- `activities/` and `processes/` for contextualized actions and transformations;
- `representations/` for contextualized information forms;
- `observers/` and `perception/` where observation or perceptual interpretation is involved;
- future `spatial/` and `temporal/` layers for spatial and temporal semantics;
- `registry/` for retained evidence and routing decisions.

## Evidence and Provenance

The GIOP definition is a semantic synthesis supported by ISO/IEC 11179 context concepts, context-aware computing literature, observation and measurement models, and imaging/viewing/assessment standards. External terminology is evidence, not automatic GIOP authority.

## Trust and Validation

Validation requires stable semantic meaning, non-collapse with Condition/State/Relation/Metadata, identifiable contextual scope, appropriate cross-layer responsibility, and traceable evidence.

## Lifecycle

**CANONICAL — V3.1.** Future revisions must preserve stable identity and record semantic changes through GIOP lifecycle/versioning controls.

## Machine / AI Interpretation

A machine should treat Context as a frame used to qualify interpretation, retrieval, comparison, evaluation, or execution. Context should not be silently converted into a class, value, condition, or assertion. Stable IDs and explicit contextual relations should be preferred over ambiguous natural-language proximity.

## Retrieval Anchors

`context`, `contextual frame`, `setting`, `circumstance`, `purpose`, `perspective`, `situational frame`, `definition context`, `use context`, `interpretation context`, `evaluation context`.

## Visitor Universe

**Primary access:** all 45 Visitor Universe classes, with relevance varying by task.

**Entry depth:**

- Depth 0 — orientation: what Context is and why it matters;
- Depth 1 — conceptual: components, dimensions, and distinctions;
- Depth 2 — applied: context selection in imaging/measurement/viewing workflows;
- Depth 3 — technical: cross-layer qualification and formal relationships;
- Depth 4 — specialist/research: evidence, competing context models, uncertainty, and semantic boundaries.

These are access depths, not visitor classes.

**Machine access:** stable ID, definition, family, cross-layer relations, registry links, and retrieval anchors.

## What This Context Does Not Mean

It does not mean:

- physical environment only;
- condition only;
- metadata only;
- a container holding every surrounding fact;
- a measurement condition;
- a viewing condition;
- a workflow or process;
- an ontology or class hierarchy;
- a visitor-specific definition.

## Semantic Boundary

`CONTEXT = reusable contextual frame`

`CONTEXT COMPONENT = entity/condition/state/quantity/relation/etc. referenced by the frame`

`CONTEXTUALIZED ELEMENT = element whose interpretation/use is framed`

`VISITOR ACCESS FRAME = navigation metadata, not semantic meaning`

## Cross-References

See `contexts/README.md` and `registry/CONTEXT-KNOWLEDGE-REGISTRY.md` for the family specification and retained research corpus.
