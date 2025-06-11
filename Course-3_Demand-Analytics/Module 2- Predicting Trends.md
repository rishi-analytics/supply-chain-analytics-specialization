# Module 2 Summary – Predicting Trend in Demand

Welcome to **Week 2 of the Demand Analytics specialization**!  
After laying the foundation in Week 1, this week was all about **hands-on forecasting**—specifically building and interpreting a **linear regression model** to predict demand trends over time. This was the first time I really saw the data come to life.

---

##  Learning Objectives

- Understand how to identify demand patterns and how they influence forecasting.
- Learn the importance of clean, well-structured data.
- Use **Excel** to build and interpret a **linear regression model**.

---

## 📚 Lecture Highlights

### ▶️ Video 1: Forecasting Models & Demand Patterns

This video explored how **statistical forecasting** works by analyzing past demand data to project future trends. Some key principles I took away:

- All forecasts contain errors—don't expect perfection.
- The longer the time horizon, the less accurate the forecast.
- Forecasting at an **aggregate level** (e.g., company-wide vs. store-level) tends to be more reliable.

📌 I really liked the examples:
- **Stationary**: stock indices  
- **Trends**: long-term expenses like social security  
- **Seasonality + Trend**: beer sales  
- **Exogenous impact**: price changes affecting demand (e.g., kids' shoes)

---

### ▶️ Video 2: Data Collection & Pre-processing

This one emphasized the golden rule of analytics: **“Garbage in, garbage out.”**  
I realized just how critical data preparation is before running any model.

- I learned to use **monthly aggregation** to remove noisy fluctuations.
- Ensured each column had one consistent variable (no merged headers, etc.)
- Removed missing values and fixed inconsistencies.

 Here's what I visualized:
- 📈 [Line Plot – Sales Trend](https://unioulu-my.sharepoint.com/:x:/g/personal/rkesari21_students_oamk_fi/EVmAReqDq0xOtcceVOmvbI0BvoF3u8D__MY6KNYodc5AVQ?e=hNVxqi)  
- 🔵 [Scatter Plot – Monthly Demand](https://unioulu-my.sharepoint.com/:x:/g/personal/rkesari21_students_oamk_fi/EapR7g2OuJhJgIWHTCkx1FIB9U42ObmOxM4RUBAt8uQ68w?e=ufeFH3)

---

### ▶️ Video 3: Date Format Pitfalls

This part was surprisingly useful.  
I hadn’t realized how easily Excel date formats could mess up your entire workflow:

- Incorrect formats prevent proper sorting and aggregation.
- Time-based plots and regression won’t work with broken date formats.
- Lesson learned: always double-check your date column before modeling.

---

### ▶️ Video 4: Linear Regression Modeling in Excel

This was my favorite part—finally getting my hands dirty with **real modeling**.  
I built a regression model using Excel's built-in **Data Analysis > Regression** tool.

📄 [Excel Output – Linear Model](https://unioulu-my.sharepoint.com/:x:/g/personal/rkesari21_students_oamk_fi/EbWs-WDvoUNEu0IPSi5nvPMBygQUmQt7I285Vftb92susA?e=M3Mu0t)

#### Regression Equation:
\[
\hat{Y} = a + bX
\]

Where:
- \( \hat{Y} \) = predicted units sold  
- \( a \) = intercept  
- \( b \) = slope  
- \( X \) = time (months)

**Key results:**
- **R² = 0.439** → the model explains 43.9% of demand variation.
- **P-value = 0.000417** for the slope → statistically significant trend detected.

---

## 🧠 Assignment Summary

### 📊 Visualization Task
I worked on the provided Excel files to visualize demand trends:
- Built both **scatter plots** and **line charts** from monthly sales.
- Compared against provided solutions to validate my approach.
- Felt like I was finally thinking like a demand analyst.

### 📉 Linear Regression Task
- Used the cleaned dataset to fit a linear model.
- Interpreted the output:
  - R², coefficients, p-values
  - Residuals and line-fit charts
  - ANOVA significance

✅ Gained confidence in model interpretation and saw how powerful even a simple model can be with clean data.


---

## ✅ Quiz Reflections: Module 2 – Regression-based Forecasting

> All answers below were submitted correctly 🎯  
> This quiz tested foundational concepts of regression modeling in demand forecasting.

| Question | Topic | Correct Answer |
|----------|-------|----------------|
| Q1 | Least Squares Method | Minimizing the sum of squares of all errors |
| Q2 | R-Square Interpretation | The model can explain 43.9% of the variation in the data | While 56.1% come from random unexaplianable errors
| Q3 | p-value of the Slope | The smaller the p-value is, the better a predictor the regression equation is |
| Q4 | Popular Demand Patterns | Fluctuations that combine trend and seasonality | Trend Over time, either linear or non-linear |

---

📌 **Quick Takeaways**:
- The **least squares method** is used to find the best-fitting regression line by minimizing squared prediction errors.
- **R² (R-squared)** tells how much of the variation in demand the model can explain — here, 43.9%.
- **p-value** helps test the significance of predictors; smaller p-values imply stronger predictive power.
- Real-world demand patterns often exhibit **trends + seasonal fluctuations**, not just one or the other.

---
## 🔍 My Reflection

This module was a **turning point** in the course. I moved from theory to action—transforming raw data into meaningful demand trends.  
What really stood out was how **data cleaning and visualization aren’t just technical chores—they directly impact forecasting outcomes.**  
I also loved using Excel for modeling— it made everything feel tangible and real.

Looking forward to **Module 3: Competitive Positioning**, where I'll begin comparing companies and seeing how data supports strategic decisions.
