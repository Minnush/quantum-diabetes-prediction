# Hybrid Quantum-Classical Neural Network for Diabetes Prediction

**Project Report** | Real Execution on IBM Quantum Hardware

## Overview
Developed a **hybrid quantum-classical neural network (QNN)** for binary diabetes prediction using the **Pima Indians Diabetes Dataset**.

- **Quantum part**: Angle encoding on **8 qubits** executed on IBM’s real **156-qubit ibm_fez** processor (via PennyLane + Qiskit)
- **Classical part**: PyTorch MLP for post-processing
- **~100+ real quantum jobs** submitted to IBM Quantum Workloads (tagged "Diabetes1")

## Key Results
| Model                      | Accuracy | Notes                          |
|----------------------------|----------|--------------------------------|
| Hybrid Quantum Model       | **72%**  | Limited by hardware noise      |
| Classical Baseline         | **78%**  | Pure PyTorch MLP               |

**Proof-of-concept** demonstrating end-to-end hybrid QML on NISQ hardware.

## Technologies
- **Quantum**: PennyLane, Qiskit, IBM Quantum (ibm_fez)
- **Classical**: PyTorch, scikit-learn
- **Dataset**: Pima Indians Diabetes (768 samples, 8 features)

## Full Project Report
📄 **[Download Full 16-Page Report (PDF)](HYBRID%20QUANTUM%20COMPUTING%20NEURAL%20NETWORK%20ON%20PREDICTING%20DIABETES%20USING%20PIMA%20INDIAN%20DIABETES%20DATASET.pdf)**  
Contains complete code, step-by-step execution, IBM Workloads screenshots, confusion matrices, and final outputs.

## How to Run
1. Open the PDF → copy code blocks into Google Colab
2. Install: `!pip install pennylane pennylane-qiskit qiskit-ibm-runtime torch`
3. Use your own IBM Quantum token for real hardware execution

## Learnings
- Real quantum hardware execution on ibm_fez
- Handling noise in NISQ devices
- Hybrid QML pipeline for healthcare

---

**Authors**: Minnushaa A. A (23MIS1035)
**Date**: April 2026  
**Made for academic project**
