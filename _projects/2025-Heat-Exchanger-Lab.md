---
layout: project
title: Heat Exchanger Lab
description: Class Lab
image: /assets/images/ParallelflowSetup.png
---


As part of a class project, we were asked to select a real-world instance of a device or system that we have learned about in MAE 2210: Thermodynamics, explained how it works in detail, and then discussed how its performance would change under change in design or operating conditions. 

We chose a heat exchanger and our suppplies were:
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

![Photo of Exchanger]({{ "/assets/images/Exchanger.png" | relative_url }}){: .inline-image-l}

The four ports of the heat exchanger are labeled – 1 and 2 flow to each other, and 3 and 4 flow to each other. We used the bucket with the attached immersion heater as the hot water source and placed a pump inside. The bucket with the Styrofoam insulation was our cold water source and we placed a pump inside. We set and recorded the temperature of these two reservoirs, starting with them completely full to maximize our run time. 

![Photo of solution]({{ "/assets/images/ParallelflowSetup.png" | relative_url }}){: .inline-image-r}

The resevior ports of our exchangers were then directed into the two empty buckets to record the final temperature after exchanging heat. Then to start the experiment we turned on the power to the pumps to begin exchanging. The full setup is shown at the right


To consider differences in design, we observed the effect of operation of the exchanger in parallel flow vs counter flow. To have parallel flow we directed inflow to ports 1 and 3, so that the hot and cold water would flow together and out through ports 2 and 4. Counter flow was flipped, with inflow sent to ports 1 and 2, so the water flows against each other and out through ports 3 and 4. Our findings for each experiment are described below.

![Photo of Parallel Flow]({{ "/assets/images/ParallelflowSetup.png" | relative_url }}){: .inline-image-l}

Parallel: We found the initial temperature of the water in the cold reservoir to be 6.0 degrees Celsius and the warm reservoir to be 40.0 degrees Celsius. During the process the temperature of the exchanger was at 20.0 degrees. The temperature of the water from the cold reservoir after going through the exchanger was 20.5 degrees and the water from the warm reservoir was 23.8 degrees.

![Photo of Counter Flow]({{ "/assets/images/CounterflowSetup.png" | relative_url }}){: .inline-image-l}

Counter-flow: We found the initial temperature of the water in the cold reservoir to be 5.0 degrees Celsius and the warm reservoir to be 40.0 degrees Celsius. The initial temperature of the exchanger was 20.8 degrees Celsius. During the process the exchanger was at 18.0 degrees. The temperature of the water from the cold reservoir after going through the exchanger was 25.7 degrees and the water from the warm reservoir was 18.8 degrees.

![Photo of Work]({{ "/assets/images/HeatExchangerWork.jpg" | relative_url }}){: .inline-image-r}

We analyzed the solution to steady state energy, entropy, and mass flow below. Our assumptions include a steady state system, water as an incompressible substance, equivalent flow rates from the pumps, negligble work input to the system. negligible potential and kinetic energy changes for the system, and that the Temperature of the exchanger we observed during operation was uniform across the boundary. Our values are as shown in terms of the unidentified mass flow rate.

We could have made an assumption for the value of mass flow rate, however each question was in terms of it, so it was easy enough to compare them assuming that it was consistent for the whole system, thus it would have the same effect on all of the values making it unimportant.

As can be seen the counter flow transfers heat better than the parallel flow, this is because counter flow has more opportunity to transfer heat with different water, as the water it exchanges with is now always changing. Whereas, parallel flows are always transfering with the same water as they move together, so are unable to transfer as much heat. It also appears from this that our counter flow setup violates the 2nd law of thermodynamics, leaving the outflow of the cold resevoir warmer than the outflow of the warm resevoir. However, this is allowed, and intuitively makes sense, because the flow from the warm resevior should be able to reach a temperature approaching that of the cold resevior if it continues to exchange heat with a constant temperature flow from the cold resevior, and vice versa. It is also explained through entropy balance, as entropy transfers through heat from the surroundings as well as being generated, and as can be seen the generation of each flow is roughly the same, and non-negative, indicating that the 2nd law is kept intact. On the other hand the heat lost in parallel is far larger than that in counter flow, which is because counter flow more efficiently transfers its heat between the flows and thu has less opportunity for it to be lost to the surroundings.

Our analysis indicates that there is similar entropy generation between the two experiments, but that counter flow is clearly better for less heat being lost to surroundings and for more heat to be transferred between the flows.