# Quantum Circuit Simulator & Visualization

## Overview
This project demonstrates fundamental concepts of quantum computing by building and simulating
quantum circuits using Qiskit. The focus is on understanding qubits, quantum gates, superposition,
entanglement, and probabilistic measurement outcomes through hands-on experimentation and visualization.

All simulations are executed on a quantum simulator backend and analyzed using measurement histograms.

---

## Objectives
- Simulate basic quantum states and measurements
- Apply common quantum gates and observe their effects
- Demonstrate superposition and entanglement
- Visualize probabilistic outcomes of quantum measurements

---

## Concepts Covered
- Qubits and computational basis states
- Superposition using the Hadamard (H) gate
- Quantum gates: X (NOT), Z (Phase Flip)
- Multi-qubit systems and entanglement
- Measurement and probabilistic behavior of quantum systems

---

## Implementation Details

### 1. Superposition
A Hadamard gate is applied to a single qubit initially in the |0⟩ state to create a superposition.
Measurement results show approximately equal probabilities for |0⟩ and |1⟩.

### 2. Quantum Gates
- **X Gate**: Demonstrates state inversion from |0⟩ to |1⟩
- **Z Gate**: Applies a phase flip that becomes observable after a basis transformation

### 3. Entanglement
A two-qubit circuit is constructed using a Hadamard gate followed by a CNOT gate.
Measurement results show correlated outcomes, demonstrating quantum entanglement.

---

## Tools & Technologies
- Python
- Qiskit
- Qiskit Aer Simulator
- Matplotlib

---

## Results
Measurement outcomes are visualized using histograms, clearly illustrating:
- Probabilistic outcomes of superposed states
- Deterministic behavior of certain quantum gates
- Correlated measurements in entangled states

These results highlight fundamental differences between classical and quantum computation.

---

## Learning Outcomes
- Gained hands-on experience with quantum circuit construction and simulation
- Understood how quantum gates manipulate qubit states and phases
- Learned the role of transpilation in executing quantum circuits on simulators
- Built a strong foundation for advanced quantum algorithms and quantum machine learning

---

## Future Work
- Implementation of Grover’s search algorithm
- Quantum random number generation
- Variational quantum classifiers and hybrid quantum-classical models

---

## References
- IBM Qiskit Documentation
- Quantum Computation and Quantum Information by Nielsen & Chuang