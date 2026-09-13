# Model — Cross-Layer Validation

**Scope:** `02 SEMANTICS/models`  
**Status:** PROVISIONAL VALIDATION RECORD

## Validation Matrix

| GIOP area | Model interaction | Decision |
|---|---|---|
| Class | A model may describe a class, but does not become the class ontology | Preserve Class authority |
| Property | Model may contain or estimate properties; Property owns characteristic semantics | Separate |
| Condition | Conditions qualify model use, training, observation, or evaluation | Separate |
| State | A model can encode or predict state; State owns current mode/configuration | Separate |
| Quantity | Model parameters or outputs may be quantities; Quantity owns measurable concepts/values | Separate |
| Activity | Training, fitting, simulation, inference, calibration, and evaluation are activities when occurrence is primary | Separate |
| Process | A modelling or ML pipeline may be a process | Separate |
| Relation | Model associations use admitted relation vocabulary only | Preserve six-relations authority |
| Context | Application, measurement, viewing, operational, or assessment framing stays in Context | Separate |
| Observation / Perception | Observations can provide data to a model; perception remains perception | Separate |
| Result | Predictions, estimates, scores, and outputs are results where applicable | Separate |
| Workflow | A prescribed modelling or evaluation procedure remains workflow/procedure semantics | Separate |
| Computational Method | Algorithm remains the method that may construct/use/train/evaluate a model | Separate |
| Implementation | Software may implement or expose a model | Separate |
| Representation | Model carriers remain Representation; model identity remains purpose/target-based | Separate |
| Provenance | Source, lineage, authenticity, and evidence remain Foundation-level concerns | Separate |
| BIL | Integrity evaluation may consume model-associated evidence; BIL does not own Model | Separate |

## Critical Collision Tests

### Model / Representation

Passed. The candidate Model is defined by target-oriented modelling purpose and abstraction, while Representation is defined by information-bearing form. The overlap of representations of models does not collapse the authorities.

### Model / Algorithm

Passed. Algorithm is implementation-independent computational method. Model can be an input, output, object of evaluation, or operational construct without becoming an algorithm.

### Model / Software

Passed. Software is a concrete implementation artifact. Model is not assigned to the implementation layer merely because many computational models are distributed as software artifacts.

### Model / Predictive and Causal Representations

Passed. Predictive/causal representation entries remain representation responsibilities. A predictive or causal model is retained as controlled vocabulary pending independent review.

### Model / Digital-Twin Representation

Passed. Digital-Twin Representation remains information-bearing form. A Digital-Twin Model remains candidate model vocabulary; digital-twin system and state semantics remain external responsibilities.

### Model / Result

Passed. A prediction produced by a model is not identical to the model. Result ownership remains independent.

### Model / Process

Passed. Training/model-development pipelines can be Process; the model is the construct produced or used by such a course.

## Relation Authority Check

No new predicate is required for the generic Model entry. No model-specific canonical relation has been introduced.

## Visitor Universe Check

All 45 visitor categories can retrieve the same `SEM-MODEL-GENERIC-001` at different entry depths. No category receives a duplicate semantic record.

## Lifecycle Check

The Model candidate has a distinguishable authoring and validation lifecycle and is not silently treated as Active Canonical.

## Final Validation Decision

The generic Model responsibility is semantically coherent and sufficiently distinct from established layers to remain a controlled V3.1 candidate. Active promotion requires an independent Gate-J-compatible review; this phase does not infer such approval from unrelated prior batches.