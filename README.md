# Financial-market-analysis-for-AI-companies

### 📈 AI R&D Investment vs. Stock Returns  

## Overview  
This project explores whether **AI-focused R&D spending** by leading tech firms (e.g., Google, Meta, OpenAI) translates into superior shareholder returns.  
We analyze financial and R&D datasets, apply machine learning models, and conduct **portfolio backtesting** to compare the performance of high R&D spenders against a market benchmark.  

## 🔹 Key Objectives  
- Evaluate the **relationship between R&D spend, AI revenue growth, and stock performance**.  
- Test if high R&D intensity generates **alpha (excess returns)**.  
- Compare risk-adjusted performance using **Sharpe Ratios**.  
- Provide insights for **investors, hedge funds, and policy makers**.  

## 🛠️ Methodology  
1. **Data**  
   - Synthetic Kaggle dataset (2015–2024).  
   - Features: R&D spend, AI revenue, growth %, events, stock impact.  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation analysis of R&D vs. stock impact.  
   - Trend analysis of AI revenue growth.  

3. **Machine Learning Models**  
   - Regression (baseline).  
   - Tree-based models (Random Forest, XGBoost) for feature importance.  

4. **Portfolio Backtesting**  
   - Constructed portfolio of **Top R&D Spenders**.  
   - Compared cumulative returns against **Market Benchmark Portfolio**.  
   - Evaluated **Sharpe Ratios** and risk-return trade-offs.  

---

## 📊 Results  

- **Cumulative Returns:**  
  - R&D portfolio peaked at ~1.6× market growth but collapsed sharply afterward.  
  - Market benchmark delivered **steady positive returns**.  

- **Sharpe Ratios:**  
  - Portfolio Sharpe: **-0.08** → Poor risk-adjusted performance.  
  - Market Sharpe: **0.72** → Superior, consistent risk-return balance.  

---

## 🔎 Insights  

- **Technical:** R&D intensity is not a standalone alpha factor.  
- **Financial:** Market portfolio outperforms in risk-adjusted terms.  
- **Business:** Hedge funds should treat R&D as a **secondary filter**, not a primary driver.  

---

## 🚀 Future Extensions  

- Deploy **interactive dashboard** for strategy testing.  
- Extend to **multi-factor portfolio models** (profitability, momentum, size).  
- Containerize & deploy on **Kubernetes** for scalable simulations.  

---


