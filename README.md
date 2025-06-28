# 🏦 Loan Status Prediction using SVM

This project predicts the approval status of loan applications using a **Support Vector Machine (SVM)** classifier. The model is trained on a dataset that includes demographic and financial details of applicants.

---

## 📌 Project Goals

- Predict whether a loan will be approved (`Y`) or not (`N`)
- Preprocess real-world data including missing values and categorical features
- Train and evaluate a Support Vector Machine model

---

## 📁 File Contents

- **Loan_Status_Prediction.ipynb**: Jupyter Notebook containing:
  - Data loading and analysis
  - Cleaning missing data
  - Label encoding for categorical features
  - Training and testing an SVM model
  - Accuracy evaluation and prediction output

---

## ⚙️ Workflow Summary

1. **Data Preprocessing**
   - Replaced missing values with suitable defaults
   - Converted categorical features using label encoding

2. **Model Building**
   - Trained a Support Vector Machine (SVM) classifier
   - Used `train_test_split` to divide training and testing sets

3. **Evaluation**
   - Measured model accuracy using `accuracy_score`
   - Printed classification results

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `sklearn`:
  - `SVC` (Support Vector Classification)
  - `LabelEncoder`
  - `train_test_split`
  - `accuracy_score`

---

## ✅ Output

- The model predicts loan approvals based on applicant data.
- Accuracy and performance are printed in the notebook.

---

## 🚀 Future Improvements

- Try other classifiers (Random Forest, XGBoost, etc.)
- Use grid search for SVM hyperparameter tuning (`C`, `kernel`, etc.)
- Deploy the model using a simple web framework like Streamlit

---

## 👨‍💻 Author

This notebook is part of my machine learning learning journey using Python and scikit-learn. Feedback and suggestions are welcome!
