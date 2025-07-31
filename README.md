# O-GARCH-MODEL
A collaborative deep-dive into the dynamics of portfolio volatility using the Orthogonal GARCH (O-GARCH) framework applied to five actively traded stocks listed on the JSE. Developed as a capstone group project for the Risk Measurement 1 module in the BCom Honours in Quantitative Finance program at the University of Johannesburg, this repository showcases the intersection of theory, data, and teamwork in quantitative risk modeling.

---

## 🎯 Objectives
- Select five liquid JSE stocks across distinct industries to construct a diversified portfolio.
- Preprocess historical price data and compute log returns; assess stationarity for time series suitability.  
- Apply Principal Component Analysis (PCA) to extract orthogonal risk factors and reduce dimensionality. 
- Fit univariate GARCH(1,1) models to principal components to capture volatility clustering and persistence. 
- Reconstruct the dynamic covariance matrix using PCA loadings and conditional variances.  
- Forecast portfolio-level volatility under equal-weighted and optimized asset allocations. 
- Interpret conditional variances and asset correlations to draw strategic insights for investment risk management.
- Critically evaluate the robustness, limitations, and theoretical assumptions of the O-GARCH model.

---

## 📊 Dataset
- Daily closing prices for five selected JSE-listed stocks (2020–2024), each representing distinct sectors (e.g., Financials, Telecommunications, Healthcare, Retail, Energy).
- Data sourced via **Yahoo Finance API** and handled using Python libraries for preprocessing and transformation.
- Log returns computed for modeling; visualizations generated to assess volatility dynamics.

---

## 🧠 Tools Used
- **Python**: NumPy, Pandas, Matplotlib, Seaborn, arch, statsmodels, sklearn. 
- **Jupyter Notebook**: for code execution and analysis. 

---

## 📈 Key Insights 
- The first two PCA components captured the majority of systemic return variance.  
- GARCH(1,1) models revealed strong persistence and evident volatility clustering. 
- Covariance matrix reconstruction visualized changing correlations across time. 
- Portfolio volatility fluctuated across weighting schemes, highlighting the importance of allocation mechanics.
- Strategic analysis suggested varying contribution of sectoral assets to total volatility risk.

---

## 💼 Risk Management Implications
Through orthogonal decomposition and conditional variance modeling, this project demonstrates how volatility shifts across components can reshape portfolio risk. The findings suggest that optimized allocations guided by insights into risk factors can enhance resilience in volatile market regimes, particularly in emerging economies such as South Africa.

---

## 📝 Conclusion
This repository documents a hands-on implementation of the O-GARCH model for academic risk modeling, emphasizing data-driven volatility analysis, model critique, and real-world application. Future iterations may include dynamic correlation models (DCC-GARCH), regime switching, and broader asset universes.

---

## 📂 Included Files
- `O-GARCH-code.ipynb` – Full Jupyter Notebook with modeling steps and visualizations  
- `O-GARCH_Final_Report.docx` – Comprehensive summary of project findings, methodology, and strategic recommendations

---

## 👥 Contributors
- **Team Members** *(MO SEEPAMORE(OT-Theo), EM DJUIDJE, US SIGEBETSHU, MSS SITHOMO )* — All group members contributed equally to the research, analysis, modeling, and presentation. Leadership was shared collaboratively throughout the project.  
- **University of Johannesburg**, Risk Measurement 1 (2025)

