# Health-Insurance-Fraud-Detection-GNN
This repository contains the implementation of my MSc thesis on fraud detection in health insurance using graph neural networks. The proposed approach models relationships between providers and insured individuals as a graph and applies GNNs to identify potentially fraudulent providers based on network structure and claim patterns.

This repository contains the implementation of my MSc thesis on fraud detection in health insurance using graph neural networks.

The proposed approach models relationships between healthcare providers and insured individuals as a graph and applies graph-based deep learning to identify potentially fraudulent providers by leveraging both structural patterns and claim-related features.

---

## 📂 Dataset

This project uses a **HEALTHCARE PROVIDER FRAUD DETECTION ANALYSIS** from Kaggle.

The dataset includes:
- Claims information
- Insured individuals
- Binary target indicating potential fraud
---

## 📌 Methodology
- Preprocess the raw dataset for graph construction.
- Construct a graph representing provider relationships based on shared insured individuals.
- Extract relevant features from claims and providers.
- Train a graph neural network model for fraud classification.

---

## ⚙️ Requirements
- Python 3.9+
- PyTorch
- PyTorch Geometric
- NumPy
- Pandas
- Scikit-learn
- NetworkX
- Matplotlib
- Seaborn
