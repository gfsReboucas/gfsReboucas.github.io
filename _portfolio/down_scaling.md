---
title: "Down-Scaled Modeling of Wind Turbine Gearboxes"
excerpt: "Reduced-order gearbox models preserving safety factors and dynamic behavior across scales"
collection: portfolio
permalink: /portfolio/down_scaling
---

## Down-Scaled Modeling of Wind Turbine Gearboxes

### Purpose
Testing full-scale wind turbine gearboxes is expensive and logistically challenging.  
This project focused on developing a methodology to create down-scaled gearbox models that preserve both structural integrity and dynamic behavior, enabling more efficient testing and analysis.

### Approach
I developed a structured scaling methodology for multi-stage wind turbine gearboxes, ensuring that key characteristics are maintained across different power levels:

- Gear safety factors (based on ISO 6336)  
- Resonance and frequency distribution  
- Structural and dynamic consistency  

The scaling process separates parameters based on their influence on:
- Mechanical integrity  
- Dynamic response  

A step-by-step procedure was implemented to compute appropriate scaling factors and allow fine-tuning of the resulting designs.

<figure>
  <img src="{{site.url}}/images/projects/DT_comparison.png" alt="Cross-scale gearbox comparison"/>
  <figcaption>
  Wind turbine gearboxes across scales (5000 kW to 0.5 kW) with preserved safety factors and dynamic characteristics.
  </figcaption>
</figure>

### Key Results
- Achieved gearbox models with **similar safety factors and resonance distribution** (within ~5% deviation) across multiple scales  
- Enabled realistic representation of large-scale drivetrain behavior using compact test setups  
- Provided a systematic framework for scaling complex multi-stage gear systems  

### Engineering Value
This work enables:
- Cost-effective experimental testing of wind turbine drivetrains  
- Faster iteration in gearbox design and validation  
- Improved understanding of dynamic behavior without full-scale infrastructure  

### Implementation
- Gear safety factors evaluated using KISSsoft (ISO 6336)  
- Scaling and optimization implemented in MATLAB  
- Automated workflow using COM interface between MATLAB and KISSsoft  
- Object-oriented structure for modular and reusable modeling  

### Tools
MATLAB · KISSsoft · Simpack (context) · COM interface integration

### References
[**Rebouças** and Nejad, 2020)](/publication/A3)