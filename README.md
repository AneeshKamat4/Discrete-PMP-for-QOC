# Discrete-PMP-for-QOC
A discrete-time variant of the Pontryagin Maximum Principle tailored for experimental demonstrations of quantum optimal control while adhering strictly to state, action, and frequency constraints.

This report describes the theoretical framework behind the discrete-time Pontryagin Maximum Principle and outlines a template for its potential application to qubit control. In experimental systems, qubit control is achieved by sending pulses that are discretized in time, a constraint rooted in the DAC-based signal generation equipment. Quasi-continuous assumptions underline every attempt at optimal control of qubits due to the finite rise time associated with DACs, and the desire for smooth, bandwidth-limited control pulses. Incorporating this discrete nature of control right at the synthesis stage is desirable for accurate system modelling and subsequent optimization. Often, there are particular frequencies which one would like to avoid to ensure precise control. 

The discrete-time Pontryagin Maximum Principle provides first-order conditions for optimality, naturally incorporates the
discrete nature of the pulses, and is capable of handling experimental constraints even in the frequency domain. A simple problem formulation is presented, and various experimental constraints are considered on the dynamics of the system, the control pulses actuated and the bandwidth of operation. Shooting techniques to solve the resulting two-point boundary value
problem are discussed and some techniques for practical implementation are ideated.
