# Process Boundary Rule

## Governing Rule

**Process = organized temporal course of interrelated or interacting activities that uses, transforms, or coordinates inputs toward results.**

## Non-Equivalence

```text
Process ≠ Activity
Process ≠ Procedure
Process ≠ Result
Process ≠ State
Process ≠ Condition
Process ≠ Context
Process ≠ Representation
Process ≠ Algorithm
Process ≠ Software
Process ≠ Workflow document
Process ≠ Project
Process ≠ Method
```

## Routing Matrix

| Observed responsibility | Canonical route | Reason |
|---|---|---|
| organized temporal course | Process | primary responsibility |
| actual occurrence | Activity | occurrence semantics |
| prescribed way of doing | Procedure / applicable layer | specification semantics |
| output/generated information | Result | outcome semantics |
| recognized mode at temporal locus | State | state semantics |
| environmental/operational circumstance | Condition | circumstance semantics |
| interpretive/situational frame | Context | framing semantics |
| information-bearing form | Representation | representational semantics |
| computational method | Algorithm / applicable layer | method semantics |
| implementation artifact | Software / applicable layer | implementation semantics |
| named execution workflow | candidate pending analysis | workflow can denote model, artifact, or process |

## Granularity Rule

A Process may be composite and may include or organize multiple Processes and Activities. Granularity must follow the semantic scope of the assertion, not arbitrary decomposition.

## Temporal Rule

A temporal duration is necessary for the ordinary process interpretation but is not sufficient by itself. A long-running Activity remains an Activity when its primary identity is the occurrence itself.

## Transformation Rule

A transformation may occur within a Process, but not every transformation is itself a Process. If the primary identity is a specific occurrence, route to Activity; if the identity is a measurable characteristic, route to Quantity/Property; if it is an algorithmic method, route to Algorithm.

## Workflow Rule

A workflow may denote a process, a process model, a procedure, a software automation artifact, or a representation of one of these. The lexical term `workflow` therefore cannot automatically define a canonical Process subtype.

## Result Rule

Results remain independent semantic objects. A Process may contribute to a Result, but the Result is not a Process state, stage, or subclass.

## Relation Rule

No new relation authority is created here. Existing GIOP relations may be reused only according to their established semantics.

## Visitor Rule

No visitor-specific Process records are permitted. All visitor classes enter the same canonical Process knowledge through different entry depths.

## Canonicalization Rule

```text
NEW / RECOVERED KNOWLEDGE
        ↓
SEMANTIC REGISTRY
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

`VERIFIED ≠ CANONICAL`; `NON-CANONICAL ≠ FALSE`; `DEFERRED ≠ DELETED`.
