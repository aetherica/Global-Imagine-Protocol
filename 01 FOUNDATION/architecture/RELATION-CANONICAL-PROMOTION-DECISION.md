# Relation Canonical Promotion Decision

## Final State
**PROMOTED TO ACTIVE CANONICAL — SCOPED V3.1 RELATION BATCH**

## Canonical Seed
The following six Relation concepts are active canonical for the scoped V3.1 decision:

- `SEM-RELATION-PART-OF-001` — `part-of`
- `SEM-RELATION-PARTICIPATES-IN-001` — `participates-in`
- `SEM-RELATION-OBSERVES-001` — `observes`
- `SEM-RELATION-REPRESENTS-001` — `represents`
- `SEM-RELATION-DERIVED-FROM-001` — `derived-from`
- `SEM-RELATION-HAS-RESULT-001` — `has-result`

All six are versioned at 1.0.0 within the scoped implementation.

## Reconciliation Outcome
The canonical index and README now distinguish the six-concept seed from retained relation knowledge. `viewing-distance` remains discoverable as `SEM-RELATION-VIEWING-DISTANCE-001` with status **ROUTED — SPECIALIZED RELATION CANDIDATE**. This prevents both silent deletion and premature expansion of the core Relation vocabulary.

## Validation
The companion Relation Semantic Validation Record reports Gates A–J PASS. Gate J approval is recorded in `GATE-J-RELATION-PROMOTION-APPROVAL.md`.

## Architectural Consequences
The Relation layer now provides the reusable connection layer needed to connect the existing Class, Condition, Activity, Result, Representation, Quantity, and other semantic layers without absorbing their responsibilities. Relation assertions remain instance-level knowledge and may carry qualification, evidence, provenance, and asserted/inferred status.

## Visitor Universe
No visitor-specific relation definitions are created. The same canonical relation receives different entry depths: orientation, technical semantic contract, and formal/machine interpretation.

## Scope Control
This decision does not canonicalize the broader recovered relation corpus. Operational/usage, dependency, measurement, spatial, temporal, causal, identity/equivalence, mapping, and other high-risk or specialized relation families remain candidates for later explicit routing and promotion decisions.

## Lifecycle
Current state: ACTIVE CANONICAL for the named scoped seed. Future semantic changes require explicit review, validation, promotion, versioning, and preservation of prior decisions.
