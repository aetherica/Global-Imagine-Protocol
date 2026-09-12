# Result Semantic Layer

**Status:** CLOSED — CURRENT V3.1 RESULT NUCLEUS
**Version:** 1.0.0

Result owns an entity produced, generated, or otherwise established as the outcome of an activity or execution. It is deliberately distinct from the activity that produced it, a quantity value contained in it, and a representation used to encode or present it.

## Canonical entry

- `SEM-RESULT-GENERIC-001` — Result — Active

## Core chain

`Procedure → Activity / Execution → Result → Representation`

`has-result` is the admitted relation connecting the execution/activity side to Result.

## Boundary

Result ≠ Measurement Result as a universal synonym. A measurement result is a specialized metrological interpretation. Result ≠ Representation; one result may have one or more representations. Result ≠ Quantity Value; a result may contain, assert, or provide values without becoming identical to the quantity concept.

Visitor Universe changes entry depth, not Result identity.
