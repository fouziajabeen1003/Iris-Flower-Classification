# 🌸 Iris Flower Classification using K-Nearest Neighbors

A Python-based Machine Learning project that classifies Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) based on sepal and petal measurements. The model is built using `scikit-learn` and utilizes the K-Nearest Neighbors (KNN) algorithm with an interactive terminal interface for single-sample prediction.

---

## 📌 Project Overview

This project demonstrates a classic supervised machine learning workflow:
1. **Dataset Loading**: Using Scikit-Learn's built-in Iris dataset.
2. **Data Splitting**: 80% training data, 20% testing data.
3. **Model Training**: K-Nearest Neighbors Classifier ($k=3$).
4. **Evaluation**: Model accuracy evaluation on unseen test data.
5. **Interactive Prediction**: Accepts custom flower dimensions directly from user input to predict the species in real time.

---

## 🛠️ Features & Algorithm

- **Algorithm**: K-Nearest Neighbors (`KNeighborsClassifier`)
- **Neighbors ($k$)**: 3
- **Features Used**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target Classes**: `setosa`, `versicolor`, `virginica`

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.x installed along with `scikit-learn`:

```bash
pip install scikit-learn
