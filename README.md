# 📘 Human Activity Recognition Using Smartphone

**Final Year Research Project – B.Tech CSE, C.V. Raman Global University (2025)**  
**Author:** Tusar Kumar Parida
---
**Research paper:** <a href="https://github.com/user-attachments/files/20643193/Human.Activity.Recognition.pdf" style="text-decoration: none;">Research Paper</a>

---
[![View on Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebook-blue?logo=kaggle)](https://www.kaggle.com/sylvianclee/human-activity-recognition-cnn-lstm)
---

## 📌 Overview

This research project focuses on recognizing and classifying different human activities (such as walking, sitting, and standing) using data from smartphone sensors like accelerometers and gyroscopes. The project compares both traditional machine learning models and deep learning techniques to determine the most accurate approach for human activity recognition (HAR).

---

## 🎯 Objectives

- Preprocess smartphone sensor data effectively for analysis.
- Implement and compare Machine Learning algorithms:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM with RBF kernel)
- Build a Deep Learning model using a 3-layer Long Short-Term Memory (LSTM) network.
- Combine ML and DL predictions through ensemble learning.
- Evaluate models using core metrics and visualizations.

---

## 🧠 Model Approach

This project implements a **hybrid model** combining both **Machine Learning (ML)** and **Deep Learning (LSTM)** techniques to solve Human Activity Recognition (HAR) more effectively.

### 🔹 Machine Learning Models:
- **Decision Tree**, **Random Forest**, **SVM**, and **Logistic Regression** were used to provide insights into feature importance and offer quick, interpretable results.

### 🔹 Deep Learning Model:
- An **LSTM (Long Short-Term Memory)** network was built to capture **temporal dependencies** and **sequential patterns** from the time-series sensor data. It outperformed ML models in capturing motion-related patterns.

### 🔹 Ensemble Learning:
- A **majority voting ensemble** method was applied to combine predictions from LSTM and the ML models. This two-pronged approach leverages:
  - LSTM's time-pattern learning capability.
  - ML models' strength in identifying key features.

✅ The **ensemble model** achieved an impressive **accuracy of 95.22%**.

---

## 🔍 Model Evaluation

- **Accuracy**, **Precision**, **Recall**, **F1-score**
- **Training Curves** (see Fig. 3 in report) – for observing model convergence
- **Confusion Matrices** – for class-wise performance distribution
- **Model Architecture Diagrams** – to assist in tuning and optimization

---

## 📊 Dataset

- **Name:** UCI HAR Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)  
- **Classes:**
  - Walking
  - Walking Upstairs
  - Walking Downstairs
  - Sitting
  - Standing
  - Laying

---

## 📂 Results
## 🔍 Model Comparison

| Model                     | Accuracy |
|--------------------------|----------|
| Logistic Regression      | 84%      |
| Decision Tree            | 87%      |
| Random Forest            | 91%      |
| SVM (RBF Kernel)         | 89%      |
| LSTM (3-layer)           | 94%      |
| **Ensemble (LSTM + ML)** | **95.22%**  |

✅ The **ensemble model (LSTM + ML)** achieved the highest accuracy, making it most effective for time-series activity recognition.

---

## 📈 Key Results

- **Best Performing Model:** Ensemble (LSTM + ML)
- **Best Accuracy:** 95.22%
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, and Confusion Matrix
- **Observation:** Combining deep learning (LSTM) with ML models significantly improved accuracy and robustness.

---




