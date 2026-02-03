# 🏠 USA House Price Prediction

## 📊 Project Overview

This project investigates key factors influencing housing prices in Baton Rouge, Louisiana, using a dataset of 856 properties collected in 2005. The analysis includes data exploration, statistical testing, and predictive modeling using **simple** and **multiple linear regression** techniques. It was completed as part of my MSc in Applied Data Science and emphasises real-world statistical modeling, interpretation, and communication of insights.

---

## 🔍 Objectives

- Explore and visualise relationships between property features and sale prices  
- Apply statistical tests (t-tests, chi-squared) to draw inferences  
- Build and interpret simple and multiple regression models  
- Evaluate model performance and conduct feature selection  
- Communicate findings clearly and accurately  

---

## 🛠️ Tools & Technologies

- **Language**: R  
- **Packages**: `fastDummies`, `DescTools`, `caret`, `MASS`, `stats`  
- **Techniques**:  
  - Data visualisation  
  - Correlation analysis  
  - Hypothesis testing (t-test, chi-squared test)  
  - Linear regression (log-transformed models)  
  - Feature selection using AIC and cross-validation  

---

## 📈 Key Results

- **Log(area)** is a highly significant predictor: every 1% increase in area corresponds to a **1.03% increase** in sale price  
- Houses on the **waterfront** or with a **fireplace** were significantly more expensive  
- The final reduced regression model, built through **stepwise AIC selection**, outperformed the full model in terms of generalisability  
- **Presence of a pool**, interestingly, was *not* a significant price predictor  
- Statistical tests confirmed that waterfront homes have higher mean prices, and that pools and fireplaces are not independent features  

---

## 🧠 What I Learned

- How to apply statistical reasoning to real-world housing data  
- Importance of feature transformation (e.g. log-scaling) for linear modeling  
- Evaluating model fit and assumptions using residual plots  
- Trade-offs between model complexity and performance (AIC vs. RMSE)  
- Clear communication of technical findings through visualisations and narrative  

---

## 📁 Project Structure

📦USA-House-Price-Prediction/  
 ┣ 📄 USA House Price Prediction.pdf      ← Full report with methodology, analysis, and results  
 ┣ 📄 README.md             ← This file  
 ┗ 📄 MA334-SP-7_code_2322761                 ← R script


---

## 📌 How to Run

This project was completed in R. To reproduce the analysis:

1. Clone the repository  
2. Open the R scripts in `/code`  
3. Ensure all required packages are installed  
4. Run the scripts sequentially  

---

## 🤝 Acknowledgements

**Data Source**: Dr. Kelley Pace, Department of Finance, Louisiana State University  
**Course**: Applied Data Science MSc, University of Essex (2024–2025)
