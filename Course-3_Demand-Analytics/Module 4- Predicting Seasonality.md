# ✅ Module 4 – Predicting Seasonality

> Final module completed! This module focused on capturing **seasonal patterns** in demand forecasting by using **categorical variables**, improving model fit, and **testing forecast accuracy** with real data.

---

## 🎯 Learning Objectives

- Build demand forecasting models with **seasonality**
- Create and test **forecasts**
- Model and format **categorical variables**

---

## 📊 Key Concepts and Learnings

### 🧩 Modeling Seasonality with Categorical Variables

| Topic | Key Idea |
|-------|----------|
| **Binary/Dummy Variables** | Used to represent months (e.g., Feb = 1 if Feb, 0 otherwise). |
| **N-1 Rule** | One category (month) is left out as a reference to avoid multicollinearity. |
| **High Model Fit** | R-square improved to **94.9%** with seasonality added. |
| **Significant Variables** | Time, Sale Price, and November were impactful. |
| **Residual Validity** | Mostly valid, though a slight curve hints at minor model refinement needs. |

---

### 📈 Forecasting and Testing

| Topic | Key Idea |
|-------|----------|
| **Forecast Period** | Model trained on 2011–2012 to predict 2013. |
| **Error Testing** | Compared predictions to actual Jan–Mar 2013 sales. |
| **Metrics Used** | **MAD** (Mean Absolute Deviation) and **MAPD** (Mean Absolute Percentage Deviation). |
| **Conclusion** | Statistical models help **capture trend + seasonality**, improving **demand planning** accuracy. |

---
## 🧪 Quiz – Modeling and Formatting Categorical Variables

| ❓ Question | ✅ Correct Answer |
|------------|------------------|
| **1. When to use categorical variables?** | The variable can only choose discrete values, such as 1 or 0 (yes or no) |
| **2. How to model a categorical variable?** | We select some but not all options (or categories) of the variable, and set up a binary variable for each option (or category). |

🎯 **Score: 100%**  
---

## 📁 Mini Project: Forecasting with Seasonality

> I rebuilt the model from scratch using Excel, this time assigning a **different default month** than shown in the lecture.

### ✅ Tabs in Excel:
1. `Seasonality` – Includes multiple regression model with time, price, and seasonality + outputs.
2. `Forecasting` – Forecasts for 2013 and forecast error calculations (MAD & MAPD).

🔗 [Excel File – My Final Mini Project](https://unioulu-my.sharepoint.com/:x:/g/personal/rkesari21_students_oamk_fi/EVhJiXr8_spPneJe6t7cogkBslibGSfPUGzXy6jMmj-jMA?e=SmW2Yp)

---

## 🧠 Personal Reflection

This final module tied everything together by introducing **seasonality modeling**—a game-changer in demand forecasting. I learned how to **format categorical variables**, **build more holistic regression models**, and finally **test predictions** using actual future data. Understanding **when** people buy—not just **how much**—feels like a key takeaway. It was rewarding to see the numbers align through forecasting accuracy tests, and I now feel confident applying this approach in real-world demand planning scenarios.

---
