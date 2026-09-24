# Parametric-Sensitivity-source-code
# Nanofluid Flow and Heat/Mass Transfer – MATLAB BVP4C

## Overview

This repository contains MATLAB code for the numerical investigation of coupled nanofluid flow, heat transfer, and mass transfer using the **BVP4C** method.

The governing equations are transformed into a system of **12 first-order nonlinear ODEs** and solved as a boundary-value problem.

## Numerical Method

* **Software:** MATLAB
* **Solver:** BVP4C
* **Absolute tolerance:** `1e-6`
* **Relative tolerance:** `1e-6`
* **Parameter studied:** Thermal radiation parameter (`Rd`)

## Main File

```text
Paper3.m
```

The code calculates:

* Velocity profiles: `f'(η)` and `g'(η)`
* Temperature profile: `θ(η)`
* Nanoparticle concentration: `φ(η)`
* Solute concentration: `χ(η)`
* Skin-friction coefficient: `Cf`
* Nusselt number: `Nu`
* Sherwood number: `Sh`
* Nanoparticle mass transfer rate: `Nn`

## How to Run

Open MATLAB, place `Paper3.m` in the working directory, and run:

```matlab
Paper3
```

The code automatically solves the BVP for the prescribed `Rd` values and generates the corresponding profiles.

## Purpose

The code is provided for **academic research, numerical analysis, and reproducibility** of the associated nanofluid flow and heat/mass transfer study.
