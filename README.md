# Regularization in High-Dimensional Regression
## A Comparative Study of Ridge, Lasso, and Elastic Net

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/regularization-study/blob/main/Rushil_Ravi_Regularization_Project.ipynb)

---

## 📋 Overview

This project compares three regularization methods for high-dimensional regression:

- **Ridge Regression** (L2 penalty)
- **Lasso** (L1 penalty)  
- **Elastic Net** (L1 + L2 penalties)

The study evaluates each method on:
- Prediction accuracy (Test MSE, R²)
- Variable selection (Sensitivity, False Discovery Rate)
- Computational efficiency (Training time)

---

## 🎯 Key Findings

| Scenario | Best Method | Key Insight |
|----------|-------------|-------------|
| Sparse + Independent features | **Lasso** | Highest sensitivity (82%) |
| Dense signals | **Ridge** | Best prediction, fastest |
| Correlated features | **Elastic Net** | Most robust, handles correlation |
| High-dimensional (p > n) | **Elastic Net** | Best balance of prediction & sparsity |

**Simple rule:** *"If you don't know your data, start with Elastic Net"*

---

## 📁 Repository Structure

regularization-study/
│
├── regularization-comparative-study.ipynb # Main Jupyter notebook
├── requirements.txt # Python dependencies
├── README.md # This file
│
├── results/ # Generated outputs
│ ├── simulation_results.csv
│ ├── statistical_tests.csv
│ ├── learning_curves.csv
│ ├── gene_expression_results.csv



---

## 🚀 How to Run

### Option 1: Google Colab (Recommended - No Setup)

1. Click the "Open In Colab" badge above
2. Go to **Runtime → Run all**
3. Wait 10-15 minutes for the simulation to complete
4. Results save to your Google Drive


Contact
Author: Rushil Ravi

Course: STAT 654 - Statistical Computing with R & Python

Email: rushil_ravi@tamu.edu

GitHub: Rushil-Ravi

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Professor Sharmistha Guha for guidance and feedback

Hoerl & Kennard (1970) - Ridge regression

Tibshirani (1996) - Lasso

Zou & Hastie (2005) - Elastic Net
