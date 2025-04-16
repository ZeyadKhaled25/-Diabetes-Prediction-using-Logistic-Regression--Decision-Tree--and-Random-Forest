# 🧪 Diabetes Prediction using Logistic Regression, Decision Tree, and Random Forest

This project applies three popular machine learning models — **Logistic Regression**, **Decision Tree**, and **Random Forest** — to perform binary classification on the **Pima Indians Diabetes Dataset**. The goal is to predict whether a patient has diabetes based on medical data.

## 📂 Dataset
- **Source:** [Pima Indians Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features:** Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target:** Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## 📈 Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## ✅ Experiments Performed

1. **Baseline Models**
   - Trained and evaluated each model with default parameters.

2. **Feature Scaling**
   - Applied `StandardScaler` to scale features and observe model performance changes.

3. **Train-Test Split Adjustment**
   - Changed the train-test split from 70/30 to 80/20 and compared results.

4. **Hyperparameter Tuning**
   - Used `GridSearchCV` to optimize hyperparameters for each model.

5. **Data Sampling**
   - Used **SMOTE** to handle class imbalance and improve model performance.

---

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

Visualizations (heatmaps) are used to better understand the confusion matrices.

---

## 🏆 Best Results

| Model                        | Accuracy |
|-----------------------------|----------|
| Random Forest (SMOTE)       | **0.840** |
| Decision Tree (SMOTE)       | 0.827    |
| Logistic Regression (SMOTE) | 0.763    |

---

## 📝 Report Summary

- **Best Performing Model:** `Random Forest (SMOTE)`
- **Main Challenge:** Handling class imbalance and selecting optimal hyperparameters.
- **Key Learnings:**
  - **SMOTE** greatly improves model performance on imbalanced datasets.
  - **GridSearchCV** is effective in boosting model accuracy when tuned well.
  - **Feature Scaling** benefits models like Logistic Regression more than tree-based models.


