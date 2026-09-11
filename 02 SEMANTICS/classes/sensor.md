# Sensor

**GIOP Semantic Class ID:** `SEM-CLASS-SENSOR-001`

## Identity

**Preferred Name:** Sensor  
**Artifact Class:** Sensing Element or Sensing Subsystem  
**Artifact Type:** Sensor  
**Primary Domain:** Sensing and imaging  

## 5W1H Orientation

**What:** A sensor is an element or subsystem that responds to an input and produces a signal or other output suitable for sensing, detection, measurement, or information acquisition.

**Why:** A sensor provides a physical or computational interface between an observed input and a usable sensing output.

**Who:** Sensors may be designed, integrated, calibrated, tested, operated, or evaluated by engineers, scientists, technicians, automated systems, or instrument manufacturers.

**Where:** Sensors occur in cameras, measuring systems, scientific instruments, industrial systems, vehicles, robotics, environmental monitoring, consumer devices, and other sensing contexts.

**When:** Sensor behavior depends on the input, operating condition, configuration, temporal behavior, and response characteristics of the sensor.

**How:** A sensor detects or responds to a specified input through a physical or other sensing mechanism and produces an output signal, state, value, or data product.

## Semantic Definition

A **Sensor** is a sensing entity that is directly affected by an input of interest and provides an output used for detection, sensing, measurement, or information acquisition.

The definition is mechanism-independent. A sensor may use optical, electrical, thermal, mechanical, chemical, magnetic, acoustic, biological, or other mechanisms.

## Imaging Scope

In imaging contexts, a sensor may be an array or sensing subsystem that spatially samples incident radiation or another imaging signal. Examples include image sensors used in cameras and specialized scientific detectors.

An imaging sensor is not equivalent to the complete camera system.

## Distinctions

### Sensor vs Camera

A sensor is a sensing element or subsystem. A camera is a system-level capture entity that may incorporate a sensor.

### Sensor vs Detector

Detector is a broader or domain-specific designation for an entity that detects a signal. Sensor emphasizes an element directly affected by the input and used for sensing or measurement. The terms may overlap in particular technical domains and should not be treated as universally interchangeable.

### Sensor vs Measuring System

A sensor may be part of a measuring system. The measuring system is the complete configured system used to perform measurement.

### Sensor vs Signal

A sensor is an entity. A signal is an output or information-bearing phenomenon produced, transmitted, or processed by a sensor or another source.

### Sensor vs Measurement

A sensor participates in sensing or measurement. Measurement is an activity and is not a sensor class.

## Principal Types

Examples include:

- image sensor;
- CMOS image sensor;
- CCD image sensor;
- infrared sensor;
- photodetector;
- thermal sensor;
- temperature sensor;
- pressure sensor;
- motion sensor;
- acoustic sensor;
- chemical sensor;
- magnetic sensor;
- multispectral sensor;
- hyperspectral sensor;
- event-based imaging sensor.

The examples are not an exhaustive taxonomy.

## Technical Characteristics

Relevant sensor characteristics may include:

- sensing principle;
- spectral response;
- spatial sampling;
- temporal response;
- sensitivity;
- responsivity;
- dynamic range;
- noise characteristics;
- saturation behavior;
- linearity or nonlinearity;
- pixel or element geometry;
- fill factor where applicable;
- readout characteristics;
- conversion characteristics;
- dark response;
- temperature dependence;
- calibration parameters;
- operating range.

These are properties or quantities associated with sensor instances and are not intrinsic to the class definition.

## Calibration and Measurement Context

A sensor can provide information used in measurement, but sensor class membership does not establish calibration, traceability, accuracy, uncertainty, or measurement suitability.

Claims about sensor performance should identify the relevant configuration, conditions, measurement method, and evidence.

## Trust and Validation

Appropriate evidence may include:

- manufacturer documentation;
- standardized characterization;
- calibration records;
- laboratory measurements;
- independent testing;
- controlled experimental data.

A sensor model name alone is insufficient evidence for a numerical performance claim.

## Lifecycle

`Design → Manufacture → Integration → Characterization → Calibration / Verification → Deployment → Operation → Maintenance → Retirement`

## Relations

A sensor may:

- be integrated into a camera;
- receive optical radiation;
- detect an input;
- produce a signal;
- participate in a measuring system;
- be characterized by quantities and properties;
- require calibration;
- operate under defined conditions;
- contribute to a representation.

## Machine and AI Interpretation

A machine should interpret **Sensor** as a sensing entity. It should not infer a specific sensing mechanism, spectral range, calibration status, accuracy, noise level, or application without explicit evidence.

## Retrieval Anchors

Primary terms: `sensor`, `sensing element`, `sensing subsystem`.

Related terms: `image sensor`, `detector`, `photodetector`, `imaging sensor`, `sensor array`.

## Semantic Boundary

This class establishes **what a sensor is as a sensing entity**. It does not define sensor-specific performance values, calibration procedures, measurement results, signals, operating conditions, camera identity, or manufacturer claims.
