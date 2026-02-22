# BB84-Simulation

# 🛡️ Interactive BB84 Quantum Key Distribution (QKD) Simulation

An interactive Python simulation of the **BB84 Protocol**, the world's first quantum cryptography scheme. Built using **IBM Qiskit**, this project allows users to manually participate in the key exchange process as Alice, Bob, or even an eavesdropper (Eve).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PJPxwaIwWlRUHg-Ny-mghKmi5UGeXubx?usp=sharing)

---

## 🚀 Overview
The BB84 protocol uses the principles of quantum mechanics (superposition and the observer effect) to secure a communication channel. This simulation is unique because it is **interactive**—the user provides the inputs for bits and bases to see exactly how the quantum state changes.

### 🌟 Key Features
* **Manual Input**: You control Alice's bits, Alice's bases, and Bob's bases.
* **Eavesdropping Simulation**: Input Eve's bases to see how her measurements disturb the qubits and introduce errors.
* **Real Quantum Circuits**: Uses Qiskit's `AerSimulator` to simulate real-world quantum measurement behaviors.
* **Sifting Logic**: Automatically calculates the final shared key based on matching bases.

---

## 🛠️ How to Run the Project

### Option 1: Run in Google Colab (Recommended)
Click the badge at the top or [Click Here](https://colab.research.google.com/drive/1PJPxwaIwWlRUHg-Ny-mghKmi5UGeXubx?usp=sharing) to run the code instantly in your browser without installing anything.

### Option 2: Run Locally
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/luckyrajyemul-035/bb84-simulation.git](https://github.com/luckyrajyemul-035/bb84-simulation.git)
   cd bb84-simulation
