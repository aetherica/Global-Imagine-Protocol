# Model — Semantic Analysis Specification

**ID:** `SEM-MODEL-GENERIC-001`  
**Status:** PROVISIONAL — V3.1 CANDIDATE SEMANTIC LAYER  
**Scope:** Generic Model responsibility only

## 1. Identity and Primary Responsibility

Model denotes a purpose-specific construct used to abstract, characterize, simulate, predict, explain, design, compare, or reason about a selected target system, phenomenon, structure, behavior, or domain of interest.

The defining responsibility is the **modeling construct and its target-oriented purpose**, not the physical or digital carrier used to store it.

## 2. Substantive 5W1H

### What

A Model is a deliberately constructed abstraction whose content, structure, assumptions, parameters, idealizations, or learned organization are selected for a purpose relative to a target. The target may be a physical system, phenomenon, process, population, environment, conceptual domain, or other object of study.

A model can be formal or informal, deterministic or probabilistic, mechanistic or empirical, learned or hand-specified, static or dynamic, computational or non-computational. These are dimensions of model use or type; they do not by themselves create separate GIOP layers.

### Why

Model semantics are required because reasoning often concerns an abstraction of a target rather than the target itself, and because different carriers can express the same model. A model may support explanation, prediction, simulation, design, analysis, estimation, control, communication, or decision support without becoming the Activity, Algorithm, Software, Result, or Representation used in that work.

### Who

Models may be authored, calibrated, trained, selected, evaluated, interpreted, or consumed by researchers, engineers, operators, institutions, software systems, or other eligible agents. The creator or user is not part of the model's semantic identity. An automated system can also carry or execute a model without the model becoming the system.

### Where

Model semantics apply across science, engineering, imaging, optics, computer vision, artificial intelligence, statistics, simulation, architecture, systems engineering, manufacturing, medicine, economics, preservation, and other domains where a selected abstraction is used for a defined purpose. Domain specialization belongs in the relevant domain or controlled candidate set when generic Model no longer provides adequate semantic specificity.

### When

A model has a lifecycle across formulation, parameterization or training where applicable, validation, use, revision, versioning, retirement, and possible supersession. A model may be static or time-varying in what it describes, but temporal change in the target is not itself the model's lifecycle.

### How

A model is established by selecting a target and purpose, deciding what aspects are retained or abstracted, defining assumptions or learned parameters where applicable, and validating whether the model is fit for its intended use. Training is a type of Activity or Process when performed; an algorithm is the computational method; software is an implementation; representations are carriers through which model information may be expressed or exchanged.

## 3. Semantic Definition

A Model is a purpose-specific abstraction or construct that stands for, characterizes, or structurally corresponds to selected aspects of a target for reasoning, explanation, prediction, simulation, design, analysis, or related use.

The semantic center is the combination of **selected target, modelling purpose, and abstraction**. A file, tensor, diagram, code artifact, trained parameter set, or physical object may carry or realize a model, but the carrier is not automatically the model identity.

## 4. Scope and Boundary

### Model owns

- the purpose-specific abstraction as a semantic construct;
- the selected target or target class at the model's scope;
- the assumptions, idealizations, structure, or learned organization that define the model as a model;
- the model's intended analytical, predictive, explanatory, simulation, design, or comparable use.

### Model does not own

- information-bearing form or encoding — Representation;
- computational method — Algorithm;
- concrete executable artifact — Software;
- occurrence of training, simulation, fitting, evaluation, or inference — Activity;
- organized temporal course — Process;
- prescribed procedure — Workflow / Procedure;
- generated output — Result;
- measurable characteristic — Property / Quantity;
- current configuration or mode — State;
- environmental or operational circumstance — Condition;
- interpretive setting — Context;
- provenance or integrity governance — Foundation / BIL as applicable.

## 5. Core Distinctions

### Model vs Representation

Representation concerns an information-bearing form. Model concerns the purpose-specific abstraction and its target-oriented role. A model can have multiple representations, and one representation can carry information about more than one model. The overlap does not justify collapsing the layers.

### Model vs Algorithm

An Algorithm specifies a computational method. A Model is the construct on which the method operates or which the method may construct, parameterize, evaluate, or use. Training an ML model does not make the model an algorithm.

### Model vs Software

Software is a concrete implementation artifact. A model may be encoded in or realized by software, and software may manipulate multiple models. Their identities remain distinct.

### Model vs Result

A model may be produced or modified as the outcome of an Activity, but a model is not synonymous with every output generated from model use. Predictions, measurements, renderings, and other outputs retain Result responsibility where applicable.

### Model vs State

A model can include or predict states, but the current state of a model-bearing system is not the model itself. State remains the current recognized mode or configuration.

### Model vs Causal / Predictive Representation

A causal or predictive Representation expresses information in a representation form. A causal or predictive Model is a target-oriented construct whose purpose includes causal or predictive reasoning. Representation and Model therefore cross-reference conceptually but do not collapse.

## 6. Cross-Domain Significance

The generic Model responsibility provides a stable semantic landing point for model terminology across scientific, engineering, AI, computational, and domain-specific practices. It permits a machine-learning model, a scientific model, and a system model to be recognized as model instances without forcing them into one inheritance taxonomy or prematurely promoting every named model type.

This also prevents representation-specific vocabulary from absorbing model semantics merely because many models are encoded as representations, and prevents algorithm/software vocabularies from absorbing the model itself.

## 7. Trust and Evidence

Evidence for a model claim can include source definitions, model specifications, training or calibration records, validation results, version history, documentation, or implementation observations. Evidence quality and provenance are not themselves model semantics.

A source calling an artifact a “model” is evidence of terminology use, not automatic evidence that GIOP should create a separate semantic identity. Conflicting domain meanings must be preserved until primary responsibility is resolved.

## 8. Visitor Universe Integration

All visitor categories consume the same Model identity. A novice may enter through target and purpose; a scientist through assumptions, scope, and validation; an engineer through structure and realization; an AI/ML specialist through training and inference context; a machine consumer through the stable ID, structured metadata, and routing anchors. These are entry depths, not alternate model identities.

## 9. Lifecycle

`CANDIDATE → PROVISIONAL → VALIDATED → PROMOTION REVIEW → ACTIVE` is the applicable governance trajectory when promotion is pursued. Retirement or supersession must preserve prior identity and provenance rather than silently replacing it.

For the current phase the generic Model remains **PROVISIONAL**, because this authoring pass establishes semantic responsibility and evidence boundaries but does not inherit unrelated Gate-J approval.

## 10. Retrieval Anchors

`SEM-MODEL-GENERIC-001`, `MODEL`, `MODELLING`, `MODEL CONSTRUCT`, `TARGET SYSTEM`, `PURPOSE-SPECIFIC ABSTRACTION`, `SCIENTIFIC MODEL`, `MATHEMATICAL MODEL`, `COMPUTATIONAL MODEL`, `MACHINE-LEARNING MODEL`, `AI MODEL`, `SIMULATION MODEL`

## 11. Evidence Families Used

- ISO/IEC 22989 terminology for AI models and related AI concepts.
- ISO/IEC 23053 framework terminology for ML-based AI systems.
- OMG Model Driven Architecture and MOF traditions for model/metamodel distinction and implementation separation.
- W3C PROV for distinction between entities, activities, and provenance-bearing processes.
- W3C Machine Learning Schema work as evidence that ML algorithms, datasets, experiments, and results require separable semantic treatment.
- Scientific modelling literature and philosophy-of-science work on models as purpose-specific representations of target systems.

External traditions are evidence for synthesis, not GIOP authority.