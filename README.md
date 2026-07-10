# Intrusion Detection System using Metaheuristic-Optimized Random Forest

## 📌 Overview

This project implements a machine learning-based Intrusion Detection System (IDS) using a Random Forest classifier enhanced with metaheuristic optimization techniques.

The goal is to improve classification performance by jointly optimizing:
- Model hyperparameters
- Feature selection

Three metaheuristic algorithms are explored:
- Simulated Annealing (SA)
- Genetic Algorithm (GA)
- Tabu Search (TS)

---

## 🚀 Key Features

- Intrusion detection using Random Forest
- Feature selection integrated with model training
- Hyperparameter tuning via metaheuristic optimization
- Comparison of multiple optimization strategies
- Full evaluation using:
  - Cross-validation F1 score
  - Test accuracy and F1 score
  - Confusion matrix analysis
- Visual performance comparison and trade-off analysis

---

## 🧠 Methods Used

### Base Model
- Random Forest Classifier (baseline)

### Optimization Techniques
- Simulated Annealing: probabilistic search with cooling schedule
- Genetic Algorithm: population-based evolutionary optimization
- Tabu Search: memory-based local search

Each method optimizes:
- Model hyperparameters
- Feature subset selection

---

## 📊 Dataset

This project uses the **UNSW-NB15 dataset**, a benchmark dataset for network intrusion detection.

- Source: UNSW Canberra Cyber Range Lab
- Classes: Normal vs Attack traffic

---

## 📈 Results

The optimized models are evaluated using:
- F1 Score (primary metric)
- Accuracy
- Precision / Recall
- False Positive Rate
- Cross-validation performance

Visual comparisons include:
- Confusion matrices
- F1 vs Accuracy comparison
- Feature reduction vs performance trade-off

---

## 📁 Project Structure
intrusion-detection-rf-metaheuristics/
│
├── notebook.ipynb # Main implementation
├── SETUP.md # Environment setup guide
├── README.md # Project overview (this file)
├── data/ # Dataset (not included in repo)
├── results.pdf # Generated findings and plots


---

## ⚙️ Setup Instructions

Please refer to **SETUP.md** for full installation, dataset setup, and execution instructions.

---

## 🧩 Requirements

- Python 3.10+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn