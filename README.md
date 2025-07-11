# 🔍 Sonar vs Mine Prediction – Machine Learning Project

This project aims to predict whether a given sonar signal is reflected from a **mine** or a **rock**, using a **Logistic Regression** classification model.

It is based on a real-world dataset from the **UCI Machine Learning Repository** and demonstrates the full ML workflow — from data preprocessing to model evaluation.

---

## 📂 Dataset Information

- **Source:** [UCI ML Repository – Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Samples:** 208
- **Features:** 60 numeric frequency-based features (values from sonar returns)
- **Target Values:**
  - `R` → Rock
  - `M` → Mine

---

## 🚀 Project Workflow

1. Load and explore the dataset
2. Preprocess the data (label encoding, feature-target separation)
3. Train/test split
4. Train a **Logistic Regression** model
5. Predict and evaluate using **accuracy score**
6. Predict on custom input data

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab 

---

## 📈 Model Performance

- **Model Used:** Logistic Regression
- **Test Accuracy:** ~83% (may vary slightly depending on train/test split)

---

## 🧪 Sample Prediction

```python
input_data = (0.02, 0.037, 0.038, ..., 0.01)  # new sonar reading
prediction = model.predict([input_data])
