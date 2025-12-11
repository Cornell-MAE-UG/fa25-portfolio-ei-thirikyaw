---
layout: project
title: Actuator Project
image: /assets/images/image1.jpg
---

Task:
Given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear actuator (pick from this online catalog, use max force values only), design a
frame/mechanism to lift the maximum possible weight to the highest possible height. Assume all the supports and bar/actuator are rigid.

Selected Actuator: IMA55 RN05
Force up to 35.81 kN
Stroke Length: 0.5 cm

It can't be on either edge of the rod because if you place the actuator at point O the system will have a higher height but it can't withstand as much weight. However, if you place the actuatir on the right edge, the height is limited by the actuator's length. 

![Photo of design]({{ "/assets/images/image2.jpg" | relative_url }}){: .inline-image-l}

Part 2:
For the material,I chose aluminum because it is lightweight. I used a pinned-pinned set up with a free end to model the problem. The design criteria we were given is that the max vertical deflection cannot exceed 2% of its length, which in my case would be a max defelction of 0.0224 m. The max deflection I got using this design is 0.00181 mm which is well within the acceptable range. Using the volume and density of aluminum, I found that the mass of the beam is 5.74 kg which is relatively lightweight. 


![Photo of design]({{ "/assets/images/image3.png" | relative_url }}){: .inline-image-l}
![Photo of design]({{ "/assets/images/image4.png" | relative_url }}){: .inline-image-l}
![Photo of design]({{ "/assets/images/image5.png" | relative_url }}){: .inline-image-l}