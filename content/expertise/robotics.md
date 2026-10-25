---
title: Robotics
weight: 3
image: images/Robotics.svg
---
Robotics is where everything in mechatronics has to work at the same time: mechanics, electronics, control and software.

## Cable-driven aerial positioning system (PI7)

<img class="feature-image" src="/images/Robotics.svg" alt="Illustration of the cable-driven positioning system: two motor spools on towers hold cables that suspend a payload">

For the Integrated Project 7 at USP (2025), our team of eight built a **spidercam-style cable robot**. Two DC motors at the top of a frame wind and unwind cable spools; by changing the two cable lengths, the system moves a suspended payload to any point of a vertical plane.

The project covered all four pillars of mechatronics in one student-built system:

- **Mechanics:** a structural frame and spool mechanism, designed and manufactured by the team.
- **Electronics:** custom motor-driver PCBs (designed in DipTrace) around the L298N dual H-bridge, with both bridges in parallel for higher current, a 7805 regulator for the logic supply and a 26-way ribbon cable to the controller boards.
- **Control:** the motor was identified from step-response experiments as a first-order plant, and a **PID position controller** was tuned first in MATLAB and then experimentally on the final structure. It runs on a PIC16F886 microcontroller per motor, reading an incremental encoder (1920 pulses per turn) and driving the motor by PWM.
- **Computing:** a Raspberry Pi Pico W receives commands from a PC (USB or Wi-Fi) and sends setpoints to both motor controllers over serial.

The result was a stable, responsive system that received commands, drove the motors and measured position in real time. The main limitation, a mismatch between the two gearboxes, showed how hardware details set the limits of pure feedback control.

### Related coursework
Advanced Control, Robot Motion Planning, Optimal Control and Decision Making, Methods in Neuromechanics, Modeling and Reduction of Complex Systems (TUM) · Control I, Dynamic Systems I & II, Mechanisms for Automation, Microprocessors in Automation and Robotics, Embedded Systems, Actuators and Drives (USP).
