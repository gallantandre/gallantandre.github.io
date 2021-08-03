---
title: Humanoid Robot Control
lang: en
content_type: project
---

![Tidom]({{ "assets/images/tidom-large.jpg" | relative_url }})

Now this was a fun project! Before starting my PhD, I worked as a researcher in France. The project involved working on the locomotion of a humanoid robot (not The Terminator). This robot (Tidom) with a total of 12 joints in both of its legs is about the size of a four year old child.

My work was to build the control algorithm from the ground up to control all 12 motors synchronously to allow other researchers to implement their experiments on the robot. To do this, I designed a C program on a PLC to communicate with and command all the microcontrollers in each joint using CANopen communication. CANopen is a communication standard that is built upon CAN, and since the PLC we used only had CAN libraries, I built my own implementation of CANopen to be able to speak with the joint controllers.

## Expertise developed
- Real-time control
- C/C++
- PLC programming
- CAN / CANopen communication protocols
- Motor control and tuning
