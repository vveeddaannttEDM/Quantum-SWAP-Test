# Quantum SWAP Test

This repository implements the **Quantum SWAP Test** — a fundamental quantum algorithm used to determine the similarity (or inner product) between two quantum states. The SWAP test has applications in quantum machine learning, quantum fingerprinting, and entanglement detection.

---

## 🧠 What is the SWAP Test?

The SWAP Test is a quantum algorithm that estimates the overlap between two quantum states, |ψ⟩ and |ϕ⟩. It uses:
- A control qubit
- Two quantum registers to hold the input states
- Hadamard gates and a controlled-SWAP operation

It outputs the **fidelity** or **inner product squared** between the two states.

---

## 🛠 Implementation Details

- Built using **Qiskit** (IBM Quantum)
- Simulated on the **Qiskit Aer simulator**
- Can be extended to N-qubit state comparisons
- Includes examples with both identical and orthogonal states



