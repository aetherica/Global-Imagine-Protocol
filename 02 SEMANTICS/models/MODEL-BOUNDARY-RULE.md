# Model — Boundary Rule

**Scope:** `02 SEMANTICS/models`  
**Status:** PROVISIONAL BOUNDARY CONTROL

## Ownership Rule

The `models/` folder owns the semantic identity of a **purpose-specific model construct**. It does not own every artifact, process, representation, method, result, or implementation that may be associated with a model.

## Non-Collapse Rules

1. Model ≠ Representation. Representation owns the information-bearing form; Model owns the purpose-specific abstraction and target-oriented modelling role.
2. Model ≠ Algorithm. Algorithm owns the computational method; Model is the construct being formulated, parameterized, trained, evaluated, or used.
3. Model ≠ Software. Software owns concrete implementation artifacts; a software artifact can implement or manipulate a model.
4. Model ≠ Activity. Training, calibration, simulation, inference, evaluation, and fitting are occurrences and route to Activity where that is the primary responsibility.
5. Model ≠ Process. A modelling or training pipeline may be a Process; the model is not the temporal course.
6. Model ≠ Procedure / Workflow. A procedure specifies how work should be performed; a model is the construct used or produced by that work.
7. Model ≠ Result. A model can be produced or updated as a result, but a prediction, estimate, rendering, or measurement result is not automatically the model.
8. Model ≠ State. Model identity persists independently of a current configuration or mode of a model-bearing system.
9. Model ≠ Condition. Environmental, operating, measurement, or viewing circumstances qualify model use but are not absorbed into model identity.
10. Model ≠ Context. Interpretive or application framing remains Context ownership.
11. Model ≠ Property / Quantity. Characteristics and measured values of a model remain in their respective layers.
12. Model ≠ Relation. Connections involving a model use existing relation authority; no model-specific relation predicate is introduced here.
13. Model ≠ Class. A model may describe classes or instances without becoming a Class ontology.
14. Model ≠ Ontology. An ontology is a knowledge-structuring artifact or formal vocabulary; not every ontology is a model and not every model is an ontology.
15. Model ≠ BIL integrity. BIL may evaluate integrity of information or configuration associated with model use, but BIL does not own model semantics.

## Representation Boundary

A model may be expressed through diagrams, equations, files, graphs, programs, parameter sets, tensors, text, meshes, or other representations. Multiple representations may express one model, and one representation may encode information about several semantic entities. The carrier does not determine model identity.

## Computational Boundary

A model may be computational, but computational realization does not move the model into Computational Methods or Implementations. `Algorithm` owns method; `Software` owns implementation; `Activity`/`Process` owns execution or organized work.

## AI / ML Boundary

Machine-learning model and AI model are controlled model vocabulary. They are not a separate canonical GIOP layer at this stage. Their algorithms, training activities, software implementations, datasets, evaluation results, parameters, representations, and system contexts retain their existing owners.

## Physical / Scale Model Boundary

A physical or scale model may be materially embodied. The semantic Model identity is the purpose-specific abstraction or surrogate role; the physical bearer retains its own Class, Object, Material, Property, State, and other applicable semantics.

## Digital-Twin Boundary

A digital-twin model can be a Model candidate, while the digital-twin system, representations, synchronization activities, state, data, software, and results retain their respective responsibilities. No automatic promotion of “Digital-Twin Model” is made by lexical association.

## Relation Authority

Only existing GIOP relations may be used where applicable: `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result`. Terms such as `models`, `instantiates`, `implements`, `conforms-to`, `has-input`, or `has-output` are not admitted as new canonical relation predicates by this folder.

## Promotion Boundary

A specialized Model concept can be promoted only after independent identity, responsibility, duplicate-authority, evidence, boundary, relation, lifecycle, and cross-layer validation. Frequency of use, common terminology, or external standard naming is insufficient on its own.