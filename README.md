## 🧠 Project Overview

This project demonstrates the use of machine learning techniques for solving two different binary classification problems:

1. **Credit Default Prediction**: Predict whether a person will default on their credit payment using financial indicators.
2. **Sonar Signal Classification**: Classify sonar signals as either rocks or mines using frequency-based features.

---

## 📁 Datasets Used

1. **Credit Default Dataset**

   * Label: `Y` (0 = no default, 1 = default)
   * Features: Financial variables
   * Preprocessing: Standardization for kNN distance-based learning

2. **Sonar Dataset**

   * Labels: `Class` (`Rock` or `Mine`)
   * Features: 60 continuous sonar signal values
   * Preprocessing: Drop label from input features, model training and testing split

---

## 🔍 Techniques Applied

### ✅ Supervised Learning Algorithms:

* k-Nearest Neighbors (kNN)
* Logistic Regression
* Decision Trees
* Support Vector Machines (SVM)
* Random Forests

### 🧪 Evaluation Metrics:

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score
* ROC-AUC curves

---

## ⚙️ Methodology Summary

### Credit Default (Part 2)

* Loaded credit dataset
* Standardized features using `StandardScaler`
* Trained a kNN classifier and evaluated results
* Analyzed decision boundaries and misclassifications

### Sonar Dataset (Part 1)

* Loaded and split sonar dataset
* Applied multiple classifiers (kNN, Decision Tree, SVM)
* Compared models using multiple metrics
* Visualized ROC curves for model performance interpretation

---

## 🧠 Insights

* **Data preprocessing**, particularly standardization, plays a crucial role in improving kNN and SVM results.
* **kNN** performs well when distance measures are meaningful and input space is normalized.
* **Random Forests** and **SVMs** yielded robust performance in both datasets.
* ROC curves provided valuable insight into model performance under varying classification thresholds.

---

## 🛠 Requirements

Install required Python libraries:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

---

## 📌 Future Improvements

* Tune hyperparameters using GridSearchCV or RandomizedSearchCV
* Introduce cross-validation to better assess generalization
* Explore feature importance analysis for interpretability

👨‍💻 Author
Hasib Uddin Goldsmiths, University of London BSc Computer Science (2025)
