# Automatic Control Project

## Overview
The project entails a linear cart moving along a V-slot aluminum rod. This cart is linked to a motor, which rotates via a belt mechanism. Additionally, the motor is outfitted with an encoder to monitor its movement.

## Simulation and Modeling
We created a simulation using **MATLAB Simulink** to replicate real-world conditions accurately. This involved:
- Calculating parameters
- Establishing a mathematical model
- Conducting parameter estimations to ensure the simulation's fidelity to the actual system

## System Identification
Our primary goal was to align the simulation's behavior with real-world scenarios. This required accurately estimating various factors influencing the cart's speed, such as different types of friction.

Key steps included:
- Integrating input signals (PWM)
- Measuring the cart's output velocity
- Utilizing **Simulink/Simscape** for system modeling and simulation
- Employing analytical tools and MATLAB Simulink's **Parameter Estimation** feature to determine precise system parameters

## PID Controller Implementation
We implemented a **PID controller** to precisely control the linear distance traveled by the cart, ensuring it accurately reached specified points. Further improvements involved:
- Controlling the cart's velocity to reach points at maximum or user-defined speeds
- Eliminating steady-state errors and overshoots

## Validation and Testing
Thorough testing, including **load testing** and **graphical analysis**, confirmed the correctness and robustness of our implemented model. The final system demonstrated high accuracy and stability in both position and velocity control.

---
This project required both **technical proficiency** and **critical evaluation of simulation expertise**, enabling us to compare responses of physical and simulated systems under different input signals. The results successfully validated our approach, ensuring optimal control performance.

