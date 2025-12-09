---
layout: project
title: Wind Turbine Blade Design
description: Fluids and Heat Transfer Laboratory Design Project
technologies: [Autodesk Fusion]
image: /assets/images/Blade-CAD.jpg
---

#### Project Overview

For this project in the MAE 4272 Fluids and Heat Transfer Laboratory, our team was tasked with designing the blades for a small-scale wind turbine that could efficiently generate power under realistic operating conditions. The design was constrained by strict geometric limits (maximum blade length and hub compatibility), a fixed angular velocity capped at 2000 RPM, and a wind environment modeled by a Weibull distribution. Rather than optimizing for idealized conditions, the goal was to design a blade that performed reliably at a representative wind speed, balancing aerodynamic efficiency with structural and experimental feasibility.

#### Design process

Our design process combined aerodynamic modeling with iterative decision-making. Using blade element momentum principles, we derived pitch and chord distributions along the blade radius to maintain favorable angles of attack across the span. These calculations informed the blade’s twist and taper geometry, which was implemented in CAD and refined to meet manufacturing and hub-interface constraints. Throughout the process, particular attention was paid to how design choices would translate to measurable performance during testing, ensuring the blade geometry could be meaningfully evaluated in the wind tunnel.

#### Testing & Performance Analysis

The blades were experimentally tested in a wind tunnel at three discrete wind speeds (4.7 m/s, 5.6 m/s, and 6.8 m/s) using a controlled torque brake to vary rotational speed. I contributed primarily to developing the experimental procedure and leading the post-processing and analysis of the data. For each test condition, turbine rotational rate and electrical power output were recorded and used to generate power–RPM curves, which allowed us to directly compare blade performance across operating conditions and assess how effectively the design translated increased wind speed into usable power.

Comparison of the three power curves reveals clear performance trends. At the lowest wind speed (4.7 m/s), the blade generated limited power and exhibited a rapid drop-off at higher RPMs, indicating a narrow efficient operating range near the minimum wind speed required for sustained rotation. At the intermediate wind speed (5.6 m/s), which most closely aligned with the design condition, the turbine achieved higher peak power and maintained more stable performance across a broader RPM range. At the highest wind speed (6.8 m/s), the blade produced its maximum observed power output but showed increased sensitivity at high rotational speeds, suggesting growing aerodynamic or mechanical losses. Taken together, these results confirmed the blade’s robustness at moderate wind speeds while highlighting opportunities to improve low-speed efficiency and refine high-speed performance in future design iterations.


![Shaded rendering of earlier version]({{ "/assets/images/power-1.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Shaded rendering of earlier version]({{ "/assets/images/power-2.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Shaded rendering of earlier version]({{ "/assets/images/power-3.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}
