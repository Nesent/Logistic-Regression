# 📘 Assignment 4 – Logistic Regression (From Scratch)

## 🧠 Objective

This project implements **logistic regression from scratch** using **batch gradient descent**, to classify a binary dataset. No machine learning libraries like `scikit-learn`, `TensorFlow`, or `PyTorch` are used for modeling. Only `numpy`, `pandas`, and `matplotlib` are allowed for computation and visualization.

---

## 📁 Files Included

- `Logistic_regression.ipynb` – Jupyter notebook containing the complete implementation
- `Logistic_Regression_Assignment_Solution.docx` – Final report with code snippets, plots, and evaluation metrics
- `AS.pdf` – Original assignment brief

---

## 🛠️ Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn` (for evaluation metrics only)

Install dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 Tasks Covered

1. **Training Logistic Regression:**
   - Normalizes input features
   - Implements batch gradient descent
   - Uses sigmoid activation

2. **Model Evaluation:**
   - Final cost and learned parameters
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score

3. **Visualizations:**
   - Cost function vs. iterations (for different learning rates)
   - Decision boundary plotted over dataset

---

## 📊 Key Results

✅ Final cost: 0.2467
✅ Learned parameters (theta): [1.34, -2.15, 0.89]
✅ Accuracy: 0.9200
✅ Precision: 0.9130
✅ Recall: 0.9310
✅ F1 Score: 0.9220


---

## 📌 Notes

- Uses learning rates `α = 0.1` and `α = 5` for comparison.
- Code is **fully from scratch** with vectorized operations.
- Plots are generated using `matplotlib` and embedded in the Word report.

---

## 📬 Author Info

_Name: SOUMYA BHATTACHARJEE_  
_Roll No: 2206219_  
_Course: Machine Learning ;IT 06 ;KIIT_
