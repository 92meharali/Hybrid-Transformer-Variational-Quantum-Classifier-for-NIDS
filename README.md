# Hybrid Transformer-Variational Quantum Classifier for NIDS

## Overview
This repository contains a comprehensive implementation of a **Hybrid Transformer-Variational Quantum Classifier (VQC)** for Network Intrusion Detection Systems (NIDS). The model is designed to leverage both classical deep learning and quantum machine learning to detect network anomalies efficiently, evaluated on the **NSL-KDD** dataset.

## Features
- **Data Acquisition & Preprocessing:** Automated loading, exploratory data analysis (EDA), and preprocessing of the NSL-KDD dataset.
- **Classical Transformer Encoder:** An improved classical Transformer model incorporating positional encoding and non-linear dimensionality reduction to prevent representational collapse.
- **Variational Quantum Classifier (VQC):** A parameterized quantum circuit implemented using PennyLane to classify network traffic.
- **Hybrid Architecture:** Combining the Transformer feature extractor with the VQC for a full end-to-end training pipeline.

## Technologies Used
- PyTorch (Deep Learning & Auto-differentiation)
- PennyLane (Quantum Machine Learning)
- Scikit-Learn (Metrics & Preprocessing)
- Matplotlib & Seaborn (Data Visualization)

## How to Use
1. Clone the repository.
2. Install the required dependencies: `pip install torch pennylane scikit-learn matplotlib`.
3. Open and run the `Hybrid_Transformer_VQC_NIDS.ipynb` notebook.
