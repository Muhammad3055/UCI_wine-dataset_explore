# UCI_wine-dataset_explore
# 🍷 Wine Quality Prediction — Regression & Classification

This project implements a **complete machine learning pipeline** to predict the quality of Portuguese *Vinho Verde* wine using physicochemical features.  
It covers **Linear Regression**, **Stochastic Gradient Descent**, **Regularization (Ridge, Lasso)**, **Polynomial Regression**, and **Logistic Regression** for classification.

---

## 📂 Dataset

- **Source:** [UCI Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Samples:** 1,599 (red wine) & 4,898 (white wine)
- **Features:** 11 numeric physicochemical properties (e.g., acidity, sugar, alcohol)
- **Target:** Quality score (0–10)

---

## 🧩 Tasks Covered

✅ **Data Preprocessing**  
- Handle missing values  
- Scale features  
- Polynomial feature expansion

✅ **Model Training**  
- Linear Regression (Normal Equation)  
- Stochastic Gradient Descent (SGD)  
- Ridge & Lasso Regression (regularization)  
- Logistic Regression & SGDClassifier (binary classification)

✅ **Model Evaluation**  
- RMSE & R² for regression  
- Accuracy & F1-score for classification  
- Learning curves  
- Feature importance analysis

✅ **Optimization**  
- Batch Gradient Descent  
- Early Stopping  
- Grid Search for hyperparameter tuning

---

## 🔬 Results

| Model              | RMSE | R² | Time (s) |
|--------------------|------|-----|----------|
| Linear Regression  | ...  | ... | ...      |
| SGD Regressor      | ...  | ... | ...      |
| Ridge Regression   | ...  | ... | ...      |
| Lasso Regression   | ...  | ... | ...      |

| Classifier         | Accuracy | F1-score | Time (s) |
|--------------------|----------|----------|----------|
| Logistic Regression | ...      | ...      | ...      |
| SGD Classifier      | ...      | ...      | ...      |

(*Fill with your real numbers*)

---

## 📈 Key Insights

- Regularization reduces overfitting by shrinking coefficients.
- Polynomial features can improve accuracy but increase overfitting risk.
- Logistic Regression effectively classifies good vs. bad wine.

---

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the notebook or Python script
python UCI_wine.ipynb
