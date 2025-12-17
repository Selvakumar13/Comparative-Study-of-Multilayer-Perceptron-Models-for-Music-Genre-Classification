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

.
├── Notebook/
│ ├── Baseline_MLP_model.ipynb
│ ├── Baseline_MLP_model_hyper_parameter tuning.ipynb
│ ├── Deep_MLP_model.ipynb
│ └── Autoencoders with MLP.ipynb
│
├── Music_Genre_Classification_Report.pdf
├── requirements.txt
└── README.md

yaml
Copy code

> **Note:**  
> Preprocessed datasets and trained model weights are intentionally excluded from the
> repository to keep it lightweight and reproducible.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Selvakumar13/Comparative-Study-of-Multilayer-Perceptron-Models-for-Music-Genre-Classification.git
   cd Comparative-Study-of-Multilayer-Perceptron-Models-for-Music-Genre-Classification
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
Copy code
jupyter notebook
Run notebooks in the Notebook/ directory sequentially.

🎵 Dataset
GTZAN Music Genre Dataset
Introduced by Tzanetakis & Cook (2002), containing 1,000 audio tracks across 10 genres.

Original dataset:
https://marsyas.info/downloads/datasets.html

Kaggle mirror:
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

Each track is 30 seconds long, sampled at 22,050 Hz.

📄 Report
A full experimental report is included:

Music_Genre_Classification_Report.pdf

The report covers:

Feature preprocessing

Model architectures

Training methodology

Quantitative evaluation

Comparative discussion and conclusions

🛠️ Technologies Used
Python

PyTorch

NumPy, Pandas

Scikit-learn

Jupyter Notebook

👤 Author
Selvakumar Murugan Konar
MSc Computer Science (Artificial Intelligence & Data Science)

📚 References
Tzanetakis, G., & Cook, P. (2002). Musical genre classification of audio signals.
IEEE Transactions on Speech and Audio Processing.
