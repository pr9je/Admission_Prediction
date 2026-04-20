# 🎓 Jamboree Admission Prediction

## 📌 Problem Statement
Predict the probability of admission into top universities using applicant data such as GRE, TOEFL, CGPA, SOP, LOR, and Research experience.

---

## 📊 Dataset
- GRE Score (0–340)
- TOEFL Score (0–120)
- University Rating (1–5)
- SOP, LOR (1–5)
- CGPA (0–10)
- Research (0/1)

---

## 🔍 Key Insights
- CGPA is the strongest predictor of admission
- GRE score significantly impacts probability
- Research experience boosts chances
- SOP & LOR have moderate influence

---

## ⚙️ Model
- Linear Regression (Statsmodels)
- R² ≈ 0.80 (Strong predictive performance)

---

## 🧪 Assumptions Checked
- No multicollinearity (VIF < 5)
- Homoscedasticity satisfied
- Residuals normally distributed

---

## 📈 Results
- MAE: Low
- RMSE: Low
- R²: ~0.8

---

## 🚀 Business Recommendations
- Focus on improving CGPA & GRE scores
- Encourage research experience
- Deploy model as admission prediction tool

---

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Statsmodels, Scikit-learn

---

## 📂 Project Structure

Jamboree-Admission-Prediction/
│
├── data/                # Dataset
├── notebook/            # Jupyter notebook (EDA + analysis)
├── images/              # Visualizations used in README
├── README.md
├── requirements.txt
└── .gitignore

---

