# Wind-Tunnel-Project


A small-scale experimental wind tunnel designed and built to investigate **aerodynamics, airflow, aerodynamic forces, and experimental data analysis**.

The project combines mechanical design, electronics, sensors, programming, physics, and data analysis to create a functional experimental platform for testing aerodynamic models.

> **Status:** In Development
> **Started:** August 2026

---

## Project Objective

The goal of this project is to design and build a functional wind tunnel capable of producing controlled airflow and collecting experimental measurements from models placed inside the test section and to test the drag and lift forces.


Some of the questions I hope to investigate include:

* How does drag change with air velocity?
* How repeatable are the measurements?
* Can experimental data be used to estimate the coefficient of drag?
* What are the largest sources of experimental uncertainty?
* How closely do experimental results agree with theoretical predictions?
* What is the relation between lift force and angle of attack?

---

## Scientific Background

One of the fundamental equations used to describe aerodynamic drag is:

\(F_D = \frac{1}{2}\rho v^2 C_D A\)

Where:

* $F_D$ = drag force
* $\rho$ = air density
* $v$ = air velocity
* $C_D$ = coefficient of drag
* $A$ = reference area

The project will also consider the Reynolds number:

\(Re = \frac{\rho v L}{\mu}\)

Where:

* $Re$ = Reynolds number
* $\rho$ = air density
* $v$ = flow velocity
* $L$ = characteristic length
* $\mu$ = dynamic viscosity

These relationships will help compare the experimental measurements with theoretical expectations.

---

## Wind Tunnel Design

The planned wind tunnel consists of several main sections:

1. **Airflow generation** — produces the airflow.
2. **Flow conditioning** — helps improve the uniformity of the airflow.
3. **Test section** — contains the model being tested.
4. **Measurement system** — sensors measure airflow and aerodynamic forces.
5. **Diffuser/exhaust** — guides the air out of the system.

### Current Design

> Design and construction are currently in progress.

Design drawings, CAD models, and photographs will be added as the project develops.

---

## Electronics & Sensors

The measurement system is being designed to collect experimental data electronically.

Planned measurements include:

* **Lift Force**
* **Drag Force**
* **Dynamic & Differential Pressure**
* **Freestream Airspeed**
* **Ambient Air Temperature**
* **Ambient Barometric Pressure**
* **Relative Humidity**
* **Air Density**
* **Coefficient of Lift & Drag**

The general measurement pipeline will be:

**Sensors → Microcontroller → Computer → Python → Data → Analysis**

The exact sensors and electronics will be documented as the system is finalized.

---

## Software

Python will be used to process and analyze the experimental measurements.

Planned software functionality includes:

* Sensor data logging
* CSV data storage
* Data cleaning
* Statistical analysis
* Graph generation
* Experimental/theoretical comparison
* Calculation of aerodynamic quantities

### Planned Python Tools

* Python
* NumPy
* Matplotlib
* Pandas
* SciPy *(if required)*

---

## Repository Structure

```text
wind-tunnel/
│
├── README.md
├── BOM.csv
│
├── CAD/
│   └── design-files
│
├── electronics/
│   ├── schematics/
│   └── wiring/
│
├── firmware/
│   └── microcontroller-code
│
├── python/
│   ├── data-logging/
│   └── analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── results/
│   └── graphs/
│
├── documentation/
│   ├── design-notes/
│   └── experiment-notes/
│
└── images/
    └── build-progress/
```

The structure will evolve as the project becomes more complex.

---

## Experimental Data

Raw experimental measurements will be preserved separately from processed data.

This will allow the analysis to be reproduced and make it possible to compare different processing methods.

Where appropriate, each dataset will include information such as:

* Date
* Model tested
* Air velocity
* Temperature
* Pressure
* Sensor configuration
* Number of measurements
* Calibration information
* Experimental conditions

---

## Project Documentation

Photos and videos will be used to document major stages of construction and testing.

Documentation will include:

* Initial designs
* Failures
* Construction
* Electronics
* Sensor installation
* Calibration
* First successful measurements
* Experimental testing
* Final system

---

## Future Improvements

Potential future improvements.

---

## Learning Goals

Through this project, I aim to develop practical experience in:

* Aerodynamics
* Fluid mechanics
* Experimental physics
* Mechanical design
* Electronics
* Sensors and instrumentation
* Python programming
* Data analysis
* Experimental uncertainty
* Scientific research
* Engineering documentation

---

## About the Project

This project is part of my independent exploration of **aerospace engineering, physics, programming, and experimental research**.

---

## License

This project is primarily intended for educational and research purposes.
