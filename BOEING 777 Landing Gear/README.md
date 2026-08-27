# Aircraft Landing Gear — CAD & FEA Design Project

## Overview

Independent mechanical engineering project focused on the design, modelling and
structural analysis of an aircraft landing gear assembly.

The project was developed to improve practical experience in mechanical CAD,
structural mechanics, finite element analysis (FEA), material selection and
engineering design validation.

The design was inspired by a commercial aircraft main landing gear configuration,
with particular focus on the bogie beam and its load-bearing structure.

---

## Project Objectives

- Design a complete aircraft landing gear assembly
- Develop a multi-component CAD model and assembly
- Determine representative structural loading conditions
- Select suitable materials using engineering performance criteria
- Analyse critical components using FEA
- Validate simulation results against analytical calculations
- Identify areas of high stress and excessive deformation
- Redesign components to achieve a target factor of safety
- Develop engineering drawings and design documentation

---

## Design Development

The landing gear assembly was modelled in Fusion 360.

The assembly consisted of 17 individually modelled components, including:

- Bogie beam
- Wheel assemblies
- Wheel axle
- Upper and lower links
- Shock strut
- Outer cylinder
- Torque link
- Clevis mounting
- Retraction mechanism components

The assembly was developed as a complete mechanical system rather than
modelling individual components in isolation.

---

## Loading Conditions

The primary structural analysis considered representative aircraft landing
gear loading conditions.

The applied loads per wheel were:

| Loading condition | Load |
|---|---:|
| Vertical | 513 kN |
| Braking | 411 kN |
| Crosswind | 102 kN |

The loading conditions were applied to assess the structural response of the
landing gear under combined operational loads.

The bogie beam had an overall length of approximately 3450 mm, with the axle
locations distributed along the beam.

---

## Material Selection

Material selection was performed using material performance indices, considering
properties including:

- Yield strength
- Density
- Strength-to-weight performance

Titanium 6Al-4V was selected for the primary bogie beam due to its high
strength-to-weight performance and suitability for demanding aerospace
applications.

---

## Analytical Analysis

Hand calculations were performed to establish an independent reference against
which the FEA results could be assessed.

The bogie beam was initially approximated using Euler-Bernoulli beam theory.

Key calculations included:

- Bending moment
- Second moment of area
- Bending stress
- Beam deflection

For the analysed beam cross-section, the second moment of area was calculated
as approximately:

**I = 2.32 × 10⁹ mm⁴**

The analytical calculations provided an initial estimate of the structural
response before performing the finite element analysis.

---

## Finite Element Analysis

FEA was performed to investigate the structural response of the landing gear
components.

The analysis considered:

- Von Mises stress
- Total deformation
- Critical stress concentrations
- Factor of safety

The results were used to identify critical regions of the design and determine
whether the initial geometry was structurally adequate.

### FEA Validation

FEA results were compared against independent hand calculations at multiple
locations.

The comparison was used to assess the accuracy of the simulation rather than
treating the FEA output as inherently correct.

Representative validation results included:

| Parameter | FEA / Analytical Error |
|---|---:|
| Beam displacement | 12% |
| Maximum stress | ~6.6% |
| Additional validation locations | 6.91%, 3.76%, 5.86% |

The relatively small differences between the analytical and numerical results
provided confidence in the FEA model for the investigated loading condition.

---

## Design Iteration

The initial design was assessed using the calculated loading conditions and FEA.

Regions experiencing high stress were identified, including the area around the
bogie beam and trunnion connection.

The initial cylindrical geometry was subsequently redesigned to improve its
structural performance.

The redesigned geometry incorporated a more efficient structural cross-section
with material concentrated away from the neutral axis, increasing the second
moment of area without simply increasing the overall material volume.

The design process therefore followed an iterative:

**Design → Analyse → Identify Critical Areas → Redesign → Validate**

approach.

---

## Final Design

The final design was assessed against the target structural requirements.

A target factor of safety of approximately **1.5** was achieved for the
investigated loading condition.

The final design was supported by both numerical FEA results and independent
analytical calculations.

---

## Engineering Validation

A key objective of the project was to avoid relying solely on simulation
software.

The final workflow was:

1. Establish loading conditions
2. Develop analytical calculations
3. Create the CAD geometry
4. Apply loads and constraints in FEA
5. Compare FEA and analytical results
6. Identify critical regions
7. Modify the design
8. Re-run the analysis
9. Verify the final factor of safety

This provided an engineering check on the numerical model and demonstrated the
relationship between theoretical mechanics, CAD and computational analysis.

---

## Software & Tools

### CAD
- Fusion 360

### Engineering Analysis
- Finite Element Analysis (FEA)
- Euler-Bernoulli beam theory
- Mechanics of materials
- Bending stress analysis
- Deflection calculations

### Engineering Design
- Material selection
- Structural optimisation
- Design iteration
- Engineering drawings
- Mechanical assembly design

---

## Key Outcomes

- Designed a 17-component aircraft landing gear assembly
- Developed a detailed CAD model in Fusion 360
- Analysed representative vertical, braking and crosswind loading
- Applied analytical beam theory to independently estimate structural response
- Validated FEA against hand calculations
- Achieved approximately 1.5 factor of safety in the final design
- Iteratively redesigned critical geometry based on FEA results
- Developed practical experience in mechanical design and structural analysis

