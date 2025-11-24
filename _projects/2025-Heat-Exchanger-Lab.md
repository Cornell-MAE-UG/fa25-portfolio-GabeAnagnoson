---
layout: project
title: Heat Exchanger Lab
description: Class Lab
image: /assets/images/ParallelflowSetup.png
---


As part of a class project, we selected a real-world instance of a device or system that we have learned about in our class MAE 2210: Thermodynamics, explained how it works in detail, and then discussed how its performance would change under change in design or operating conditions. 

The supplies for this lab are:
• one heat exchanger
• two water pumps
• 4 water buckets
• ice
• water
• styrofoam for insulation
• an immersion heater
• one thermocouple
• four thermometers
• food dye

The four ports of the heat exchanger are labeled – 1 flows to 2 (and visa versa), and 3 flows to 4 (and visa versa). We used the bucket with the attached immersion heater as the hot water source and placed a pump inside. We used the bucket with the Styrofoam insulation as the cold water source and placed a pump inside. We set and measured the temperature of these two reservoirs. We started with these reservoirs completely full to maximize our run time. We directed the tubes from the two reservoir ports into the two empty buckets. We set up thermometers in each of the reservoirs and on the surface of the heat exchanger. We turned on the power to the pumps (shown to the right) using the power strip.
![Photo of solution]({{ "/assets/images/ParallelflowSetup.png" | relative_url }}){: .inline-image-l}
![Photo of Exchanger]({{ "/assets/images/Exchanger.png" | relative_url }}){: .inline-image-l}
![Photo of Cross Section 1]({{ "/assets/images/CrossSection1.png" | relative_url }}){: .inline-image-l}
![Photo of Cross Section 2]({{ "/assets/images/CrossSection2.png" | relative_url }}){: .inline-image-l}

To consider differences in design, we observed the effect of operation of the exchanger in parallel flow vs counter flow.

Parallel: We found the initial temperature of the water in the cold reservoir to be 6.0 degrees Celsius and the warm reservoir to be 40.0 degrees Celsius. During the process the temperature of the exchanger was at 20.0 degrees. The temperature of the water from the cold reservoir after going through the exchanger was 20.5 degrees and the water from the warm reservoir was 23.8 degrees.

Counter-flow: We found the initial temperature of the water in the cold reservoir to be 5.0 degrees Celsius and the warm reservoir to be 40.0 degrees Celsius. The initial temperature of the exchanger was 20.8 degrees Celsius. During the process the exchanger was at 18.0 degrees. The temperature of the water from the cold reservoir after going through the exchanger was 25.7 degrees and the water from the warm reservoir was 18.8 degrees.

![Photo of Parallel Flow]({{ "/assets/images/ParallelflowSetup.png" | relative_url }}){: .inline-image-l}

![Photo of Counter Flow]({{ "/assets/images/CounterflowSetup.png" | relative_url }}){: .inline-image-l}

We analyzed the solution to steady state energy, entropy, and mass flow below. Our assumptions include a steady state system, water as an incompressible substance, equivalent flow rates from the pumps. Negligble work input to the system. Negligible potential and kinetic energy changes for the system. And that the Temperature of the exchanger we observed during operation was uniform across the boundary. Our values are as shown in terms of the unidentified mass flow rate.
![Photo of Work]({{ "/assets/images/HeatExchangerWork.jpg" | relative_url }}){: .inline-image-l}

We could have made an assumption for the mass flow rate, however each question was in terms of it, so it was easy enough to compare them assuming that its effect on all of the values would be the same.

As can be seen the counter flow transfers heat better than the parallel flow, this is because counter flows have more opportunity to transfer heat with different water as what is transfering heat between the flows is always changing. Whereas, parallel flows are always transfering with the same water as they move together, so have less opportunity to transfer heat. It also appears from this that our counter flow setup violates the 2nd law of thermodynamics, leaving the outflow of the cold resevoir warmer than the outflow of the warm resevoir. However, this can be explained by a non adiabatic system, as entropy through heat enters from the surroundings as well as being generated, and as can be seen the generation of each flow is roughly the same, and non-negative, indicating that the 2nd law is kept intact. On the other hand the heat lost in parallel is far larger than that in counter flow, which we believe is because the counter flow more efficiently transfers its heat between the flows and thus less opportunity for it to be lost to the surroundings.