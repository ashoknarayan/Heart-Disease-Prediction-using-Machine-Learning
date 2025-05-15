# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the presence of heart disease using various machine learning algorithms.

🧠 I forked and revisited this project to learn the **basics of ML**, and also upgraded it to work with the latest Python versions. Along the way, I identified issues, fixed them, and added a new model to the comparison: **Neural Network using PyTorch**.

---

## 🚀 Machine Learning Algorithms Used

1. 📊 **Logistic Regression** (Scikit-learn) — *Accuracy: 85.25%*
2. 📈 **Naive Bayes** (Scikit-learn) — *Accuracy: 85.25%*
3. 🧮 **Support Vector Machine (Linear)** (Scikit-learn) — *Accuracy: 81.97%*
4. 🧊 **K-Nearest Neighbours** (Scikit-learn) — *Accuracy: 67.21%*
5. 🌳 **Decision Tree** (Scikit-learn) — *Accuracy: 81.97%*
6. 🌲 **Random Forest** (Scikit-learn) — *Accuracy: 90.16%*
7. ⚡ **XGBoost** (Scikit-learn) — *Accuracy: 83.61%*
8. 🤖 **Neural Network** (PyTorch) — *Accuracy: 78.69%*

---

## 🛠️ My Contribution

- 🔁 **Forked** an existing project to explore and learn fundamental ML algorithms.
- 🧪 **Tested and compared** 8 different models on the heart disease dataset.
- 🧰 Identified that the project had **Python version constraints** (original code broke on Python 3.13).
  - 📉 Graphing modules and
  - 🧠 Neural Network (Keras/TensorFlow) were not working on Python 3.13.
- 🔧 **Adapted the neural network implementation** to work using **PyTorch**, making it compatible with the latest Python versions.
- 📦 Cleaned and structured the code to work on **Python 3.10+** environments smoothly.
- 📈 Included model comparison based on test accuracy to identify the best-performing algorithm.

---

## 📊 Results Summary

| Model                  | Accuracy   |
|------------------------|------------|
| Logistic Regression    | 85.25%     |
| Naive Bayes            | 85.25%     |
| Support Vector Machine | 81.97%     |
| K-Nearest Neighbors    | 67.21%     |
| Decision Tree          | 81.97%     |
| Random Forest          | 🏆 **90.16%** |
| XGBoost                | 83.61%     |
| Neural Network (PyTorch) | 78.69%   |

---

## 📌 Requirements

- Python 3.10 (or compatible with your setup)
- pandas, numpy, seaborn, matplotlib
- scikit-learn
- xgboost
- torch (for PyTorch neural network)

---

## 📁 Dataset

The dataset used is the classic [Heart Disease UCI dataset](https://www.kaggle.com/ronitf/heart-disease-uci).

---

## 🙌 Acknowledgement

Thanks to the original author of the project and community discussions (like [this one](https://stats.stackexchange.com/a/136542)) that helped in improving model generalization and avoiding overfitting.

---

⭐ **If you found this useful, give it a star and check out my other ML experiments!**
