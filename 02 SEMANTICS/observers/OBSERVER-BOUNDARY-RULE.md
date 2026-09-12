# Observer Boundary Rule

**Semantic Layer:** Observer  
**Version:** 1.0.0  
**Status:** Active  

## Governing Rule

The Observer layer owns reusable semantics whose primary responsibility is an observing entity/participant or a reusable formal model of observer response.

## Hard Boundaries

- Observer is not Observer Model.
- Observer is not Observation or Measurement.
- Observer Model is not Procedure, Algorithm, Software, Dataset, Representation, or Result.
- Perceptual experience or interpretation belongs to Perception, not Observer.
- A task or viewing context qualifies an observer-related assertion; it does not automatically define a new Observer concept.
- A numerical model parameter is not automatically a Quantity; classify it by its independent semantic role.
- A standard document is not automatically the semantic object it specifies.
- A dataset containing observer functions is not automatically the Observer Model.

## Standard Observer Boundary

A Standard Observer is a candidate specialization of Observer Model when a recognized authority defines a reusable observer-response construct with stable scope. CIE standard colorimetric observers provide strong evidence for this pattern. The CIE 1931 and CIE 1964 functions and datasets are representations/data associated with the observer models rather than replacements for model identity.

## Individual and Population Boundary

Individual Observer, Population Observer, Human Observer Model, and related terms may describe different scopes. They should remain candidates until the intended responsibility is demonstrably independent of the generic Observer Model and the distinction is reusable across the corpus.

## Visitor Neutrality

Visitor Universe categories must never determine whether a term is an Observer, Observer Model, Observation, Perception, or another semantic layer. Audience relevance changes entry depth, not semantic identity.
