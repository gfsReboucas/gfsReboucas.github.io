---
title: "Down-scaled modelling of Wind Turbine Gearboxes"
excerpt: ""
collection: portfolio
permalink: /portfolio/down_scaling

---

<p align="justify">
Despite the widespread use of scaled models in the wind industry and engineering in general, gearboxes are tested at full scale in specialized facilities, leading to expensive and restrictive tests. These problems can be mitigated with appropriate down-scaled gearboxes as the ones shown in~\cref{fig:DT_comparison}. The 4 gearboxes at the top have similar safety factors and resonance distribution (max. 5% relative deviation) as the reference gearbox at the bottom. These results were obtained with a step-by-step procedure in which the parameters to be scaled are divided according to their relation to the gearbox’s integrity and dynamic behavior. The method, which is described in~\cite{Reboucas2020}, allows for fine-tuning once an overall scaling has been done.
</p>
![DT_comp](/images/projects/DT_comparison.png)
*Schematics of WT gearboxes with different rated power (5000 kW to 0.5 kW) but similar safety factors and resonance distribution. \colorbox{red}{red: sun/pinion gear;} \colorbox{blue}{blue: planet/wheel gear;} \colorbox{ring}{green: ring gear;} \colorbox{carrier}{orange: planet carrier;} \colorbox{mshaft}{brown: main shaft;} \colorbox{shaft}{yellow: output shafts} for each gear stage.*
<p align="justify">
The effects of gear parameters on safety factors are evaluated with KISSsoft, while MATLAB’s root-finding and optimization methods are used to find appropriate scaling factors. Both software are used in a structured form, combining their main characteristics.
</p>
<p align="justify">
This project is a good opportunity to develop myself within gear calculations and software development practices. Using an object-oriented approach, I obtained a better understanding of gear safety calculation while implementing some parts of ISO 6336 standard for estimating the pitting safety factors of planetary and parallel gear stages. I used KISSsoft's COM interface to control it using MATLAB. These abilities combined give me the expertise to develop robust analysis and design simulation tools for gears and other machine elements in a concise and integrated perspective.
</p>

