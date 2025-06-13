# 📘 Module 3: Predicting the Impact of Price and Other Environmental Factors

> This week focused on enhancing regression models by incorporating price and external variables like home sales, validating models through residual analysis, and building multiple regression models using Excel.

---

## 🎯 Learning Objectives

- Validate regression models using residual analysis.
- Improve model accuracy by adding price and external environmental factors.
- Interpret multiple regression outputs and derive actionable insights.

---

## 🎥 Video Lecture Summaries

### 📌 Lecture 1: Model Validation and Improvement

- **Residuals** = Actual – Predicted; used to spot model errors.
- **Validation Techniques**:
  - **Linearity**: Random residual patterns = good. Patterns = model form issue.
  - **Independence**: No cyclical patterns. Patterns = time-based autocorrelation.
  - **Normality**: Bell-shaped residual histogram = good.
  - **Equal Variance**: Variance should remain constant across predictions.

✅ Residual analysis helps flag missing variables or patterns needing further model refinement.

---

### 📌 Lecture 2: Multiple Regression with Trend, Price & Other Factors

- **Retail Price dropped**: from $949.98 → $799.95.
- **Home Sales Data**: Included to test environmental impact.
- **Model Variables**:
  - **Time in Month**
  - **10-Piece Set Sale Price**
  - **Total Home Sales (Millions)**

- **Model Outcome**:
  - **R-Square improved**: 43.9% → 84.8%.
  - **Significant Predictors**:
    - Time in Month: ➕12.48 units/month
    - Sale Price: ➖6.27 units per $1 increase
  - **Insignificant**: Total Home Sales (p > 0.10)

✅ Residual plots revealed seasonality patterns → Opportunity for future improvements.

---

### 📌 Lecture 3 & 4: Multiple Regression in Excel

- Steps to build model in Excel using *Data Analysis Toolpak*:
  1. Place independent variables side-by-side (no missing values).
  2. Input dependent variable (Sold Units).
  3. Run regression.
- **Visualization**:
  - Plot: Predicted vs. Actual
  - Add: 45° reference line to assess accuracy.

✅ Enhanced model understanding through visual diagnostics.

---

## 🧪 Mini Project: Multiple Regression in Excel

- Built and analyzed multiple regression model on cookware sales.
- Outputs Included:
  - Summary statistics
  - Coefficient table
  - Residual output
  - Residual plot (Time in Month)
  - Line fit plot

🔗 [📊 View Excel Regression Project](https://unioulu-my.sharepoint.com/:x:/g/personal/rkesari21_students_oamk_fi/ETPtvwzXeO1PsP-NTjw2p7MB3H1xsX2sI0OEIMdAA8cSfA?e=Tfm99l)




# 🧪 Quiz Summary – Residuals & Model Assumptions

### ✅ What is a residual?

A **residual** is the difference between an actual observed value and the predicted value from the model — in other words, it’s the **error**:
\[
\text{Residual} = Y_{\text{actual}} - Y_{\text{predicted}}
\]

Residuals help us understand what our model **misses** and how reliable it is.

### ✅ Causes of residuals

- **Random noise**: unpredictable factors (e.g., weather, accidents, one-off events)
- **Omitted variables**: important predictors missing from the model
- **Wrong model form**: using a linear model when a nonlinear one fits better

### ✅ Diagnosing Model Conditions with Residuals

| Condition               | When It’s Met                                        | Quiz Insight |
|------------------------|-----------------------------------------------------|--------------|
| **Linearity**          | Residuals are randomly scattered (white noise)      | ✔️           |
| **Independence**       | Residuals aren't correlated over time               | ⚠️ (missed)  |
| **Equal Variance (Homoscedasticity)** | Residuals have constant variance           | ✔️           |

📌 **Reflection:** One question was missed due to not selecting **all** correct options on independence — a reminder to check for **multiple correct answers** in future quizzes!

---
✅ **Quiz Reflections: Module 3 – Multiple Regression**

> All answers below were submitted correctly 🎯  
> This quiz focused on interpreting regression outputs, especially coefficients and statistical significance.

| Question | Topic | Correct Answer |
|----------|-------|----------------|
| Q1 | Significance of Variables (p-value < 10%) | ✅ 10-Piece Set sale price (p = 0.0000752) <br> ✅ Time in month (p = 0.051) <br> ❌ Total Home Sales (p = 0.589) |
| Q2 | Meaning of Coefficient: Time in month (12.48) | On average, the sold units increase by 12.48 units for each month |
| Q3 | Meaning of Coefficient: 10-Piece Set sale price (–6.27) | On average, the sold units decrease by 6.27 units for every $ of price increase |

---

📌 **Note**: Lower p-values indicate stronger evidence that a variable **significantly influences** the dependent variable (sales, in this case).

🧠 Correctly understood the **trend**, **direction**, and **impact** of each variable in the multiple regression model!

---

## 🧠 Personal Reflection: What I Learned

- I understood how **residuals** are more than just numbers — they tell us what the model is missing.
- Adding more relevant variables (like **price** and **external factors**) really boosts model performance.
- A model with a high R-Square doesn't mean it's perfect — checking **residual patterns** is crucial.
- I realized **seasonality** can be hidden in the residuals, and we must look deeper beyond trends and pricing.
- Building the model myself in Excel gave me confidence in handling real datasets and interpreting outputs properly.

---
