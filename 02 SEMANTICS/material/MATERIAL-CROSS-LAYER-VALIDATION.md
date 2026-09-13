# Material — Cross-Layer Validation

**Status:** IMPLEMENTATION-COMPLETE — CLASS-ROUTED DOMAIN COORDINATION

| Validation question | Primary owner | Material routing decision |
|---|---|---|
| What is the physical substance/medium? | Class — Material | Route to `SEM-CLASS-MATERIAL-001`. |
| What characteristic does the material have? | Property | Do not create a material property concept under Material. |
| What measurable kind or value is involved? | Quantity / Quantity Value | Route measurement semantics outward. |
| Was the material measured or characterized? | Activity — Measurement | The material may be the target; measurement remains Activity. |
| What was produced by characterization? | Result | Result remains separate from Material. |
| What specific thing is made from the material? | Class — Object | Object identity remains separate. |
| What boundary/interface exhibits the material? | Surface | Surface remains separate. |
| Is the concept fibre/yarn/fabric/textile structure/finish? | Textile | Route to Textile where textile responsibility is primary. |
| Is the concept a wearable article/component? | Garment | Route to Garment where garment responsibility is primary. |
| Was the material changed, processed, manufactured, tested, or recycled? | Activity / Process / Workflow | Route the operation outward. |
| Is the target a temporary mode or environmental state? | State / Condition | Route state/condition outward. |
| Is the target a photo, scan, mesh, drawing, file, or encoding of material? | Representation | Representation owns the information-bearing form. |
| Is the claim about origin, history, authenticity, or custody? | Foundation / Provenance | Keep provenance distinct from Material. |
| Is the claim supported by analytical evidence? | Evidence / Validation | Evidence and decision remain distinct from Material. |
| Does material affect biological/configurational integrity? | BIL | BIL may evaluate; it does not own Material. |

## Validation Invariants

1. `SEM-CLASS-MATERIAL-001` remains the only canonical Material identity.
2. No new Material semantic layer is introduced.
3. No new Relation predicate is introduced.
4. Material-specific vocabulary remains subject to independent ownership analysis.
5. Visitor routing changes access depth only and never creates a material-specific ontology.

## Machine Validation Rule

A machine classifier may infer a material label from image, spectral, contextual, or textual evidence, but the inferred label must be treated as an assertion/inference supported by evidence and confidence rather than silently equated with the Material itself. Representation, observation, measurement, evidence, and material identity remain distinct.

## Outcome

Cross-layer validation passes with Material fully routed to the existing Class authority and all adjacent responsibilities preserved.
