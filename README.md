# Quadcopter-model-and-control
Quadcopter model and control 

In this research, we examined the mathematical modeling and control of quadcopters. The NewtonEuler and Euler-Lagrange equations were employed to derive the differential equations for quadcopter dynamics, which were validated through Matlab simulations. We initially used a PD controller to stabilize the quadcopter's attitude and developed a heuristic technique to manage its trajectory.
We linearized the PID model to obtain the system matrices (A, B, C) for implementing an LQR controller. The LQR controller provided optimal control for the complex system, yielding better performance than the PD controller. Additionally, we introduced noise into the system to test 
robustness. The LQR controller demonstrated superior response to noise compared to the PD controller, maintaining stability and accurate trajectory tracking.
