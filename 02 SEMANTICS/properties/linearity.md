# Linearity

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-LINEARITY-001
- **Canonical Label:** Linearity
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Linearity is a characteristic describing how closely a defined system's output-response relationship follows a specified linear reference relationship over a defined input or operating range.

### Who / What Can Bear It
Sensors, imaging systems, measuring systems, and other eligible systems for which an input-output relationship and reference linearity model are defined.

### Where
It concerns the response relationship of the relevant system over a defined input, output, or operating domain.

### When
Its realization depends on the selected range, reference model, operating conditions, system state, and evaluation method.

### Why
The Property separates the reusable characteristic of linear response behaviour from fitted parameters, residuals, errors, and measurement results.

### How
It may be characterized through a defined reference relationship, fitting method, regression, residual analysis, or standardized measurement procedure.

## Semantic Definition

**Linearity is a reusable canonical semantic concept denoting a characteristic of an eligible system concerning how closely its defined output-response relationship follows a specified linear reference relationship over a defined input or operating domain.**

## What This Property Characterizes

It characterizes linear response behaviour relative to an explicitly defined reference and domain. It does not itself specify the range, fitted line, deviation, or numerical error.

## Bearer / Applicability

Applicable to sensors, imaging systems, measuring systems, and other systems for which linearity can be meaningfully defined. Applicability requires an identifiable response relationship and reference framework.

## Distinctions

- **Linearity vs Sensitivity:** sensitivity concerns response dependence; linearity concerns conformity of the response relationship to a specified linear reference.
- **Linearity vs Accuracy:** accuracy concerns agreement with a reference or true value under a measurement definition; linearity concerns response-form behaviour.
- **Linearity vs Noise:** noise is variability or disturbance and may affect evaluation, but is not linearity itself.
- **Linearity vs Linearity Error:** error/deviation is a quantitative realization or result, not the characteristic concept.

## Quantification

Quantitative realizations may include linearity error, deviation from a fitted line, residuals, slope/intercept parameters, or other defined indicators. Their interpretation depends on the reference model, domain, fitting method, and procedure.

## Value Semantics

The Property itself has no numerical value. A linearity error or fitted parameter MUST retain its quantity/value semantics and evaluation context.

## Conditions and Context

Relevant context may include input range, output domain, reference model, fitting method, gain, exposure/integration conditions, temperature, operating state, calibration state, and test configuration. These qualifiers are not asserted by the Property itself.

## Measurement Context

Linearity evaluation requires an explicit definition of the response relationship, reference, domain, and evaluation method. A Property assertion does not establish a particular standard, regression method, or error value.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `characterized-by`. Fitted models and error results remain separate semantic entities.

## Subproperties

No specialized linearity subtype is canonicalized in the seed vocabulary.

## Synonyms / Related Terms

Related terms include linear response and response linearity. Terminological equivalence depends on the declared reference and domain.

## Evidence and Provenance

Supported by measurement and imaging characterization practice, including EMVA 1288 treatment of linearity and linearity error. The GIOP definition is an independent semantic synthesis from that evidence.

## Trust and Validation

Presence of the Property MUST NOT be interpreted as proof of a numerical linearity range, maximum error, calibration validity, or compliance with a particular test standard.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Domain-specific forms may be introduced through the normal verification workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible bearer when a linear-response characteristic is applicable. It MUST NOT infer a numerical error, range, fitted model, or test outcome from the Property alone.

## Retrieval Anchors

`linearity`, `linear response`, `response linearity`, `linearity error`, `linear response characteristic`

## What This Property Does NOT Mean

It does not mean zero error, perfect measurement accuracy, calibrated operation, or an unlimited linear operating range.

## Semantic Boundary

`LINEARITY → PROPERTY`

`LINEARITY ERROR / DEVIATION → QUANTITY / VALUE / RESULT`

`FITTING / REGRESSION → MODEL / ACTIVITY as applicable`

`LINEARITY EVALUATION → ACTIVITY / MEASUREMENT`

`CALIBRATION STATUS → STATE / STATUS`

This document defines the reusable characteristic concept only.