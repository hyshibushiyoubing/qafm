# 📘 Forecasting Bank Liquidity Risk

This repository contains our final project for **QF603: Quantitative Analysis of Financial Markets**, focused on forecasting liquidity risk for U.S. banks using advanced time series modeling techniques.

---

## 🎯 Objective

Predict the **Total Loans to Total Deposits (LTD)** ratio as a key liquidity risk indicator, focusing primarily on **First Republic Bank (FRCB)**, which collapsed in Q2 2023.

---

## 🏦 Banks Analyzed

- Bank of America  
- Fifth Third  
- JPMorgan Chase  
- US Bank (USB)  
- Wells Fargo (WFC)  
- Citizens Financial Group  
- FCNCA (Silicon Valley Bank acquirer)  
- FRCB (bankrupt in 2023)

---

## 📈 Models Used

1. **OLS Regression** – Baseline model for explanatory relationships  
2. **ARIMA** – Time series forecasting of LTD ratio  
3. **VAR** – Multivariate interdependencies across macro and bank-level indicators  
4. **VECM** – Long-term cointegration model for economic equilibrium behavior

---

## 📊 Data Sources

- **Bloomberg**: Bank-specific financials  
- **Federal Reserve**: Macro indicators including:
  - Fed Funds Rate  
  - CPI  
  - Unemployment Rate  
  - Real GDP

> Covers **9 years of quarterly data**

---

## 🧠 Key Findings

- **OLS** and **ARIMA** performed well on stable banks, with MAPE < 5%
- **VAR** captured dynamic relationships but struggled with sharp changes
- **VECM** showed poor short-term accuracy and overestimated future risk
- **FRCB's** liquidity ratio forecasts reflected true deterioration pre-bankruptcy

---

## 🙋 Contribution

**My responsibility:**  
I was responsible for the **VAR (Vector Autoregression) model** implementation and analysis. This involved:

- Selecting macroeconomic and bank-level indicators  
- Performing lag selection using AIC/BIC  
- Estimating VAR models for each bank  
- Interpreting impulse response functions (IRFs) and forecast error variance decomposition  
- Evaluating model fit and predictive power across stable vs. distressed banks

---

## 📌 Conclusion

The project showcases a multi-model approach to liquidity forecasting, highlighting how traditional and advanced time series models behave under different bank risk profiles.
