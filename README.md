# Quantum-Teleportation-Noise-ML
Predicting quantum teleportation fidelity under noise using classical machine learning.

---

📌 **Overview**

This project analyzes quantum teleportation in the presence of noise, combining quantum circuit simulations with classical machine learning techniques to study and classify teleportation performance.

The objective is to understand how noise impacts teleportation fidelity, predict the fidelity of the teleported state, and evaluate whether classical ML models can identify patterns associated with successful and unsuccessful teleportation events.

---

🧠 **Motivation**

Quantum teleportation is a fundamental protocol in quantum information, enabling the transfer of an unknown quantum state using entanglement and classical communication.  
In realistic scenarios, however, noise severely degrades performance, particularly on NISQ-era quantum devices.

This project explores:

- The effect of noise on teleportation fidelity
- The feasibility of classifying teleportation outcomes using classical ML models
- Which features are most influential in noisy teleportation processes

---

▶️ **Reproducibility and Usage**

The project is designed to be executed in Google Colab.  

The notebook includes:

- Automatic installation of required dependencies
- Google Drive mounting for loading and saving datasets and trained models
- Explicit paths adapted for Colab environments

**Recommendations:**

1. Open `Teleportation.ipynb` in Google Colab
2. Download datasets from the `data` directory
3. Downloas trained models from the `models` directory

Due to the probabilistic nature of quantum measurements and noise simulations, re-running the full notebook may produce different numerical results.

---

⚠️ **Notes on Language**

Some variable names, comments, and outputs in the notebook remain in Spanish.  
The code was originally developed and executed in Spanish and later partially translated for readability.


Only the cells that do not affect the experimental measurements were re-executed during the translation process.
Cells whose re-execution would alter the results were intentionally left unchanged to preserve the consistency of the reported data and conclusions.
