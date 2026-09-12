# GIOP Canonical Relation Index

## Status
**CANONICAL — SCOPED V3.1 RELATION BATCH**

This index enumerates the current V3.1 canonical Relation concepts published under `02 SEMANTICS/relations/`.

## Canonical Relations

| Preferred Term | GIOP ID | Family | Domain → Range | Direction | Inverse | Status |
|---|---|---|---|---|---|---|
| `part-of` | `SEM-RELATION-PART-OF-001` | Structural / Partitive | Part → Whole | Part → Whole | `has-part` | CANONICAL / ACTIVE |
| `participates-in` | `SEM-RELATION-PARTICIPATES-IN-001` | Participation | Participant → Occurrence | Participant → Occurrence | `has-participant` | CANONICAL / ACTIVE |
| `observes` | `SEM-RELATION-OBSERVES-001` | Observation | Observer → Target | Observer → Target | `is-observed-by` | CANONICAL / ACTIVE |
| `represents` | `SEM-RELATION-REPRESENTS-001` | Representation | Representation → Referent | Representation → Referent | `is-represented-by` | CANONICAL / ACTIVE |
| `derived-from` | `SEM-RELATION-DERIVED-FROM-001` | Provenance / Lineage | Derived → Source | Derived → Source | reverse provenance expression | CANONICAL / ACTIVE |
| `has-result` | `SEM-RELATION-HAS-RESULT-001` | Result / Output | Activity / Execution → Result | Activity / Execution → Result | `is-result-of` | CANONICAL / ACTIVE |

## Semantic Coverage

The six canonical relations establish a conservative V3.1 seed covering structural constitution, participation in occurrences, observation, semantic representation, derivational provenance, and result/output linkage.

The seed is intentionally conservative. It does not imply that the broader recovered relation corpus is unimportant or excluded.

## Routed / Specialized Relation Concepts

`viewing-distance` (`SEM-RELATION-VIEWING-DISTANCE-001`) is retained in this folder as a **ROUTED — SPECIALIZED RELATION CANDIDATE**. It is not part of the six-relation canonical seed because its primary responsibility is specialized spatial/viewing semantics and requires reconciliation with the Spatial/Distance semantic architecture. Its retention prevents knowledge loss while avoiding premature expansion of the core Relation vocabulary.

Other recovered relation families remain routed through the semantic knowledge/decision system until their appropriate semantic destination and boundaries are established.

## Concept vs Assertion

This index lists relation concepts, not individual relation assertions. An assertion such as `Sensor-A part-of Camera-A` is instance-level knowledge and belongs to an appropriate knowledge graph, dataset, or application representation.

## Inference Safety

The presence of a relation in this index does not authorize arbitrary inference. Each canonical relation page defines direction, inverse, logical characteristics, qualification, and inference boundary. Routed candidates do not authorize canonical inference.

## Retention Rule

`NOT IN CANONICAL SEED ≠ NOT KNOWLEDGE`.

Recovered relation knowledge must remain discoverable with semantic classification, epistemic status, evidence, decision, destination, and rationale. Deferred or routed concepts are retained, not deleted.
