# Comparative Study of Multilayer Perceptron Models for Music Genre Classification

This repository presents a comparative deep learning study on **music genre classification**
using the **GTZAN dataset**. Multiple Multilayer Perceptron (MLP) architectures were designed,
trained, and evaluated to analyze the impact of depth, hyperparameter tuning, and
representation learning on classification performance.

The project was implemented as part of an advanced Deep Learning coursework and emphasizes
experimental rigor, reproducibility, and clear performance analysis.

---

## 📌 Project Overview

Music genre classification is a multi-class audio classification problem where the goal is
to assign a musical track to one of several predefined genres based on extracted features.

In this work:
- Handcrafted audio features were used as inputs
- Multiple MLP variants were implemented and compared
- An autoencoder-based approach was explored for representation learning
- Models were evaluated using held-out validation and test splits

---

## 🧠 Models Implemented

- **Baseline MLP**
  - Simple feed-forward neural network
  - Serves as a performance reference

- **Hyperparameter-Tuned MLP**
  - Tuned using systematic hyperparameter search
  - Optimized learning rate, hidden units, and regularization

- **Deep MLP**
  - Increased depth and capacity
  - Regularization techniques to reduce overfitting

- **Autoencoder + MLP Classifier**
  - Autoencoder for feature compression
  - MLP trained on latent representations

---

## 📊 Results Summary (Test Accuracy)

| Model                         | Accuracy |
|--------------------------------|----------|
| Baseline MLP                  | 90.99%   |
| Tuned MLP                     | 92.33%   |
| Deep MLP                      | 92.53%   |
| Autoencoder + MLP             | 87.00%   |

A detailed analysis including confusion matrices, learning curves, and architectural
comparisons is provided in the project report.

---

## 📁 Repository Structure

