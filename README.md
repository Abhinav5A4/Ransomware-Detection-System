# 🛡️ Ransomware Detection Using Machine Learning

A Machine Learning project designed to detect ransomware using static analysis of PE (Portable Executable) file features. Built with Python, Streamlit, and scikit-learn, and powered by explainable AI using LIME.

---

## 📌 Project Overview

This project classifies `.exe` files as **ransomware** or **legitimate software** using machine learning based on structural and metadata features. It includes:

- Feature selection with **Information Value (IV)** and **Weight of Evidence (WoE)**
- Class imbalance handling using **SMOTE**
- A robust **Random Forest Classifier**
- **Model evaluation** with metrics like accuracy, precision, recall, F1, AUC, and MCC
- **Interpretability** using **LIME**
- An **interactive Streamlit web app** interface

---

## 🧠 Technologies Used

- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn (RandomForestClassifier, metrics)
- imbalanced-learn (SMOTE)
- lime (Local Interpretable Model-Agnostic Explanations)
- Streamlit (web app frontend)

---
