---
layout: project
title: Statics Design Problem
description: Design Problem for Statics and Mechanics of Solids Class
image: /assets/images/final-statics-design.jpeg
---

For a class, we were asked to design a mechanism to lift a load of maximum weight, the maximum height: We were given a 2D design space 150cm long and 50cm tall, a rigid bar of a fixed length, 3 pin supports, two of which needed to be mounted on the ground and a linear
actuator of our choice from a catalog, using its maximum force values and assuming all the supports and bar/actuator are rigid for the first step.

![Photo of work]({{ "/assets/images/statics-geometry-design.jpeg" | relative_url }}){: .inline-image-l}

My solution was to use the bar to rotate the load at the from whatever the lowest angle between the bar and actuator I could find was, to pushing the bar to vertical. My solution to maximizing the change in height and the weight was to position the actuator 90 degrees with the bar at the lowest and stipulate it must be at its fully extended length at the top. This gave a system of equations which solving for gave me the all the dimensions of the system.

To find the actual dimensions I needed to know what actuator I was using, so from the catalog I reviewed all of the dimensions of them and found the 3 with the highest values for length change and max force. It is important to note that there were actuators with higher forces however their lengths did not fit in my design space so they were impractical. As is shown it wasn't very close as to which actuator was better, as the RSA64 both pushed a higher load, and for further than the next two closest so I went with it.

This gave me a bar length of 153.6 cm, an initial angle of 12.415 degrees with the ground, and an actuator with a maximum force of 58kN over a 152.4 cm length change.

![Photo of work]({{ "/assets/images/statics-design-load.jpeg" | relative_url }}){: .inline-image-r}

The next problem was to solve for the maximum load I could lift. This was simply a matter of crawing a free body diagram and solving for the moment about the pivot pin. If the force of the actuator exceeds the moment caused by the load it will move, any vertical force from the load not supported by the actuator will simply distribute to the pin. I just set the moments equal and solved given the max force of our actuator and dimensions of the bar, giving me a maximum load to be lifted of 48.66 kN.

To be sure this is the maximum load I checked the endconditions of the bar and at the top, all of the load will be supported by the pin, while the most load is pushed by the actuator at the bottom. Thus, I concluded that once the actuator could move the load at the bottom it would only get easier for it to move the load as it reached the top, because the distance from the load to the pin would decrease, and the moment would follow.

![Photo of work]({{ "/assets/images/statics-design-deflection.jpeg" | relative_url }}){: .inline-image-l}

Step two of the problem was to stop treating the bar as rigid, and solve for the maximum deflection. I found this by first translating the axis to treat the bar as horizontal at the bottom, as this is where the moment will be highest so we will have the highest deflection. I then solved the relations between the forces and finally solved the double integral moment equations to find the deflection. There was three boundary conditions, for the pin, and the continuity at the spot where the actuator connects, this meant two of the constants were still unsolvable. So, I approximated the curvature at the pin to be zero, in other words considering the pin to be a fixed support, this made the most sense to me, as any condition at the actuator would not give me an extra equation and we were solving for deflection at the opposite end.

Solving it out I got an equation which was solvable with only a value for young's modulus of our material, and the area moment of inertia of our cross sectional design.

![Photo of work]({{ "/assets/images/statics-design-cross-section.jpeg" | relative_url }}){: .inline-image-r}

The final step was to design the beam such that it had a vertical deflection of no more than 2% of the length. I plugged this value into the deflection equation from before, giving me a minimum value for the area moment of inertia of our beam. This was far smaller than any of the I beam values so I used a hollowed out cylinder, which has theoretically the best optimization for any area to moment of inertia, so I was simply optimizing the equations for the two. However, if you are to continue to increase the outer radius the inner radius will follow getting closer and closer, decreasing the thickness of your material, until it would be theoretically infinitely thin.

To reconcile this, I simply picked a value for the outer radius which gave a reasonable thickness (about 1 cm) and solved for that. I was instructed to make it as material optimizing as possible, but a super thin material would also fail, so I compromised with a cross section that matched the minimum I value, but didn't make the steel unreasonably thin. This ended up being a hollow steel cylinder with an outer radius of 4cm and an inner radius of 3.37cm.

![Photo of work]({{ "/assets/images/statics-design-final.jpeg" | relative_url }}){: .inline-image-l}

In conclusion, this is my final design: A 153.59 cm long bar, made of structural steel in a hollowed cylinder with inner radius 3.37 cm, outer radius 4 cm. Pinned to the ground at the left, at an angle of 12.415 degrees, and 125.83 cm from the left of the beam, pinned at a right angle to an RSA64 Linear actuator, with a maximum load of 48.66kN at the free end of the bar.

The bar can be pushed to vertical, a total height change for the load of 120.57 cm. The maximum deflection of the bar, is when it is at the bottom, and it is at the load, moving the bar 3.07 cm from its neutral position.