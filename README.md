# Noisy-Quantum-Circuit-Simulation

This task addresses noise challenges in quantum computing, building functions to simulate noise, optimize gate basis, perform quantum addition, and analyze noise effects.

### 1. Noise Model

Objective: Add Pauli noise after each gate. 

Approach: Created a function to inject random Pauli operators (X, Y, Z) based on probability parameters α (for one-qubit gates) and β (for two-qubit gates).

### 2. Gate Basis Transformation

Objective: Transform a quantum circuit into a limited gate set {CX, ID, RZ, SX, X}.

Approach: Constructed a function to rewrite circuits to this gate set, supporting standard quantum hardware.

### 3. Quantum Addition with Draper Adder

Objective: Implement quantum addition using the Draper adder algorithm.

Approach: Constructed the Quantum Fourier Transform (QFT) from scratch, facilitating number addition on quantum circuits.
