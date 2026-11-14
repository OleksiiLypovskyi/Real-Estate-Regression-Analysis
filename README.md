# Real Estate Pricing Determinants Analysis (Econometric Modeling)

## 📌 Project Overview
An empirical study analyzing the key economic and infrastructural factors influencing housing market prices in the Xindian district (New Taipei City). Based on a dataset of 414 residential property observations, the project applies multiple linear regression and hypothesis testing to identify pricing drivers and support data-driven real estate valuation.

* **Language / Documentation:** English presentation ready
* **Domain:** Quantitative Real Estate Economics & Statistics

---

## 🛠 Tools & Methodology
* **Methods:** Multiple Linear Regression, Descriptive Statistics, Two-Sample t-Test.
* **Key Independent Variables:**
  * House Age ($X_2$)
  * Distance to the Nearest MRT/Metro Station ($X_3$)
  * Number of Convenience Stores in Walking Distance ($X_4$)
* **Target Variable:** House Unit Price ($Y$)

---

## 📊 Key Findings & Econometric Model

The estimated multiple linear regression model yielded a coefficient of determination of **$R^2 = 0.5411$** (Adjusted $R^2 = 0.5377$), successfully explaining over 54% of price variance.

### Regression Equation:
$$Y = 42.98 - 0.252 X_2 - 0.0054 X_3 + 1.297 X_4$$

### Economic Interpretation of Coefficients:
* **House Age ($X_2$):** Each additional year of building age decreases the unit price by an average of $0.252$ units, holding other factors constant.
* **MRT Proximity ($X_3$):** Every extra meter of distance from a metro station negatively impacts the value by $0.0054$ units.
* **Convenience Stores ($X_4$):** Local infrastructure density shows a strong positive effect — each additional store nearby increases unit price by $1.297$ units.

### Hypothesis Testing (t-Test):
A two-sample t-test was conducted to evaluate price differences between properties with low ($\le 3$) versus high ($> 3$) convenience store density. The test overwhelmingly rejected the null hypothesis ($p \approx 1.77 \times 10^{-35}$), confirming a statistically significant pricing premium for well-serviced locations.

---

## 📁 Repository Contents
* `project_data.xlsx` — Cleaned dataset used for analysis.
* `report_data.pdf` — Full project report.
