# Temperature Condition

**Semantic ID:** `SEM-CONDITION-TEMPERATURE-001`  
**Preferred Name:** Temperature Condition  
**Semantic Class:** Condition  
**Domain:** Optical Imaging  
**Status:** Active  
**Version:** 1.0.0

> Temperature Condition describes the thermodynamic temperature context relevant to a defined imaging, observation, measurement, or environmental situation; it is not itself a camera setting, color appearance, or measurement result.

## 5W1H Orientation

### What

A Temperature Condition describes the thermodynamic temperature context associated with a defined object, material, environment, measurement system, or imaging situation.

### Why

Temperature can influence optical behavior, material response, sensor behavior, measurement conditions, environmental stability, and the interpretation of observations. The temperature context therefore needs to remain distinguishable from the physical quantity of temperature itself, from color temperature, and from any result derived from a measurement.

### Who

The concept is relevant to observers, photographers, cinematographers, optical engineers, sensor engineers, imaging scientists, metrology professionals, thermal-imaging specialists, laboratory personnel, simulation systems, and machine-readable systems.

### Where

It may apply to scenes, objects, materials, optical systems, sensors, measurement systems, laboratories, environmental conditions, displays, and computationally modeled environments.

### When

A Temperature Condition is always interpreted for a specified temporal context. Temperature may vary over an instant, interval, exposure, acquisition sequence, processing period, or longer environmental period.

### How

A Temperature Condition is characterized by identifying the relevant physical system or region and the temperature context applicable to that system or region. Where quantitative characterization is required, the associated temperature quantity, scale, measurement procedure, uncertainty, and time context must be specified separately.

## Semantic Definition

**Temperature Condition** is the contextual thermodynamic-temperature circumstance associated with a defined physical system, region, object, material, environment, or measurement configuration.

Temperature Condition provides context for interpreting temperature-dependent behavior. It does not itself represent a temperature quantity value, a measurement result, a color-temperature setting, or a perceptual appearance.

## Scope

This condition concerns physical thermodynamic temperature as contextual information. A temperature value belongs to the quantity layer; a recorded temperature observation or measurement result belongs to the appropriate result/measurement semantics.

## Core Distinctions

### Temperature Condition vs Temperature Quantity

Temperature Condition describes the contextual circumstance. Temperature as a measurable physical quantity expresses the magnitude of thermodynamic temperature for a defined quantity system.

### Temperature Condition vs Measurement Result

A measured temperature is a result produced through a measurement process. The condition describes the state being characterized, including its temporal and contextual scope.

### Temperature Condition vs Color Temperature

Color temperature is an optical/colorimetric concept associated with the chromatic appearance of radiation and is not interchangeable with the physical thermodynamic temperature of an object or environment.

### Temperature Condition vs Correlated Color Temperature

Correlated color temperature (CCT) characterizes the color appearance of a light source or radiation relative to a reference radiator. It is not a general substitute for physical temperature.

### Temperature Condition vs Sensor Temperature Setting

A device may expose a temperature-related setting, calibration coefficient, or compensation parameter. Such implementation details must not redefine the underlying semantic meaning of physical temperature.

### Temperature Condition vs Ambient Condition

Ambient temperature is a particular contextual temperature associated with the surrounding environment. Temperature Condition may also concern the temperature of a sensor, material, optical component, object, or other defined system.

## Context Dimensions

Where materially relevant, a Temperature Condition should be interpreted with respect to:

- spatial region or physical system;
- temporal instant or interval;
- temperature scale or reference;
- measurement method or procedure;
- thermal equilibrium or transient state;
- relevant material or device characteristics;
- environmental coupling;
- whether the statement concerns physical condition, measured value, calibration, compensation, or representation.

## Imaging and Measurement Significance

Temperature may influence optical and imaging systems through thermal expansion, refractive-index changes, material response, detector behavior, electronic characteristics, dark signal, calibration stability, and environmental changes. The existence and magnitude of any such effect must be established for the relevant system and measurement context rather than assumed universally.

A temperature context can therefore participate in a measurement model as a contextual or influence quantity without becoming the measurement result itself.

## Cross-Domain Significance

Temperature Condition provides a bridge between:

`Environment / Object → Temperature Condition → System Response → Observation / Measurement → Result`

It may also participate in camera and sensor characterization, laboratory measurements, optical-system stability, material behavior, thermal environments, and calibration workflows.

## Relations

Potential canonical relations include:

- `has-condition`
- `has-temperature-condition`
- `influences`
- `applies-to`
- `measured-by`
- `has-result`

These relations are resolved independently in the GIOP semantic relation domain.

## Trust

Statements about Temperature Condition should identify the relevant physical system, spatial/temporal scope, and measurement context whenever those dimensions materially affect interpretation.

A statement such as “the temperature was 25 °C” is incomplete for technical use unless it is clear what was at that temperature, when, where, and how the value was established.

Color temperature or CCT terminology must not be silently interpreted as physical thermodynamic temperature.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`TEMPERATURE CONDITION`, `TEMPERATURE`, `THERMODYNAMIC TEMPERATURE`, `AMBIENT TEMPERATURE`, `COLOR TEMPERATURE`, `CORRELATED COLOR TEMPERATURE`, `CCT`, `TEMPERATURE EFFECT`, `THERMAL CONDITION`, `INFLUENCE QUANTITY`
