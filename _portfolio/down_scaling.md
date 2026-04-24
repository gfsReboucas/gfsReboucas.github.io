---
title: "Down-Scaled Modeling of Wind Turbine Gearboxes"
excerpt: "Case study: preserving safety factors and drivetrain dynamics across gearbox scales"
collection: portfolio
permalink: /portfolio/down_scaling
---

## Case Study: Down-Scaled Modeling of Wind Turbine Gearboxes

### Purpose
Full-scale wind turbine gearbox testing is expensive and difficult to iterate quickly.  
This work developed a structured down-scaling method to create compact gearbox models while preserving key design and dynamic characteristics required for engineering decisions.

### Approach
The workflow separates scaling targets by function and constraint, then applies parameter scaling with iterative checks:

- Structural integrity targets (gear safety factors using ISO 6336)
- Dynamic targets (resonance distribution and drivetrain response)
- Practical design constraints for manufacturability and testability

A repeatable, step-by-step process was implemented to compute scale factors, update geometry and loading, and verify behavior at each iteration.

<figure>
  <img src="{{site.url}}/images/projects/DT_comparison.png" alt="Cross-scale gearbox comparison"/>
  <figcaption>
  Wind turbine gearboxes across scales (5000 kW to 0.5 kW) with matched safety factors and comparable dynamic signatures.
  </figcaption>
</figure>

### Key Results
- Reproduced safety factors and resonance trends with deviations around 5% across evaluated scales
- Reduced dependence on full-scale test infrastructure for early validation work
- Established a reusable method for scaling multi-stage gearbox concepts

### Engineering Value
- Enables faster concept screening for drivetrain architectures
- Supports lower-cost validation planning and risk reduction
- Improves confidence when extrapolating scaled-test results to larger systems

### Implementation
- Safety factor evaluation in KISSsoft (ISO 6336)
- Scaling and optimization logic in MATLAB
- Automated data exchange between MATLAB and KISSsoft via COM interface
- Modular object-oriented structure to support reuse across cases

### Tools
MATLAB · KISSsoft · Simpack (context models) · COM automation

### References
[**Rebouças** and Nejad, 2020](/publication/A3)
