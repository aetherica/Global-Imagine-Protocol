# GIOP Relation Knowledge — Retained Semantic Registry

## Status

**CANONICAL RETENTION / AUDIT RECORD**

## Purpose

This registry preserves the complete recovered relation knowledge identified during the V3.1 Relation semantic pass while separating evidence, semantic classification, canonical admission, and routing.

This registry is **not** the canonical Relation vocabulary and is not a substitute for future specialized semantic folders.

The governing GIOP rule is:

> **No recovered knowledge is discarded because it is not currently canonical in `relations/`. Knowledge is retained and semantically routed.**

The working pipeline is:

`SOURCE → RECOVERED KNOWLEDGE → REGISTRY → CLASSIFY → EVIDENCE ASSESSMENT → VERIFY → CONFLICT / RECONCILIATION → SEMANTIC SYNTHESIS → CATEGORY ASSIGNMENT → CANONICAL DECISION → PRIMARY SEMANTIC ENTRY + CROSS-LAYER REFERENCE`

`VERIFIED ≠ CANONICAL`

`NOT CANONICAL HERE ≠ NOT KNOWLEDGE`

`DEFERRED ≠ DELETED`

## Registry Record Contract

Every retained relation concept or relation-family candidate is represented with:

- stable registry ID;
- preferred term;
- epistemic status;
- semantic type and family;
- canonical status;
- recovered meaning / synthesized definition;
- subject/domain and object/range where determinable;
- direction and inverse where applicable;
- logical characteristics where justified;
- evidence and provenance;
- conflicts/open questions;
- GIOP semantic decision;
- destination or future destination;
- reconsideration trigger.

A registry record preserves a semantic decision. Detailed canonical exposition belongs in the destination semantic layer.

---

## A. Structural / Partitive Relations

### A1. Part Of

- **Registry ID:** `TERM-RELATION-PART-OF-001`
- **Preferred Term:** `part-of`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** RELATION
- **Family:** STRUCTURAL / PARTITIVE
- **Canonical Status:** CANONICAL
- **Primary Destination:** `relations/part-of.md`
- **Definition:** A directed structural relation in which a first participant is a constituent part of a second participant or whole.
- **Domain:** eligible part/component/constituent/substructure
- **Range:** eligible whole/composite/assembly/system
- **Inverse:** `has-part`
- **Logical Characteristics:** generally non-symmetric; ordinary proper-part interpretation is irreflexive; transitivity may apply when the asserted relation genuinely uses the canonical part–whole semantics.
- **Evidence:** OBO Relation Ontology part–whole patterns; ISO terminology traditions distinguishing partitive relations; GIOP cross-layer architecture analysis.
- **Conflicts / Open Questions:** domain-specific `component-of` may require a narrower distinction from general part–whole semantics.
- **GIOP Decision:** Admit as canonical structural relation; do not collapse use, participation, location, or provenance into `part-of`.
- **Reconsideration:** permitted if GIOP explicitly changes proper-part/non-proper-part semantics.

### A2. Has Part

- **Registry ID:** `TERM-RELATION-HAS-PART-001`
- **Preferred Term:** `has-part`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** INVERSE RELATION
- **Family:** STRUCTURAL / PARTITIVE
- **Canonical Status:** ROUTED ELSEWHERE / INVERSE OF CANONICAL
- **Primary Destination:** inverse representation of `relations/part-of.md`
- **Definition:** The inverse direction of `part-of`, connecting a whole to a constituent part.
- **Domain:** eligible whole/composite/assembly/system
- **Range:** eligible part/component/constituent
- **Inverse:** `part-of`
- **Logical Characteristics:** inherits the applicable inverse semantics of `part-of`.
- **Evidence:** formal ontology relation patterns and GIOP inverse-direction analysis.
- **Conflicts / Open Questions:** whether retrieval requires a separately named canonical page is an architecture question, not a semantic deletion.
- **GIOP Decision:** Retain as an inverse term; do not create a duplicate canonical concept page solely for grammatical reversal.
- **Reconsideration:** permitted if a future machine/retrieval specification requires a first-class inverse artifact.

### A3. Component Of

- **Registry ID:** `TERM-RELATION-COMPONENT-OF-001`
- **Preferred Term:** `component-of`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** SPECIALIZED RELATION
- **Family:** COMPONENT / SYSTEM
- **Canonical Status:** DEFERRED
- **Destination:** future relation specialization / system architecture semantics
- **Definition / Recovered Meaning:** A relation proposed for identifying a component as belonging to or constituting a larger system or assembly.
- **Domain:** system component / subsystem / engineered element
- **Range:** system / assembly / engineered whole
- **Inverse:** `has-component` (proposed)
- **Logical Characteristics:** unresolved; must not be assumed identical to `part-of` or automatically transitive.
- **Evidence:** engineering/system modeling practice; GIOP relation research.
- **Conflicts / Open Questions:** principal unresolved boundary is `component-of` versus general `part-of`, especially where functional system semantics are intended.
- **GIOP Decision:** Retain and defer. No knowledge loss. Resolve specialization boundary before canonical admission.
- **Reconsideration:** when system/component semantics are separately authored and cross-validated.

### A4. Has Component

- **Registry ID:** `TERM-RELATION-HAS-COMPONENT-001`
- **Preferred Term:** `has-component`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** INVERSE / SPECIALIZED RELATION
- **Family:** COMPONENT / SYSTEM
- **Canonical Status:** DEFERRED
- **Destination:** future component/system relation model
- **Definition / Recovered Meaning:** Proposed inverse of `component-of`, from a system or assembly to an eligible component.
- **Inverse:** `component-of`
- **GIOP Decision:** Retain as unresolved inverse terminology; do not duplicate `has-part` semantics without a component boundary.
- **Conflicts / Open Questions:** depends on resolution of `component-of`.

---

## B. Participation Relations

### B1. Participates In

- **Registry ID:** `TERM-RELATION-PARTICIPATES-IN-001`
- **Preferred Term:** `participates-in`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** RELATION
- **Family:** PARTICIPATION
- **Canonical Status:** CANONICAL
- **Primary Destination:** `relations/participates-in.md`
- **Definition:** Directed involvement of an eligible participant in an activity, process, event, or other qualifying occurrence.
- **Domain:** eligible participant/entity
- **Range:** activity/process/event/occurrence
- **Inverse:** `has-participant`
- **Logical Characteristics:** directed, non-symmetric, generally non-transitive, non-causal by default.
- **Evidence:** OBO participation patterns; provenance/process modeling; GIOP activity/process boundary.
- **GIOP Decision:** Canonical generic participation relation; role-specific claims require additional semantics.
- **Reconsideration:** only through explicit semantic revision.

### B2. Has Participant

- **Registry ID:** `TERM-RELATION-HAS-PARTICIPANT-001`
- **Preferred Term:** `has-participant`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** INVERSE RELATION
- **Family:** PARTICIPATION
- **Canonical Status:** ROUTED ELSEWHERE / INVERSE OF CANONICAL
- **Destination:** inverse representation of `participates-in`
- **Definition:** Inverse direction from an activity/process/occurrence to an eligible participant.
- **Inverse:** `participates-in`
- **GIOP Decision:** Retain as inverse retrieval/machine term; no duplicate canonical page solely for inverse direction.

---

## C. Observation Relations

### C1. Observes

- **Registry ID:** `TERM-RELATION-OBSERVES-001`
- **Preferred Term:** `observes`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** RELATION
- **Family:** OBSERVATION
- **Canonical Status:** CANONICAL
- **Primary Destination:** `relations/observes.md`
- **Definition:** Directed relation connecting an eligible observer to an eligible target observed under a meaningful observation context.
- **Domain:** observer / observing entity / formal observer model
- **Range:** object / scene / phenomenon / signal / state / other eligible target
- **Inverse:** `is-observed-by`
- **Logical Characteristics:** directed, non-symmetric, generally non-transitive; self-observation requires explicit model semantics.
- **Evidence:** scientific observation modeling; imaging observation practice; formal ontology distinctions between observation and measurement.
- **GIOP Decision:** Canonical observation relation. Do not infer measurement, perception, accuracy, or representation from observation alone.
- **Reconsideration:** only through explicit observation-model revision.

### C2. Is Observed By

- **Registry ID:** `TERM-RELATION-IS-OBSERVED-BY-001`
- **Preferred Term:** `is-observed-by`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** INVERSE RELATION
- **Family:** OBSERVATION
- **Canonical Status:** ROUTED ELSEWHERE / INVERSE OF CANONICAL
- **Destination:** inverse representation of `observes`
- **Definition:** Inverse direction from an observed target to an observer.
- **Inverse:** `observes`
- **GIOP Decision:** Retain; no separate canonical page required solely for inverse wording.

---

## D. Representation Relations

### D1. Represents

- **Registry ID:** `TERM-RELATION-REPRESENTS-001`
- **Preferred Term:** `represents`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** RELATION
- **Family:** REPRESENTATION
- **Canonical Status:** CANONICAL
- **Primary Destination:** `relations/represents.md`
- **Definition:** Directed semantic representational correspondence in which an eligible representation stands for, depicts, encodes, models, describes, or otherwise represents an eligible referent.
- **Domain:** representation / representational artifact
- **Range:** represented entity / phenomenon / state / event / concept / referent
- **Inverse:** `is-represented-by`
- **Logical Characteristics:** directed, generally non-symmetric and non-transitive; no uniqueness, identity, completeness, or accuracy follows.
- **Evidence:** information representation models; imaging and documentation semantics; RDF/OWL as design evidence.
- **GIOP Decision:** Canonical representation relation. Keep representation distinct from observation, provenance, identity, and fidelity.
- **Reconsideration:** explicit representational-model revision only.

### D2. Is Represented By

- **Registry ID:** `TERM-RELATION-IS-REPRESENTED-BY-001`
- **Preferred Term:** `is-represented-by`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** INVERSE RELATION
- **Family:** REPRESENTATION
- **Canonical Status:** ROUTED ELSEWHERE / INVERSE OF CANONICAL
- **Destination:** inverse representation of `represents`
- **Definition:** Inverse direction from a referent to a representation that represents it.
- **Inverse:** `represents`
- **GIOP Decision:** Retain as inverse term; do not duplicate the canonical concept.

---

## E. Provenance / Lineage Relations

### E1. Derived From

- **Registry ID:** `TERM-RELATION-DERIVED-FROM-001`
- **Preferred Term:** `derived-from`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** PROVENANCE RELATION
- **Family:** PROVENANCE / LINEAGE
- **Canonical Status:** CANONICAL
- **Primary Destination:** `relations/derived-from.md`
- **Definition:** Directed provenance relation in which a derived entity has lineage originating from, or produced through derivation from, an eligible source/predecessor.
- **Domain:** derived artifact/result/representation/data product/entity
- **Range:** source/predecessor/artifact/result/entity
- **Inverse:** `had-derived-output` (terminology retained as conventional inverse candidate)
- **Logical Characteristics:** directed and non-symmetric; direct derivation must not be confused with inferred lineage; unrestricted transitivity is not assumed.
- **Evidence:** W3C PROV-O derivation patterns; provenance and lineage practice; GIOP provenance boundary.
- **GIOP Decision:** Canonical provenance relation. Preserve direct versus inferred lineage and separate generation/use/attribution from derivation.
- **Reconsideration:** through future provenance model only.

### E2. Had Derived Output

- **Registry ID:** `TERM-RELATION-HAD-DERIVED-OUTPUT-001`
- **Preferred Term:** `had-derived-output`
- **Epistemic Status:** VERIFIED / TERMINOLOGY PENDING
- **Semantic Type:** INVERSE / PROVENANCE RELATION
- **Family:** PROVENANCE / LINEAGE
- **Canonical Status:** ROUTED ELSEWHERE / INVERSE CANDIDATE
- **Destination:** future provenance vocabulary
- **Definition:** Proposed inverse direction from a source/predecessor to an entity derived from it.
- **Inverse:** `derived-from`
- **GIOP Decision:** Retain as provenance inverse terminology; final preferred label may be aligned during provenance-layer authoring.

### E3. Was Generated By / Generated By

- **Registry ID:** `TERM-RELATION-GENERATED-BY-001`
- **Preferred Term:** `generated-by`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** PROVENANCE RELATION
- **Family:** PROVENANCE / GENERATION
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `provenance` / process-oriented semantic layer
- **Definition / Recovered Meaning:** Relates a generated entity or artifact to the activity/process that generated it.
- **Domain:** generated entity/artifact/result
- **Range:** activity/process/generation event
- **Evidence:** W3C PROV-O generation model.
- **GIOP Decision:** Retain and route to provenance/process semantics. Do not collapse generation into `derived-from`; generation identifies the producing occurrence, while derivation identifies lineage.

### E4. Used

- **Registry ID:** `TERM-RELATION-USED-001`
- **Preferred Term:** `used`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** PROVENANCE / OPERATIONAL RELATION
- **Family:** USAGE / PROVENANCE
- **Canonical Status:** DEFERRED
- **Destination:** future provenance/activity semantics
- **Definition / Recovered Meaning:** A qualifying activity/process uses an entity, artifact, instrument, input, or resource.
- **Domain:** activity/process
- **Range:** entity/resource/input/instrument
- **Evidence:** W3C PROV-O usage pattern; GIOP activity/process boundary.
- **Conflicts / Open Questions:** broad operational use may overlap with a future general `uses`; temporal qualification is often essential.
- **GIOP Decision:** Retain; defer canonical relation until provenance/activity and generic operational-use boundaries are settled.

### E5. Was Associated With / Associated With

- **Registry ID:** `TERM-RELATION-ASSOCIATED-WITH-001`
- **Preferred Term:** `associated-with`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** ASSOCIATIVE / PROVENANCE RELATION
- **Family:** ASSOCIATIVE / PROVENANCE
- **Canonical Status:** DEFERRED
- **Destination:** future associative/provenance semantics
- **Definition / Recovered Meaning:** A broad association connecting an entity to another qualifying entity, often through a process, agent, context, or provenance structure without asserting a narrower relation.
- **Logical Characteristics:** must not be assumed symmetric or transitive unless a future canonical definition explicitly establishes those characteristics.
- **Evidence:** W3C PROV-O association pattern; general associative relation traditions.
- **GIOP Decision:** Retain as broad relation knowledge; do not use as a semantic substitute for a narrower verified relation.

### E6. Attributed To

- **Registry ID:** `TERM-RELATION-ATTRIBUTED-TO-001`
- **Preferred Term:** `attributed-to`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** PROVENANCE RELATION
- **Family:** PROVENANCE / ATTRIBUTION
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future provenance / responsibility semantics
- **Definition / Recovered Meaning:** Relates an entity or artifact to an agent/entity to which it is attributed under an attribution convention.
- **Evidence:** W3C PROV-O attribution pattern.
- **GIOP Decision:** Retain and route to provenance/attribution semantics; do not equate attribution with authorship, ownership, or causation without additional definitions.

---

## F. Operational / Usage Relations

### F1. Uses

- **Registry ID:** `TERM-RELATION-USES-001`
- **Preferred Term:** `uses`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** RELATION
- **Family:** OPERATIONAL / USAGE
- **Canonical Status:** DEFERRED
- **Destination:** future operational semantics
- **Definition / Recovered Meaning:** An eligible actor, system, process, activity, or operation makes use of another eligible entity, resource, tool, component, or information object.
- **Domain / Range:** intentionally broad pending specialization analysis.
- **Logical Characteristics:** no symmetry/transitivity/functionality assumed.
- **Conflicts / Open Questions:** overlaps with `used` in provenance, `depends-on`, participation, and component/system semantics; temporal and purpose qualification may be required.
- **GIOP Decision:** Retain and defer. Resolve scope before canonical admission.

---

## G. Dependency Relations

### G1. Depends On

- **Registry ID:** `TERM-RELATION-DEPENDS-ON-001`
- **Preferred Term:** `depends-on`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** RELATION
- **Family:** DEPENDENCY
- **Canonical Status:** DEFERRED
- **Destination:** future dependency semantics
- **Definition / Recovered Meaning:** A first semantic element requires, relies upon, or has its valid operation/meaning contingent upon a second element under a defined dependency.
- **Domain / Range:** broad and context-sensitive.
- **Logical Characteristics:** transitivity may be meaningful in some dependency models but cannot be assumed globally; not symmetric by default.
- **Conflicts / Open Questions:** dependency may be functional, causal, operational, informational, lifecycle-based, or logical; these must not be collapsed.
- **GIOP Decision:** Retain as unresolved relation family; specialize before canonicalization.

---

## H. Measurement Relations

### H1. Measures

- **Registry ID:** `TERM-RELATION-MEASURES-001`
- **Preferred Term:** `measures`
- **Epistemic Status:** VERIFIED / BOUNDARY PENDING
- **Semantic Type:** RELATION
- **Family:** MEASUREMENT
- **Canonical Status:** DEFERRED
- **Destination:** future measurement semantics / activities / quantities
- **Definition / Recovered Meaning:** Connects a measuring system or measurement activity to the entity, quantity, or measurand being measured under a defined measurement context.
- **Domain:** measuring system and/or measurement activity, depending on model.
- **Range:** measurand / quantity / phenomenon / entity being measured.
- **Logical Characteristics:** not assumed transitive, symmetric, or causal.
- **Evidence:** VIM measurement concepts and GIOP distinction between measurement activity, measuring system, quantity, result, and relation.
- **Conflicts / Open Questions:** whether GIOP should distinguish `measures` as system-to-measurand from an activity-to-measurand relation; the boundary with `observes` must remain explicit.
- **GIOP Decision:** Retain and defer until quantity/measurement semantics are authored. No knowledge deletion.

---

## I. Spatial Relations

### I1. Located In

- **Registry ID:** `TERM-RELATION-LOCATED-IN-001`
- **Preferred Term:** `located-in`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** SPATIAL RELATION
- **Family:** SPATIAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `spatial/`
- **Definition / Recovered Meaning:** Relates an entity or spatial object to a spatial region, place, container, or location in which it is located under a specified spatial reference.
- **Inverse:** `contains` (subject to spatial containment boundary)
- **Evidence:** GeoSPARQL spatial relation patterns; spatial ontology practice.
- **GIOP Decision:** Retain and route to spatial semantics. Do not use structural `part-of` as a universal substitute.

### I2. Contains

- **Registry ID:** `TERM-RELATION-CONTAINS-001`
- **Preferred Term:** `contains`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** SPATIAL RELATION
- **Family:** SPATIAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `spatial/`
- **Definition / Recovered Meaning:** Inverse spatial relation in which a spatial container or region contains another entity or region.
- **Inverse:** `located-in` or a more specific spatial inverse depending on containment model.
- **Evidence:** GeoSPARQL and spatial relation modeling.
- **GIOP Decision:** Retain; specialized spatial semantics must distinguish topological containment from structural constitution.

### I3. Overlaps

- **Registry ID:** `TERM-RELATION-OVERLAPS-001`
- **Preferred Term:** `overlaps`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** SPATIAL RELATION
- **Family:** SPATIAL / TOPOLOGICAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `spatial/`
- **Definition / Recovered Meaning:** A spatial/topological relation indicating that two spatial entities have an overlap under the applicable spatial model.
- **Evidence:** OGC GeoSPARQL topological relations.
- **GIOP Decision:** Retain for spatial layer; no global `relations/` canonical page in this pass.

### I4. Touches

- **Registry ID:** `TERM-RELATION-TOUCHES-001`
- **Preferred Term:** `touches`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** SPATIAL RELATION
- **Family:** SPATIAL / TOPOLOGICAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `spatial/`
- **Definition / Recovered Meaning:** Spatial/topological contact relation under a defined geometry/topology model.
- **Evidence:** OGC GeoSPARQL.
- **GIOP Decision:** Retain and route to spatial semantics; physical contact must not be inferred from lexical co-occurrence.

---

## J. Temporal Relations

### J1. Before

- **Registry ID:** `TERM-RELATION-BEFORE-001`
- **Preferred Term:** `before`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** TEMPORAL RELATION
- **Family:** TEMPORAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `temporal/`
- **Definition / Recovered Meaning:** Temporal ordering relation in which one temporal interval/event precedes another under the applicable temporal model.
- **Inverse:** `after`
- **Evidence:** Allen interval algebra and temporal reasoning traditions.
- **GIOP Decision:** Retain and route to temporal semantics.

### J2. After

- **Registry ID:** `TERM-RELATION-AFTER-001`
- **Preferred Term:** `after`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** TEMPORAL RELATION
- **Family:** TEMPORAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `temporal/`
- **Definition / Recovered Meaning:** Inverse temporal ordering relation indicating that one event/interval follows another.
- **Inverse:** `before`
- **Evidence:** Allen interval algebra.
- **GIOP Decision:** Retain and route to temporal semantics.

### J3. During

- **Registry ID:** `TERM-RELATION-DURING-001`
- **Preferred Term:** `during`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** TEMPORAL RELATION
- **Family:** TEMPORAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `temporal/`
- **Definition / Recovered Meaning:** Temporal relation in which one interval/event occurs within another interval under the applicable interval model.
- **Inverse:** `contains` in the temporal sense; must not be conflated with spatial `contains`.
- **Evidence:** Allen interval algebra.
- **GIOP Decision:** Retain and route to temporal semantics.

### J4. Meets

- **Registry ID:** `TERM-RELATION-MEETS-001`
- **Preferred Term:** `meets`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** TEMPORAL RELATION
- **Family:** TEMPORAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `temporal/`
- **Definition / Recovered Meaning:** Temporal interval relation in which one interval ends at the boundary where another begins under the applicable temporal model.
- **Evidence:** Allen interval algebra.
- **GIOP Decision:** Retain and route to temporal semantics.

### J5. Temporal Overlaps

- **Registry ID:** `TERM-RELATION-TEMPORAL-OVERLAPS-001`
- **Preferred Term:** `overlaps` (temporal sense)
- **Epistemic Status:** VERIFIED
- **Semantic Type:** TEMPORAL RELATION
- **Family:** TEMPORAL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `temporal/`
- **Definition / Recovered Meaning:** Temporal interval relation indicating partial temporal overlap under the applicable interval algebra.
- **Conflicts / Open Questions:** lexical collision with spatial `overlaps` requires typed semantic identity and should not be resolved by a single unqualified concept.
- **GIOP Decision:** Retain as a distinct temporal relation sense; route to temporal semantics.

---

## K. Causal / Influence Relations

### K1. Causes

- **Registry ID:** `TERM-RELATION-CAUSES-001`
- **Preferred Term:** `causes`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** CAUSAL RELATION
- **Family:** CAUSAL / INFLUENCE
- **Canonical Status:** DEFERRED
- **Destination:** future causal semantics
- **Definition / Recovered Meaning:** A first entity, event, activity, or process brings about or contributes to an effect under a specified causal interpretation.
- **Logical Characteristics:** causal semantics are model-dependent; no unrestricted transitivity, symmetry, or determinism should be assumed.
- **Evidence:** causal modeling traditions; GIOP distinction between causation, provenance, participation, and influence.
- **Conflicts / Open Questions:** causal relation may require temporal ordering, mechanism, intervention, counterfactual or domain-specific evidence.
- **GIOP Decision:** Retain and defer. Do not infer causation from `participates-in`, `derived-from`, `observes`, or `affects`.

### K2. Affects

- **Registry ID:** `TERM-RELATION-AFFECTS-001`
- **Preferred Term:** `affects`
- **Epistemic Status:** UNDER VERIFICATION
- **Semantic Type:** CAUSAL / INFLUENCE RELATION
- **Family:** CAUSAL / INFLUENCE
- **Canonical Status:** DEFERRED
- **Destination:** future causal/influence semantics
- **Definition / Recovered Meaning:** A first entity, condition, process, or event has an influence on a second entity, state, property, outcome, or behavior without necessarily establishing full causation.
- **Logical Characteristics:** no symmetry/transitivity assumed.
- **Conflicts / Open Questions:** boundary between influence, causal effect, correlation, dependency, and contextual association.
- **GIOP Decision:** Retain and defer until causal/influence semantics are formally scoped.

---

## L. Identity / Equivalence Relations

### L1. Same As

- **Registry ID:** `TERM-RELATION-SAME-AS-001`
- **Preferred Term:** `same-as`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** IDENTITY RELATION
- **Family:** IDENTITY / EQUIVALENCE
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `identity/`
- **Definition / Recovered Meaning:** Identifies two semantic references as denoting the same entity or identity under the applicable identity criteria.
- **Logical Characteristics:** normally reflexive, symmetric, and transitive when true identity semantics are intended.
- **Evidence:** identity/equivalence modeling traditions; OWL identity patterns.
- **GIOP Decision:** Retain and route to identity semantics. Identity must not be inferred from similarity, representation, derivation, or correspondence.

### L2. Equivalent To

- **Registry ID:** `TERM-RELATION-EQUIVALENT-TO-001`
- **Preferred Term:** `equivalent-to`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** IDENTITY / EQUIVALENCE RELATION
- **Family:** IDENTITY / EQUIVALENCE
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future `identity/` or equivalence semantics
- **Definition / Recovered Meaning:** Relates two semantic elements as equivalent under an explicitly defined equivalence criterion without necessarily asserting numerical, physical, or entity identity.
- **Logical Characteristics:** depends on the equivalence model; commonly symmetric and transitive.
- **Conflicts / Open Questions:** must remain distinct from `same-as`; equivalence can be conceptual, structural, representational, or semantic rather than strict identity.
- **GIOP Decision:** Retain and route to identity/equivalence semantics.

### L3. Corresponds To

- **Registry ID:** `TERM-RELATION-CORRESPONDS-TO-001`
- **Preferred Term:** `corresponds-to`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** ASSOCIATIVE / CORRESPONDENCE RELATION
- **Family:** ASSOCIATIVE / CORRESPONDENCE
- **Canonical Status:** DEFERRED
- **Destination:** future correspondence / identity semantics
- **Definition / Recovered Meaning:** Connects two elements that correspond under a specified mapping, alignment, representation, or semantic convention without automatically asserting identity or representation.
- **Logical Characteristics:** unresolved; must not be assumed symmetric or transitive globally.
- **Evidence:** correspondence/alignment modeling; GIOP representation and identity boundary analysis.
- **GIOP Decision:** Retain and defer until correspondence is separated from representation, equivalence, and identity.

---

## M. General Associative Relations

### M1. Related To

- **Registry ID:** `TERM-RELATION-RELATED-TO-001`
- **Preferred Term:** `related-to`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** ASSOCIATIVE RELATION
- **Family:** ASSOCIATIVE
- **Canonical Status:** DEFERRED
- **Destination:** future associative semantics
- **Definition / Recovered Meaning:** A deliberately broad relation indicating that two semantic elements are related under a stated or retrievable association without asserting a narrower relation.
- **Logical Characteristics:** may be symmetric in a future definition, but this must be explicit; no transitivity assumed.
- **Evidence:** SKOS `related` pattern; associative relation traditions.
- **GIOP Decision:** Retain as a broad associative candidate but do not use it to replace a more precise relation when one is known.

### M2. Associated With

- **Registry ID:** `TERM-RELATION-ASSOCIATED-WITH-002`
- **Preferred Term:** `associated-with`
- **Epistemic Status:** VERIFIED / BROAD
- **Semantic Type:** ASSOCIATIVE RELATION
- **Family:** ASSOCIATIVE
- **Canonical Status:** DEFERRED
- **Destination:** future associative/provenance semantics
- **Definition / Recovered Meaning:** Broad association between two eligible semantic elements when a narrower relation is not yet established or is intentionally not asserted.
- **Logical Characteristics:** unresolved; must not be assumed transitive or causal.
- **Conflicts / Open Questions:** duplicate lexical territory with provenance association requires context-sensitive semantic distinction.
- **GIOP Decision:** Retain; resolve generic associative versus provenance-specific usage during specialized layer authoring.

---

## N. Unresolved / Cross-Cutting Relation Knowledge

### N1. Relation Assertion

- **Registry ID:** `TERM-RELATION-ASSERTION-001`
- **Preferred Term:** `relation assertion`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** OTHER / ASSERTION MODEL
- **Family:** CROSS-CUTTING RELATION MODEL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** Relation specification / future knowledge-graph representation model
- **Definition:** An instance-level statement that a particular relation concept holds between identified participants.
- **Model:** `RELATION CONCEPT → RELATION ASSERTION → OPTIONAL QUALIFICATION / CONTEXT`
- **Evidence:** RDF/OWL triple/property modeling; GIOP concept-versus-assertion distinction.
- **GIOP Decision:** Retain as foundational relation modeling knowledge. Canonical relation pages describe concepts, not individual assertions.

### N2. Inferred Relation

- **Registry ID:** `TERM-RELATION-INFERRED-RELATION-001`
- **Preferred Term:** `inferred relation`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** OTHER / INFERENCE MODEL
- **Family:** CROSS-CUTTING RELATION MODEL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** future machine/inference specification
- **Definition:** A relation assertion produced by an explicitly permitted inference rule from asserted or previously inferred relations.
- **Model:** `ASSERTED RELATION → INFERENCE RULES → INFERRED RELATION`
- **Evidence:** OWL reasoning characteristics; SKOS transitive broader/narrower distinction; GIOP inference-boundary analysis.
- **GIOP Decision:** Retain as machine-semantics knowledge. No inference may be assumed unless the canonical relation definition authorizes it.

### N3. Qualified Relation

- **Registry ID:** `TERM-RELATION-QUALIFIED-RELATION-001`
- **Preferred Term:** `qualified relation`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** OTHER / QUALIFICATION MODEL
- **Family:** CROSS-CUTTING RELATION MODEL
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** relation specification / provenance / context model
- **Definition:** A relation assertion accompanied by qualification needed to represent time, space, role, process stage, provenance, observation conditions, measurement context, or another semantic modifier.
- **Evidence:** W3C PROV-O qualified relations; GIOP context/qualification analysis.
- **GIOP Decision:** Retain as cross-cutting modeling knowledge; qualification must not be confused with creating a new relation concept.

### N4. Direct vs Inferred Lineage

- **Registry ID:** `TERM-RELATION-DIRECT-VS-INFERRED-LINEAGE-001`
- **Preferred Term:** `direct versus inferred lineage`
- **Epistemic Status:** VERIFIED
- **Semantic Type:** PROVENANCE / INFERENCE MODEL
- **Family:** PROVENANCE / LINEAGE
- **Canonical Status:** ROUTED ELSEWHERE
- **Destination:** provenance and machine/inference semantics
- **Definition:** Distinction between an explicitly evidenced derivational relation and lineage obtained through a chain or inference rule.
- **GIOP Decision:** Retain as mandatory provenance reasoning distinction; never silently convert inferred ancestry into a direct derivation claim.

---

## Canonical Seed Relations

The current V3.1 canonical Relation seed is:

1. `part-of`
2. `participates-in`
3. `observes`
4. `represents`
5. `derived-from`

These five are the current canonical `relations/` pages. They are **not** the complete recovered Relation knowledge corpus.

## Knowledge-Retention Guarantee

Every relation term or relation-model concept recovered during the semantic pass remains represented in this registry or in its appropriate future primary semantic layer.

The following are therefore intentionally retained even though they are not current canonical `relations/` pages:

- `has-part`;
- `component-of` / `has-component`;
- `has-participant`;
- `is-observed-by`;
- `is-represented-by`;
- provenance generation, usage, attribution, and association relations;
- `uses`;
- `depends-on`;
- `measures`;
- spatial relations such as `located-in`, `contains`, `overlaps`, `touches`;
- temporal relations such as `before`, `after`, `during`, `meets`, temporal `overlaps`;
- causal/influence relations such as `causes`, `affects`;
- identity/equivalence relations such as `same-as`, `equivalent-to`, `corresponds-to`;
- associative relations such as `related-to`, `associated-with`;
- cross-cutting concepts such as relation assertion, inferred relation, and qualified relation.

Their current absence from `relations/` is a semantic routing decision, not deletion.

## Routing Principle

When future semantic folders are authored, retained relation knowledge must move from provisional registry-only routing to a primary canonical semantic entry where appropriate. The registry record remains as the audit trail and cross-layer decision record.

Examples:

`located-in → spatial/`

`before / after / during / meets → temporal/`

`same-as / equivalent-to → identity/`

`generated-by / attributed-to → provenance/`

`measures → quantities / measurement semantics`

`causes / affects → future causal semantics`

`uses / depends-on → future operational/dependency semantics`

## Completion State

The Relation semantic pass is complete only with respect to the current canonical seed and its retained research corpus. The five canonical relation pages plus this retained registry establish:

1. complete current canonical relation seed coverage;
2. explicit distinction between relation concepts and assertions;
3. explicit direction/inverse handling;
4. explicit logical-characteristic and inference boundaries;
5. retention of specialized relation families;
6. preservation of deferred, unresolved, and routed knowledge;
7. a durable path for future semantic expansion without reconstructing prior research.

No relation knowledge is silently discarded.
