# GIOP Canonical Relation Index

## Status

**CANONICAL**

This index enumerates the current V3.1 canonical Relation concepts published under `02 SEMANTICS/relations/`.

## Canonical Relations

| Preferred Term | GIOP ID | Family | Domain → Range | Direction | Inverse | Status |
|---|---|---|---|---|---|---|
| `part-of` | `SEM-RELATION-PART-OF-001` | Structural / Partitive | Part → Whole | Part → Whole | `has-part` | CANONICAL / ACTIVE |
| `participates-in` | `SEM-RELATION-PARTICIPATES-IN-001` | Participation | Participant → Occurrence | Participant → Occurrence | `has-participant` | CANONICAL / ACTIVE |
| `observes` | `SEM-RELATION-OBSERVES-001` | Observation | Observer → Target | Observer → Target | `is-observed-by` | CANONICAL / ACTIVE |
| `represents` | `SEM-RELATION-REPRESENTS-001` | Representation | Representation → Referent | Representation → Referent | `is-represented-by` | CANONICAL / ACTIVE |
| `derived-from` | `SEM-RELATION-DERIVED-FROM-001` | Provenance / Lineage | Derived → Source | Derived → Source | provenance inverse | CANONICAL / ACTIVE |
| `has-result` | `SEM-RELATION-HAS-RESULT-001` | Result / Output | Activity / Execution → Result | Activity / Execution → Result | `is-result-of` | CANONICAL / ACTIVE |

## Semantic Coverage

The six canonical relations establish a conservative V3.1 seed covering:

- structural constitution;
- participation in occurrences;
- observation;
- semantic representation;
- derivational provenance;
- result/output linkage.

The seed is intentionally conservative. It does not imply that the broader recovered relation corpus is unimportant or excluded.

## Retained Relation Families

Relation knowledge recovered during research also includes candidate or specialized families for:

1. component/system relations;
2. operational/usage relations;
3. dependency relations;
4. measurement relations;
5. spatial relations;
6. temporal relations;
7. causal/influence relations;
8. identity/equivalence relations;
9. associative/correspondence relations;
10. additional provenance relations;
11. unresolved or conflicted relation concepts.

These remain retained and are routed through the semantic registry until their dedicated semantic destination is authored and their boundaries are sufficiently reconciled.

## Concept vs Assertion

This index lists relation **concepts**, not individual relation assertions.

For example, `part-of` is a canonical relation concept. An assertion such as `Sensor-A part-of Camera-A` is instance-level knowledge and belongs to an appropriate knowledge graph, dataset, or application representation rather than this canonical concept page.

## Inference Safety

The presence of a relation in this index does not authorize arbitrary inference. Each relation page defines its direction, inverse, logical characteristics, qualification, and inference boundary.

Machines must use those definitions rather than infer semantics from the English relation name alone.

## Retention Rule

Any recovered relation term not present in this index remains discoverable through the semantic knowledge registry with its semantic type, epistemic status, evidence, canonical decision, destination, and rationale.

`NOT IN THIS INDEX ≠ NOT KNOWLEDGE`
