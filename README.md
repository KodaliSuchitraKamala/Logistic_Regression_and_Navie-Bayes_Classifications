# Logistic Regression & Naive Bayes Classifications

This repository provides a comprehensive implementation and comparison of two popular classification algorithms: **Logistic Regression** and **Naive Bayes**. The goal is to demonstrate their functionality, performance, and trade-offs using standard datasets.

---

## 📋 Table of Contents

1. [Project Overview](#project-overview)  
2. [Algorithms Explained](#algorithms-explained)  
3. [Dataset](#dataset)  
4. [Installation & Setup](#installation--setup)  
5. [Usage Guide](#usage-guide)  
6. [Evaluation Metrics](#evaluation-metrics)  
7. [Experiment Results](#experiment-results)  
8. [Adding New Data](#adding-new-data)  
9. [Contributing](#contributing)  
10. [License](#license)  

---

## 🧠 Project Overview

This project aims to:
- Implement **Logistic Regression** and **Naive Bayes** classifiers from scratch and using scikit-learn.
- Compare model accuracy, precision, recall, F1‑score, and ROC‑AUC.
- Explore decision boundaries, assumptions, and suitable use cases.
- Create clear visualizations and reporting.

---

## Algorithms Explained

### Logistic Regression
- A discriminative model used for binary and multiclass classification.
- Outputs probabilities via the logistic (sigmoid) function.
- Estimates model parameters through Maximum Likelihood Estimation, often with regularization (L1, L2).

### Naive Bayes
- A generative model based on Bayes’ theorem with the “naive” assumption of feature independence.
- Variants include:
  - **GaussianNB** (continuous features)
  - **MultinomialNB** (count data like TF-IDF)
  - **BernoulliNB** (binary features)

---

## 🗂 Dataset

The starter dataset (e.g., `data/sample.csv`) should include:

| Feature 1 | Feature 2 | ... | Label |
|-----------|-----------|-----|-------|
| 0.5       | 1.2       | ... | 0     |
| 1.1       | 0.3       | ... | 1     |

- Ensure no missing values.
- Includes numerical/categorical features and a target column (`label`).

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/KodaliSuchitraKamala/Logistic_Regression_and_Navie-Bayes_Classifications.git
   cd Logistic_Regression_and_Navie-Bayes_Classifications
