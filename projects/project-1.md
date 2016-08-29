---
layout: project
type: project
image: images/AKMicromouse.jpg
title: Micromouse
permalink: projects/micromouse
date: 2015
labels:
  - Robotics
  - PIC
  - Embedded C
  - 
summary: Software lead for a team that developed a robot which successfully solved a 16 x 16 maze.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
</div>

The goal of the Micromouse project is to create an autonomous robot that can solve a 16 x 16 maze structure in the least amount of time. The robot may not have any sort of remote control functionality and the cost of the robot is limited to $500.

As the software lead for the project, I was primarily responsible for programming the robot's functionalities. There were three main modules involved in this: the sensing module, the motor stepping module and the tracking module. To implement the sensing module, we used low-cost and readily-available infrared sensors. I used an analog-to-digital conversion (ADC) and calibration curve to get accurate distance readings from the IR sensors. To implement the motor stepping module, I used interrupts to control the stepping rate of each of our two stepper motors. Lastly, to implement the tracking module, I used distance readings from the sensing module and the motor-stepping module to control the robot's movements via a K-controller. Our team successfully implemented a right wall-hugger which was able to navigate to the center of the maze. 

For more information on this international competition sponsored by IEEE, please visit the  [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



