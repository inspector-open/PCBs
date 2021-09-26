# PCBs
Repository for schematics and PCBs

# Aim

The main aim of this project is to explore the field of remote-control Internet access PCB inspection tools. The main problem of this area that, to the best of our knowledge, there is no such device that would use Internet or any other protocol to share images of the inspected PCB and to probe different points of circuitry at the same time. We intend to base our design on the existing base of open-source products, such as microscopes, mechatronic tools and instruments and their software integration. 

# Idea

The idea for now is to create a main platform/module which should have a microscope, set of LEDs, ability to either move camera of the microscope or move PCB relative to the microscope, to have at the very least two probes that can be placed at an arbitrary point of the PCB. The ideal result is to have such a system that would be able to inspect an arbitrary number of PCBs without external manipulations. In this case, it will allow an engineer, who remotely inspects a PCB, to go through all the boards without the need to call for assistance of the person on the other side of the screen. It is extremely useful in a scenario when a project collaboration features decentralised team that works strictly remotely.

# Plan

1) Make a chassis where a microscope and PCB can be placed and moved one in relation to another
2) Add probes
3) Add a method or mechanism that will place PCBs onto the inspection pad and take them away from it.


A huge obstacle for PCB inspection in large and small quantities is their power management. As a result, we may have to design a certain method that will ensure that when a PCB is placed onto the inspection pad, it will be fed with the respective voltage and sufficient current.
