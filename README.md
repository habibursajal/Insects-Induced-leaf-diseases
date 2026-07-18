# Insects-Induced-Leaf-Diseases

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch 2.0+](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the supplementary material and source code for the research manuscript titled **"Insects-Induced Leaf Diseases Classification using Hybrid Stacking Ensemble"**, which is currently under peer review.

This project implements a high-accuracy agricultural image classification pipeline, featuring a hybrid stacking ensemble, rigorous statistical ablation studies, and comprehensive evaluation metrics.

---

## 📌 1. Overview
The goal of this research is to accurately classify leaf diseases using deep learning. To ensure computational reproducibility, we provide:
*   **Hybrid Stacking Ensemble:** Integration of top-performing CNN models.
*   **Statistical Validation:** Pairwise ablation study with **McNemar's Test** and **Bootstrap 95% Confidence Intervals**.
*   **Performance Metrics:** Macro Precision, Recall, F1-score, and Cohen's Kappa.
*   **Automated Reporting:** Pipeline to generate Q1-journal-ready LaTeX tables and high-resolution visualizations.

---

## 🔬 2. Experimental Setup & Reproducibility
We have strictly controlled the environment to ensure that our results can be replicated.

*   **Environment:** Python 3.10+, PyTorch 2.0.0+ (CUDA 11.8).
*   **Random Seed:** `42` (Fixed for all data splits and model weight initializations).
*   **Preprocessing:** Images resized to `224x224`, normalized using ImageNet mean `[0.485, 0.456, 0.406]` and std `[0.229, 0.224, 0.225]`.

---

## 📂 3. Repository Structure
```text
Insects-Induced-leaf-diseases/
├── src/
│   └── Insects_Leaf_Diseases_Research.ipynb   # Main research pipeline
├── requirements.txt                           # Full dependency list
├── LICENSE                                    # MIT License
└── README.md                                  # Documentation

```

---

## 🚀 4. Installation & Usage

### Setup

```bash
git clone [https://github.com/habibursajal/Insects-Induced-leaf-diseases.git](https://github.com/habibursajal/Insects-Induced-leaf-diseases.git)
cd Insects-Induced-leaf-diseases
pip install -r requirements.txt

```

### Running the Experiments

Since the implementation is contained within a Jupyter Notebook, please follow these steps:

1. Open the repository in your preferred environment (Jupyter Notebook, JupyterLab, or VS Code).
2. Navigate to `src/` directory.
3. Open and run `Insects_Leaf_Diseases_Research.ipynb` sequentially.
*Note: Ensure your data directory is correctly mapped as specified in the notebook configuration.*

---

## 💾 5. Pre-trained Model Weights

The weights for our trained models are available for peer review and replication purposes.

🔗 **Download Weights:** https://drive.google.com/drive/folders/1H8hqfh6VWt-VhLjDdKKp-Ji4yJa2pBq4?usp=sharing

*Instructions: Download the weights and ensure the file paths in the notebook are updated to point to your local weight directory.*

---

## 📊 6. Citation

This paper is currently under peer review. We will update this section with the official citation once the paper is published. If you use this codebase for your research in the meantime, please acknowledge this repository.

---

## 📜 7. License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
